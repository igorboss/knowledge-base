# Kirjeldus
...

# Kodeerimine
- SNOMED: [replaceme |M�iste kirjeldus|](concept:snomed-ct|replaceme)

# Tulemus
- T��p: t�isarv
- Vahemik: |0<=X<100|

## Minu mudel
```fsh
Logical: MyObservationModel
Parent: Element
* patient                     1..1 Reference(Patient) "Observed patient" "Patsient keda uuritakse."
* performer               0..1 Reference(Practitioner) "The professional that perform observation." "Teostaja."
* effectiveDateTime 1..1 dateTime "Time of observation" "M��tmise aeg"
* value                       0..1 decimal "Numeric value" "Arvuline vastus"
* xxx        1..1 SI  "Kommnt1" "Komment2"
```
