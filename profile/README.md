
# FHDW-Gruppe3 


## Anforderungen 1
### Systemanforderung
- Das System soll zwei 4-bit Zahlen verknüpfen
- Operationen:
  > - AND, OR, NOT, ADD, Sub, MUL, Reserved, Reserved
- Folgende Flags sind gefordert:
  > - Carry, Overflow, Equal, Zero

### Randbedingungen
- Entwurf mit LogicWorks
- Alle Ein- und Ausgänge sind "registered"
- Folgende Bauteile stehen aus technologischen Gründen zur Verfügung (genügt das?):
    > - 16 x D-FlipFlops
    > - 1 x 74181 _[ALU]_
    > - 1 x PROM (maximal 5 Adressbits, beliebig viele Speicherbits)
    > - Beliebige logische Gatter, keine komplexen Schaltnetze mit Ausname von Multiplexern

### Entwurfsziel:
- __Maximale Geschwindigkeit__


## Aufgaben für nächste Woche
- Entwurf eines Blockschaltbildes für die CPU
- Entwurf eines kleinen Programms zur Addition von 2 Operanden (3,6), die im Speicher an der Adresse **0x80** und **0x81** liegen
- Abspeichern des Ergebnisses ab Speicherstelle **0xA0**
- Anschließende Multiplikation des Ergebnisses mit 3
- Abspeichern dieses Ergebnisses ab Speicherstelle **0F0h**
- Erläutern des Ablaufs...
- Keine Entwurfs-Details...
