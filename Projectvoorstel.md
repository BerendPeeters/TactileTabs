# Projectvoorstel 
## Door: Berend Peeters (11789891)

## Wat vragen
### 1. Wat is het probleem (niet de oplossing) dat jouw project gaat oplossen. Wees duidelijk en specifiek.
> Er is, naar mijn weten, geen eenvoudig toegankelijke manier om basgitaarnoten te interpreteren met een schermlezer.  
### 2. Wie zijn je toekomstige gebruikers? In andere woorden, voor wie bouw je dit project? 
> Blinde en slechtziende mensen die gebruik maken van een schermlezer, basgitaar spelen en geen muziek braille kunnen lezen.
### 3. In welke setting wordt je project gebruikt?
> Tijdens het leren van een nummer of muziekstuk. Met gebruikmaking van een PC, laptop of smartphone met een schermlezer en de mogelijkheid geluid of braille over te dragen.
### 4. Wat doet jouw oplossing anders of beter dan bestaande oplossingen? Wat is je niche?
> Mijn oplossing is toegankelijk voor alle schermlezer gebruikers zonder dat deze muziek braille hoeven te kennen.

### Schets je oplossing
Omschrijving: Deze website vraagt om een input die een bepaald muzieknummer signaleert. De site neemt deze input en zoekt de bijbehorende bass tab. Deze bas-tab wordt vervolgens omgezet in een voor slechtzienden leesbare vorm en weergegeven op een tweede scherm op een schermlezer vriendelijke manier.

### Index pagina layout:
![Index pagina](index_sketch.png)

### tab pagina layout:
![Tab pagina](tab_sketch.png)

## Features
### Lijst met alle features:
#### - Tab ophalen 
  - Scraping (Want geen API)
    - Maken van een prompt die de juiste info ophaalt 
    - Pup of soortgelijke app integreren 
#### - Transformator 
  - Checken database
  - Schoon maken gescrapte data
  - Vertalen van schone data
  - Opslaan van schoone data 
#### - Toegankelijke webpagina HTML
  - Index pagina
    - Minimalistisch
    - Groote font
    - Kleuren omkeerbaar
  - Tab pagina
    - Minimalistisch
    - Aanpasbare logische font
    - Sublieme schermlezer navigatie 
    - Kleuren omkeerbaar
    - Sneltoetsen 
#### - Account
  - inloggen
  - opslaan 
  - uitloggen
  - Eigen pagina 
    - Python
    - HTML
#### - Download mogelijkheid 
#### - Feedback 
  - Nieuwe tafel toevoegen 
  - Python 
  - HTML

### Noodzakelijke features:
#### - Tab ophalen (Verzamelt ruwedata)
  - Scraping (Want geen API)
    - Maken van een prompt die de juiste info ophaalt 
    - Pup of soortgelijke app integreren
#### - Transformator (Genereert product)
  - Schoon maken gescrapte data
  - Vertalen van schone data
  - Doorspelen vertaalde data
#### - Toeganke webpagina HTML (Toegankelijkheid doelgroep)
  - Index pagina
    - Minimalistisch
    - Groote font
  - Tab pagina
    - Minimalistisch
    - Aanpasbare logische font
    - Sublieme schermlezer navigatie 

### Niet noodzakelijke features:
#### - Transformator 
  - Checken database
  - Opslaan van schoone data in database
#### - Toegankelijke webpagina HTML
  - Index pagina
    - Kleuren omkeerbaar
  - Tab pagina
    - Kleuren omkeerbaar
    - Sneltoetsen 
#### - Account 
  - Registreren
  - Inloggen
  - opslaan/verwijderen 
  - uitloggen
  - Account verwijderen
  - Eigen pagina 
    - Python
    - HTML
#### - Download mogelijkheid 
#### - Feedback 
  - Nieuwe tafel toevoegen 
  - Python 
  - HTML

### Lijst van belang:
#### 1. Feedback 
  - Nieuwe tafel toevoegen 
  - Python 
  - HTML
#### 2. Transformator 
  - Checken database
  - Opslaan van schoone data in database
#### 3. Account 
  - Registreren
  - Inloggen
  - opslaan/verwijderen 
  - uitloggen
  - Account verwijderen
  - Eigen pagina 
    - Python
    - HTML
#### 5. Toegankelijke webpagina HTML
  - Index pagina
    - Kleuren omkeerbaar
  - Tab pagina
    - Kleuren omkeerbaar
    - Sneltoetsen 
#### 6. Download mogelijkheid 

## Requirements
### Bron:
#### > https://www.ultimate-guitar.com/
  - Bron voor tabs
  - API toegang is niet mogelijk vanwege copyright 

### Libraries:
#### > Beautiful Soup of andere parsing library  voor HTML binnen python
  - Tool voor scraping tabs
#### > Flask 
  - Voor het verbinden van Python en HTML
  - In het speciaal
    - Flask
    - flash
    - redirect
    - render_template
    - request

## Wat wordt moeilijk?
- Human error in tabs wegwerken
- Website toegankelijk krijgen
- Alle mogelijke aanslag technieken integreren
- Toegang krijgen tot alle nummers op UG
- Een duidelijk eindpunt creëren

