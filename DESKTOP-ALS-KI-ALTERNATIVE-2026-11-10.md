# Neue Option: stationärer KI-PC statt zweitem Laptop (10.11.2026)

## Anlass und Nutzervorgabe
Der Nutzer sagt: **Laptop wird nur zu Hause und permanent am Strom benutzt. Akku, Gewicht und Display sind nicht kaufentscheidend.** Die vier Anforderungen bleiben: **(1) gute CPU, (2) mindestens 32GB RAM, (3) >=512GB SSD, (4) gute NVIDIA-GPU, idealerweise >8GB dedizierter VRAM**, alle Kosten **maximal 1.100€**. Einsatz Cloud-KI (Claude Code/Codex/Antigravity), Docker/WSL2, GitHub und **lokale Ollama/LLM-Modelle**, kein Gaming. Vorheriger Laptopwunsch ist nicht ausdrücklich aufgehoben: **Desktop-PC ist eine neue Alternative, NICHT bereits die beschlossene Geräteklasse**. Bei Nutzer prüfen, ob Desktop-Tower grundsätzlich infrage kommt. Die ursprüngliche Top4-Laptop-Liste NICHT ändern, bevor er es sagt.

## Neue Erkenntnis
Bei einem Desktop können 12–16GB dedizierter NVIDIA-VRAM für <1100€ möglich sein, samt >=32GB RAM und >=512GB SSD. Besonders für größere lokale LLMs bringt VRAM mehr als ein leistungsstärkerer Prozessor; für CPU-lastige Builds kann ein ASUS Ryzen9 7845HX/7940HX schneller als Desktop Ryzen7 5700X bzw i5-12500 sein. Für Cloud-KI selbst liefert ein besserer Prozessor nicht automatisch mehr Token/s (Modell läuft auf Server). **GPU ist nicht nur für Design relevant, sondern entscheidend für Ollama/CUDA**, daher nicht streichen.

## Anbieter 1: NEU Webplanet Desktop 846€ (am Shop verifiziert)
- **Produktdirektlink**: https://webplanetcomputer.eu/products/kopie-von-webplanet-fluster-ssd-pc-quad-core-office-multimedia-pc-computer-inkl-windows10-64-bit-intel-quad-core-4x2-41-ghz-8gb-ram-256gb-ssd-hdmi-vga-dvd-rw-w11
- **Preis:** 846€ **inkl. MwSt** auf live geöffneter Produktseite (10.11.2026), Bestellbutton vorhanden; Händlerbestätigung der Lagerverfügbarkeit / Zahlungs-/Lieferumfang muss vor Kauf erfolgen.
- **CPU:** Ryzen7 5700X (8C/16T Zen3), **32GB DDR4**, **1TB M.2 SSD**, **NVIDIA RTX3060 12GB GDDR6**, Windows11 Pro installiert/aktiviert laut Verkäufer.
- **Deutschlandversand explizit kostenlos**: https://webplanetcomputer.eu/policies/shipping-policy (WPC Trading GmbH, Steyr, Österreich). Händleradresse/Kontaktdaten vorhanden; Service, Garantie, verwendete Teile und Zahlungsabsicherung prüfen.
- **Nachteile:** ältere RTX3060 kann bei kleineren vollständig in 8GB passenden LLMs langsamer sein als moderne RTX4060/5060, aber +4GB VRAM hilft größeren Kontexten/Modellen; Ryzen7 5700X CPU weit hinter Ryzen9 7845HX bei parallelen Builds. Hauptboard B450M-H, genannte Netzteilmarke CoolerMaster 750W 80+Bronze, konkrete GPU-Hersteller/Speichermodelle beim Verkäufer erfragen.

## Anbieter 2: gebraucht Berlin-Pankow 950€ VB, RTX5060 Ti **16GB**
- **Direktlink** https://www.kleinanzeigen.de/s-anzeige/rtx-5060-ti-16-gb-pc/3562674747-228-3473
- **10.11.2026 Direktseite geöffnet:** Angebot **950€ VB, nur Abholung, Pankow 13187**, RTX5060 Ti 16GB, Intel Core i5-12500 (6 P-Kerne / 12 Threads), **32GB RAM**, **1TB SSD** laut Verkäufer.
- **Wesentliche Einschränkung:** CPU i5-12500 erfüllt „gute CPU“ im allgemeinen Arbeitsalltag, aber nicht „besonders starke Multicore CPU“ wie 12-Kern-Ryzen9. Kein Board-/Netzteil-/Kaufbeleg und keine GPU-Z-Screenshots. Verkäuferaccount „Jaymon“ neuere Plattformhistorie (seit 2025), Reputation „NA JA Zufriedenheit“, andere sehr ähnlich formulierte Anzeige Nr 3554744417 zu **860€** RTX5060Ti 16GB/32GB/1TB mit angeblichem „i5-12400K“ (unplausible Intel-Bezeichnung; i5-12400 oder 12400F bekannt). Das kann ein zweites Gerät oder Fehler sein, aber **Doppel-/Datenrisiko unbedingt klären**.
- **KEINE Kaufempfehlung ohne aktuelle Live-Fotos, CPU/GPU-Z/Taskmanager, SSD-SMART, Benchmark/Temperaturen unter Last, Kaufbelege, GPU-Seriennummer anonymisiert, vor Ort vor Bezahlung testen**. Verkäufer muss erklären, ob zwei verschiedene PCs gemeint sind.

