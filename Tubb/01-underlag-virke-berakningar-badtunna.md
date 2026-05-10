# Underlag v0 – virke och beräkningar för vedeldad badtunna

## 1) Syfte med detta dokument
Detta är **inte** slutlig byggmanual ännu.
Målet här är att:
1. säkra korrekta mått och uträkningar,
2. dela upp arbetet i tydliga delmoment,
3. få allt bekräftat innan slutlig steg-för-steg-guide skrivs.

Fokus i denna version: **virke för vägg och golv**, samt **anslutning golv ↔ väggspjälor (urfräsning)**.

---

## 2) Kända förutsättningar (från er)
- Befintlig tunna finns redan (storlek ska efterliknas).
- Beslag och övrigt finns redan: spännband i metall, kamin, stolar, skydd, pump.
- Virke till vägg + golv: spontad furu **20 x 95 mm**.
- Väggkonstruktion: **56 st spjälor**, varje spjäla **1000 mm** lång.
- Bygghandelns längder att välja mellan: **3,01 m**, **3,3 m**, **3,6 m**.
- Golv: cirkel, ungefär **Ø 1600 mm**.

> Viktigt: För spontat virke är den täckande bredden (effektiv bredd)  mindre än 95 mm. För beräkningar används 85 mm, på faktisk bräda.

---

## 3) Del A – Väggspjälor (56 st à 1000 mm)

### A1. Grundåtgång
Behov: 56 000 mm (56,0 löpmeter) färdiga bitar.

Varje butiksbräda (3,01 / 3,3 / 3,6) ger praktiskt 3 st bitar à 1000 mm.
Därför behövs alltid minst:
- `tak(56 / 3) = 19` brädor (totalt 57 bitar, 1 bit i reserv).

### A2. Jämförelse av butikslängder (endast vägg)
- **19 st x 3,01 m**
  - köpt längd: 57,19 m
  - kapspill från ändar: 0,19 m
  - extra färdig bit: 1 st
- **19 st x 3,3 m**
  - köpt längd: 62,70 m
  - kapspill från ändar: 5,70 m
  - extra färdig bit: 1 st
- **19 st x 3,6 m**
  - köpt längd: 68,40 m
  - kapspill från ändar: 11,40 m
  - extra färdig bit: 1 st

### A3. Slutsats för väggvirke
Om pris/meter är liknande är **3,01 m tydligt mest materialeffektivt** för väggspjälorna.
Ert tidigare antagande 19 st 3,3 m fungerar, men det är inte optimalt för spill.

---

## 4) Del B – Kontroll av diameter/omkrets för vägg

Med 56 spjälor blir omkretsen:
- `C = 56 × effektiv bredd`
- `D = C / pi`

Kontrollvärden:
- vid 85 mm effektiv bredd -> D ≈ 1515 mm
- vid 89 mm effektiv bredd -> D ≈ 1586 mm
- vid 90 mm effektiv bredd -> D ≈ 1604 mm

För exakt Ø1600 med 56 spjälor behövs effektiv bredd:
- `effektiv bredd ≈ (pi × 1600) / 56 = 89,76 mm`

### B1. Praktisk tolkning
- Om ni verkligen vill landa på ca Ø1600 med 56 spjälor, behöver den verkliga täckbredden ligga runt **89,5–90,0 mm**.
- Om verklig täckbredd är nära 85 mm blir tunnan istället närmare **Ø1515 mm**.

**Bekräfta detta tidigt med provmätning av faktisk täckbredd på 5–10 hopspontade brädor.**

---

## 5) Del C – Golv (runt, ca Ø1600)

Nedan är omräknat med:
- diameter 1600 mm,
- effektiv radbredd 85 mm,
- 19 rader över cirkeln,
- +20 mm kapmarginal per rad.

### C1. Korrigerad kaplista (symmetrisk)
Teoretisk maxlängd i mitten kan inte bli större än 1600 mm (diametern).

Kaplängder (mm), från ytterkant in mot mitten:
- 488
- 863
- 1090
- 1253
- 1376
- 1468
- 1537
- 1584
- 1611
- 1620 (mitt)
- 1611
- 1584
- 1537
- 1468
- 1376
- 1253
- 1090
- 863
- 488

### C2. Materialestimat för golvet (från samma lista)
En enkel packningsjämförelse ger ungefär:
- med 3,01 m -> 9 brädor
- med 3,3 m -> 8 brädor
- med 3,6 m -> 8 brädor

