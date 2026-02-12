# Protokoll: Linienverfolgung mit Hinderniserkennung

**Datum**: [12.02.2026]
**Gruppe**: [Namen der Teammitglieder]
**Rollenverteilung**:
- Vision Engineer: Magdalena Jahn
- Control Engineer: [Name]
- Safety Engineer: [Name]

## 1. Systemübersicht

### 1.1 Architekturdiagramm
[Skizze oder Beschreibung der Node-Kommunikation]

### 1.2 Verwendete Topics
| Topic | Publisher | Subscriber | Frequenz |
|-------|-----------|------------|----------|
| ... | ... | ... | ... Hz |

## 2. Linienerkennung

### 2.1 Algorithmus
[Kurze Beschreibung: Welchen Ansatz haben Sie gewählt?]

### 2.2 Parameter
- ROI (Region of Interest): [Bildbereich]
- Schwellwert: [Wert]

### 2.3 Herausforderungen
[Was hat gut funktioniert? Was war schwierig?]

## 3. PID-Regelung

### 3.1 Finale Parameter
| Parameter | Wert |
|-----------|------|
| $K_P$ | |
| $K_I$ | |
| $K_D$ | |
| $v$ (linear) | |

### 3.2 Tuning-Prozess
[Welche Werte haben Sie getestet? Was war die Auswirkung?]

| $K_P$ | $K_I$ | $K_D$ | Beobachtung |
|-------|-------|-------|-------------|
| | | | |

### 3.3 Bezug zu VL 10
[Wie haben sich die theoretischen Konzepte in der Praxis bestätigt?]

## 4. Hinderniserkennung

### 4.1 Parameter
- Prüfwinkel: [z.B. -30° bis +30°]
- Stopp-Distanz: [z.B. 0.35 m]

### 4.2 Zuverlässigkeit
[Wie zuverlässig wurde das Hindernis erkannt?]

## 5. Gesamtsystem

### 5.1 Testlauf
- [ ] Linie erkannt
- [ ] Roboter folgt Linie stabil
- [ ] Hindernis erkannt → Stopp
- [ ] Nach Entfernung → Weiterfahrt

### 5.2 Video
[Link oder Dateiname des Videos]

## 6. Fazit

### 6.1 Was haben wir gelernt?
[Wichtigste Erkenntnisse der Übung]

### 6.2 Verbesserungsvorschläge
[Was würden Sie bei mehr Zeit verbessern?]

---

**Erstellungswerkzeuge**: ROS2 Jazzy, Python 3, OpenCV
**Hardware**: TurtleBot 3 Burger