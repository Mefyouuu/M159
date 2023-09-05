# Lernziele: Schriftlicher Teil

## Verzeichnisdienst Grundlagen

### Was ist ein Verzeichnisdienst?
Ein Verzeichnisdienst ist ein System, das Informationen über Ressourcen (z. B. Benutzer, Computer) speichert und bereitstellt, um den Zugriff und die Verwaltung dieser Ressourcen in einem Netzwerk zu erleichtern.

## Directory Services und deren Eigenschaften

### Funktionsweise und Einsatz eines Directory Services
Ein Directory Service ermöglicht die Speicherung, Suche und Bereitstellung von Informationen über Objekte in einem Netzwerk.

### Eigenschaften des Verzeichnisdienstes kennenlernen:
- **Skalierbarkeit:** Die Fähigkeit, mit dem Wachstum der Netzwerkressourcen umzugehen.
- **Erweiterbarkeit:** Die Möglichkeit, neue Attribute oder Objektklassen hinzuzufügen.
- **Sicherheit:** Die Gewährleistung des sicheren Zugriffs auf die gespeicherten Informationen.
- **Verfügbarkeit:** Die kontinuierliche Verfügbarkeit der Dienste.
- **Performance:** Die Effizienz der Abfrage- und Update-Operationen.

## Standards im Microsoft Active Directory (MS AD)

### Welche Standards (X.500, DNS und LDAP) werden im MS AD eingesetzt?
- **X.500:** Definiert die Struktur und Namensgebung im Verzeichnisdienst.
- **DNS:** Dient zur Auflösung von Domänennamen in IP-Adressen.
- **LDAP:** Protokoll zur Kommunikation und Abfrage im Verzeichnisdienst.

## X.500 Standard

### Eigenschaften des X.500 Standards verstehen:
- **Namensbildung (DN, RDN):** Distinguished Name (DN) und Relative Distinguished Name (RDN) für die Identifikation von Objekten.
- **Schemaaufbau mit Objektklassen:** Definition von Objekttypen und deren Attribute.
- **Eigenschaften der Attribute:** Beschreibung von Eigenschaften eines Objekts.

### Begriffe im AD-Schema-Editor oder Attribut-Editor erklären können:
- **Objektbezeichnung:** Der Name eines Verzeichnisobjekts.
- **Objektklasse:** Die Kategorie, zu der ein Objekt gehört.
- **Attributbezeichnung:** Der Name eines Attributs.
- **Attributwert:** Der Wert eines Attributs.

### Unterschiede zwischen Klassen und Attributen erklären.
Klassen definieren Objekttypen, während Attribute Eigenschaften von Objekten beschreiben.

## OID (Object Identifier)

### Was ist eine OID?
Eine Object Identifier (OID) ist eine eindeutige Nummer zur Identifikation von Objekten und Attributen im X.500-Verzeichnisdienst. OIDs werden in verschiedenen IT-Bereichen verwendet, einschließlich Security-Zertifikaten und SNMP-MIBs.

## Replikationsmodelle im X.500 Standard

### Erklären der beiden Replikationsmodelle:
- **Single-Master:** Ein Server ist für bestimmte Änderungen verantwortlich (z. B. Schemaänderungen).
- **Multi-Master:** Mehrere Server können Änderungen vornehmen, wobei Konflikte gelöst werden müssen.

## Domain Name System (DNS)

### Hierarchischer Aufbau und Eigenschaften des DNS-Systems verstehen.
Das DNS ist ein hierarchisches System zur Auflösung von Domänennamen in IP-Adressen.

## Zonentypen im DNS

### Arten von Zonentypen kennenlernen und deren Funktionsweise erklären.
- **Primärzone:** Die ursprüngliche Quelle für DNS-Daten.
- **Sekundärzone:** Eine Kopie der Primärzone zur Redundanz.
- **Stubzone:** Enthält Verweise auf DNS-Server anderer Domänen.
- **AD-integrierte Zone:** Speichert DNS-Zonendaten im Active Directory.

## Domäne und Standort

### Domänenmodell verstehen und grafische Darstellung der Domänen analysieren.
- **Sicherheitsgrenzen:** Trennung von Zugriffsrechten.
- **Schutzschema:** Sicherheits- und Zugriffseinstellungen.
- **DC Empfehlungen:** Empfohlene Anzahl der Domänencontroller.
- **Replikation DC RODC:** Read-Only Domain Controller für sicherheitskritische Standorte.

## Organisational Unit (OU)

### Strukturierungsmöglichkeiten der OU verstehen und Praxisbeispiele zu Themen wie Firmenstrukturabbildung, Verwaltungstätigkeiten, Gruppenrichtlinien und Sichtbarkeit kennen.

## Active Directory Strukturen

### Unterschiede zwischen Einzeldomäne, Domänenstruktur (Tree), Gesamtstruktur (Forest) und Mehrgesamtstruktur (Multi-Forest) verstehen.

## Logische und Physische Sichtweisen

### Unterschiedliche Sichtweisen im Active Directory kennen und deren Darstellungsform und Aufgaben verstehen.

# Lernziele: Praktischer Teil

## AD Grundlagen

- Installation eines AD Servers gemäß Anleitung durchführen.
- Konfiguration des AD-Schema-Editors als MMC-Snap-In und Eigenschaften von Klassen sowie Attributen im Tool finden.
- Erstellen eines Computers, Benutzers usw. im Attribut-Editor und Überprüfung der Einstellungen.
- Verstehen der Wechselwirkung zwischen Schema- und Attribut-Editor.

## Entwurf AD

- Planung eines einfachen Directory Service Konzepts unter Verwendung von Best-Practise Methoden und Merkregeln für die logische und physische Sicht.
- Lösen von Fallbeispielen zur Berechnung der Mindestanzahl von DCs und Definition von Domänenbezeichnungen.
