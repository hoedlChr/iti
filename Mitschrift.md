# Modul 1
## Lernziele
### Kühlungsdesign für Rechenzentren erklären und planen
### Infrastrukturelles Bebauungsmanagement erarbeiten
### Serverformfaktoren für definierte Bedarfe auswählen
### Physischen und virtuellen Betrieb differenzieren
### Funktionalitäten von virtuellen Maschinen erläutern
### Sicherheitsfeatures im virtuellen Betrieb beschreiben
### Einsatz der Virtualisierungsebenen erklären
### Lizenzen und Subscriptions differenzieren
### Lizenzverträge unterscheiden
## Lernerfolgskontrolle
### Erklären Sie die Warm- und Kaltgangkonzepte
### Planen Sie ein Kühldesign für ein Rechenzentrum mit 4 Schrankreihen und Doppelboden, wobei eine Schrankreihe besonders hohe Kühlbedarfe aufweist
### Wählen Sie einen Serverformfaktor für eine hoch skalierbare Umgebung mit hoher Packdichte und geringen lokalen Speicherbedarfen aus
### Differenzieren Sie den physischen und virtuellen Betrieb von Servern hinsichtlich der Nutzbarkeit von CPU Ressourcen
### Erläutern Sie vier Funkationalitäten von virtuellen Maschinen
### Beschreiben Sie sechs Sicherheitsfeatures im virtuellen Betrieb
### Erklären Sie konkrete Anwendungsbeispiele für den Nutzung der drei Virtualisierungsebenen
### Differenzieren Sie die Handhabung von Lizenzen mit Software Assurance und Subscriptions
### Unterscheiden Sie  die Lizenzverträge hinsichtlich der Standardisierungspflicht, der Anwendbarkeit (Unternehmens-größe) und der Notwendigkeit einer Softwarewartung
# Modul 2
## Lernziele
### Übertragungstechniken differenzieren
* ATA/IDE
  * Advanced Technology Attachement / Integrated Disc Electronics
  * Festplattencontroller -> Laufwerkselektronik
  * Übertragungstechnik mit 16bit
* SATA
  * Jedes Gerät hat einen eigenen Anschluss
  * Kabellängen von 1m bis 8m
  * 150 bis 600 MB/s
  * 7200U/min
  * Archivsysteme
* SCSI
  * Small Computer System Interface
  * Festplattencontroller ist zentral
  * 5MB/s bis 320MB/s
* SAS
  * Serial Attached SCSI
  * 15000U/min
  * Höhere Verfügbarkeit
* NVME
  * Nonvolatile Memory Express
  * SSDs
  * mit PCIe Bus
* Fibre Channel
  * Storage Area Networks
  * 5 Level
  * Upper Layer Protocols
### Disksybsysteme erklären und auswählen
* RAID
  * RAID 0
    * high performance
    * keine Redundanz
  * RAID 1
    * Spiegerlung der Platten
  * RAID 5
    * Blockweises Striping über alle Platten
    * eine Platte kann ausfallen
  * RAID 10
    * RAID 0 und 1
* JBOD
  * Just a bunch of disks
### Storagesysteme beschreiben und auswählen
* Primärspeicher
  * SSD, RAID und NAS
  * Direkt am Server oder Speichernetzwerk
* Sekundärspeicher
  * langsame Speichersysteme, Backupsoftware
* Archivspeicher
  * auf weiteren Datenträger ausgelagert
* DAS
  * Direkt Attached Storage
  * Tier 1 und Tier 0
  * Datenbank bzw. Caching
  * nur ein Host
  * SATA, SAS, eSATA, USB, FireWire
* NAS
  * Network Attached Storage
  * Alternative zu SAN
  * Clients Anbindung
  * Tier 2 und Tier 3
  * Backup-to-Disk
  * SMB, CIFS, NFS
* SAN
  * Storage Area Network
  * Eigenes System
  * Verschiedene Hersteller
  * Teuere Komponenten
  * Komplizierte Konfig
  * Tier 0 und Tier 1 sowie Tier 2 und Tier 3
  * Fibre Channel Protokoll
