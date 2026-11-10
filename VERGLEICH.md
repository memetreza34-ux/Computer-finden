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
