# Canstein Video Player – Benutzerhandbuch

Willkommen zum **Canstein Video Player**!  
Diese App ermöglicht das Abspielen und Verwalten von Videos mit einem versteckten Admin-Bereich, der per Gesten oder Passcode erreichbar ist.  
Dieses Handbuch beschreibt alle Funktionen im Detail.

---

## Inhaltsverzeichnis
1. [Videowiedergabe](#videowiedergabe)
2. [Admin-Bereich](#admin-bereich)
   - [Aktuelles Video & Steuerung](#aktuelles-video--steuerung)
   - [Einstellungen](#einstellungen)
3. [Video-Bibliothek](#video-bibliothek)
   - [Videos hinzufügen](#videos-hinzufügen)
   - [Reihenfolge ändern & löschen](#reihenfolge-ändern--löschen)
4. [Gestensteuerung](#gestensteuerung)
   - [Zugriffsgeste anpassen](#zugriffsgeste-anpassen)
   - [Gesten aufzeichnen](#gesten-aufzeichnen)
   - [Reihenfolge ändern & löschen](#reihenfolge-ändern--löschen-1)
5. [Passcode-Schutz](#passcode-schutz)
   - [Passcode aktivieren/deaktivieren](#passcode-aktivierendeaktivieren)
   - [Passcode ändern](#passcode-ändern)
6. [Import von Videos](#import-von-videos)
   - [Aus „Fotos“](#aus-fotos)
   - [Aus „Dateien“](#aus-dateien)
7. [Weitere Funktionen](#weitere-funktionen)

---

## Videowiedergabe
- **Automatisches Abspielen**: Beim Start wird automatisch das erste gespeicherte Video geladen und abgespielt.  
- **Fortlaufende Wiedergabe**: Nach Ende eines Videos startet automatisch das nächste.  
- **Fehlerhandling**: Sollte ein Video fehlschlagen oder stocken, wird automatisch das nächste Video gestartet.  
- **Steuerung**: Die Oberfläche zeigt nur das Video. Die Wiedergabe läuft ohne sichtbare Player-Bedienelemente.  

---

## Admin-Bereich
Der **Admin-Bereich** bietet Kontrolle über Videos, Einstellungen und Sicherheitsoptionen.  
Er ist durch eine **Gestenfolge** oder einen **Passcode** geschützt.

### Aktuelles Video & Steuerung
- Anzeige des aktuell spielenden Videos (Name und Speicherort).  
- **Nächstes Video abspielen**: Startet das nächste Video in der Liste.  
- **Bestimmtes Video abspielen**: Öffnet eine Auswahl aller Videos, um ein bestimmtes Video direkt zu starten.  

### Einstellungen
- **Videos**: Öffnet die Video-Bibliothek.  
- **Zugriffsgeste**: Verwaltung der Gestenfolge für den Zugriff auf den Admin-Bereich.  
- **Passcode**: Verwaltung des Passcodes.  

---

## Video-Bibliothek
Die **Video-Bibliothek** listet alle gespeicherten Videos und ermöglicht deren Verwaltung.  

### Videos hinzufügen
1. **Name eingeben** (optional, sonst wird Dateiname genutzt).  
2. **Videoquelle auswählen**:
   - [Aus „Fotos“](#aus-fotos)  
   - [Aus „Dateien“](#aus-dateien)  
3. Mit **Ausgewähltes Video hinzufügen** bestätigen.  

### Reihenfolge ändern & löschen
- Mit **Bearbeiten** (oben rechts) kann die Reihenfolge per Drag & Drop geändert werden.  
- **Nach links wischen → Löschen** entfernt ein Video aus der Bibliothek.  
- Änderungen werden automatisch gespeichert.  

---

## Gestensteuerung
Die App kann durch eine **Gestenfolge** entsperrt werden.  

### Zugriffsgeste anpassen
- Standard-Gestenfolge: **Tippen, Tippen, Langes Drücken, Wischen**  
- Im Menü **Zugriffsgeste** kann die Reihenfolge geändert oder zurückgesetzt werden.  

### Gesten aufzeichnen
- Über **Neu aufzeichnen** können neue Gestensequenzen erstellt werden.  
- Unterstützte Gesten:
  - **Tippen**  
  - **Langes Drücken**  
  - **Wischen**  
- Die neue Folge wird gespeichert und ersetzt die alte.  

### Reihenfolge ändern & löschen
- Mit **Bearbeiten** kann die Reihenfolge der Gesten per Drag & Drop geändert werden.  
- Gesten können per Wisch nach links gelöscht werden.  
- Wenn die Liste leer ist, wird automatisch die Standardfolge wiederhergestellt.  

---

## Passcode-Schutz
Optional kann ein **Passcode** eingerichtet werden, um den Admin-Bereich zusätzlich abzusichern.  

### Passcode aktivieren/deaktivieren
- Im Menü **Passcode** kann ein Passcode aktiviert oder entfernt werden.  
- Wird kein Passcode gesetzt, ist der Admin-Bereich standardmäßig ungeschützt (außer per Gestenfolge).  

### Passcode ändern
1. Bestehenden Passcode eingeben (falls vorhanden).  
2. Neuen Passcode festlegen und bestätigen.  
3. Mit **Fertig** speichern.  

---

## Import von Videos
### Aus „Fotos“
- Über die Schaltfläche **Aus „Fotos“** wird ein Video aus der Fotomediathek importiert.  
- Das Video wird in den App-Speicher kopiert.  

### Aus „Dateien“
- Über die Schaltfläche **Aus „Dateien“** kann ein Video aus der Dateien-App ausgewählt werden.  
- Unterstützte Formate: `.mp4`, `.mov`, `.qt` und weitere Standard-Videotypen.  

---

## Weitere Funktionen
- **Vorschau-Bild**: Jedes Video zeigt eine kleine Miniaturansicht (QuickLook-Thumbnail).  
- **Automatisches Speichern**: Änderungen an Reihenfolge, Gesten oder Passcodes werden automatisch gespeichert.  
- **Zurücksetzen & Animationen**: Gestenfolgen setzen sich automatisch nach einigen Sekunden zurück, falls nicht vollständig eingegeben.  
- **Notfall-Reset**: In den normalen iOS-Einstellungen (unter „Canstein Video Player“) gibt es ein **SettingsBundle** mit dem Schalter  
  **„App beim nächsten Start zurücksetzen“**.  
  - Wenn dieser aktiviert wird, setzt die App beim nächsten Start **nur die Sicherheits-Einstellungen (Passcode und Gestenfolge)** zurück.  
  - **Videos bleiben dabei erhalten.**  

---

✨ Viel Spaß beim Nutzen des **Canstein Video Players**!