### Unified Storage beschreiben
* any type of data on a single operating environment
### Storageportfolios analysieren
### Kennzahlen erläutern
* RPO - Recovery Point Objective - Data Loss
* RTO - Recovery Time Objective - Recovery Time
### Redundanzformen erklären
* Operational Recovery
* Remote Backup Disaster Recovery
* Business Continuance
* Continuous Availability
### Cluster-Funktionalitäten differenzieren
* Single Loop
* Double Loop
* Standard Cluster (2 Heads, 4 Disk Shelfs)
* Metro Cluster (2 Heads, 8 Disk Shelfs)
## Lernerfolgskontrolle
### Differenzieren sie SAS und SATA, nennen Sie deren Einsatzgebiete und leiten Sie deren Herkunft her
* SATA
  * Serial ATA
  * Controller auf der Festplatte 
  * 72000U/min
* SAS
  * Serial Atached SCSI
  * RAID
  * Controller nicht auf der Festplatte
  * 15000U/min
### Erklären sie die RAID Level; 0, 1, 5 und 10
* RAID 0
  * Keine Redundanz
  * Extrem Schnell
* RAID 1
  * Eine von zwei kan Ausfallen
  * 1:1 Kopie
* RAID 5
  * Drei Festplatten eine kann ausfallen
* RAID 10
  * Kombi aus 1 und 0
### Wählen Sie ein Disksubsystem für einen hochredundanten und performanten Betrieb aus
* RAID 10 ?
### Beschreiben Sie drei Storagetypen für eine leistungsfähige Umgebung mit vom Netzwerk getrennter Datenführung aus
* DAS
* SAN
* NAS?
### Beschreiben Sie den Begriff Unified Storage
* any type of data on a single operating environment
### Analysieren Sie das Storageportfolio eines Hersteller hinsichtlich Blockstorage mit hoher Speicherkapazität
### Erläutern Sie die Kennzahlen RPO und RTO
* Recovery Point Objective - wie viele Daten wurden verloren
* Recoery Time Objective - wie lange ist das letzte backup her
### Erklären Sie die vier NetApp Redundanzformen inklusice der benötigten Komponenten
* Single Loop
* Double Loop
* Standard Cluster (2 Heads, 4 Disk Shelfs)
* Metro Cluster (2 Heads, 8 Disk Shelfs)
### Differenzieren Sie die NetApp Standard und Metro Cluster hinsichtlich der Redundanzfunktionalitäten im Detail
# Modul 3
## Lernziele
### Sicherungskennzahlen ableiten und darstellen
* DownTime
  * 99% -> 87h 22min
  * 99,5% -> 43h 41min
  * 99,9% -> 08h 45min
  * 99,99% -> 00h 52min
  * 99,999% -> 00h 05min
* Service Level Requirements (SLR)
  * Anforderung vom Kunden
* Service Level Targets (SLT)
  * Möglichkeit seitens des internen Dienstleisters
* Service Level Agreements (SLA)
  * Vereinbarung Kunden interner Dienstleister
* Operation Level Agreements (OLA)
  * Interne Vereinbarung von SLA zu Endkunden
* Underpinning Contracts (UC)
  * Externe Vereinbarung von SLA zu Endkunden
* Mean Time Between Failures (MTBF)
  * Zeit zwischen zwei Fehlern
* Mean Time To Repair (MTTR)
  * Zeit des Ausfalls
* Mean Time To Failure (MTTF)
  * Zeit von Reperatur zu nächsten Fehler
### Service Level Typen differenzieren
### Auswahl an Sicherungsmedien beschreiben
* USB / SD
* DVD / Blu Ray
* Festplatte (eSATA)
* NAS - Systems
* Dediziertes BackUp-2-Disk
* Cloud Backup
### Sicherungsarten mit Vor- und Nachteilen gegenüberstellen und für ein Fallbeispiel auswählen
* Vollständige Sicherung
  * Jeden Tag vollgas Sicherung
