# A/B Testing – Maximum Bidding vs. Average Bidding

##  Projektbeschreibung
Dieses Projekt analysiert die Wirksamkeit zweier unterschiedlicher Gebotsstrategien 
(**Maximum Bidding** und **Average Bidding**) anhand eines A/B-Tests für eine E-Commerce-Website. 
Ziel ist es zu untersuchen, ob sich die beiden Strategien hinsichtlich der 
**durchschnittlichen Kaufanzahl (Purchase)** statistisch signifikant unterscheiden.

##  Datensatz
- Kontrollgruppe: Maximum Bidding  
- Testgruppe: Average Bidding  
- Variablen: Impression, Click, Purchase, Earning  

##  Methodik
- Einlesen und Zusammenführen der Daten  
- Hypothesen: H0 = kein Unterschied, H1 = Unterschied in den Käufen  
- Annahmenprüfung: Normalverteilung & Varianzhomogenität  
- Test: Unabhängiger Zwei-Stichproben-t-Test (α = 0.05)

## Ergebnisse
- Normalverteilung & Varianzhomogenität erfüllt  
- t-Test: **p > 0.05 → H0 kann nicht verworfen werden**  
- Kein signifikanter Unterschied zwischen Kontroll- und Testgruppe in den Käufen


##  Empfehlung
- Beide Strategien (**Maximum Bidding** & **Average Bidding**) können parallel eingesetzt werden  
- Weitere Metriken wie Klicks, Engagement, Revenue und Conversion Rate berücksichtigen  
- Testdauer ggf. verlängern für robustere Ergebnisse
