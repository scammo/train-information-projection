# TIP = **T**rain-**I**nformation-**P**rojection

![](/client/static/giphy.gif)

We want to use LED Projectors and project information from the Platform onto the train. For example: What kind of seats (for disabled people, bicycles, DB.Comfort) are in the wagon. 

Imagine a world where you step down onto the platform. You don't need to look for some small screens but have huge and easy to read projection on the train. You immediately know which waggon you have in front of you and can easily orientate. 
The project is at the moment in the phase of a mvp.

## FAQ
**What is an LED Projector**
A Projector LED (or german Beamer) is kinda like a normal project but with a few differences: it uses way less energy, it does not need to preheat - the image is instant and the life time is much longer. We think that a beamer on a busy platform will last 3-5 years before it needs to be replaced.

**Can you even see the projection?**
Yes! LED Beamers can be really brigt. You might not see it 100% outside if the sun is really bright in the summer but all the other times. And the white colors of the ICEs and ICs are great projection area. 

**Will the passengers inside the train get blinded?**
With a method called Project Mapping you can only project things on white surfaces and cut out the window. 

**How many projectors would you need per platform?**
We don't really know. Out first thought is that every steps (treppe) and lift (Fahrstuhl) should get a projector and every area around the doors. It would also be cool to project on the whole area but in the end it will also be cost factor. 

**Have you tested it on real trains?**
Nope! We were not allowed to, but the used the "Der kleine ICE" trains for visualising it for presentation. 

**Why not project directly on the platform**
Cool idea, we also thought about it. It could be an addon but if the platform is crowded (keep in mind that an ICE has more than 800 seats) you will have a hard time to see anything that is projected on the floor.


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

