# Cloud-Migration

## Migrations-stile

Lift and Shift: Das System so wie es ist, auf das selbe OS in die Cloud verschieben.

Re-Plattform

Re-Architecture: System so anpassen, das Services und Tools der Cloud verwendet werden.

## Probleme

Abhängigkeit: Häufig sind die von einer Cloud-Migration betroffenen Systeme eng verzahnt. Z.B. nutzt System B Services und Daten von System A oder beide nutzen eine gemeinsame Datenbank. 

Lösung API: Daten und Dienste von System A werden durch eine API abstrahiert. Dann stellt man System B so um, dass System A nur noch über die API genutzt wird. So kann man B in die Cloud schieben, ohne das A direkt mit migriert werden muss.

