allgemeine Vorarbeiten
=================
- mysql-umstellung@urz.uni-halle.de als Queue in otrs einrichten (tz, 01.07.2011)
- Rechte fuer Thomas Zimmermann und Michael Schaarschmidt auf die Queue im otrs festlegen (tz, 01.07.2011)

Nicht-a6-Accounts bereinigen
============================
- alle nicht-a6 Accounts als csv exportieren (ms, 28.06.2011)
- csv mit allen nicht-a6 Accounts in Nutzerprojekt importieren (ms, 28.06.2011)
- pruefen, welche nicht-a6 Accounts nicht mehr existieren (ms, 28.06.2011)
- Liste der ungueltigen nicht-a6 Accounts (incl. DBs) an Thomas Zimmermann  
  geben (ms, 28.06.2011)
- ungueltige nicht-a6 Accounts in mysql sperren (ms, 28.06.2011)
- alle gueltigen nicht-a6 Accounts per Mail ueber die Umstellung informieren

a6-Accounts bereinigen
======================
- alle a6-Accounts als csv exportieren (ms, 28.06.2011)
- csv mit allen a6-Accounts in Nutzerprojekt importieren (ms, 28.06.2011)
- alle a6-Accounts ohne Referenz (incl. DBs) an Thomas Zimmermann weiter geben (ms, 28.06.2011)
- alle a6-Accounts mit Referenz auf Gueltigkeit der Referenz pruefen (ms, 28.06.2011)
- alle a6-Accounts ohne gueltige Referenz in mysql sperren (ms, 28.06.2011)
- alle a6-Accounts mit gueltiger Referenz per Mail ueber Umstellung informieren (ms, 28.06.2011)

Neue Server installieren
========================
- Server db-mysql.urz.uni-halle.de mit SLES-11 installieren (tz, 01.07.2011)
- mysql-5.5.X auf db-mysql.urz.uni-halle.de installieren (tz, 01.07.2011)
- Server db-mysql-backup.urz.uni-halle.de mit SLES-11 installieren (tz, 01.07.2011)
- mysql-5.5.X auf db-mysql-backup.urz.uni-halle.de installieren (tz, 01.07.2011)
- kerberos-Plugin fuer mysql ausprobieren (ms, ...07.2011)

Backups einrichten
==================
- Master-Slave-Betrieb zwischen db-mysql und db-mysql-backup einrichten (ms, ...07.2011)
- cronjob auf db-mysql-backup zum stuendlichen Backup einrichten (ms, ...07.2011)
- cronjob einrichten, der alle Backups loescht, die: (ms, ...07.2011)
  - aelter als drei Monate sind und um 0:00 Uhr angelegt wurden
