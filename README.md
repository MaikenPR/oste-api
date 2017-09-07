# Oste API Dokumentation

## Resurser

### GET /cheeses

Resursen repræsenterer alle oste i kartoteket. 
Resursen er formateret på følgende måde:

```JSON
[{
    "varenr":420420,
    "navn": "buko pikant",
    "pris": 30,
    "type": "smøreost",
    "producent":"buko",
    "antal": 30,
    "beskrivelse":{
        "tekst": "God til de travle dage .",
        "smag": "blid",
        "vægt": 125,
        "billede": "smoereostpikant.jpg"
    }
}]
```

### GET /cheeses/\<varenummer>

Resursen repræsenterer en enkelt os i kartoteket

Resursen er formateret på følgende måde:

```JSON
{
    "varenr":1235,
    "navn":"feta",
    "pris":2144,
    "producent":"Arla",
    "antal":15,
    "beskrivelse":{
        "tekst":"Græsk feta er en hvid blød ost i saltlage. Den har en mild, men samtidig en tydelig saltsmag. Fetaosten er egnsbeskyttet, så det er kun feta produceret i Grækenland må kaldes Feta. Vi kalder derfor vores ost for Apetina®, når den sælges indenfor EU.",
        "smag":"Salt smag",
        "vægt": 1000,
        "billede":"Leakkerfeta.jps"
    }
}
```