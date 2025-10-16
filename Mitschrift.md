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
### Unified Storage beschreiben
### Storageportfolios analysieren
### Kennzahlen erläutern
### Redundanzformen erklären
### Cluster-Funktionalitäten differenzieren
## Lernerfolgskontrolle
### Differenzieren sie SAS und SATA, nennen Sie deren Einsatzgebiete und leiten Sie deren Herkunft her
### Erklären sie die RAID Level; 0, 1, 5 und 10
### Wählen Sie ein Disksubsystem für einen hochredundanten und performanten Betrieb aus
### Beschreiben Sie drei Storagetypen für eine leistungsfähige Umgebung mit vom Netzwerk getrennter Datenführung aus
### Beschreiben Sie den Begriff Unified Storage
### Analysieren Sie das Storageportfolio eines Hersteller hinsichtlich Blockstorage mit hoher Speicherkapazität
### Erläutern Sie die Kennzahlen RPO und RTO
### Erklären Sie die vier NetApp Redundanzformen inklusice der benätigten Komponenten
### Differenzieren Sie die NetApp Standard und Metro Cluster hinsichtlich der Redundanzfunktionalitäten im Detail
# Modul 3
## Lernziele
### Sicherungskennzahlen ableiten und darstellen
### Serive Level Typen differenzieren
### Auswahl an Sicherungsmedien beschreiben
### Sicherungsarten mit Vor- und Nachteilen gegenüberstellen und für ein Fallbeispiel auswählen
### Technische Sicherungsstrategien erklären
### Fragestellungen und Anforderungen zur Entwicklungs von Sicherungsstrategien ableiten
## Lernerfolgskontrolle
### Leiten Sie drei vorgestellte Sicherungskennzahlen ab
### Differenzieren Sie die fünf Verträge für die Konkretisierung von Service Levels und beschreiben Sie deren Unterschiede
### Beschreiben Sie die Auswahl von Sicherungsmedien
### Stellen Sie drei Sicherungsarten gegenüber
### Zählen Sie Vor- und Nachteile von drei Sicherungsarten auf
### Unterscheiden Sie Deduplizierungsmethoden und -punkte
### Erklären Sie drei technische Sicherungsstrategien
### Leiten Sie Fragestellungen und Anforderungen zur Entwicklung von Sicherungsstrategien zu
# Modul 4
## Lernziele
### Infratructure Ansätze differenzieren
### Software Defined Networking und Software Defined Storage beschreiben und mit traditionellen Ansätzen vergleichen
### Architektur eines Software Defined Datacenter ableiten
### Eigenschaften von Cloud Computing nennen
### Cloud Servicemodelle erklären und auswählen
### Cloud Bereitstellungsmodelle unterscheiden
### Chancen und Risiken der Cloud Nutzung aufzählen
## Lernerfolgskontrolle
### Differenzieren Sie Infrastructure Ansätze
### Vergleichen Sie Software Defined Networking und Software Defined Storage mit traditionellen Ansätzen und beschreiben Sie die beiden Begriffe
### Nennen Sie die Eingeschaften von Cloud Computing
### Wählen Sie ein Cloud Servicemodell für einen spezifischen Anwendungsfall aus und erklären dieses
### Unterscheiden Sie die fünf Cloud Bereitstellungsmodelle
### Zählen Sie Chancen und Risiken der Cloud Netzung auf