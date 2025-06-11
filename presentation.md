# Einleitung Motivation Vorstellung
* Haus von 1958 in Werl
  * Hohlblocksteine
  * Größtenteils 2-fach Verglasung
  * Kein Wärmedämmverbundsystem (WDVS)
  * Dach neu gedämmt mit 16cm PUR
  * Ost/Süd/West PV Anlage
  * 6,8 kWh DIY Batterie (LiFePo4)
* 2 Erwachsene, 1 Kind

# Problemstellung / Zielsetzung / Anforderungen
* Gasheizung (17–22 kW), technisch am Ende der Lebensdauer (EOL), inkl. Warmwasser
    * Verbrauch 18.000 - 20.000 kWh Gas pro Jahr ca. 8 kWh / Tag für Warmwasser
    * Nur Heizkörper (Guss sowie Typ 22 und Typ 33), keine Flächenheizung
* Gas ist teuer, klimaschädlich und nur begrenzt vorhanden
* Selbst erzeugter Strom soll mehr genutzt werden
* Wärmepumpen sind geil: thermische Leistung immer über elektrischer Leistung

# Dimensionierung
* DIN Heizlast stark theoretisch vs Wärmemengenzähler (WMZ) vs Auslegung nach Verbrauch in 24h
* Warmwasser getrennt vs integriert
* Warmwasser 200L reicht für 30min duschen oder eine Badewanne
* Modulationsgrenze: 3,0 kW thermisch min
* Ergebnis: Panasonic WH-MDC07**J**3E5 (7kW)

# Material und Werkzeug Fundament
* Treppensteine
* Mörtel
* Bohrkrone für Wanddurchbruch
* Sickergrube herstellen

# Material und Werkzeug Sanitärinstallation
* Rohrsysteme
* Presszange
* Rohr
* Fittinge
* Verschraubungen

# Material und Werkzeug Elektroinstallation
* 5x2,5mm²
* FI 30mA plus 2 Sicherungen
* Shelly PRO 3EM zum Messen
* WLAN für Heishamon

# Hausautomatisierung & Monitoring
* Heishamon Platine
* MQTT Server
* Grafana
* ESPhome

# Aufbau
* Armaturen
* Planungszeichnung
* Zeitlicher Aufwand Warmwasser (neben der Arbeit)
    * ~ 1 Woche Planung
    * ~ 1 Woche Warmwasserspeicher
* Zeitlicher Aufwand Heizung (neben der Arbeit)
    * ~ 4 Wochen Planung
    * ~ 1 Woche Fundament
    * ~ 1 Woche Armaturen
    * ~ 1 Woche Verrohrung
    * Danach: Tests, Optimierung

# Kosten
* Installationsmaterial und Werkzeug: ~1.500 € (davon 900 € für die Presszange)
* Kosten Heizung: 3.800 €
* Kosten Warmwasser: 2.300 €

# Ergebnisse
* Daten aus Grafana
* Raumtemperatur: 21-22°C

## Heizung
* 3.200 kWh Strom pro Jahr Heizung (davon ca. 20% aus PV Erzeugung)
* COP Heizung: ca. 4,5

## Warmwasser
* 350 kWh Strom pro Jahr Warmwasser (davon ca. 80% aus PV Erzeugung)
* COP Warmwasser: ca. 3,2

# Optimierungen & Learnings
* Fast alle Heizkörperventile abgebaut
* Vorlauftemperatur auf 33°C @ 10°C und 40°C @ -10°C
* Verbrauchsoptimierung durch Abschaltung bei stabiler Außen- und Innentemperatur (z.B. 2h mittags, 3h nachts)

# Wartung
* Filter reinigen
* Außengerät reinigen
* Ab und zu ins Monitoring schauen

# Dos und Donts
* (-) Überdimensionierung
* (-) Geringe Rohrdurchmesser
* (o) Klemmringverschraubungen
* (+) Planung im Winter/Frühling
* (+) Ausführung Ende Heizsaison
* (+) Warmwasser zuerst

# Häufige fragen
* Ist ein Hybridsystem sinnvoll?
* Wie funktioniert der Rückbau der Gasheizung?
* Was passiert beim Abtauen?
* Wie schlimm ist Takten?
* Ist eine Kombi aus Trinkwasser und Heizung mit einer Wärmepumpe sinnvoll?
* BAFA-Förderung nur mit Fachunternehmererklärung

# Informationsquellen
* youtube sonnenperle
* haustechnikdialog
* panasonic aquarea wiki
* pipetec dokumentation

# Fragerunde
