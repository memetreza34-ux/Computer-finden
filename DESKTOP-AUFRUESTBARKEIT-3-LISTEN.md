# Desktop-PC: Aufrüstbarkeit und Erweiterbarkeit – drei Listen

**Stand:** 11.11.2026  
**Projekt:** Computer-finden  
**Zweck:** Verbindliche technische Prüfliste für die Suche nach einem neuen, langlebigen KI-Desktop-PC (Black Friday 2026).  
**Rahmen:** Bis 1.100 € Gesamtpreis (inkl. Versand und zwingender Nachrüstungen), Onlinebestellung, vorzugsweise Händler mit physischer Filiale in Berlin und geklärter Reklamationsabwicklung. Einsatz: viele parallele Claude-Code-/Codex-/Antigravity-Agenten, Builds, GitHub-Projekte, Docker/WSL2 und lokale Modelle mit Ollama. **Kein Gaming-Fokus.**  
**Noch keine Geräteauswahl oder Kaufentscheidung.**

## Grundregel

Bei üblichen Desktop-PCs sind die meisten ganzen Bauteile **austauschbar**. Die folgenden Kategorien unterscheiden zwischen Eigenschaften, die sich *am vorhandenen Bauteil* nicht erweitern lassen, Zusatzhardware, die *ohne Ausbau* eingebaut werden kann, und Komponenten, die bei einem Upgrade üblicherweise *ersetzt* werden.

## Liste 1 – Eigenschaften, die am vorhandenen Bauteil nicht einzeln aufrüstbar sind

| Eigenschaft | Was geht nicht? | Konsequenz |
|---|---|---|
| **Dedizierter GPU-VRAM** | RTX-Karte mit 8 GB nicht einfach auf 12/16 GB VRAM aufstockbar | Ganze Grafikkarte austauschen |
| **CPU-Kernzahl / CPU-Architektur** | Bestehenden Prozessor nicht um Kerne erweitern | Ganze CPU austauschen (Kompatibilität prüfen) |
| **CPU-Sockel am Mainboard** | AM4 nicht nachträglich in AM5 verwandeln | Mainboard wechseln, gegebenenfalls RAM/CPU ebenfalls |
| **Mainboard-Chipsatz** | B450/B550/B650 nicht auf dem Board in B850 ändern | Mainboard ersetzen |
| **Feste Mainboard-Controller / Anschlüsse** | Einzelnen verbauten Chipsatz-/USB-/LAN-Controller nicht üblicherweise aufrüsten | Zusatzkarten/Adapter möglich, sofern freie Anschlüsse/Slots vorhanden |
| **Fest verlöteter Systemspeicher** | Verlöteten RAM nicht normal wechseln/aufstocken | Für Desktop-Kauf nur Standard-RAM-Steckplätze akzeptieren |

**Wichtig:** Ein Bestandteil kann als ganzes Bauteil trotzdem austauschbar sein; „nicht aufrüstbar“ bezieht sich auf die einzelne Eigenschaft.

## Liste 2 – Erweiterbar, ohne vorhandene Hardware entfernen zu müssen

| Komponente | Gesuchte Voraussetzung | Möglichkeit später |
|---|---|---|
| **Arbeitsspeicher (RAM)** | **Vier DIMM-Steckplätze, 32 GB zunächst als 2 × 16 GB, zwei Slots frei** | Zwei zusätzliche kompatible 16-GB-Module -> 64 GB **ohne Ausbau** der ursprünglichen 32 GB |
| **M.2-/NVMe-SSD** | Mindestens zwei nutzbare M.2-Steckplätze; bei 1 TB ab Werk mindestens einer frei | Zweite SSD ergänzen (z. B. 1 oder 2 TB) |
| **SATA-SSD/HDD** | Freie SATA-Anschlüsse, Stromstecker und Laufwerksplätze | Weitere Laufwerke ohne Ausbau |
| **PCIe-Karten** | Freier, trotz Grafikkarte physisch zugänglicher PCIe-Steckplatz mit passenden Lanes | Zusätzliche Netzwerk-/USB-/Capture-Karten |
| **WLAN/Bluetooth** | M.2-Key-E/PCIe/USB-Lösung und Antennenmöglichkeit | Adapter ergänzen |
| **Gehäuselüfter** | Freie Lüfterplätze, passende Header/Hubs und Platz | Zusätzliche Lüfter |
| **USB-Ports** | Freie interne USB-Header oder PCIe-Steckplätze | Weitere Anschlüsse |
| **SATA-Speicherschächte** | Freie 2,5-/3,5-Zoll-Montageplätze | Zusätzliche SSD/HDD |