Spill i uppskattningen blir lägst för 3,3 m i just detta upplägg.

> <Viktigt att plankorna är bredare än nödvändigt och sen kapas runt i efterhand >

---

## 6) Del D – Anslutning golv och väggspjälor (urfräsning)

Detta är den kritiska detaljen. För 20 mm tjock väggspjäla bör urfräsning vara tillräcklig för låsning men lämna god restgodstjocklek.

### D1. Rekommenderat startmått (att verifiera mot befintlig tunna)
- Spårbredd (för golvets tjocklek): **21,0–21,5 mm**
- Spårdjup in i spjäla: **8,0 mm**
- Kvarvarande gods utåt: **12,0 mm** (20 - 8)
- Spårets underkant över spjälans nederkant: **22–25 mm**

Det ger:
- tillräckligt grepp för golvet,
- tillräcklig styrka kvar i spjälan,
- lite spel för svällning och montering.

### D2. Rörelse/svällning (viktigt)
- Lämna **1–1,5 mm spel i spårbredd** relativt golvets faktiska tjocklek.
- Lämna **ca 2–3 mm total diameterspel** mellan golvskivans ytterkant och spårbotten i torrmontering.
- Målet är tätning när träet sväller av vatten, utan att spjälor spricker.

### D3. Verifieringsmetod före slutkap
1. Ta 2–3 spillbitar av väggspjälor.
2. Fräs spår med måtten ovan.
3. Prova med en golvbit i verklig tjocklek.
4. Fukta provbitar (simulerad svällning) och kontrollera att inget nyper hårt.
5. Justera sedan spårbredd/spårdjup i små steg (0,5 mm).

---

## 7) Del E – Delinstruktioner att bekräfta innan slutlig byggguide

### E1. Materialbeslut
- Bekräfta verklig effektiv bredd på er 20x95 spont.
- Bekräfta måldiameter (är 1600 mm exakt krav, eller ska befintlig tunna styra fullt?). - Inte exakt plankor måste vara längre än nödvändigt men optimalt sett till spill. 
- Välj inköpslängd för väggspjälor (förslag: 3,01 m).
- Välj inköpslängd för golv (förslag: 3,3 m i detta beräkningsfall).
Vi behöver veta hur många 3,6 plankor verkligen än nödvändiga, det är bara mittersta 4-5 plankorna som överstige 1,6 som gör dessa nödvändiga. Vi vill öka mängden 3,01 så långt det går. 

### E2. Mätpunkter på befintlig tunna (måste in före slutguide)
- Invändig diameter upptill och vid golvspår. - utgå från 1600mm 
- Exakt golvtjocklek (faktisk, inte nominell). Vi använder samma virke 20x95 spont även för golv men använder 45x95 i 300mm tvärgårgående under golv plankor. Eftersom dessa är 95 och allt ska stå på dessa ska underkant av brädor (under fräs) inte vara större än detta. 
- Exakt spårbredd, spårdjup och spårets höjdplacering från underkant. Enligt tidigare beräkningar - 8mm djup 25mm bred 90mm upp från botten.
- Antal spjälor och deras verkliga täckbredd i befintlig tunna.

### E3. Säkerhet (barn med i byggprocess)
- Barn gör mätning, märkning, sortering och enkel skruv-/tvinghjälp.
- Vuxen gör all sågning, fräsning och tunga moment.

---

## 8) Öppna frågor till nästa version
1. Är måldiameter exakt 1600 mm, eller ska den följa befintlig tunna även om den avviker? 
2. Vad är uppmätt effektiv bredd på era faktiska brädor (snitt över flera brädor)?
3. Vill ni minimera spill eller minimera antal köpta brädor (om priser skiljer mycket mellan längder)?
4. Kan ni mäta spåret i befintlig tunna så låser vi exakta fräsmått i nästa version?

---

## 9) Kort sammanfattning just nu
- För vägg (56 x 1 m): 19 brädor krävs oavsett längdval; **3,01 m är mest materialeffektivt**.
- För golv Ø1600 med 19 rader och 85 mm täckbredd är kaplistan ovan en konsekvent geometri-baserad start.
- Kopplingen golv/vägg bör börja på spår ca **21–21,5 mm brett, 8 mm djupt, 22–25 mm upp från underkant**, och sedan verifieras med provfräsning innan slutkap.
