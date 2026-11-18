# FISI/FIAE-Prüfungsvorbereitung (IHK Köln)

Ein Obsidian-Vault zur Vorbereitung auf AP1 und AP2 für Fachinformatiker:innen Systemintegration (FISI) und Anwendungsentwicklung (FIAE), ausgerichtet auf die Prüfungen im Bezirk der IHK Köln (Aufgabensätze bundeseinheitlich von der ZPA Nord-West, Prüfungskatalog ab 2025). Enthalten sind Lernmodule, Aufgaben, interaktive Trainer, Karteikarten und Probeprüfungen. Gemeinsame AP2-Materialien für beide Fachrichtungen liegen unter `AP2/Gemeinsam`.

## Voraussetzungen

- [Obsidian Desktop](https://obsidian.md/download) installieren.
- Die interaktiven Module verwenden DataviewJS. Dataview ist im Vault unter `.obsidian/plugins/dataview` enthalten und als Community-Plugin eingetragen. Beim ersten Öffnen kann Obsidian fragen, ob Community-Plugins aktiviert werden dürfen.

## Vault herunterladen

Es gibt zwei Wege, den Vault zu bekommen. Wähle **einen** davon:

### Variante A: Mit Git klonen (empfohlen)

Du kannst den Vault später mit `git pull` aktualisieren. Dafür muss Git installiert sein.

1. Ein Terminal öffnen und in den Ordner wechseln, in dem der Vault gespeichert werden soll.
2. Klonen:

   ```powershell
   git clone https://github.com/ycsysynjv8-ux/FIAP-2.git
   ```

### Variante B: Als ZIP herunterladen (ohne Git)

Du brauchst kein Git, bekommst aber keine Updates. Für neue Inhalte lädst du die ZIP-Datei erneut herunter.

1. Die Seite [ycsysynjv8-ux/FIAP-2](https://github.com/ycsysynjv8-ux/FIAP-2) öffnen und **Code → Download ZIP** wählen.
2. Die ZIP-Datei in einen Ordner deiner Wahl entpacken.

### Danach (bei beiden Varianten)

1. In Obsidian **Vault öffnen → Als Vault in einem Ordner öffnen** wählen und den geklonten bzw. entpackten Ordner auswählen.
2. Falls Obsidian den eingeschränkten Modus aktiviert hat, unter **Einstellungen → Community-Plugins** den Modus deaktivieren und Dataview aktivieren. DataviewJS muss in den Dataview-Einstellungen zugelassen sein, damit die interaktiven Module und Probeprüfungen laufen.

> Lernfortschritte und Prüfungsergebnisse werden lokal gespeichert und nicht mit GitHub synchronisiert.

## Aufbau und Nutzung

- `AP1/00 Start` und `AP2/00 Start` enthalten die Einstiegsseiten und Übersichten.
- Unter AP2 sind FISI und FIAE getrennt organisiert; `AP2/Gemeinsam` enthält WiSo, Projektarbeit und gemeinsam nutzbare Inhalte.
- Öffne in Obsidian die Startseite der gewünschten Prüfung und folge den internen Wiki-Verknüpfungen.
- Die Probeprüfungen bieten Timer, interaktive Aufgaben, Musterlösungen und Punkteauswertung. Antworten und Fortschritt werden je nach Modul lokal in Obsidian gespeichert.
- Die Handreichungen und formalen Vorgaben der IHK Köln zur Projektarbeit sind nicht im Vault enthalten (Urheberrecht). Links zu den aktuellen Fassungen stehen in `AP2/Gemeinsam/50 Nachschlagen/IHK Köln – offizielle Informationen.md`.

## Offline-Nutzung

Nach dem Klonen bzw. Entpacken liegen Markdown-Notizen und beigefügte Dateien lokal vor. Obsidian kann sie ohne Internet öffnen. Internet wird für Aktualisierungen von GitHub sowie zum Installieren oder Aktualisieren von Obsidian und Plugins benötigt.
