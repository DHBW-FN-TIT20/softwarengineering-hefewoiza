# Systemidee (Konzept in Stichpunkten)

- Entwicklung "authentic Meal Rating Service" (kurz aMRS)

- Ziel
  - Verwirklichung der vom Auftraggeber gewünschten Erweiterung des Informationsportals zum Angebot von Tagesgerichten um eine authentische Bewertung veganer Produkte 

- aMRS
  - verwaltet vegane Produkte des Informationsportals
  - bietet Kunden die Möglichkeit ihr Essen zu bewerten
    - verifiziert Kunden als tatsächliche Käufer
    - überprüft die Bewertung zusätzlich auf Spam- & Scam-Eigenschaften
    - vermeidet so unauthentische Bewertungen
  - speichert ältere vegane Tagesgerichte (x Tage lang) + Bewertungen
    - `(+)` Bewertung zu späterem Zeitraum möglich
    - `(+)` Wiederverwendung von Bewertungen bereits bekannter Gerichte
  - parallel-betriebenes System 
    - `(+)` wenig (teure) Anpassungen am bereits vorhandenen Informationsportal
  
- Käufer-Verifizierung über Scan der Restaurant-Rechnung
  - `(+)` kein "Kassen-Plugin" nötig

TODO: Skript-Punkt "(Auftraggeber), Entwickler und Anwender einbeziehen"
TODO: Skript-Punkt "Widersprüche beseitigen" ?
TODO: Skript-Punkt "Interessenskonflikte klären" ?

## Voraussetzungen an das bereits vorhandene Informationsportals 

- Informationen über Gerichte müssen abrufbar sein (Weg egal (Web-API, ...))
  - vegane Produkte müssen als solche gelabelt sein
  - "Rechnungs-Namen" von jedem Gericht muss gegeben und in Restaurant-Kontext konsistent sein
    - Bsp: "Veganes Tofu-Schnitzel mit Pommes" → "VEG-SCHNITZEL-POMMES"
- Verknüpfung zum Starten des Bewertungs-Prozesses (Aufruf unseres Systems)

## Entwicklungsstufen

1. oben beschrieben
2. Userauthentifikation (→ zusätzliche Authentifizierungsmaßnahme gegen Scam-Bewertungen)

## Kosten

TODO:



QUESTION: "Kennzeichnung der veganen Gerichte" auch auf Legacy System oder nur für unser System?

QUESTION: "Bewertung zu späterem Zeitraum möglich" Wie, wenn nicht mehr auf dem Infoportal? (vielleicht mit generellem Gerichte-Bewerten-Button auf Infoportal)

QUESTION: Braucht man das Event zum Seite-Aktualisieren?

# Ablaufbeschreibung der Systemidee 




QUESTION: Wohin gehört Skript-Thema "Interessenshalter"?