# Bewertungsmethodik und erste Vergleichsergebnisse

**Stand: 10.11.2026.** Methodik auf die drei konkreten Angebote angewandt. Keine vorgetäuschten gemessenen Benchmarks; wichtige Zustandsdaten fehlen noch.

## Muss-Kriterien (alle drei erfüllen nominell)
- Windows, mindestens 32 GB RAM, mindestens 512 GB SSD, gute CPU.
- NVIDIA-GPU für lokale KI vorhanden. ASUS 1/2: RTX 4060 8 GB; MSI: RTX 4050 6 GB.
- Docker Desktop/WSL2 grundsätzlich softwareseitig möglich; die GPU-Einrichtung muss nach dem Kauf praktisch konfiguriert/getestet werden.

## Gewichte für spätere vollständige Bewertung (100)
| Kategorie | Gewicht |
|---|---:|
| Lokale KI & GPU (VRAM, TGP, Treiber) | 35 |
| Cloud-KI & Entwickleralltag (CPU/RAM/SSD/WSL2) | 25 |
| Preis-Leistung gegenüber echten Alternativen | 20 |
| Zustand, Qualität, Wartbarkeit und Käuferrechte | 15 |
| Mobilität, Display, Anschlüsse, Akku | 5 |

Bei unklarer Modellidentität bzw. unbekanntem Gebrauchtzustand **keine fiktive Gesamtnote** berechnen. Bei der späteren Punktematrix jede Kategorie 0–10, Gesamt = Summe (Punkte/10 × Gewicht).

## Vorläufiges Ergebnis

1. **ASUS ROG Strix G17 G713PV-LL145W, 1.100 € VB:** Hardware vorläufig führend; **Kauf nur nach Aufklärung des Widerspruchs** Anzeige „FHD 144 Hz“ versus SKU „WQHD 240 Hz“. CPU 16 Kerne, RTX 4060 8 GB, 32 GB/1 TB. Bester bedingter Kandidat.
2. **ASUS ROG Strix G17 G713PV-HX058W, 1.000 € VB:** sehr leistungsfähig, gleiche GPU, 12-Kern-CPU und FHD-Display. Bei guter Verhandlung und sauberer Prüfung sehr vernünftig.
3. **MSI Stealth A16 AI+ A3HVEG-298NN, 999 € neu:** kompakter, neu, NPU und modernere Konnektivität; nur 6 GB GPU-VRAM und geringere CPU-Dauerleistung, RAM verlötet. Eher für Cloud-KI und Mobilität als lokale LLMs.

**Ranking kann sich ändern**, wenn der ASUS 1 eine andere SKU/Display-Konfiguration ist, die Geräte verschlissen sind, gebrauchte Verkäuferdaten nicht überprüfbar sind oder eine attraktive Neuware-Alternative auftaucht.

## Preis- und Verhandlungsheuristik
| Gerät | Inserat | Einstiegsvorschlag | Zielbereich | Obergrenze für „gut gekauft“* |
|---|---:|---:|---:|---:|
| ASUS 1 | 1.100 € VB | ~900 € | ~950–1.000 € | ca. 1.050 € bei wirklich gutem Zustand und nachgewiesener WQHD-SKU |
| ASUS 2 | 1.000 € VB | ~800 € | ~850–900 € | ca. 950 € bei wirklich gutem Zustand |
| MSI 3 | 999 € neu | kein Privat-VB | 999 € aktuell | Alternative im Neuwaremarkt prüfen |

* **Keine garantierten Verkaufspreise:** Einschätzung auf Basis gesichteter Anzeigen, technischer Unterschiede, Alter und Sicherheitsrisiko. Angebote sind keine Verkaufstransaktionen.

