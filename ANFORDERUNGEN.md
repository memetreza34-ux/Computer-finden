# Anforderungen und Nutzungsszenarien
**Erfasst:** 10.11.2026. **Quelle für persönliche Anforderungen:** Angaben des Nutzers im Gespräch. Unbekanntes nicht ergänzen oder schätzen.

## A. Vorhandenes Gerät und Kaufziel
- MacBook mit Apple M4, 16 GB RAM (Unified Memory), 256 GB SSD.
- Ergänzung durch **Windows-Laptop**; keinesfalls automatisch das MacBook ersetzen.
- Nutzung für eigenständige digitale Geschäfts-/Entwicklungsprojekte, Software, KI-Werkzeuge und GitHub/Open-Source-Experimente.
- **Muss:** 32 GB RAM oder mehr; mindestens 512 GB SSD; gute CPU; Windows.
- **Offen:** Budget, maximale Bildschirmgröße/Gewicht, neu vs. gebraucht, Akkulaufzeitpriorität, Kaufzeitpunkt und konkrete drei Modelle.
- **Wünschenswert, abhängig von Preis und wirklichem Mehrwert:** dedizierte NVIDIA-GPU, 1 TB SSD, RAM- und SSD-Aufrüstbarkeit.

## B. Nutzungsszenario 1: Cloud-KI / moderne Entwicklungswerkzeuge
Werkzeuge als Beispiele: Claude Code, Codex, Antigravity und vergleichbare servergestützte KI. Daneben IDEs, Git/GitHub, Browser mit vielen Tabs, lokale Testserver, Dev-Tools, Datenbanken.

Wichtig:
1. Gute CPU-Dauerleistung und schnelles Multitasking.
2. Mindestens 32 GB RAM bei vielen parallelen Prozessen.
3. SSD-Kapazität, schnelles I/O, zuverlässiges Netzwerk und Windows-Kompatibilität.
4. Tastatur, Display, Anschlüsse, Geräuschpegel und Arbeitstauglichkeit.
5. **Keine unnötigen Ausgaben für GPU nur wegen Cloud-KI:** Der eigentliche Sprachmodell-Rechenaufwand kann auf entfernten Servern stattfinden. Lokale Builds oder spezielle Workflows können dennoch GPU/CPU benötigen.

## C. Nutzungsszenario 2: Lokale KI, Docker, GitHub-Projekte
Beispiele: Ollama, selbst gehostete LLMs, Embedding-/RAG-Tests, lokale API-Dienste, Docker Compose, GitHub-Open-Source-Stacks, WSL2/Linux-Entwicklung.

Wichtig:
1. **VRAM der GPU**: kontrollieren, ob eine dedizierte GPU und wie viel eigener Videospeicher vorhanden sind.
2. **NVIDIA/CUDA bevorzugt**, da für viele lokale-KI- und GPU-Docker-Workflows breiter unterstützt. AMD/iGPU ggf. prüfen statt pauschal ausschließen.
3. **32 GB Arbeitsspeicher Minimum**, bei mehreren Containern + CPU-Offloading kann 64 GB sinnvoll sein.
4. **512 GB SSD Minimum**, 1 TB bevorzugt wegen großer Modellgewichte, Container-Images und Repositories.
5. Funktionierende **WSL2-/Virtualisierungs- und Treiberunterstützung**, vorzugsweise Windows 11 auf x86-64.
6. **Thermik, Leistungslimits (Laptop-GPU-TGP), Netzteil, Aufrüstbarkeit** klären.

### Grobe Einordnung – nicht als exakte Modellgarantie verwenden
- **Ohne dedizierte GPU:** Cloud-KI, Docker, Programmierung und kleine lokale Modelle möglich; lokale Inferenz mit CPU/iGPU kann deutlich langsamer sein.
- **8 GB dedizierter VRAM:** sinnvolle Einstiegsklasse, etwa für viele quantisierte 7B/8B-Modelle. Kontextfenster und Runtime-Overhead mit einrechnen; größere Modelle können zum Teil im RAM laufen, dann mit Tempoverlust.
- **12–16 GB VRAM:** attraktiver für größere Quantisierungen bzw. Modelle, komplexere lokale Tests, mehr Reserven.
- **Noch mehr VRAM:** gut für große lokale Modelle, aber Preis und tatsächlicher Nutzen müssen passen.
- Ein **„AI“-Prozessor / NPU-TOPS-Wert** allein ist kein Ersatz für den RAM-/GPU-VRAM-Vergleich.

