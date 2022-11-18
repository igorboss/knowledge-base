# Kirjeldus
...

# Kodeerimine
- SNOMED: [replaceme |Mõiste kirjeldus|](concept:snomed-ct|replaceme)

# Tulemus
- Tüüp: täisarv
- Vahemik: |0<=X<100|

## Minu mudel
```fsh
Logical: MyObservationModel
Parent: Element
* patient                     1..1 Reference(Patient) "Observed patient" "Patsient keda uuritakse."
* performer               0..1 Reference(Practitioner) "The professional that perform observation." "Teostaja."
* effectiveDateTime 1..1 dateTime "Time of observation" "Mõõtmise aeg"
* value                       0..1 decimal "Numeric value" "Arvuline vastus"
* xxx        1..1 SI  "Kommnt1" "Komment2"
```
