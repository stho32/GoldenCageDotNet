# KI-Initialisierung

Diese Datei enthält Befehle zur schnellen und effektiven Initialisierung von KI-Tools für die Arbeit mit diesem Projekt.

## Vollständige Projekt-Initialisierung

```bash
# Grundlegende Projektstruktur verstehen
cat README.md
cat CLAUDE.md

# Anforderungen lesen
find ./Dokumentation/Anforderungen -name "*.md" -exec echo "=== {} ===" \; -exec cat {} \;

# Architektur-Dokumentation laden
cat ./Dokumentation/Architektur/CodeStyle.md
cat ./Dokumentation/Architektur/ProgrammierPatterns.md

# Technologie-Stack verstehen
find ./Dokumentation/Technologien -name "*.md" -exec echo "=== {} ===" \; -exec cat {} \;
```

## Standard-Prompts verfügbar machen

```bash
# Security Review Prompt
cat ./Dokumentation/Commands/Security-Review.md

# Code Quality Prompt  
cat ./Dokumentation/Commands/Code-Quality.md

# Architektur-Prüfung Prompt
cat ./Dokumentation/Commands/Architektur-Pruefung.md

# Rechtschreibprüfung Prompt
cat ./Dokumentation/Commands/Rechtschreibpruefung.md
```

## Schnell-Initialisierung (Basis)

```bash
# Nur die wichtigsten Informationen für schnellen Start
cat README.md
cat ./Dokumentation/Anforderungen/README.md
ls -la ./Source/
ls -la ./Tests/
```

## Entwicklungsumgebung verstehen

```bash
# Aktueller Code-Stand
find ./Source -name "*.cs" -o -name "*.csproj" -o -name "*.sln" | head -20
find ./Tests -name "*.cs" | head -10

# Verfügbare Scripts
ls -la ./Scripts/
```

## KI-Prompt für Vollinitialisierung

```
Bitte führe eine systematische Repository-Analyse durch, um den Inhalt effektiv zu verstehen:

1. **Projekt-Überblick verstehen:**
   - Lies README.md für grundlegendes Projektverständnis
   - Studiere CLAUDE.md für Entwicklungsrichtlinien

2. **Architektur und Technologie-Stack analysieren:**
   - Lies alle Dateien in ./Dokumentation/Architektur/ (CodeStyle, ProgrammierPatterns)
   - Studiere alle Technologie-Dokumentationen in ./Dokumentation/Technologien/
   - Verstehe die gewählten Patterns und Technologie-Entscheidungen

3. **Anforderungen und Kontext erfassen:**
   - Lies ./Dokumentation/Anforderungen/README.md für das Format
   - Analysiere alle vorhandenen Anforderungen (R*.md Dateien)
   - Verstehe die fachlichen und technischen Anforderungen

4. **Code-Struktur vollständig analysieren:**
   - Untersuche ./Source/Code/ - analysiere alle .cs, .csproj, .sln Dateien
   - Prüfe ./Source/DBMigrations/ für Datenbankstruktur
   - Analysiere ./Tests/ für Test-Strategien und -Abdeckung
   - Betrachte ./Scripts/ für Automatisierungsskripts

5. **Zusammenhangserkennung:**
   - Verbinde Anforderungen mit Code-Implementation
   - Prüfe Konsistenz zwischen Architektur-Dokumentation und tatsächlichem Code
   - Identifiziere Lücken oder Inkonsistenzen

6. **Status-Report erstellen:**
   - Gib eine strukturierte Zusammenfassung des Repository-Inhalts
   - Bewerte den Implementierungsgrad der Anforderungen
   - Identifiziere nächste Entwicklungsschritte
   - Weise auf potenzielle Verbesserungen hin

Verwende die Standard-Prompts aus ./Dokumentation/Commands/ für spezifische Analysen.
Achte besonders auf die Verbindung zwischen Dokumentation und Implementation.
```

## Einzelne Bereiche initialisieren

### Nur Anforderungen
```bash
cat ./Dokumentation/Anforderungen/README.md
find ./Dokumentation/Anforderungen -name "R*.md" -exec cat {} \;
```

### Nur Architektur
```bash
find ./Dokumentation/Architektur -name "*.md" -exec cat {} \;
```

### Nur Technologien
```bash
find ./Dokumentation/Technologien -name "*.md" -exec cat {} \;
```

## Hinweise

- Führe die Befehle in der angegebenen Reihenfolge aus für optimale KI-Initialisierung
- Die vollständige Initialisierung gibt der KI den besten Kontext für Entwicklungsaufgaben
- Für spezifische Aufgaben reicht oft die entsprechende Einzelbereich-Initialisierung