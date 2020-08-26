# Hotspot-driven Testing

Komplexer Code ist anfällig für Regressionen. Häufige Änderungen erhöhen die Regressionswahrscheinlichkeit zusätzlich. Hotspot-driven Testing kombiniert Änderungshäufigkeit mit Komplexität zur Priorisierung von Testkandidaten in 
ungetesteten Bestandscode.

Wir sortieren die Dateien des Projekts nach Anzahl Commits. Die Datei mit den meisten Commits steht oben. Zusätzlich weisen wir die Komplexität jeder Datei aus. Eine Datei mit vielen, nicht zu lang zurückliegenden Commits, hoher Komplexität und geringer Testabdeckung wird zu einem Testkandidat.