* Inkrementelle Sicherung
  * Sicherung der Änderung vom letzten Inkrement
  * WH: Vollständige und alle dazwischen
* Differenzielle Sicherung
  * Sicherung der Änderung in Bezug auf Voll Sicherung
  * WH: Vollständige und letzte Sicherung
### Technische Sicherungsstrategien erklären
* Synthetische Sicherung
  * Vollständige und inkrementelle Sicherungen werden regelmäßig zu einem vollständingen Sicherungssatz zusammengefasst
  * Incremental Forever bzw. reversa Deltas bezeichnet
* Deduplizierung
  * Daten werden einmal gesichert, zeiger zeigt auf weitere stellen wo daten liegen
  * Größe hängt von den blöcken ab
* Spicherabbild Sicherung
  * Datenmenge wird 1 : 1 gesichert
### Fragestellungen und Anforderungen zur Entwicklungs von Sicherungsstrategien ableiten
* Fragestellung
  * Wer?
  * Welche Daten?
  * Wann?
  * Welches Speichermedium?
  * Wo?
  * Wie lange und viele Generationen?
  * Wann und wie überprüft?
* Anforderungen
  * Regelmäßigkeit
  * Aktualität und Änderungshäufigkeit
  * Verwahrung und Gesetze
  * Prüfung der Vollständigkeit und Integrität
  * Zugänglichkeit
  * Prüfung auf Wiederherstellbarkeit
  * Datenkompression
  * Zeitfenster
  * Löschung von alten Sicherungen
## Lernerfolgskontrolle
### Leiten Sie drei vorgestellte Sicherungskennzahlen ab
* Mean Time Between Failures (MTBF)
  * Zeit zwischen zwei Fehlern
* Mean Time To Repair (MTTR)
  * Zeit des Ausfalls
* Mean Time To Failure (MTTF)
  * Zeit von Reperatur zu nächsten Fehler
### Differenzieren Sie die fünf Verträge für die Konkretisierung von Service Levels und beschreiben Sie deren Unterschiede
* Service Level Requirements (SLR)
  * Anforderung vom Kunden
* Service Level Targets (SLT)
  * Möglichkeit seitens des internen Dienstleisters
* Service Level Agreements (SLA)
  * Vereinbarung Kunden interner Dienstleister
* Operation Level Agreements (OLA)
  * Interne Vereinbarung von SLA zu Endkunden
* Underpinning Contracts (UC)
### Beschreiben Sie die Auswahl von Sicherungsmedien
### Stellen Sie drei Sicherungsarten gegenüber
* Vollständige Sicherung
  * Jeden Tag vollgas Sicherung
* Inkrementelle Sicherung
  * Sicherung der Änderung vom letzten Inkrement
  * WH: Vollständige und alle dazwischen
* Differenzielle Sicherung
  * Sicherung der Änderung in Bezug auf Voll Sicherung
  * WH: Vollständige und letzte Sicherung
### Zählen Sie Vor- und Nachteile von drei Sicherungsarten auf
### Unterscheiden Sie Deduplizierungsmethoden und -punkte
* Methode
  * Dateibasierte Deduplizierung
  * Blockbasierte Deduplizierung
* Punkte
  * Client Deduplizierung (hohe Clientauslastung, geringe Netzwerklast)
  * Server Deduplizierung (intensive Netzwerklast)
### Erklären Sie drei technische Sicherungsstrategien
* First In - First Out
  * Sobald Speichermedien über einem Wert gefüllt, älteste Sicherung gelöscht
* Grandfather - Father - Son
  * Son: Jeden Tag
  * Father: Jede Woche
  * Grandfather: Jeden Monat
* Türme von Hanoi
  * Erstes Medium: jeden zweiten Tag: 1, 3, 5, 7, 9, 11, 13, 15
  * Zweites Medium: jeden vierten Tag: 2, 6, 10, 14,
  * Drittes Medium: jeden achten Tag: 4, 12,
  * Viertes Medium: jeden zweiten Tag: 8, 16,