### Konkrete RAM-Anforderung (sehr wichtig)

- **Start:** 32 GB als **2 × 16 GB** bei vier physischen Steckplätzen (zwei belegt, zwei frei), Dual Channel.
- **Erweiterungsziel:** 64 GB durch Hinzufügen von **2 × 16 GB**, **ohne** die gekauften 32 GB herausnehmen zu müssen.
- **Vor Kauf prüfen:** Anzahl physischer Slots **und** tatsächliche Belegung (nicht nur „max. 64/128 GB“), unterstützte Gesamtkapazität, konkrete RAM-Norm, QVL/BIOS.
- **Technischer Vorbehalt:** Vier DDR5-DIMMs können geringere Taktraten, BIOS-Einstellungen oder Instabilität verursachen; separat gekaufte Kits sind nicht automatisch garantiert kompatibel. Falls Stabilität entscheidend ist, kann später ein Ersatz durch 2 × 32 GB trotz unseres Wunsches erforderlich oder besser sein. Ein vorhandenes 2 × 16-GB-Kit muss also nicht garantiert mit einem späteren Kit gemeinsam funktionieren.
- **Bei begrenztem Budget:** Ein 2-Slot-Board mit 2 × 16 GB erfüllt zwar die 32-GB-Leistung, **nicht** die gewünschte Erweiterung ohne Ausbau -> im Angebotsvergleich als Abweichung markieren.

## Liste 3 – Austauschbar; normalerweise nur eine Hauptkomponente beziehungsweise ein Hauptsteckplatz

| Bauteil | Austausch möglich? | Worauf achten? |
|---|---|---|
| **CPU** | Ja, im Sockel | Sockel, BIOS-Unterstützung, CPU-Leistungsaufnahme, VRMs/Kühler |
| **Grafikkarte (GPU)** | Ja | Standard-PCIe, Gehäuselänge/-breite, Netzteilreserve, passende Stromstecker; GPU-VRAM nur durch Kartenwechsel erhöhen |
| **Mainboard** | Ja | Gehäuseformat, CPU-Sockel, DDR4/DDR5, Stromanschlüsse, Front-I/O |
| **Netzteil** | Ja | Qualitätsmodell, ATX-Standard, Leistung/Anschlüsse; **keine modularen Kabel verschiedener Netzteile mischen** |
| **CPU-Kühler** | Ja | Sockelhalterung, Höhe, TDP/Leistungsbedarf und Gehäusefreiraum |
| **Gehäuse** | Ja | Standardteile, Platz, Kühlung, Mainboard-/GPU-/Netzteilabmessungen |
| **Boot-SSD bei nur einem M.2-Steckplatz** | Ja | Für mehr M.2-Platz ggf. bestehende SSD tauschen; freie SATA-Ports sind Alternative |
| **RAM bei allen Slots belegt** | Ja | Für Kapazitätsgewinn vorhandene Module ersetzen |
| **CMOS-Batterie** | Ja | Passender Batterietyp |

Zusätzliche GPUs können in manchen Mainboards mit mehreren geeigneten PCIe-Slots eingebaut werden, sind aber für unser Budget **nicht** die Standard-Upgrade-Strategie. Vorher Stromversorgung, Kühlung, PCIe-Lanes und Software-Unterstützung prüfen.

## Suchstandard für neue Komplett-PCs (Black Friday, Budget bis 1.100 €)

