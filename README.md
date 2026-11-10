# Windows-Laptop als Ergänzung zum MacBook – Kaufentscheidung

**Status:** Drei Favoriten erfasst, technische Spezifikationen und Preisumfeld geprüft; **keine Kaufentscheidung**. **Stand:** 10.11.2026.  
**Ziel:** Einen Windows-Laptop mit guter Preis-Leistung finden, der den bestehenden Mac ergänzt, insbesondere bei paralleler Entwicklungsarbeit und **lokaler KI**. Es soll kein Kauf ausgelöst werden.

> **Hinweis für neue Chats:** Dieses Repository ist die zentrale, fortlaufende Projektakte. Zuerst README.md, ANFORDERUNGEN.md, VERGLEICH.md und KANDIDATEN.md lesen. Bestehende Entscheidungen nutzen; keine bereits beantworteten Fragen wiederholen. Neue Modelle, Preise, Tests und Beschlüsse hier dokumentieren. Nicht belegte Daten als „unbekannt“ markieren.

## Ausgangslage

- **Bestehender Computer:** Apple MacBook mit **M4-Chip, 16 GB Unified Memory und 256 GB SSD**.
- **Gesuchtes Gerät:** zusätzlicher **Windows-Laptop** (kein notwendiger Ersatz für den Mac).
- **Nutzung:** eigene digitale Projekte und Online-Business-Workflows; Entwicklung und Automatisierung.
- **Zwei Nutzungsschwerpunkte:**
  1. **Cloud-gestützte KI-Entwicklung:** z. B. Claude Code, Codex, Antigravity und andere Anwendungen, deren wesentliche Modellberechnung über entfernte Server läuft. Lokal wichtig: schnelle CPU, ausreichender Arbeitsspeicher, SSD, Entwicklungsumgebung, Multitasking, stabile Verbindung.
  2. **Lokale KI und Open Source:** Ollama, lokale LLMs, Docker/WSL2, GitHub-Projekte, lokale Dienste und Entwicklungs-Stacks. Hier sind **GPU und insbesondere dedizierter Videospeicher (VRAM)** oft entscheidender als ein sehr teurer CPU- oder NPU-Aufpreis.

## Bereits genannte Mindestwünsche

- Windows
- **32 GB Arbeitsspeicher** oder mehr
- **512 GB SSD** oder mehr
- Gute, moderne CPU
- Optional eine **dedizierte GPU** – für tatsächlich leistungsfähige lokale LLMs stark bevorzugt
- Gute Preis-Leistung; Budget und exakte drei Favoriten **noch unbekannt**

## Vorläufige technische Zielkonfiguration

| Bauteil | Mindestwunsch | Für die geplante Nutzung attraktiver |
|---|---|---|
| Betriebssystem | Windows 11, kompatibel mit WSL2 | Windows 11, WSL2/Virtualisierung nachweislich nutzbar |
| CPU | Leistungsfähige aktuelle x86-64-Mittel-/Oberklasse | Gut gekühlte Ryzen-7-/Core-Ultra-7-H/HS/HX-Klasse oder vergleichbar (exaktes Modell testen) |
| System-RAM | **32 GB** | 32 GB gut, 64 GB bei großem lokalem Multitasking vorteilhaft |
| SSD | **512 GB** | **1 TB** bevorzugt, idealerweise erweiterbar |
| Grafik | iGPU nur mit klarer Einschränkung lokaler KI | NVIDIA RTX Laptop GPU, bevorzugt **mindestens 8 GB VRAM**; 12–16 GB+ ermöglichen größere Modelle |
| Kühlsystem | Keine anhaltende starke Drosselung | Benchmarks unter Dauerlast, Lautstärke, Stromverbrauch prüfen |
| Ausstattung | Vernünftige Tastatur, Anschlüsse, WLAN | Display, Akkulaufzeit, USB-C/Laden, Wartbarkeit, Garantie berücksichtigen |

**Wichtig:** 32 GB normaler RAM sind nicht dasselbe wie 32 GB GPU-VRAM. Eine NPU oder der Marketingbegriff „AI-PC“ ersetzt keine starke GPU für große lokale Sprachmodelle. Die jeweiligen Modellgrößen sind von Quantisierung, Kontextfenster und tatsächlichem Overhead abhängig.

## Wichtige Einordnung

- Für Cloud-KI und viele Coding-Aufgaben ist das **MacBook M4 bereits gut geeignet**; das Windows-Gerät muss einen konkreten Mehrwert bieten, nicht bloß andere Hardware.
- Docker und Ollama funktionieren auch ohne dedizierte NVIDIA-GPU; die Möglichkeiten/Leistung lokaler Modelle sind dann aber je nach Hardware begrenzt.
- Für Windows-Docker mit NVIDIA-GPU-Unterstützung in Linux-Containern sind **WSL2, passende Treiber und GPU-Kompatibilität** wichtig.
- Bei Laptop-GPUs zählen **tatsächlicher VRAM, TGP/Leistungsaufnahme, Kühlung und Dauerleistung**, nicht allein die GPU-Modellnummer.
- Keine unrealistischen Versprechen, dass große KI-Modelle auf einem 8-GB-VRAM-Laptop vollständig und schnell lokal laufen.
- Bei gebrauchten Geräten zusätzlich Akku, Zustand, Garantie, RAM-/SSD-Aufrüstbarkeit und Preisvergleich prüfen.

## Projektdateien

- [ANFORDERUNGEN.md](ANFORDERUNGEN.md) – Ziele, Muss-Kriterien, Wunschmerkmale, Prüfungen.
- [VERGLEICH.md](VERGLEICH.md) – Bewertungssystem, **vorläufiges Ranking**, Verhandlungsheuristiken und Quellen.
- [KANDIDATEN.md](KANDIDATEN.md) – **alle drei konkreten Angebote**, Daten, Quellen, Preise, wichtige Unstimmigkeiten und Besichtigung-Checkliste.
- [ENTSCHEIDUNGEN.md](ENTSCHEIDUNGEN.md) – Verlauf, offene Punkte und Beschlüsse.

## Relevante offizielle Quellen (Stand der Erstaufnahme)

- Ollama GPU-Support: https://docs.ollama.com/gpu
- Docker Desktop GPU unter Windows: https://docs.docker.com/desktop/features/gpu/
- Docker Desktop mit WSL2: https://docs.docker.com/desktop/features/wsl
- Docker Desktop Installation/Anforderungen: https://docs.docker.com/desktop/setup/install/windows-install/

**Aktueller Stand und nächster Schritt:** Nutzer hat drei Favoriten gezeigt: ASUS ROG Strix G17 G713PV-LL145W (1.100 € VB privat), ASUS G713PV-HX058W (1.000 € VB privat), MSI Stealth A16 AI+ A3HVEG-298NN (999 € neu). **ASUS 1 ist bedingt führend**, bietet 16-Kern-CPU und laut SKU WQHD 240 Hz; aber die Anzeige behauptet abweichend FHD 144 Hz. **Vor Kauf exakt Modellnummer und Bildschirm verifizieren, Akkuzustand/SSD/Dauerlast prüfen und Preis verhandeln**. Vergleich und Prüfplan stehen in KANDIDATEN.md, VERGLEICH.md und ENTSCHEIDUNGEN.md. Budget notieren, sobald bekannt. Noch kein Kauf und kein Verkäuferkontakt.