## Weiterer Vergleich
- ASUS 1 gegenüber ASUS 2: CPU 7940HX (16C/32T) statt 7845HX (12C/24T); **identische RTX 4060 Laptop GPU**; Display laut SKUs **WQHD 240 Hz** statt **FHD 144 Hz**. Bei nur 100 € Inseratsabstand ist das erste Gerät technisch attraktiver, sofern seine Identität stimmt.
- MSI: Ryzen AI 5 340 (6C/12T), RTX 4050 6 GB, RAM onboard, 512 GB SSD, rund 2,1 kg und 99 Wh. NPU für unterstützte on-device-Workflows, aber keine automatische Ollama/CUDA-Beschleunigung der eigenen Modelle.
- 8 GB VRAM: oft sinnvoll für quantisierte kleinere Modelle; keine unbedingte Zusage für jedes 7B/8B-Modell, Größe und Kontext entscheiden. Größere Modelle können CPU-Offload verlangen und langsamer werden.
- Das MacBook M4 (16 GB/256 GB) ist für Cloud-KI bereits gut; Mehrwert eines Windows-Laptops ist parallele x86/Windows-/NVIDIA-/WSL2-Entwicklung, mehr Speicher sowie CUDA-Modelle.
- **Aktueller Marktanker:** zahlreiche gebrauchte RTX-4060-Laptops mit 32 GB RAM für ~800–1.100 € inseriert (keine Kaufabschlüsse). **Neue RTX-5060/8GB-Laptops** ab ungefähr 1.099 € mit meist nur 16 GB RAM beachten; Gesamtkosten für 32 GB berechnen.

## Quellen
- ASUS-1-Anzeige: https://www.kleinanzeigen.de/s-anzeige/asus-rog-strix-g17-gaming-laptop-ryzen-9-rtx-4060-32-gb-ram/3565620969-278-3460
- ASUS-1-SKU: https://geizhals.de/asus-rog-strix-g17-g713pv-ll145w-90nr0c34-m00ct0-a3303247.html
- ASUS-2-Anzeige: https://www.kleinanzeigen.de/s-anzeige/asus-gaming-laptop-17-3-zoll-ryzen-9-32gb-rtx4060/3564575142-278-3453
- ASUS-2-SKU: https://geizhals.de/asus-rog-strix-g17-g713pv-hx058w-eclipse-gray-90nr0c34-m00ar0-a3143620.html
- MSI-Angebot: https://www.mediamarkt.de/de/product/_msi-stealth-a16-ai-a3hveg-298nn-160-zoll-amd-ryzentm-ai-5-340-32-gb-512-gb-nvidia-geforce-rtxtm-4050-windows-11-home-3057841.html
- MSI-SKU: https://preisvergleich.heise.de/msi-stealth-a16-ai-a3hveg-298nn-0015fk-298-a3887355.html
- GPU VRAM nach NVIDIA: https://www.nvidia.com/de-de/geforce/laptops/compare/
- Vergleichbare Angebote: https://www.kleinanzeigen.de/s-notebooks/laptop-32gb-rtx-4060/k0c278
- Docker GPU mit WSL2: https://docs.docker.com/desktop/features/gpu/


## Nachtrag 10.11.2026: MSI Cyborg 15 B13WFKG-827 gegenüber den ursprünglichen drei Nutzermodellen

**Klarstellung:** Vergleich **der technischen Angebote**, nicht unabhängig bestätigte Verkaufbarkeit/Verfügbarkeit. Neue harte Grenze des Nutzers: **maximal 1.100 € Gesamtpreis inklusive RAM-Aufrüstung**. Nutzung nur Business, Cloud-KI, Ollama, Docker, GitHub; kein Gaming.

| Merkmal | ASUS Strix 1 | ASUS Strix 2 | MSI Stealth 3 | MSI Cyborg neu |
|---|---|---|---|---|
| Ursprünglicher Angebotspreis | 1.100 € gebraucht | 1.000 € gebraucht | 999 € neu | 949 € neu (plus ca. 70 € hypothetischer RAM) |
| CPU | Ryzen 9 **7940HX** | Ryzen 9 **7845HX** | Ryzen AI 5 **340** | Core i5 **13420H** |
| Kerne/Threads | 16/32 | 12/24 | 6/12 | 8 (4P+4E)/12 |
| GPU | RTX 4060 Laptop | RTX 4060 Laptop | RTX 4050 Laptop | RTX 5060 Laptop |
| Dedizierter VRAM | **8 GB** | **8 GB** | **6 GB** | **8 GB** |
| Max. GPU Power laut SKU | 140 W | 140 W | 105 W | **55 W** |
| RAM ab Kauf | 32GB | 32GB | 32GB verlötet | **16GB (1×16, 1 Slot frei)** |
| RAM nach geplantem Ausbau | 32GB | 32GB | 32GB | **32GB bei kompatiblem +16GB Modul** |
| SSD | 1TB | 1TB | 512GB, zweiter M.2-Slot | 512GB, nur ein M.2-Slot |
| Zustand | gebraucht privat | gebraucht privat | neu Handel | neu Handel |

