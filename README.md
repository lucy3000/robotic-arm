# Robotic Arm — 6-Achs-Roboterarm im Eigendesign

Ein von Grund auf selbst entworfener 6-Achs-Roboterarm. Lernprojekt mit dem Fokus,
jeden Schritt selbst zu verstehen statt einen Bausatz nachzubauen. Der AR4 von
Annin Robotics dient ausschließlich als Referenz.

## Ziel & Prinzipien

Leitprinzip: **Lerneffekt zuerst**, Leistungsfähigkeit zweitrangig, Kosten drittrangig,
einfache Umsetzung am unwichtigsten.

**Spezifikation (Stand: in Arbeit)**

| Parameter | Zielwert |
|---|---|
| Traglast am Greifer | _noch festzulegen_ |
| Reichweite | _noch festzulegen_ |
| Achsen | 6 |
| Wiederholgenauigkeit | _noch festzulegen_ |

## Aktueller Stand

- [x] Projektstruktur & Repo aufgesetzt
- [ ] Phase 0 — Vorbereitung & Grundlagen
- [ ] Phase 1 — Spezifikation
- [ ] Phase 2 — Mechanische Auslegung
- [ ] Phase 3 — CAD-Modellierung
- [ ] Phase 4 — Prototyping
- [ ] Phase 5 — Elektronik & Software

## Repo-Struktur

| Ordner | Inhalt |
|---|---|
| `docs/` | Projektplan, Entscheidungs-Logbuch, Notizen |
| `01-specification/` | Pflichtenheft, Arbeitsraum-Skizzen |
| `02-mechanics/` | Drehmomentberechnungen, Motor- & Getriebewahl |
| `03-cad/` | Fusion-360-Quelldateien, STL-/STEP-Exporte (via Git LFS) |
| `04-electronics/` | Verkabelungsplan, Stückliste, Pinbelegung |
| `05-software/` | ROS-2-Pakete, Firmware, Kinematik-Code |
| `hardware/` | Stücklisten, Datenblätter |
| `media/` | Fotos, Renderings, Videos |

## Werkzeuge

- ROS 2 Jazzy auf Ubuntu 24.04 (WSL2 / Windows 11)
- VS Code mit WSL-Extension
- Fusion 360 (CAD, Simulation, FEM)
- 3D-Druck für die Strukturteile

## Hinweise

Große Binärdateien (`*.stl`, `*.step`, `*.f3d`, `*.f3z`) werden über
[Git LFS](https://git-lfs.com/) verwaltet. Nach dem Klonen einmalig `git lfs install`
ausführen.

## Lizenz

_noch festzulegen — Vorschlag: MIT für Code, CC-BY-4.0 für Hardware-Designs_
