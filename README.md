# Windows-Laptop als Ergänzung zum MacBook – Kaufentscheidung

**Status:** **Feste Gesamtkaufgrenze 1.100€** (inklusive RAM-Aufrüstung), preiswerter 16GB-SO-DIMM-Einbau möglich; **kein Kauf beschlossen**. **Stand:** 10.11.2026.  
**Ziel:** Einen Windows-Laptop mit guter Preis-Leistung finden, der den bestehenden Mac ergänzt, insbesondere bei paralleler Entwicklungsarbeit und **lokaler KI**. Es soll kein Kauf ausgelöst werden.

> **Hinweis für neue Chats:** Dieses Repository ist die zentrale, fortlaufende Projektakte. Zuerst README.md, ANFORDERUNGEN.md, VERGLEICH.md und KANDIDATEN.md lesen. Bestehende Entscheidungen nutzen; keine bereits beantworteten Fragen wiederholen. Neue Modelle, Preise, Tests und Beschlüsse hier dokumentieren. Nicht belegte Daten als „unbekannt“ markieren.

## Ausgangslage

- **Bestehender Computer:** Apple MacBook mit **M4-Chip, 16 GB Unified Memory und 256 GB SSD**.
- **Gesuchtes Gerät:** zusätzlicher **Windows-Laptop** (kein notwendiger Ersatz für den Mac).
- **Nutzung: ausschließlich Business/KI/Entwicklung, KEIN Gaming.** Eigene digitale Projekte und Online-Business-Workflows; Entwicklung und Automatisierung.
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
- [BUDGET-1100-RAM-GPU-2026-11-10.md](BUDGET-1100-RAM-GPU-2026-11-10.md) – **NEUESTE UND VERBINDLICHE Einschränkung: max. 1100€ insgesamt**, aufrüstbarer Arbeitsspeicher, nicht aufrüstbare NVIDIA-GPU, kaufbarer MSI RTX5060-Deal.
- [NOTEBOOKSBILLIGER-2026-11-10.md](NOTEBOOKSBILLIGER-2026-11-10.md) – **NEUSTER STAND**, konkrete NBB-Angebote/Verfügbarkeit, 32-GB-RAM-Gesamtkosten und Shop-Links.
- [MARKTRECHERCHE-2026-11-10.md](MARKTRECHERCHE-2026-11-10.md) – historische erweiterte Marktanalyse (**drei dort vorgeschlagene Angebote inzwischen vom Nutzer als gelöscht gemeldet**).
- [BERLIN-ANGEBOTE-2026-11-10.md](BERLIN-ANGEBOTE-2026-11-10.md) – **NEUE aktive Berliner Shortlist**, Preise, Verkäufer-Risiken und direkte geprüfte Anzeigenlinks.

## Relevante offizielle Quellen (Stand der Erstaufnahme)

- Ollama GPU-Support: https://docs.ollama.com/gpu
- Docker Desktop GPU unter Windows: https://docs.docker.com/desktop/features/gpu/
- Docker Desktop mit WSL2: https://docs.docker.com/desktop/features/wsl
- Docker Desktop Installation/Anforderungen: https://docs.docker.com/desktop/setup/install/windows-install/

**Aktueller Stand und nächster Schritt:** Nutzer hat drei Favoriten gezeigt: ASUS ROG Strix G17 G713PV-LL145W (1.100 € VB privat), ASUS G713PV-HX058W (1.000 € VB privat), MSI Stealth A16 AI+ A3HVEG-298NN (999 € neu). **ASUS 1 ist bedingt führend**, bietet 16-Kern-CPU und laut SKU WQHD 240 Hz; aber die Anzeige behauptet abweichend FHD 144 Hz. **Vor Kauf exakt Modellnummer und Bildschirm verifizieren, Akkuzustand/SSD/Dauerlast prüfen und Preis verhandeln**. Vergleich und Prüfplan stehen in KANDIDATEN.md, VERGLEICH.md und ENTSCHEIDUNGEN.md. Budget notieren, sobald bekannt. Noch kein Kauf und kein Verkäuferkontakt.


