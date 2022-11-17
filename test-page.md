Text


[sub page](page:subpage-of-test-page)

[Apple](concept:snomed-ct|735215001)

[active](concept:publication-status|active)

## Logical model
{{def:number-of-previous-pregnancies-model}}


## Profile EEBase-Organization
{{def:EEBase-Organization}}


## Emoji support
:carrot:

I love Wiki :smile: 

## Json support
```json
{ "text": "JSON example" }
```

## Embedded FSH support
```fsh
Logical: MyProcedureModel
Parent: Element
* code 1..1 Coding "Code of procedure." "Protseduuri kood."
* code from https://terminology-server/ValueSet/some-vs (required)
* patient 1..1 Reference(Patient) "Subject of procedure." "Patsient."
* performer 0..1 Reference(Practitioner or PractitionerRole) "The people who performed the procedure." "Protseduuri teostaja."
* performed 1..1 dateTime "When the procedure was performed." "Millal protseduur teostatud."
* note 1..1 string "Additional information about the procedure" "Lisa informatsioon protseduuri kohta"
```