| Bauteil | Mindeststandard | Bevorzugt / langfristig |
|---|---|---|
| **Mainboard/Plattform** | Standard-mATX/ATX, nachvollziehbares **genaues** Boardmodell, ausreichend VRM/Kühlung, aufrüstbare RAM/SSD-Steckplätze | **AM5 mit B650/B850** und vier DIMM-Slots, zwei M.2-Steckplätze oder mehr; AM4/B550 nur bei überzeugendem Preisvorteil |
| **CPU** | Solide moderne 6- bis 8-Kern-CPU; keine CPU nur wegen Marketingnamen auswählen | Leistungsfähiger Ryzen 7 oder vergleichbar, gute dauerhafte Multi-Core-Leistung |
| **System-RAM** | **32 GB** im Endpreis; Konfiguration und freie Slots verifizieren | **2 × 16 GB, 2 von 4 Steckplätzen frei**, damit Ausbauziel 64 GB ohne Entfernen; bei 4 DIMMs DDR5-Stabilität prüfen |
| **SSD** | **512 GB NVMe** | 1 TB NVMe mit **freiem zweiten M.2-Slot** |
| **NVIDIA-GPU** | Dedizierte NVIDIA-GPU, mindestens 8 GB VRAM als Kompromiss für lokale KI | 12–16 GB VRAM; exaktes Modell, Stromversorgung und Erweiterungsoptionen prüfen |
| **Netzteil** | Genauer Hersteller/Modellname, ausreichende Leistung, Schutzfunktionen | Solide Markenqualität und Reserven für nächste GPU |
| **Kühlung/Gehäuse** | Ausreichend Kühlung, Gehäuse mit Standardbauteilen | Guter Airflow, Platz für stärkere GPUs und zusätzliche Lüfter |
| **Betriebssystem** | Windows 11 / WSL2 geeignet oder Windowskosten im Gesamtbudget | NVIDIA-CUDA/Ollama/Docker gut unterstützbar |
| **Kaufweg** | Neu, Gesamtpreis <=1.100 €, seriöser Verkäufer | Online-Lieferung nach Hause; **echte Händlerfiliale in Berlin** und klarer Rückgabe-/Gewährleistungsweg für **diesen** Onlinekauf |
| **Verifikation** | Tatsächliche **Endpreis-/Verfügbarkeit**, SKU, Verkäufer und Komponenten schriftlich/auf der Artikelseite nachweisen | Keine Marketplace-Angebote als lokale Filialservice-Garantie ausgeben, wenn Dritthändler zuständig ist |

### Abwägungen und harte Prüfungen

1. **Teuer bzw. schlecht nachzurüsten:** GPU-VRAM nur durch GPU-Tausch; Sockel/Chipsatz nur durch Mainboardtausch. Daher Plattform, Netzteil und Gehäuse nicht wegen eines kurzfristig höheren GPU-Modellnamens opfern.
2. **Leicht erweiterbar:** SSD und RAM, **aber nur bei freien Steckplätzen**. Der Nutzer möchte ausdrücklich vorhandene 32 GB RAM beim späteren Ausbau behalten, keine erzwungene Entsorgung der ursprünglichen Module.
3. **RAM-Ausbau auf DDR5:** Die Anforderung ist ein **physischer Ausbaupfad**, keine pauschale Garantie für stabilen 4-DIMM-Betrieb bei hohem Takt. Anbieter-/Mainboardspezifikationen prüfen.
4. **Cloud-KI vs. lokale KI:** Claude Code/Codex/Antigravity Cloud-Inferenz erfolgt auf Anbieterservern. Lokale Agent-Tools, Docker, Builds und Tests beanspruchen CPU/RAM/SSD der Station; Ollama nutzt bei passender Konfiguration NVIDIA-VRAM.
5. **Endpreis zählt:** Kein Gerät über 1.100 € inklusive zwingender RAM-/Windows-Ergänzung und Versand als budgetkonform bezeichnen. Lieber „nicht nachgewiesen“ als technische Daten/Slots erraten.
6. **Berlin-Filiale:** Filialexistenz reicht nicht. Vor Kauf prüfen, ob Onlineware tatsächlich in Berliner Niederlassung zurückgegeben oder reklamiert werden kann und ob der Verkäufer der Händler selbst statt Marketplace-Partner ist.

## Stand / nächste Entscheidung

Diese Datei hält **nur die technische Prüfliste** fest. Frühere Laptop- und Desktop-Angebote bleiben getrennt dokumentiert, es wurde **nichts bestellt**. Der Nutzer entscheidet anschließend, wie die Recherche weitergeht.