### Leiten Sie Fragestellungen und Anforderungen zur Entwicklung von Sicherungsstrategien ab
# Modul 4
## Lernziele
### Infratructure Ansätze differenzieren
* traditional infrastructure+
  * Getrennte Komponenten in Computing, Storage und Network
* converged infrastructure
  * Kombinierte Komponenten in Computing, Storage und Network
* hyperconverged infrastructure
  * Erweitert Converged Infrastructure um automatisierung und konsolidierte Rechenzentrumsfunktionen
* cloud infrastructure
### Software Defined Networking und Software Defined Storage beschreiben und mit traditionellen Ansätzen vergleichen
* Software Defined Networking
  * Control Plane
    * Abstraktion Hardware implementierten Kontrollschicht
    * Ordnungsgemäßen Datenverkehr
  * Data Plane
    * Paketweiterleitung
    * Bestandteil der einzelnen Netzwerkgeräte
  * Kommunikationsschnitstelle dazwischen
    * OpenFlow realisiert
  * Zentralisierte Kontrollinstanz
  * Klare Trennung zwischen Hardware und Steuerungsebene
  * Frei pgrammierbare Control Plane
  * Zugriff per Software auf Datenschicht
  * leicht Skalierbar
* Software Defined Storage
  * Abstrahiert die zugrunde liegende Storage Hardware durch eine virtuelle Datenebene
  * != Storage Virtualisierung (Storage Virtualisierung: virtualisiert vor SDS; SDS: visualisiert danach)
### Architektur eines Software Defined Datacenter ableiten
* Rechenzentrumsfaktoren in einer Softwareschicht zusammengeführt
* Abstraktion der Ressourcen
### Eigenschaften von Cloud Computing nennen
* On-Demand Self-Service
  * User selbstständig Ressourcen anfordern
* Broad Network Access
  * Standardisierte Methoden
* Measured Service
  * Cloud Angebot wird überwacht, transparenz
* Ressource Pooling
  * Zusammenschluss von Recheninstanzen
* Rapid Elasticity
  * ausstellung von Kapazität muss schnell und bedarfsgerecht erfolgen
### Cloud Servicemodelle erklären und auswählen
* Infrastructure as a Service (IaaS)
  * Rechen- und Speicherleistung (AWS)
* Platform as a Service (PaaS)
  * Entwickler eigene Anwendungen erstellen und ausführen (Windows Azure)
* Software as a Service (SaaS)
  * vorgefertigten Software Lösungen (Google Apps)
### Cloud Bereitstellungsmodelle unterscheiden
* Private Cloud
  * Individuell
  * Datensicher und Compliant
  * Skaleneffekte und Kosteneinsparungen
  * Corporate Cloud
  * Managed Cloud
  * Outsourced Cloud
* Hybrid Cloud
  * Mischform aus Private und Public Cloud
  * Lastspitzen und Ausfällen auf Public Cloud
  * Herausforderung im Design, Security und Service Integration
* Public Cloud
  * Öffentliche Infrastruktur
  * Skaleneffekte
  * keine/wenig Individuelle Anpassungen
* Community Cloud
  * Kundenzugang zu einem ERP-System, um Serviceaufträge zu erstellen bzw. Bestellungen einzusehen
* Multi Cloud
  * Parallele Nutzung von Cloud-Diensten und Cloud Plattformen, mehrere Anbieter
### Chancen und Risiken der Cloud Nutzung aufzählen
* Chancen
  * Strategisch
    * Entwicklung neuer Businessmodelle
    * Short Time to Market
    * State of the Art Technology
    * Fachabteilung höhere Verantwortung
    * Hohe Systemverfügbarkeit
  * Finanziell
    * Reduktion der Investitionskosten in eigene IT-Infrastruktur
    * Verringerung der Kapitalbindung durch Pay per Use Modelle
    * Nierdigere Betriebs- und Wartungskosten
  * Operativ
    * Schnelle Skalierung der IT-Infrastruktur
    * Schnelle Realisierung von IT-Projekten
    * Reduzierte Administrations- und Wartungsaufwand
    * Einfachter ortsunabhängiger Zugriff
