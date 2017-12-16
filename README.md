# TIP = **T**rain-**I**nformation-**P**rojection
We want to use LED Projectors and project information from the Platform on the train. For example: What kind of seats (for disabled people, bicycles, DB.Comfort) are in the wagon. 

Imagine a world where you step down onto the platform. You don't need to look for some small screens but have huge and easy to read projection on the train. You immediately know which waggon you have in front of you and can easily orientate. 
The project is at the moment in the phase of a mvp.

## Tech Stack and used API
### Open Data APIs
- Wagenreihungs Information http://data.deutschebahn.com/dhttps://twitter.com/roikiermedia/status/941990412893507585ataset/data-wagenreihungsplan-soll-daten 

### Tech Stack
- Frontend: Vue.js & Nuxt.js
- Backend: Laravel (PHP) and Couchdb to make the Wagenreihungs Data easily available 

## Contributors
@scammo - Idee, Konzept, API/Backend-Ish  
@roikiermedia - Idee, Konzept, Frontend-ish, Projektion

## #DBHackathon Open Data

More Information: https://dbmindbox.com/en/db-opendata-hackathons/event/e/dbhackathon-dbmindbox-berlin-1516122017/

## Log

### Samstag

#### 14:00
- @roikiermedia hat das Mittagessen verschlafen

#### 12:00
- Wir haben ein Präsentations Mockup erstellt https://twitter.com/roikiermedia/status/941990412893507585

#### 11:00
- DS100 Codes Sind Codes die jeder Bahnhof hat. Volle Liste: http://data.deutschebahn.com/dataset/data-wagenreihungsplan-soll-daten 
- Die Wagenreihungsdaten sind danach sortiert. Heißt für jeden Bahnhof gibt es eine Datei und dann gibt es dadrin für jede Zugnummer die Wagenreihungsdaten

#### 10:00
- Es gibt kein Frühstück mehr

### Freitag
#### 2300
- Wir können folgenden Datensatz benutzen http://data.deutschebahn.com/dhttps://twitter.com/roikiermedia/status/941990412893507585ataset/data-wagenreihungsplan-soll-daten
#### 1910
- Erste Modelle basierend auf: http://download-data.deutschebahn.com/static/datasets/fahrzeuglexikon/Fahrzeuglexikon_2016.pdf and https://twitter.com/roikiermedia/status/941990412893507585
#### 1823
https://twitter.com/roikiermedia/status/941990412893507585- Könnten die Daten vom Zugbgleiter kommen? Also der Zugbgleiter scannt alle Menschen und weiß dadurch wie viel Bestzt ist? Projekt Name: Rispe
- WLAN daten benutzen um besser Load Maganament machen
- Zugreihungs Daten API
- Möglichkeiten Aussichten: Menschen von 2. Klasse auf die 1. Klasse upgraden wenn 2. Klasse voll ist und 1. Klasse noch sehr lehr ist 
- colibri API - Fahrgastzählung



#### 1700
- https://twitter.com/sabrinkmann/status/941703944593641472