## Anbieter 3: dieselbe Quelle Pankow 860€ VB (Daten unplausibel)
- https://www.kleinanzeigen.de/s-anzeige/rtx-5060-ti-16gb-pc/3554744417-228-3473
- **Bei direktem Abruf am 10.11.2026: 860€ VB** (Suchindex zuvor 920€), 32GB DDR4, 1TB SSD, RTX5060Ti 16GB, angeblich „Intel Core i5-12400K“ – diese Modellbezeichnung im Datenblatt prüfen, wahrscheinlich Händlerfehler. SELBER Anbieter wie 950€-PC. **Keine seriös bestätigte Alternative ohne Nachweise.**

## Sonstige Angebotssichtung
- eBay gewerblicher Verkäufer Hardwareart, RTX3060 12GB / 32GB / 1TB Windows11, **direkte Seite aktuell 1.099€ (nicht ältere Suchpreis 999€)**, „2 verfügbar“, https://www.ebay.de/itm/286967568912. CPU Ryzen7 5700, nicht identisch mit Ryzen7 5700X; Daten und Verkäuferabsicherung abklären.
- Otto X-HARDWARE 869€ Ryzen7 5700X 32GB 512GB RTX3060 12GB: Shopseite zeigt **„leider ausverkauft“**, daher **nicht empfehlen**: https://www.otto.de/p/x-hardware-x-gaming-computer-5700x-32gb-512gb-nvme-ssd-plus-bis-zu-4tb-hdd-gaming-pc-amd-ryzen-7-5700x-nvidia-geforce-rtx-3060-12gb-gddr6-32-gb-ram-4000-gb-hdd-500-gb-ssd-luftkuehlung-windows-11-professional-S0F8M0I1/
- Berlin-Lichtenberg Ryzen7 5700X / RTX5060Ti 16GB / 32GB / 1TB **1.099€** direktes Inserat leitete beim live Öffnen **auf die Kategorienseite um** → **nicht als aktuell lieferbar empfehlen**, auch wenn Suchresultat alt erscheint: https://www.kleinanzeigen.de/s-anzeige/gaming-pc-ryzen-7-5700x-rtx-5060-ti-16gb-32gb-ram-1tb-ssd/3494518740-228-9680
- Berlin-Pankow Ryzen7 5700X / RTX5060Ti 16GB/32GB/1TB **1.000€** Inserat direkt ebenfalls auf Kategorie umgeleitet → **nicht als aktiv empfehlen** https://www.kleinanzeigen.de/s-anzeige/gaming-pc-rtx-5060ti-16gb/3506642046-228-3473
- Gigabyte Aero X16 Ryzen AI7 350 / RTX5060 Laptop **8GB VRAM** / 32GB / 1TB **990€ VB Rosenheim** öffentlich abrufbar: https://www.kleinanzeigen.de/s-anzeige/gigabyte-aero-16-amd-ryzen-ai-7-rtx-5060-32gb-ram-1tb-ssd/3562654075-278-7581 . **Besondere Vorsicht:** Suchresultat änderte GPU zeitweise auf „RTX 5060 Ti Laptop“, die NVIDIA nicht in offizieller Liste der Laptop-GPUs aufführt; Inserat behauptet Thunderbolt4 beim AMD-Gerät, Hersteller nennt USB4. Vor Kauf **genaue GPU per GPU-Z, Seriennummer/SKU, Rechnung, aktuelle Fotos verifizieren**, kein Versand-Vorkasse. Hersteller: https://www.nvidia.com/de-de/geforce/laptops/50-series/ ; https://geizhals.de/gigabyte-aero-x16-1vh93dec64ah-a3504780.html.
- Auch 64GB-RAM RTX3060 12GB PCs <1000€ im deutschen Gebrauchtmarkt vorhanden, aber technische Einzelheiten/Verfügbarkeit und Standort prüfen.

## Vergleich
| Gerät | CPU | RAM | SSD | GPU dedizierter VRAM | Preis |
|---|---|---|---|---|---|
| ASUS G17 Ryzen9 7845HX Laptop (Referenz) | 12C/24T | 32GB | 1TB | RTX4060 8GB | 1000€ VB |
| Webplanet Desktop | Ryzen7 5700X 8C/16T | 32GB | 1TB | RTX3060 12GB | 846€ neu |
| Pankow Desktop Angebot #3562674747 | i5-12500 6C/12T | 32GB | 1TB | RTX5060Ti 16GB | 950€ VB gebraucht |
| Pankow Desktop #3554744417 (unplausible CPU) | „i5-12400K“? | 32GB | 1TB | RTX5060Ti 16GB | 860€ VB gebraucht, verifizieren |
| eBay Desktop Hardwareart | Ryzen7 5700 8C/16T | 32GB | 1TB | RTX3060 12GB | 1099€ neu, gewerblich |

**Besonders zu klären:** Nutzer wollte ursprünglich einen zweiten **Windows-Laptop** neben MacBook M4. Er sagte jetzt ausdrücklich, dass er nur zu Hause bei Netzstrom arbeitet und Display/Akku irrelevant sind. **Desktop als Option anbieten und EINMAL fragen, ob Tower-PC erlaubt ist oder Laptopform zwingend bleibt**. Bis dahin ursprüngliche 4 Laptop-Favoriten NICHT löschen/ersetzen. Für Desktop besteht mögliche sinnvolle Workflow-Alternative als KI-Server, von MacBook aus via SSH/Remote Desktop/VS Code Remote erreichbar. Vor Remote-Betrieb sichere Konfiguration (nur im lokalen Netz, keine offenen Ports).

Stand: 10.11.2026; kein Kauf, keine Verkäuferkontaktaufnahme. Preise/Verfügbarkeiten verändern sich schnell.