* Risiken
  * Verlust des direkten Einflussbereiches der Unternehmen
  * Zentrale Datenmengen bieten eine große Angriffsfläche
  * Schwierigere Data-Loss-Prevention
  * Fehlendes Vertrauen in Datenschutz- und Datensicherheitskonzepte
  * Unzureichende Interoperabilitöt der Dienste
  * Verlagerung des Verantwortungsbereiches
  * Schatten-ITs durch unkontrollierte Cloud Nutzung
  * Ausfall des öffentlichen Netzwerks bedeutet Ausfall des Services
## Lernerfolgskontrolle
### Differenzieren Sie Infrastructure Ansätze
* Traditional Infratructure
* Converged Infrastructure
* Hyperconverged Infrastructure
* Cloud Infrstructure
### Vergleichen Sie Software Defined Networking und Software Defined Storage mit traditionellen Ansätzen und beschreiben Sie die beiden Begriffe
- Bild auf Folie
### Nennen Sie die Eingeschaften von Cloud Computing

* On-Demand Self-Service
  * User selbstständig Ressourcen anfordern
* Broad Network Access
  * Standardisierte Methoden
* Measured Service
  * Cloud Angebot wird überwacht, transparenz
* Ressource Pooling
  * Zusammenschluss von Recheninstanzen
* Rapid Elasticity
  * ausstellung von Kapazität muss schnell und bedarfsgerecht erfolgen
### Wählen Sie ein Cloud Servicemodell für einen spezifischen Anwendungsfall aus und erklären dieses
* Traditional/On Premise IT
* Colocation
* Hosting
* IaaS
* PaaS
* SaaS
### Unterscheiden Sie die fünf Cloud Bereitstellungsmodelle
* Private Cloud
  * Individuell
  * Datensicher und Compliant
  * Skaleneffekte und Kosteneinsparungen
  * Corporate Cloud
  * Managed Cloud
  * Outsourced Cloud
* Hybrid Cloud
  * Mischform aus Private und Public Cloud
  * Lastspitzen und Ausfällen auf Public Cloud
  * Herausforderung im Design, Security und Service Integration
* Public Cloud
  * Öffentliche Infrastruktur
  * Skaleneffekte
  * keine/wenig Individuelle Anpassungen
* Community Cloud
  * Kundenzugang zu einem ERP-System, um Serviceaufträge zu erstellen bzw. Bestellungen einzusehen
* Multi Cloud
  * Parallele Nutzung von Cloud-Diensten und Cloud Plattformen, mehrere Anbieter
### Zählen Sie Chancen und Risiken der Cloud Netzung auf

* Chancen
  * Strategisch
    * Entwicklung neuer Businessmodelle
    * Short Time to Market
    * State of the Art Technology
    * Fachabteilung höhere Verantwortung
    * Hohe Systemverfügbarkeit
  * Finanziell
    * Reduktion der Investitionskosten in eigene IT-Infrastruktur
    * Verringerung der Kapitalbindung durch Pay per Use Modelle
    * Nierdigere Betriebs- und Wartungskosten
  * Operativ
    * Schnelle Skalierung der IT-Infrastruktur
    * Schnelle Realisierung von IT-Projekten
    * Reduzierte Administrations- und Wartungsaufwand
    * Einfachter ortsunabhängiger Zugriff
* Risiken
  * Verlust des direkten Einflussbereiches der Unternehmen
  * Zentrale Datenmengen bieten eine große Angriffsfläche
  * Schwierigere Data-Loss-Prevention
  * Fehlendes Vertrauen in Datenschutz- und Datensicherheitskonzepte
  * Unzureichende Interoperabilitöt der Dienste
  * Verlagerung des Verantwortungsbereiches
  * Schatten-ITs durch unkontrollierte Cloud Nutzung
  * Ausfall des öffentlichen Netzwerks bedeutet Ausfall des Services