### Bewertung **für Nutzung**, nicht Gaming
- **Für CPU-intensive Entwicklung, Container, viele Prozesse:** ASUS 1 > ASUS 2 > MSI Cyborg, wobei MSI Stealth mit moderner 6-Kern-CPU zwischen Workloads variieren kann. 16C und 12C der ASUS besonders stark in paralleler Multi-Core-Dauerlast; **nicht behaupten**, dass Cloud-KI-Token auf stärkerer CPU schneller entstehen, wenn serverseitig gerechnet wird.
- **Für lokale KI/LLMs:** ASUS 1 und 2 haben **dieselbe 8GB-VRAM-Klasse** wie Cyborg, aber bei der RTX4060 potenziell deutlich größere GPU-Leistungsreserve (bis 140W vs. Cyborg RTX5060 55W). RTX5060 ist neuer und effizienter, darum **kein pauschales „4060 ist in jeder KI-Aufgabe schneller“** ohne Ollama-Praxistest. RTX4050 des Stealth mit 6GB hat den geringsten VRAM.
- **Betriebsqualität/Wert:** MSI Cyborg neu mit Händler-Gewährleistung ist risikoärmer als gebrauchte Privatgeräte, aber 512GB SSD, 55W RTX5060, i5 CPU und nur ein SSD-Slot sind Einschränkungen. Der MSI Stealth bietet 99Wh Akku, USB4, leichteres 16-Zoll-Gehäuse und 32GB onboard, aber schwächere GPU-VRAM-Reserve.
- **Für Business als Allrounder bei gleichen Preisen und nach nachgewiesenem Zustand:** ASUS Strix 1 als technische CPU-/SSD-Spitze; ASUS Strix 2 ebenso starke Option mit schwächerem FHD Display; Cyborg 15 als neues preiswertes Gerät; MSI Stealth eher Mobilität/Batterie als lokale LLMs.
- **Für Neuware und Garantie** kann Cyborg vor ASUS kommen, wenn keine zuverlässige Prüfung des gebrauchten Geräts möglich ist.
- **Kaufpreis-Rechnung:** Cyborg 949€ + angenommene (NICHT verifiziert verfügbare) 70€ kompatibles 16GB-DDR5-5200-SO-DIMM = 1.019€. Beim ASUS 1 1.100€ gebraucht ist kein Budgetpuffer mehr. ASUS 2 1.000€ gebraucht.
- **Wichtig:** der Nutzer fragt aktuell nur nach **Vergleich**, kein Kauf beschlossen. Alle Werte vor Bestellung nochmals prüfen.

### Exakte Modellquellen
- ASUS 1: https://geizhals.de/asus-rog-strix-g17-g713pv-ll145w-90nr0c34-m00ct0-a3303247.html
- ASUS 2: https://geizhals.de/asus-rog-strix-g17-g713pv-hx058w-eclipse-gray-90nr0c34-m00ar0-a3143620.html
- MSI Stealth: https://preisvergleich.heise.de/msi-stealth-a16-ai-a3hveg-298nn-0015fk-298-a3887355.html
- MSI Cyborg: https://geizhals.de/msi-cyborg-15-b13wfkg-827-0017u3-827-a3687065.html
- MSI offizielles Cyborg-GPU-TGP/Slots: https://www.msi.com/Laptop/Cyborg-15-B13WX/Specification

**Vorgabe für weitere Suche:** 1.100€ maximal inklusive Ausbau; möglichst CPU besser als i5-13420H, RTX4060/5060 mit 8GB VRAM und sinnvoller TGP, 32GB RAM fertig oder günstig nachrüstbar, >=512GB SSD. Nicht auf theoretische 16GB VRAM verzichten, wenn gleicher Preis / guter geprüfter Zustand möglich ist; aber gebrauchte Angebote nur nach verifiziertem Bestand und Zustand.