## NEUSTER STATUS vom 10.11.2026 – Berliner Neusuche
**Diese Information hat Vorrang vor der älteren Empfehlung:** Der Nutzer berichtet, dass die zuvor empfohlenen Schenker KEY 15, Lenovo ThinkPad P16 Gen1 und XMG Neo 15 M21 **gelöscht** sind und möchte **möglichst Berlin** (Abholung). Gefunden wurden drei beim Abruf sichtbare Berliner Angebote: **HP Victus 16 Ryzen 7 7840HS/RTX4060 8GB/32GB/1TB in Hellersdorf für 850 € fest**, **Gigabyte AORUS 15 i7-13620H/RTX4060 8GB/32GB/2TB in Prenzlauer Berg für 869 € VB**, **Gigabyte AERO 16 i9-12900H/RTX3080Ti 16GB/32GB/2TB in Reinickendorf für 1.299 € VB** (**nur mit Verhandlung**). Details/Links und mehrere wegen Risiken ausgeschlossene Anzeigen in BERLIN-ANGEBOTE-2026-11-10.md. Keine Live-Verfügbarkeit garantiert, keine Verkäufer kontaktiert.


## AKTUELLSTER STATUS vom 10.11.2026 – notebooksbilliger.de
Der Nutzer meldet **auch die letzte Berliner Shortlist (HP Victus 16, GIGABYTE AORUS 15, GIGABYTE AERO 16 der Privatangebote)** als bereits verkauft. Nicht erneut empfehlen. Jetzt vorerst **notebooksbilliger.de** statt Kleinanzeigen priorisieren. Dort gefunden: GIGABYTE GAMING A16 3VHK3DE894SH, Ryzen 7 260/RTX5060 8GB/16GB RAM/1TB für **1.099€ neu, sofort ab Lager**. **Wichtig: nur 16GB RAM ab Werk, damit nicht auftragskonform.** NBB Crucial DDR5-5600 16GB SO-DIMM **299€** → zusammen 1.398€ + Versand/Einbau. Ab Werk 32GB: GIGABYTE AERO X16 RTX5060 8GB/32GB/1TB **1.599€**, GIGABYTE A18 RTX5060 8GB/32GB/1TB **1.599€**, beide online sofort lagernd. Rund 1.000–1.200€ konnte kein ausreichend starker **sofort verfügbarer 32GB/RTX-Laptop** bei NBB nachgewiesen werden. **Keine Kaufempfehlung über Preisziel ohne Nutzerzustimmung, keine Bestellung.** Details: NOTEBOOKSBILLIGER-2026-11-10.md.


## WICHTIGSTE NEUE VORGABE vom 10.11.2026 – Maximalpreis 1.100 € inklusive RAM
Der Nutzer will **maximal 1.100€ für den gesamten Laptop inklusive nachträglicher RAM-Aufrüstung** ausgeben. Er hält einen **passenden 16GB-SO-DIMM für ~70€ via eBay** für möglich und kann RAM selbst einbauen. Daher werden Laptops mit **16GB ab Werk, 1×16GB + freiem SO-DIMM**, und einer **ab Werk guten NVIDIA-GPU mit >=8GB VRAM** in die Suche aufgenommen. **GPU/VRAM können bei modernen Laptops nicht intern nachgerüstet werden**; externe eGPU nur mit spezieller Schnittstelle und Zusatzkosten. Der aktuell geprüfte **MSI Cyborg 15 B13WFKG-827** mit i5-13420H/RTX5060 8GB/16GB (1×16)/512GB/Win11 kostet **949€ neu** bei MediaMarkt; **bei hypothetischem passenden 70€ RAM Modul wären es 1.019€**. Caveats: RTX5060 nur 55W, nur 1 M.2-Slot, keine Thunderbolt/USB4-eGPU; noch keine Bestellung. GIGABYTE A16 neu 1.099€ +70€ **nicht** budgetkonform; HP Omen FreeDOS 999€ 2×8GB RAM **nicht** durch einfaches +16GB-Modul auf 32GB aufrüstbar. Vollständige Prüfung: [BUDGET-1100-RAM-GPU-2026-11-10.md](BUDGET-1100-RAM-GPU-2026-11-10.md).
