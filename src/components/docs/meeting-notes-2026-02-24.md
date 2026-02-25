# Meeting Notes – Satellitdata, interoperabilitet och civil ledningsarkitektur

**Datum:** 2026-02-24  
**Typ:** Strategiskt samtal  
**Tema:** Satellitdata, realtid, NATO-standarder, civil tillämpning  

---

## 1. Satellitdata – kategorier

### Historisk data
- Används för trendanalys
- Samhällsperspektiv
- AI-träning
- Inte lämplig för realtidsbeslut

### Kommersiell data
- Äldre än 3 minuter
- Kostnad per bild
- Används i operativ verksamhet

### Realtidsdata (<3 min)
- Krävs för taktiska beslut
- Jordbruk (precision)
- Skogsindustri (storm, brand)
- Infrastruktur (översvämning, ras, trafik)

---

## 2. Arkitektur och framtidsmodell

### Multi-domän
- Rymd
- Luft
- Mark
- Internet
- Media

Mål: Skapa en gemensam lägesbild från flera datakällor.

### Digital C2 / C4ISR (civil översättning)
- GIS som nav
- Kontrollrum
- Krisledningsrum
- Gemensam operativ bild

---

## 3. Standarder och interoperabilitet

### FMN (NATO)
- Federerad samverkan
- Spiraler (4, 6, 7)
- Standardiserade informationsflöden

### ADP 17 / ADP 18
- Drönarsystem
- Informationsbearbetning

### MOSA (USA)
- Öppna system
- Modulär arkitektur
- Undvika inlåsning

### API-standardisering
- Standardiserade anrop
- Metadata-struktur
- Labeling av objekt

---

## 4. Teknologi

### Federated Learning
- Data stannar lokalt
- Endast modellparametrar delas
- Relevant för sekretessklassad data

### Agentisk AI
- Automatiska beslutsförslag
- Prioritering av resurser
- Realtidsanalys

---

## 5. Identifierade utmaningar

- Små spetsaktörer saknar helhetsperspektiv
- Stora aktörer skapar inlåsning
- Offentlig sektor vet inte alltid vad som ska upphandlas
- Myndigheter får inte sälja kommersiella tjänster
- Data ges bort istället för att struktureras

---

## 6. Strategiska frågor framåt

- Ska civila system använda NATO-liknande standarder?
- Hur skapar vi FMN-kompatibilitet i drift?
- Hur skickar vi videoströmmar och styr satelliter via standardiserade tjänster?
- Hur bygger vi en gemensam lägesbild över flera myndigheter?

---

## 7. Nästa steg

- Definiera minimal civil samverkansprofil (Spiral 1)
- Dokumentera datamodell (objekt, händelse, åtgärd)
- Identifiera tekniska POC-möjligheter