## D. Prüfpunkte vor einer Kaufempfehlung
- Exakte Modellnummer/SKU und **echte Konfiguration im Inserat**.
- CPU-Generation, Kern-/Leistungsprofil, Benchmarks und bekannte thermische Grenzen.
- GPU-Modell **plus VRAM, TGP**, Kühlung und Praxisleistung (insbesondere Ollama).
- RAM: verlötet oder aufrüstbar, maximaler Ausbau, 1x32 vs 2x16 und belegte Slots.
- SSD: Kapazität, zweiter M.2-Slot, austauschbar.
- Displayhelligkeit/-auflösung, Tastatur, Touchpad, USB-C/USB4/Thunderbolt, WLAN.
- Akkuzustand (gebraucht), Lärm, Gewicht, Ladegerät, Garantie/Gewährleistung.
- Preis neu/gebraucht, Verkäuferzuverlässigkeit, tatsächlicher Zustand, Rückgabe.
- Preis-Leistungs-Gewinn gegenüber dem bereits vorhandenen MacBook.
- Falls **Windows on ARM**: zusätzliche Software-/Treiberkompatibilität individuell prüfen; x86-64 standardmäßig bevorzugen.

## E. Bewertungskonflikte
- **Gaming-Laptop**: meist attraktiver GPU-Preis, aber schwerer/lauter/schwächere Batterie.
- **Business-Notebook**: oft kompakter/leiser, aber häufig ohne leistungsfähige dedizierte GPU.
- **CPU vs GPU**: für große lokale LLMs kann ein Mehrpreis für 12–16 GB VRAM sinnvoller sein als für die teuerste CPU mit nur 8 GB VRAM.
- **Kauf überhaupt nötig?** Bei ausschließlich cloudbasierten Aufgaben zunächst prüfen, ob das vorhandene MacBook ausreicht und nur externer Speicher/anderer Workflow benötigt wird.

## Technische Referenzen
- Ollama GPU Support: https://docs.ollama.com/gpu
- Docker GPU-Passthrough mit NVIDIA unter WSL2: https://docs.docker.com/desktop/features/gpu/
- Docker Desktop + WSL2: https://docs.docker.com/desktop/features/wsl
- Docker Desktop Windows-Anforderungen: https://docs.docker.com/desktop/setup/install/windows-install/


## Ergänzung 10.11.2026 – ausschließliche Arbeit und Berliner Abholung
- **Definitive Zweckklärung:** **ausschließlich Business/Produktivität, KI-gestützte Softwareentwicklung, Ollama und Docker, NICHT Gaming**. Gaming-Leistung/FPS und RGB sind keine Kaufkriterien; Geräte aus Gaming-Baureihen werden nur wegen ihrer für CUDA nutzbaren Hardware verglichen.
- **Geografie:** **Berlin bevorzugt**, idealerweise persönlich prüfbar bei Abholung. Außerhalb Berlins nur bei besonders gutem, begründetem Vorteil und nach ausdrücklicher Erwägung.
- **Angebotsstatus:** drei erste zusätzliche Empfehlungen (Schenker KEY 15 Karlsruhe, ThinkPad P16 Halle, XMG Neo Neukölln) laut Nutzer gelöscht. Veraltete Suchtreffer nicht als aktuelle Verfügbarkeit werten.
- Budget aus bisherigen Beispielen ungefähr 1.000 €; **keine verbindliche Obergrenze**. Die Berliner Auswahl vom 10.11.2026 enthält zwei Angebote für 850–869 € und eine 16GB-VRAM-Option für 1.299 € VB oberhalb des bisherigen Suchfensters. Siehe BERLIN-ANGEBOTE-2026-11-10.md.


## Finale Preis-/Aufrüstungspräzisierung 10.11.2026
- **Feste Obergrenze: 1.100 € Gesamtpreis**, inklusive Versand und geplantem RAM-Upgrade; Angebote für 1.200 € oder 1.599 € NICHT mehr als budgetkonform empfehlen.
- **16 GB ab Werk akzeptabel**, wenn sicher **auf 32 GB ausbaubar**, vorzugsweise **1×16 GB mit freiem SO-DIMM**; selbst eingebautes kompatibles 16GB-Modul zu angestrebten 70€ über eBay möglich, Preis nicht garantiert.
- **Keine unaufgerüsteten 16GB-Laptops als fertige Lösung ausgeben**; exakte Modul- und Steckplatzbelegung prüfen. DDR5 SO-DIMM vs DDR4/LPDDR/desktop DIMM unterscheiden.
- **NVIDIA-GPU und dedizierter GPU-VRAM nicht intern aufrüstbar**; angemessene GPU und 8GB+ VRAM direkt kaufen, spätere eGPU nicht wirtschaftlich voraussetzen.
- Business/Cloud- und lokale KI, kein Gaming. Für Ollama 8GB VRAM ist Einstieg, mehr bleibt Wunsch; 55W RTX5060 nicht automatisch schneller als 140W RTX4060.
- Suchziel **Laptoppreis max 1.030 €**, falls kompatibler RAM wirklich 70€ kostet; Versand und eventuelle weitere Kosten berücksichtigen.
- Geprüftes aktuelles Händlerbeispiel: MSI Cyborg 15 B13WFKG-827 949€ neu + 70€ angenommenes RAM = 1.019€. Dokumentiert in BUDGET-1100-RAM-GPU-2026-11-10.md.
