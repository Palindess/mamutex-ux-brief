# Mamutex.cz - Brief pre UX dizajnera: Redizajn eshopu

**Projekt:** Mamutex.cz - Redizajn eshopu na zaklade analyzy pouzitelnosti  
**UX konzultant:** Kvasnicka Jan | **Klient:** Radim Bures, radek | **Vyvojar:** Samuel Ondrisak  
**Platforma:** Shoptet  
**Datum:** 2026-03-19  
**Verzia:** v3

---

## Navigacia medzi verziami

- [v1 - Povodna struktura (bez odkazov)](verzie/v1_povodna_struktura.md)
- [v2 - Vsetky komentare (607 uloh)](verzie/v2_so_vsetkymi_komentarmi.md) | [HTML](verzie/v2_so_vsetkymi_komentarmi.html)
- **v3 - Prehladna struktura + Figma odkazy** (aktualna)

---

## Prioritna legenda

| Priorita | Dopad |
|----------|-------|
| **5 z 5** | Kriticka - najvyssi dopad na konverzie |
| **4 z 5** | Velmi vysoka - prva faza |
| **3 z 5** | Vysoka - standardna priorita |
| **2 z 5** | Stredna - dalsie fazy |
| **1 z 5** | Nizka - nice-to-have |


---

## 1. Design System / Celkový redesign

### 1.1. Revize typografie - zkontrolovat hierarchii nadpisů (H1-H6), zajistit že podnadpisy nejsou větší než H1, nastavit správné odsazení pod/nad nadpisy
**Priorita:** Vysoka | **Figma:** [#574](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-386#comment-1472987257) | [#67](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462838803) | [#191](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1464972421) | **Tagy:** #grafika, #redesign

> Na mnoha místech jsou podnadpisy větší než H1, nadpisy mají stejné odsazení nad i pod sebou místo menšího pod nadpisem

### 1.2. Definovat a sjednotit hover efekty pro všechny aktivní prvky (tlačítka, odkazy, checkboxy, fotografie v galerii, šipky)
**Priorita:** Vysoka | **Figma:** [#539](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472422773) | [#124](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-215#comment-1463210186) | [#529](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471592227) | **Tagy:** #grafika, #redesign

> Mnoho aktivních prvků nemá hover efekt, návštěvníci neví že mohou klikat. Na mobilu chybí vizuální indikace aktivních prvků (podtržení místo hover)

### 1.3. Vyřešit barvu odkazů - fialové odkazy berou příliš pozornosti, některé změnit na černé podtržené
**Priorita:** Vysoka | **Figma:** [#653](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1549058422) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | **Tagy:** #grafika, #redesign

> Fialové odkazy si berou hodně pozornosti na místech kde to není potřeba, ruší konverzní cestu

### 1.4. Přestat používat šedou barvu pro aktivní prvky - šedá vypadá jako neaktivní/disabled
**Priorita:** Vysoka | **Figma:** [#296](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466958051) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | **Tagy:** #grafika, #redesign

> Tlačítka, texty, ikony v šedé vypadají jako neaktivní prvky, návštěvníci na ně neklikají. Platí pro filtry, balíčky, ikony v hlavičce, kroky objednávky

### 1.5. Sjednotit konverzní barvu - zvážit jinou než fialovou, protože fialové menu způsobuje že CTA tlačítko nevyniká
**Priorita:** Vysoka | **Figma:** [#597](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-378#comment-1473386282) | [#33](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461722334) | [#5](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=0-1#comment-1459524855) | **Tagy:** #grafika, #redesign

> Konverzní tlačítko se ztrácí v celkovém fialovém designu, na stránce košíku je to problém

### 1.6. Zajistit minimální velikost písma 13px napříč celým webem
**Priorita:** Vysoka | **Figma:** [#536](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-404#comment-1472407010) | [#66](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462828126) | [#35](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461734739) | **Tagy:** #grafika, #redesign

> Na mobilu je písmo 11px, Google penalizuje za malé písmo v rámci přístupnosti, negativní hodnocení může ovlivnit celou doménu

### 1.7. Opravit kontrasty textů - některé šedé texty mají nedostatečný kontrast, řešit čitelnost
**Priorita:** Vysoka | **Figma:** [#225](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465284237) | [#67](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462838803) | [#457](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1470998925) | **Tagy:** #grafika, #redesign

> Několik míst nesplňuje AA standard, barvy jako #808080 na #DFD6EA jsou FAIL. I splněné AA standardy mohou mít zhoršenou čitelnost

### 1.8. Sjednotit spacing/vzdušnost - na mnoha místech příliš velké mezery oddalující obsah, na jiných příliš málo
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Klíčový prvek designu, špatný spacing odděluje související informace nebo zbytečně prodlužuje stránku

### 1.9. Vytvořit signature prvky a brandovou identitu pro vizuální obsah (infografiky, bloky v článcích, bannery)
**Priorita:** Vysoka | **Figma:** [#458](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471000623) | [#333](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467258993) | [#16](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461008782) | **Tagy:** #grafika, #redesign

> Potřeba konzistentní vizuální identity Mamutex napříč celým webem, posílení brandu a důvěryhodnosti, Google umí tyto prvky hodnotit

### 1.10. Vytvořit specifický vizuál pro věrnostní program Mamutex+ (zlatá barva na fialovém pozadí, signature prvky, mince)
**Priorita:** Vysoka | **Figma:** [#507](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-116#comment-1471390424) | [#386](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469170701) | **Tagy:** #grafika, #redesign

> Program musí být vždy jednoznačně rozeznatelný, konzistentní prezentace na všech místech eshopu

### 1.11. Přestat používat verzálky (velká písmena) v textech
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Doporučení z UX analýzy, hůře se čtou

### 1.12. Nastavit řádkování na 1.5 místo 1.8
**Priorita:** Nizka | **Figma:** [#565](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-380#comment-1472878235) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | **Tagy:** #grafika

> Příliš velké řádkování, texty se hůře čtou a zabírají více místa

### 1.13. Formátování cen - vždy s mezerou u tisíců (2 500 Kč místo 2500 Kč), telefonní čísla s mezerami
**Priorita:** Nizka | **Figma:** [#457](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1470998925) | [#321](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467143416) | [#35](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461734739) | **Tagy:** #grafika

> Lepší čitelnost pro návštěvníky

### 1.14. Navrhnout ikony pro kategorie produktů
**Priorita:** Vysoka | **Figma:** [#675](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-94#comment-1552566711) | [#292](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466914726) | [#232](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-196#comment-1465333594) | **Tagy:** #grafika

> Pro lepší orientaci ve vyhledávání a navigaci, návštěvník je nucen hodně číst bez ikon


---

## 2. Hlavička (Header) - Desktop

### 2.1. Navrhnout sticky/fixní minimalizovanou hlavičku pro desktop
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Chybí sticky hlavička na desktopu, návštěvníci ztrácejí přístup k navigaci při scrollování

### 2.2. Přidat osobní kontakt s fotkou, jménem, telefonem a provozní dobou do hlavičky + online/offline indikátor
**Priorita:** Vysoka | **Figma:** [#392](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469224140) | [#195](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465040886) | [#106](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463177688) | **Tagy:** #grafika, #redesign

> Budování důvěryhodnosti, zvýšení konverzního poměru. Má být i v minimalizované hlavičce košíku

### 2.3. Zvýraznit vyhledávací pole - přidat ikonu lupy, tmavší ohraničení, aby nevypadalo jako neaktivní
**Priorita:** Vysoka | **Figma:** [#105](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463143205) | **Tagy:** #grafika, #redesign

> Pole vypadá šedé/neaktivní, návštěvníci kteří vyhledávají mají vyšší konverze

### 2.4. Odstranit email z hlavičky, ponechat pouze telefon
**Priorita:** Stredna | **Figma:** [#522](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471567475) | **Tagy:** #grafika, #redesign

> Email odvádí návštěvníky do emailového klienta, odkud se nemusí vrátit. Email stačí v patičce

### 2.5. Navrhnout marketingovou lištu nad hlavičkou (benefit bar)
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Prostor pro komunikaci klíčových výhod, akcí


---

## 3. Hlavička (Header) - Mobil

### 3.1. Změnit barvu ikon v hlavičce z šedé na tmavou/černou
**Priorita:** Vysoka | **Figma:** [#296](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466958051) | [#523](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471570413) | [#452](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-102#comment-1470973104) | **Tagy:** #grafika, #redesign

> Šedé ikony vypadají jako neaktivní, návštěvníci si myslí že nefungují

### 3.2. Přidat ikonu lupy do vyhledávacího pole na mobilu
**Priorita:** Vysoka | **Figma:** [#674](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-94#comment-1552562666) | [#447](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-100#comment-1470915373) | [#390](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469195896) | **Tagy:** #grafika, #redesign

> Aby bylo jasné že se jedná o vyhledávání

### 3.3. Přidat online/offline tečku k ikoně chatu
**Priorita:** Stredna | **Figma:** [#524](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471573916) | [#64](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462822194) | **Tagy:** #grafika

> Aby bylo jasné že podpora je k dispozici

### 3.4. Zobrazit marketingovou lištu i na mobilu nad hlavičkou
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Mobile First přístup Googlu, nesmíme znevýhodňovat mobil


---

## 4. Mobilní navigace (Menu)

### 4.1. Oddělit řádek menu svislou čárou - oddělení názvu kategorie od šipky pro podkategorie
**Priorita:** Vysoka | **Figma:** [#561](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-428#comment-1472862451) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#250](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-9#comment-1465461211) | **Tagy:** #grafika, #redesign

> Celý řádek vypadá jako jedna položka, ale každá část dělá něco jiného, návštěvníci neví jestli jít do kategorie nebo rozbalit

### 4.2. Přidat více vzdušnosti mezi odkazy v menu pro lepší touch zóny
**Priorita:** Vysoka | **Figma:** [#373](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469125602) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | **Tagy:** #grafika, #redesign

> Aktivní prvky jsou příliš blízko sebe, Google penalizuje za malé touch zóny

### 4.3. Přidat podtržení k odkazům v menu aby vypadaly jako aktivní prvky
**Priorita:** Vysoka | **Figma:** [#539](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472422773) | [#25](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461692676) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | **Tagy:** #grafika, #redesign

> Na mobilu chybí hover efekt, podtržení je jediná indikace klikatelnosti

### 4.4. Opravit prosvítání navigačních teček banneru přes overlay menu
**Priorita:** Vysoka | **Figma:** [#558](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-428#comment-1472840428) | **Tagy:** #grafika, #redesign

> Překryvné vrstvy musí mít nejvyšší z-index, body dolů od Google za překryvy

### 4.5. Redesign odkazů na neproduktové stránky (Poradna, O nás) - odlišný vizuál, dva sloupce
**Priorita:** Stredna | **Figma:** [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | [#629](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-223#comment-1548460055) | **Tagy:** #grafika, #redesign

> Tyto odkazy by měly být vizuálně odlišné od produktových kategorií


---

## 5. Homepage

### 5.1. Redesign bannerů - prodejní bannery vedoucí na produkt/akci, s jasným CTA tlačítkem
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Bannery nejsou prodejní, nevdedou na konkrétní produkty. Na mobilu jsou texty nečitelné

### 5.2. Připravit mobilní formát bannerů (více na výšku) nebo přejít na posuvník bannerů optimalizovaných i pro mobil
**Priorita:** Vysoka | **Figma:** [#529](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471592227) | [#28](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461702481) | [#528](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471590452) | **Tagy:** #grafika, #redesign

> Desktopové bannery se špatně zobrazují na mobilu, texty jsou nečitelné

### 5.3. Přidat bannery z pravé části desktopu i do mobilní verze
**Priorita:** Vysoka | **Figma:** [#530](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471598076) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#92](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463057166) | **Tagy:** #grafika, #redesign

> Google Mobile First - obsah chybějící na mobilu je penalizován

### 5.4. Zobrazit produkty v posuvníku místo statického výpisu na HP
**Priorita:** Vysoka | **Figma:** [#73](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462873078) | [#537](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472407698) | [#327](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467229303) | **Tagy:** #grafika, #redesign

> Ušetření místa, možnost prezentovat více produktů a dalšího obsahu

### 5.5. Přidat šipky a tečky indikace pozice k posuvníkům produktů a bannerů
**Priorita:** Vysoka | **Figma:** [#186](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1464944221) | [#571](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6094-6#comment-1472975291) | [#535](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-404#comment-1471619043) | **Tagy:** #grafika, #redesign

> Návštěvníci si nemusí všimnout posuvníku, tečky indikují kolik pozic je k dispozici

### 5.6. Na mobilu zobrazovat jeden produkt na šířku místo dvou
**Priorita:** Vysoka | **Figma:** [#538](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472417360) | [#655](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1549080649) | [#568](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-382#comment-1472948354) | **Tagy:** #grafika, #redesign

> Malé fotografie, dlouhé zalomené názvy, potřeba zobrazit více parametrů u produktů. Testující říkali že nejde poznat jak produkt vypadá

### 5.7. Přidat brandový nadpis nad sekci konkurenčních výhod
**Priorita:** Stredna | **Figma:** [#315](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467115492) | [#42](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461786175) | [#294](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466942394) | **Tagy:** #grafika, #redesign

> Posílení značky, jasné sdělení kdo jste a co je na vás důležité

### 5.8. Přidat blok naposledy navštívených produktů nad patičku
**Priorita:** Stredna | **Figma:** [#96](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463078003) | **Tagy:** #grafika, #redesign

> Návštěvníci se mohou vrátit k produktům bez hledání. Existuje doplněk Shoptet

### 5.9. Přidat storytelling blok o společnosti Mamutex (fotky ze skladu/výroby, hodnoty, příběh)
**Priorita:** Stredna | **Figma:** [#343](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467380785) | [#301](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467034898) | [#30](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461708059) | **Tagy:** #grafika, #redesign

> Budování důvěryhodnosti, autenticity, propojení se zákazníkem. Materiály z velkého skladu jsou k dispozici

### 5.10. Navrhnout brandový vizuál pro newsletter sekci s motivem obálky
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Lákání k odběru, upoutání pozornosti na mobilu

### 5.11. Přidat ikonu obálky do newsletter input pole
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Upoutání pozornosti na input pro zadání emailu

### 5.12. Opravit rozbité zobrazení výhod obchodu na mobilu - špatné zarovnání
**Priorita:** Vysoka | **Figma:** [#531](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471607329) | **Tagy:** #grafika, #redesign

> Nepůsobí dobrým dojmem, problém viditelný i na Androidu

### 5.13. Sjednotit zarovnání nadpisů na mobilu (na střed jako na desktopu)
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Konzistence mezi desktop a mobile verzí


---

## 6. Cookies / Souhlas

### 6.1. Přidat ztmavení overlay za cookie lištu, souhlas v konverzní barvě
**Priorita:** Stredna | **Figma:** [#358](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-157#comment-1467517821) | [#152](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-231#comment-1463295488) | [#54](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462783471) | **Tagy:** #grafika, #redesign

> Návštěvník se má soustředit na potvrzení, psychologie barev pro konverzní cestu


---

## 7. Vyhledávání / Našeptávač (LuigisBox)

### 7.1. Redesign celého vyhledávání a našeptávače - sjednotit vizuál s kategoriemi
**Priorita:** Vysoka | **Figma:** [#434](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6077-3#comment-1469431793) | [#321](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467143416) | [#317](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467124786) | **Tagy:** #grafika, #redesign, #luigis

> Výsledky vyhledávání vypadají jako by nepatřily do eshopu. LuigisBox potřebuje grafické úpravy, půl roku je to provizorní

### 7.2. Zvýraznit hledanou frázi jinou barvou ve výsledcích vyhledávání
**Priorita:** Vysoka | **Figma:** [#635](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-225#comment-1548477073) | **Tagy:** #grafika, #luigis

> Návštěvníkům chyběla kotva k tomu co hledají, fráze není dostatečně viditelná

### 7.3. Opravit zkracování názvů produktů ve vyhledávání
**Priorita:** Vysoka | **Figma:** [#631](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-223#comment-1548470495) | [#350](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-145#comment-1467466021) | [#318](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467125882) | **Tagy:** #luigis

> Důležité informace v názvech nejsou vidět, lidé se musí proklikávat tam a zpět, ztrácí čas

### 7.4. Vyřešit aby dvě stejná tlačítka vedle sebe v našeptávači nebyla matoucí - jedno zpracovat jako kolečka
**Priorita:** Vysoka | **Figma:** [#632](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-225#comment-1548474120) | **Tagy:** #grafika, #redesign

> Rozhodovací paralýza, dvě stejná tlačítka dělají něco jiného

### 7.5. LuigisBox - změnit barvu suggested tagů z konverzní na jinou
**Priorita:** Stredna | **Figma:** [#629](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-223#comment-1548460055) | [#66](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462828126) | [#32](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461714680) | **Tagy:** #grafika, #luigis

> Neměly by být v konverzní barvě, pletou si je s CTA tlačítky

### 7.6. Přidat počet výsledků k záložkám ve vyhledávání, opravit neaktivní vzhled
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #luigis

> Záložka Články vypadá neaktivně, chybí indikace kolik výsledků se skrývá

### 7.7. Přepínač Produkty/Články umístit pod nadpis vlevo
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Lepší viditelnost pro návštěvníky

### 7.8. Otočit pořadí cen - nejdřív přeškrtnutá původní, pak aktuální větším písmem
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Standard na který jsou návštěvníci zvyklí

### 7.9. Zvětšit fotografie ve výsledcích aby štítky nezasahovaly do fotek na dva řádky
**Priorita:** Stredna | **Figma:** [#633](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-225#comment-1548475171) | **Tagy:** #grafika, #redesign

> Štítky na dva řádky zhoršují výběr produktů


---

## 8. Stránka výsledků vyhledávání

### 8.1. Sjednotit stránku výsledků s kategorickými výpisy - stejný H1 styl, řazení formou lišty, jednotný produktový výpis
**Priorita:** Vysoka | **Figma:** [#422](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-94#comment-1469404311) | [#423](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-94#comment-1469406431) | [#138](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-223#comment-1463254224) | **Tagy:** #grafika, #redesign

> Design vypadá jako by návštěvník byl jinde, může bojovat s důvěryhodností

### 8.2. Navrhnout stav pro 'Nic nenalezeno' - vizuál, rozcestník kategorií, osobní kontakt, nejprodávanější produkty
**Priorita:** Vysoka | **Figma:** [#106](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463177688) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | **Tagy:** #grafika, #redesign

> Návštěvník nesmí zůstat na mrtvé stránce, musí mít cestu dál

### 8.3. Přidat drobečkovou navigaci (Domů -> Vyhledávání)
**Priorita:** Stredna | **Figma:** [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#577](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-338#comment-1473216818) | [#463](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471032042) | **Tagy:** #grafika

> Návštěvník musí vědět kde se v hierarchii nachází


---

## 9. Kategorie / Produktové výpisy

### 9.1. Kompletní redesign filtrace - nový grafický design filtrů (Shoptet default je nevyhovující)
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Filtrace je na špatném místě, graficky nevyhovující, potřeba kompletně předělat i na mobilu

### 9.2. Mobilní filtrace jako popup/modal okno s tlačítkem potvrdit
**Priorita:** Vysoka | **Figma:** [#567](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-382#comment-1472902913) | [#106](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463177688) | [#66](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462828126) | **Tagy:** #grafika, #redesign

> Návštěvník se soustředí jen na filtrování, neruší okolní prvky

### 9.3. Výraznější tlačítko Filtrovat na mobilu
**Priorita:** Vysoka | **Figma:** [#529](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-400#comment-1471592227) | [#597](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-378#comment-1473386282) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | **Tagy:** #grafika, #redesign

> Návštěvníci kteří filtrují mají vyšší konverze, potřebujeme je více vést k filtrování

### 9.4. Ztmavit okolí při otevření řazení na mobilu
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Soustředění návštěvníka na výběr řazení

### 9.5. Přidat box s aktivními filtry nad výpis produktů s možností zrušit
**Priorita:** Vysoka | **Figma:** [#232](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-196#comment-1465333594) | [#514](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-120#comment-1471402587) | [#292](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466914726) | **Tagy:** #grafika, #redesign

> Důležité pro vstupní stránky, návštěvník neví že výpis je filtrovaný

### 9.6. Navrhnout posuvník/slider pro číselné filtry (výška, šířka, hloubka, nosnost)
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Pohodlnější nastavení rozsahu pro návštěvníky

### 9.7. Přesunout šipku rozbalení filtrů na konec řádku
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Standard pro rozbalovací prvky, lepší přehlednost

### 9.8. Zobrazit prvních 8 hodnot filtru, zbytek za tlačítkem 'Dalších (X)'
**Priorita:** Stredna | **Figma:** [#211](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465206780) | **Tagy:** #grafika

> Nezahltit návštěvníka hodnotami jednoho filtru

### 9.9. Přidat osobní kontakt pod filtry v sidebaru
**Priorita:** Vysoka | **Figma:** [#217](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465240047) | [#54](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462783471) | **Tagy:** #grafika, #redesign

> Přímý vliv na konverze a důvěryhodnost

### 9.10. Odstranit loga platebních metod z filtrace sidebaru
**Priorita:** Nizka | **Figma:** [#216](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465238349) | **Tagy:** #grafika

> Lidé je tu nehledají, patří do patičky

### 9.11. Přidat počty produktů v závorce k podkategoriím
**Priorita:** Stredna | **Figma:** [#227](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-182#comment-1465314626) | **Tagy:** #grafika

> Lepší přehled kolik produktů je za jednotlivými možnostmi

### 9.12. Zvětšit fotografie u podkategorií, dát obrázek nad text
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Lepší rozpoznatelnost typu produktů

### 9.13. Přidat jednotky k číselným filtrům (mm, cm, kg)
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Návštěvníci nemusí vědět v jaké jednotce filtrují

### 9.14. Přidat stránkování - 10-15 řádků na stránku
**Priorita:** Vysoka | **Figma:** [#200](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465122570) | **Tagy:** #grafika, #redesign

> Příliš dlouhý výpis negativně ovlivňuje rychlost načítání a konverze

### 9.15. Výpis konkurenčních výhod pod produkty v kategorii
**Priorita:** Vysoka | **Figma:** [#205](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465129446) | [#151](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-229#comment-1463294191) | **Tagy:** #grafika, #redesign

> Kategorie je často vstupní stránkou, potřeba komunikovat výhody

### 9.16. Tlačítko 'Nahoru' na konci výpisu produktů
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Rychlý návrat k filtrům a podkategoriím

### 9.17. Podkategorie znovu zobrazit i pod výpisem produktů
**Priorita:** Stredna | **Figma:** [#202](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465127285) | [#54](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462783471) | [#93](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463071250) | **Tagy:** #grafika, #redesign

> Po scrollu produktů si návštěvník lépe uvědomí co chce a proklikne se hlouběji = vyšší konverze

### 9.18. Dlaždice podkategorií nesmí být v konverzní barvě
**Priorita:** Vysoka | **Figma:** [#637](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1548521912) | **Tagy:** #grafika, #redesign

> Konverzní barva jen pro konverzní prvky, ne pro výpis podkategorií

### 9.19. Přidat parametry pod název produktu v produktové kartě ve výpisu
**Priorita:** Vysoka | **Figma:** [#583](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-340#comment-1473237095) | [#318](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467125882) | [#538](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472417360) | **Tagy:** #grafika, #redesign

> Testující chtěli vidět parametry (nosnost, rozměry) přímo ve výpisu, nejvyšší priorita z testování (5/5)

### 9.20. Přidat skladovost do produktové karty ve výpisu
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Chybí informace o dostupnosti, důležitá pro rozhodování


---

## 10. Produktový detail - Galerie a Fotografie

### 10.1. Přidat šipky pro listování fotografiemi v galerii + hover efekt na šipky
**Priorita:** Vysoka | **Figma:** [#283](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466834560) | [#219](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465244633) | [#120](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-215#comment-1463208018) | **Tagy:** #grafika, #redesign

> Návštěvníci neví že jsou další fotky, zvýšení počtu zobrazených fotek zvyšuje konverze

### 10.2. Na mobilu přidat šipku doprava u hlavní fotografie a gesto swipe
**Priorita:** Vysoka | **Figma:** [#294](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466942394) | [#292](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466914726) | [#283](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466834560) | **Tagy:** #grafika, #redesign

> Aby návštěvník viděl že jsou další fotky, zvýšení konverzí

### 10.3. Přidat hover efekt na miniatury fotografií
**Priorita:** Stredna | **Figma:** [#64](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462822194) | [#284](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466837173) | [#602](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-320#comment-1473438768) | **Tagy:** #grafika

> Aby bylo jasné že je možné kliknout a otevřít galerii

### 10.4. Řadit štítky na fotce podle délky aby co nejméně zasahovaly
**Priorita:** Nizka | **Figma:** [#282](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466832858) | **Tagy:** #grafika

> Lepší viditelnost produktové fotografie

### 10.5. Přidat do galerie i negrafický obsah - fakta, výhody, reference (jako denatura.cz)
**Priorita:** Stredna | **Figma:** [#338](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467322284) | **Tagy:** #grafika, #redesign

> Galerie nemusí být jen fotky, může obsahovat prvky podporující konverzi

### 10.6. Přidat fotky s rozměry do galerie u všech produktů
**Priorita:** Vysoka | **Figma:** [#287](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466865585) | [#292](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466914726) | [#232](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-196#comment-1465333594) | **Tagy:** #grafika

> Testující se hodně ptali na rozměry, chtěli je vidět vizuálně

### 10.7. Řešení proporcionality fotek regálů - regály různých výšek zobrazeny stejně velké zkreslují
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Fotky generované AI podle vyfocené předlohy, ořez zkresluje proporce

### 10.8. Vytvořit místo pro nahrání lifestyle fotek zákazníků k recenzím
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Potřeba autentických fotek od zákazníků


---

## 11. Produktový detail - Konverzní zóna

### 11.1. Přidat příznaky s top vlastnostmi (ikona + text): Nosnost, Rozměry, Počet polic, Montáž 6 minut
**Priorita:** Vysoka | **Figma:** [#292](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466914726) | [#600](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6095-13#comment-1473433414) | [#535](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-404#comment-1471619043) | **Tagy:** #grafika, #redesign

> Návštěvník na první pohled vidí klíčové výhody, nemá důvod hledat v popisu

### 11.2. Přidat klíčové výhody/vlastnosti produktu nad konverzní tlačítko
**Priorita:** Vysoka | **Figma:** [#294](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466942394) | **Tagy:** #grafika, #redesign

> Pomáhá přesvědčit ke koupi, zvyšuje konverze i přes mírné posunutí CTA níže

### 11.3. Redesign pole pro editaci množství - + a - tlačítka po stranách místo šipek nahoru/dolů, větší touch zóny
**Priorita:** Vysoka | **Figma:** [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | [#373](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469125602) | **Tagy:** #grafika, #redesign

> Šipky nahoru/dolů nejsou intuitivní, touch zóny příliš blízko sebe, Google penalizuje

### 11.4. Odstranit ikonu z konverzního tlačítka 'Přidat do košíku'
**Priorita:** Vysoka | **Figma:** [#302](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467036215) | **Tagy:** #grafika, #redesign

> Ikona v tlačítku snižuje konverze, lidé nad ní zbytečně přemýšlí. Testováno opakovaně

### 11.5. Zmenšit konverzní tlačítko - dát cenu, množství a CTA na jeden řádek
**Priorita:** Vysoka | **Figma:** [#658](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1550589565) | [#382](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469153872) | [#358](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-157#comment-1467517821) | **Tagy:** #grafika, #redesign

> Obří tlačítko nemusí vypadat jako tlačítko ale jako štítek, působí jako příliš agresivní tlačení na konverzi

### 11.6. Odstranit orámování u dostupnosti - nebude vypadat jako tlačítko, zobrazit klasicky zelenou barvou
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Příliš mnoho rámečků vypadajících jako tlačítka vedle sebe, zahlcující

### 11.7. Přidat odkaz 'Možnosti doručení' s popup oknem (loga dopravců, ceny, termíny)
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Návštěvník chce vědět dopravní info bez opuštění detailu

### 11.8. Přidat logo značky Mamutex na produktový detail
**Priorita:** Stredna | **Figma:** [#323](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467212696) | **Tagy:** #grafika, #redesign

> Propagace značky, interní prolinkování, SEO

### 11.9. Přidat osobní kontakt s fotkou na produktový detail
**Priorita:** Vysoka | **Figma:** [#310](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467090908) | [#668](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1551246746) | [#560](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-428#comment-1472858096) | **Tagy:** #grafika, #redesign

> Větší jistota že se mohou ozvat při problému

### 11.10. Zobrazit hvězdičky hodnocení ve fixním pruhu při scrollu
**Priorita:** Vysoka | **Figma:** [#661](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1550606207) | [#294](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466942394) | **Tagy:** #grafika, #redesign

> Vysoká hodnocení vedou ke konverzi když jsou vidět při scrollu

### 11.11. Zmenšit velikost nadpisu produktu - bere příliš místa
**Priorita:** Stredna | **Figma:** [#565](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-380#comment-1472878235) | [#538](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472417360) | **Tagy:** #grafika, #redesign

> Dlouhé názvy se hodně zalamují, na mobilu až na 6 řádků


---

## 12. Produktový detail - Obsah a Popis

### 12.1. ZRUŠIT ZÁLOŽKY - veškerý obsah zobrazit pod sebou v tematických celcích (Top priorita 5/5)
**Priorita:** Vysoka | **Figma:** [#317](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467124786) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#574](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-386#comment-1472987257) | **Tagy:** #grafika, #redesign

> Záložky se špatně indexují Googlem, návštěvníci je ignorují/přehlédnou, trend se mění. Toto je jedna z top priorit

### 12.2. Navrhnout fixní navigační lištu s kotvami na části obsahu (obrázek, název, cena, skladovost, CTA)
**Priorita:** Vysoka | **Figma:** [#318](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467125882) | [#317](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467124786) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | **Tagy:** #grafika, #redesign

> Nahrazení záložek, návštěvník vidí kde je a může se orientovat. Lišta se přichytí k hornímu okraji při scrollu

### 12.3. Na mobilu nahradit fixní lištu rozbalovací nabídkou s kotvami
**Priorita:** Vysoka | **Figma:** [#318](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467125882) | **Tagy:** #grafika, #redesign

> Mobilní ekvivalent desktopové navigační lišty

### 12.4. Navrhnout mobilní fixní pruh ve spodní části (foto, cena, dostupnost, CTA)
**Priorita:** Vysoka | **Figma:** [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#109](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463180279) | [#567](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-382#comment-1472902913) | **Tagy:** #grafika, #redesign

> Na mobilu se hodně scrolluje, CTA musí být vždy viditelné. Zobrazí se když visitor scrollne pod hlavní CTA. Priorita 4/5

### 12.5. Parametry přesunout NAD produktový popis, zobrazit ve více sloupcích přes celou šířku
**Priorita:** Vysoka | **Figma:** [#327](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467229303) | [#213](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465211523) | [#554](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-426#comment-1472447090) | **Tagy:** #grafika, #redesign

> Priorita 5/5. Parametry jsou důležité pro indexaci a interní prolinkování, neschovávat za rozbalení

### 12.6. Navrhnout blok prezentace značky pod produktovým popisem (logo, název, popis, odkazy)
**Priorita:** Stredna | **Figma:** [#323](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467212696) | **Tagy:** #grafika, #redesign

> Podpora brandu Mamutex, interní prolinkování, důvěryhodnost

### 12.7. Přidat odkaz na video jak sestavit regál, jak se produkty balí
**Priorita:** Vysoka | **Figma:** [#660](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1550597054) | [#350](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-145#comment-1467466021) | [#337](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467296640) | **Tagy:** #grafika, #redesign

> Obava z kvality balení, obava z montáže - potřeba rozbít tyto obavy

### 12.8. Přidat FAQ sekci pod detail produktu
**Priorita:** Vysoka | **Figma:** [#340](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467349264) | [#467](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471056653) | **Tagy:** #grafika, #redesign

> Ideální obsah pro AI mode a AI overview od Google, zvyšuje Authority Rank

### 12.9. Odstranit tlačítka sdílení na sociální sítě a tisk
**Priorita:** Stredna | **Figma:** [#341](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467356163) | **Tagy:** #grafika

> Nikdo je nepoužívá, berou pozornost od konverze

### 12.10. Přidat blok související články z blogu pod produktový popis
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Interní prolinkování, pomoc při rozhodování

### 12.11. Výhody u produktu by měly být specifické pro produkt, ne obecné USP eshopu
**Priorita:** Stredna | **Figma:** [#353](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-149#comment-1467494425) | [#106](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463177688) | [#413](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6095-16#comment-1469374700) | **Tagy:** #grafika, #redesign

> Při porovnání 5 produktů vedle sebe čtou stále totéž, nepomáhá to ve výběru


---

## 13. Produktový detail - Množstevní sleva / Balíčky

### 13.1. Kompletní předělání sekce množstevních slev/akčních balíčků
**Priorita:** Vysoka | **Figma:** [#597](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-378#comment-1473386282) | **Tagy:** #grafika, #redesign

> Doplněk nefunguje správně, tlačítka vypadají neaktivně (šedá), na mobilu se po kliknutí nic neděje viditelně, konverzní tlačítko mimo zobrazení

### 13.2. Opravit UX balíčků - po aktivaci se tlačítko 'Koupit výhodně v balíčku' tváří jako CTA ale nelze na něj kliknout
**Priorita:** Vysoka | **Figma:** [#597](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-378#comment-1473386282) | [#358](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-157#comment-1467517821) | [#629](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-223#comment-1548460055) | **Tagy:** #grafika, #redesign

> Priorita 5/5 - testující opakovaně klikali na falešné CTA, neviděli skutečné tlačítko

### 13.3. Přidat celkovou úsporu v Kč do názvu varianty balíčku
**Priorita:** Stredna | **Figma:** [#308](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467077625) | **Tagy:** #grafika

> Procenta + absolutní hodnota více lákají k výběru


---

## 14. Outfindo - Průvodce výběrem

### 14.1. Grafický redesign celého Outfindo průvodce - sjednotit s design systémem eshopu
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign, #outfindo

> Outfindo může customizovat, grafik navrhne a Outfindo zpracuje. Nyní nesedí s designem eshopu

### 14.2. Navrhnout oddělovač/vizuální oddělení mezi výběrem a výsledky v průvodci
**Priorita:** Vysoka | **Figma:** [#261](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-11#comment-1465500180) | **Tagy:** #grafika, #outfindo

> Potřeba jasně oddělit UI části výběru a výsledků

### 14.3. Zmenšit průvodce na výšku - příliš roztahaný, na malém monitoru nevidět produkty
**Priorita:** Vysoka | **Figma:** [#254](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-11#comment-1465474911) | **Tagy:** #grafika, #redesign

> Kompaktnější zobrazení, produkty musí být vidět

### 14.4. Přidat progress bar do průvodce - jasné kolik kroků celkem a kde se nacházíme
**Priorita:** Vysoka | **Figma:** [#639](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-11#comment-1548799372) | [#24](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461523051) | [#1](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=0-1#comment-1459520458) | **Tagy:** #grafika, #outfindo

> Aktuální navigace vypadá jako nedodělaná, mate návštěvníky

### 14.5. Přidat nadpis bloku průvodce např. 'Pomocník s výběrem' nebo 'Vyberte si svůj regál'
**Priorita:** Vysoka | **Figma:** [#54](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462783471) | [#243](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-9#comment-1465425445) | [#81](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1463022353) | **Tagy:** #grafika, #redesign

> Návštěvníci neví na co koukají, zaměňují s kategoriemi nad tím

### 14.6. Sjednotit vizuál výpisu produktů v průvodci se standardním výpisem kategorií
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #outfindo

> UI má být konzistentní

### 14.7. Sjednotit pořadí rekapitulace s pořadím kroků průvodce
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #outfindo

> Různé pořadí mate návštěvníky

### 14.8. Opravit čitelnost v průvodci - barvy textu/pozadí
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #outfindo

> Špatná čitelnost #808080 na #DFD6EA = FAIL

### 14.9. Skrýt prázdné informace o produktu v průvodci (nezobrazovat prázdná pole)
**Priorita:** Stredna | **Figma:** [#645](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-11#comment-1548826274) | [#324](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467217065) | [#287](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466865585) | **Tagy:** #outfindo

> Prázdné info mate testující - ptali se proč se to nenačetlo


---

## 15. Košík - Krok 1

### 15.1. Produkty v košíku přes celou šířku okna
**Priorita:** Vysoka | **Figma:** [#368](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469118935) | [#180](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1464912986) | **Tagy:** #grafika, #redesign

> Větší prostor pro přehlednost, soustředění na finální výběr

### 15.2. Přesunout souhrn objednávky do spodní části v prvním kroku
**Priorita:** Vysoka | **Figma:** [#376](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469131293) | **Tagy:** #grafika, #redesign

> Možnost promovat související produkty, věrnostní program, navýšit hodnotu objednávky

### 15.3. Minimalizovat pole pro slevový kód - checkbox místo rozevřeného pole
**Priorita:** Vysoka | **Figma:** [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | [#382](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469153872) | **Tagy:** #grafika, #redesign

> Rozevřené pole vypadá jako povinné, motivuje hledání kódů u konkurence přes Google

### 15.4. Druhý krok objednávky musí vypadat jako aktivní odkaz (ne šedý)
**Priorita:** Vysoka | **Figma:** [#602](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-320#comment-1473438768) | [#367](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469112137) | [#296](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1466958051) | **Tagy:** #grafika, #redesign

> Šedá barva = neaktivní prvek, návštěvníci si myslí že nemohou kliknout

### 15.5. Redesign pole pro editaci množství v košíku - + a - tlačítka, větší touch zóny
**Priorita:** Vysoka | **Figma:** [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | [#373](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469125602) | **Tagy:** #grafika, #redesign

> Stejné problémy jako na detailu - malé touch zóny, šipky místo +/-

### 15.6. Popup potvrzení při odstraňování produktu z košíku
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Snížení počtu produktů odebraných z košíku, data to potvrzují

### 15.7. Nepoužívat konverzní barvu pro tlačítko 'Pokračovat v nákupu' - jen pro hlavní CTA
**Priorita:** Vysoka | **Figma:** [#632](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-225#comment-1548474120) | **Tagy:** #grafika, #redesign

> Dvě konverzní tlačítka ruší plynulý přechod, priority 4/5

### 15.8. Blok Mamutex+ v košíku zobrazit v designu věrnostního programu
**Priorita:** Stredna | **Figma:** [#385](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469166710) | **Tagy:** #grafika, #redesign

> Konzistentní prezentace VP na všech místech


---

## 16. Košík - Krok 2 (Doprava a platba)

### 16.1. Osobní kontakt v minimalizované hlavičce košíku + Heureka badge
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Budování důvěryhodnosti v objednávkovém procesu, zvýšení dokončených objednávek

### 16.2. Přihlašovací formulář jako popup v košíku (ne přesměrování na jinou stránku)
**Priorita:** Vysoka | **Figma:** [#404](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-128#comment-1469282374) | [#388](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469177527) | [#600](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6095-13#comment-1473433414) | **Tagy:** #grafika, #redesign

> Priorita 5/5 - odvádíme zákazníka pryč z košíku, nemusí se vrátit

### 16.3. Zvýraznit formulářová pole - výraznější ohraničení, hover efekt, aktivní stav
**Priorita:** Vysoka | **Figma:** [#406](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-128#comment-1469293618) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | **Tagy:** #grafika, #redesign

> Šedá pole vypadají jako neaktivní, není jasné kde se nacházíme ve formuláři

### 16.4. Vyplněný text v polích plnou barvou (ne zástupným šedým stylem)
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Vyplněné údaje vypadají jako placeholdery, hůře se kontrolují

### 16.5. Výraznější radiobutton pro volbu dopravy a platby
**Priorita:** Stredna | **Figma:** [#394](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469233576) | **Tagy:** #grafika, #redesign

> Nyní vypadá jako neaktivní prvek

### 16.6. Přidat popup s popisem neznámých dopravců/plateb na ikonku
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Návštěvníci neznají některé dopravce (Raben), potřebují jistotu správného výběru

### 16.7. Informativní hláška nad výběrem dopravy vysvětlující vyšší ceny (nadrozměrné zásilky)
**Priorita:** Vysoka | **Figma:** [#401](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469268984) | [#248](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-9#comment-1465447143) | **Tagy:** #grafika, #redesign

> Návštěvníci zvyklí na nižší ceny dopravy, nespojí si to s velikostí regálů

### 16.8. Zobrazit celou adresu a otevírací dobu u osobního odběru
**Priorita:** Vysoka | **Figma:** [#395](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469238422) | [#482](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-108#comment-1471226098) | [#368](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469118935) | **Tagy:** #grafika, #redesign

> Návštěvníci odcházeli z košíku hledat info, nevrátili se

### 16.9. Zobrazit 'Zdarma' místo '0 Kč' u plateb
**Priorita:** Stredna | **Figma:** [#609](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-330#comment-1473465299) | [#410](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-128#comment-1469344190) | **Tagy:** #grafika

> Kouzelné slovo 'Zdarma' funguje lépe než 0 Kč

### 16.10. Zvětšit loga Google Pay a Apple Pay
**Priorita:** Nizka | **Figma:** [#396](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469244129) | **Tagy:** #grafika

> Lepší čitelnost log platebních metod

### 16.11. Chybová hláška slevového kódu zobrazit u pole, ne nahoře na stránce
**Priorita:** Stredna | **Figma:** [#389](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469188194) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#514](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-120#comment-1471402587) | **Tagy:** #grafika, #redesign

> Návštěvník se musí vracet k poli, špatný UX


---

## 17. Košík - Krok 3 (Rekapitulace)

### 17.1. Sytější barva pro názvy produktů v rekapitulaci
**Priorita:** Stredna | **Figma:** [#398](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-124#comment-1469253092) | **Tagy:** #grafika

> Drobné šedé písmo se hůře čte, potřeba rychlé kontroly

### 17.2. Zobrazit výhody registrace u checkboxu registrace v 3. kroku
**Priorita:** Stredna | **Figma:** [#409](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-128#comment-1469325888) | **Tagy:** #grafika, #redesign

> Motivace k registraci přímo při objednávce


---

## 18. Foxentry (Validace adres)

### 18.1. Změnit červený křížek validace na žlutý vykřičník
**Priorita:** Vysoka | **Figma:** [#200](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1465122570) | [#413](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6095-16#comment-1469374700) | [#388](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469177527) | **Tagy:** 

> Červený křížek je příliš agresivní, návštěvníci si myslí že nemohou odeslat objednávku. Již změněno dle update


---

## 19. Prázdný košík

### 19.1. Redesign prázdného košíku - brandové prvky, rozcestník kategorií s fotkami, osobní kontakt, výhody
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Stránka musí vrátit návštěvníky do nákupu

### 19.2. Přidat posuvník naposledy prohlížených produktů ('Rozmysleli jste se?')
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Možnost vrátit se k produktům které byly v košíku

### 19.3. Přidat drobečkovou navigaci
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Návštěvník musí vědět kde se nachází


---

## 20. Přihlášení / Registrace

### 20.1. Přidat křížek pro zavření přihlašovacího panelu na mobilu
**Priorita:** Vysoka | **Figma:** [#552](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-426#comment-1472446032) | [#306](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467058591) | [#597](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-378#comment-1473386282) | **Tagy:** #grafika, #redesign

> Návštěvníci neví že musí kliknout znovu na ikonu uživatele

### 20.2. Tlačítko přihlášení na celou šířku na mobilu
**Priorita:** Stredna | **Figma:** [#554](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-426#comment-1472447090) | **Tagy:** #grafika, #redesign

> Širší tlačítko je pohodlnější na kliknutí

### 20.3. Redesign registrační stránky - brandové prvky, výhody registrace, tlačítka přihlášení vlevo
**Priorita:** Vysoka | **Figma:** [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | [#157](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-235#comment-1463351324) | [#512](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-118#comment-1471400453) | **Tagy:** #grafika, #redesign

> Stránka by měla prezentovat výhody registrace a být vizuálně atraktivní


---

## 21. Kontaktní stránka

### 21.1. Komplexní redesign kontaktní stránky - fotky týmu, formulář, FAQ, sociální sítě, fakturační údaje, mapa s fotkou skladu
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Obsahové stránky jsou příležitost odlišit se od konkurence, budovat důvěryhodnost

### 21.2. Přidat kontaktní formulář přímo na stránku
**Priorita:** Vysoka | **Figma:** [#483](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-108#comment-1471229407) | **Tagy:** #grafika, #redesign

> Zjednodušení cesty pro návštěvníky s dotazy, nemusí přecházet do emailového klienta

### 21.3. Kompaktní obsahový blok pro výdejní sklad (adresa, mapa, foto, instrukce, navigace)
**Priorita:** Stredna | **Figma:** [#482](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-108#comment-1471226098) | [#471](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471066924) | **Tagy:** #grafika, #redesign

> Obsah musí být vizuálně propojen, návštěvníci skenují a nemusí vidět instrukce pod mapou

### 21.4. Přidat rozcestník na další stránky (Náš příběh, Doprava a platba, atd.)
**Priorita:** Nizka | **Figma:** [#487](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-108#comment-1471257044) | **Tagy:** #grafika

> Interní prolinkování a navigace


---

## 22. Doprava a platba (stránka)

### 22.1. Přidat loga dopravců a platebních metod k jednotlivým řádkům
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Rychlejší vizuální orientace

### 22.2. Informativní box o dopravě zvýraznit (podbarvení světle fialovou, ikona)
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Důležitá informace o cenách dopravy je snadno přehlédnutelná

### 22.3. Přidat FAQ sekci o dopravách a platbách
**Priorita:** Stredna | **Figma:** [#484](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-108#comment-1471235009) | **Tagy:** #grafika

> Zodpovědění dotazů přímo na stránce


---

## 23. Reklamace a vrácení zboží

### 23.1. Přidat infografiku vizualizující proces reklamace krok za krokem
**Priorita:** Vysoka | **Figma:** [#500](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-112#comment-1471359480) | **Tagy:** #grafika, #redesign

> Velké množství textu, vizuální přehled pomůže pochopit postup

### 23.2. Přidat rozcestník s kotvami na jednotlivé typy případů v horní části
**Priorita:** Stredna | **Figma:** [#501](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-112#comment-1471361736) | [#453](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1470979351) | [#318](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467125882) | **Tagy:** #grafika, #redesign

> Rychlejší nalezení relevantního obsahu

### 23.3. Tlačítko formuláře reklamace výrazněji a výše na stránce
**Priorita:** Vysoka | **Figma:** [#502](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-112#comment-1471368095) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#238](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-207#comment-1465361091) | **Tagy:** #grafika, #redesign

> Nyní je pouze v textu, snadno přehlédnutelné, kvůli tomu návštěvník přišel

### 23.4. Přidat dlaždici s osobním kontaktem ('Nejste si jisti? Zavolejte nám!')
**Priorita:** Stredna | **Figma:** [#499](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-112#comment-1471358817) | **Tagy:** #grafika, #redesign

> Zachycení nerozhodných návštěvníků

### 23.5. Přidat FAQ k reklamacím
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Zodpovědění častých dotazů


---

## 24. Mamutex+ (Věrnostní program stránka)

### 24.1. Přidat výrazné CTA k registraci - minimálně 2x na stránce
**Priorita:** Vysoka | **Figma:** [#505](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-116#comment-1471383152) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#32](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1461714680) | **Tagy:** #grafika, #redesign

> Priorita 4/5 - úplně chybí viditelná výzva k registraci, to je hlavní cíl stránky

### 24.2. Více infografik a krátkých textů v odrážkách místo dlouhých textů
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Příliš mnoho textu, návštěvníci nepřečtou

### 24.3. Přidat storytelling/reference zákazníků (kolik ušetřili)
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Social proof, motivace k registraci

### 24.4. Přidat FAQ sekci k věrnostnímu programu
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Zodpovědění dotazů

### 24.5. Konzistentní zobrazení mincí VP na všech místech kde se Mamutex+ zmiňuje
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Sjednocení vizuální identity VP


---

## 25. Blog / Poradna

### 25.1. Náhledové obrázky u VŠECH článků - priorita 5/5
**Priorita:** Vysoka | **Figma:** [#449](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-102#comment-1470939869) | [#538](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472417360) | [#473](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471081162) | **Tagy:** #grafika, #redesign

> Chybí náhledové obrázky, pozitivní vliv na proklikovost a SEO. Častá chyba Shoptet

### 25.2. Vytvořit šablonu článku vč. podpisu autora
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Jednotný formát článků, autor s fotkou a odkazem na profil pro důvěryhodnost

### 25.3. Stránkový výpis všech článků na hlavní stránce blogu (ne jen 3)
**Priorita:** Vysoka | **Figma:** [#444](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-100#comment-1470910368) | [#231](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-196#comment-1465331842) | **Tagy:** #grafika, #redesign

> Nyní se zobrazují pouze 3 články

### 25.4. První článek s větší vizuální prioritou (feature article)
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Upoutání pozornosti na nejnovější/nejdůležitější článek

### 25.5. Přidat ilustrační obrázky ke kategoriím článků
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Lepší uvedení tématu

### 25.6. Přidat počet článků za název kategorie
**Priorita:** Nizka | **Figma:** [#439](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-100#comment-1470895086) | **Tagy:** #grafika

> Lepší přehled o rozsahu obsahu

### 25.7. Tematický vizuál v horní části kategorií článků se signature prvky
**Priorita:** Stredna | **Figma:** [#464](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471043453) | **Tagy:** #grafika, #redesign

> Uvedení tématu, naladění atmosféry značky

### 25.8. Vylepšit stránkování článků - čísla stránek místo jen šipky
**Priorita:** Nizka | **Figma:** [#452](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-102#comment-1470973104) | **Tagy:** #grafika

> Návštěvníci si mohou pamatovat na které stránce článek byl

### 25.9. Šedá tlačítka filtrů/kategorií na blogu nahradit světle fialovou
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Šedá vypadá jako neaktivní

### 25.10. Přidat ikonu šipky '>' k boxům podkategorií blogu
**Priorita:** Nizka | **Figma:** [#447](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-100#comment-1470915373) | [#521](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-398#comment-1471465681) | [#420](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-94#comment-1469400886) | **Tagy:** #grafika

> Aby bylo jasné že jde o proklik, nyní vypadají jako neaktivní


---

## 26. Detail článku

### 26.1. Přidat úvodní fotografii na začátek článku
**Priorita:** Vysoka | **Figma:** [#463](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471032042) | **Tagy:** #grafika, #redesign

> Lepší uvedení článku, navození atmosféry, Google pozitivně hodnotí vizuální materiály

### 26.2. Přidat přehled obsahu (table of contents) u delších článků
**Priorita:** Vysoka | **Figma:** [#453](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1470979351) | **Tagy:** #grafika, #redesign

> Rychlá navigace, pomáhá SEO

### 26.3. Navrhnout vizuální bloky pro tipy, důležité info, zajímavosti v článcích (signature prvky)
**Priorita:** Vysoka | **Figma:** [#458](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471000623) | [#373](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-122#comment-1469125602) | [#303](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1467039375) | **Tagy:** #grafika, #redesign

> Zpřehlednění obsahu, podvědomé vnímání identity, AI mode od Google tyto prvky hodnotí

### 26.4. Bohatší okénko autora pod článkem (fotka, popis, odkaz na profil)
**Priorita:** Vysoka | **Figma:** [#467](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471056653) | **Tagy:** #grafika, #redesign

> Osobnější dojem, Authority rank, důvěryhodnost

### 26.5. Přidat subkonverzi na konec článku (newsletter, slevový kupón, odkaz na produkty)
**Priorita:** Stredna | **Figma:** [#465](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471055595) | [#54](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462783471) | **Tagy:** #grafika, #redesign

> Návštěvník musí mít co dělat po přečtení

### 26.6. Skrýt prázdné diskuze pod články
**Priorita:** Stredna | **Figma:** [#471](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471066924) | **Tagy:** #grafika

> Prázdné diskuze působí že obsah nikoho nezajímá

### 26.7. Pod článkem zobrazit náhledy dalších článků (ne jen textové odkazy)
**Priorita:** Stredna | **Figma:** [#469](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471058222) | [#440](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-100#comment-1470898880) | **Tagy:** #grafika, #redesign

> Návštěvník neví na jaký obsah bude přecházet, snižuje proklikovost

### 26.8. Zachovat konzistentní formát produktové karty i v článcích
**Priorita:** Stredna | **Figma:** [#473](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471081162) | **Tagy:** #grafika

> Zmenšení produktové karty může negativně ovlivnit proklikovost

### 26.9. Produkty v článcích zobrazit formou posuvníku
**Priorita:** Stredna | **Figma:** [#472](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-104#comment-1471076218) | **Tagy:** #grafika, #redesign

> Více produktů k prohlížení


---

## 27. Značky / Výrobci

### 27.1. Vytvořit stránku výpisu značek s hlavní prioritou Mamutex
**Priorita:** Vysoka | **Figma:** [#270](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=5-92#comment-1466056386) | **Tagy:** #grafika, #redesign

> Stránka na eshopu chybí, důvěryhodnost, SEO

### 27.2. Navrhnout detail značky - logo, signature prvky/vizuál, popis, kategorie značky, články, videa
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Podpora brandu, SEO, navigace


---

## 28. Chybová stránka (404)

### 28.1. Redesign 404 stránky - vizuální potvrzení chyby, rozcestník kategorií, nejprodávanější produkty, výhody, odkazy
**Priorita:** Vysoka | **Figma:** [#514](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-120#comment-1471402587) | **Tagy:** #grafika, #redesign

> Stránka musí lákat dále do obsahu, ne nechat návštěvníka odejít


---

## 29. Patička (Footer)

### 29.1. Konkurenční výhody zobrazovat nad patičkou na všech stránkách
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika, #redesign

> Budování důvěryhodnosti na všech landing pages


---

## 30. Recenze a Hodnocení

### 30.1. Přidat štítek 'Ověřená recenze' k recenzím z Heureka.cz
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Zvýšení důvěryhodnosti recenzí

### 30.2. Recenze kurzívou jako přímá řeč
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Lepší vizuální oddělení, osobnější dojem

### 30.3. Řazení recenzí podle data přidání
**Priorita:** Vysoka | **Figma:** [#626](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1525068158) | **Tagy:** #grafika

> Aktuální hodnocení, důvěryhodnost - testující se ptali jestli si eshop recenze negeneruje

### 30.4. Opravit špatnou čitelnost hvězdiček hodnocení (žlutá #F0B825 na bílé = FAIL)
**Priorita:** Vysoka | **Figma:** — | **Tagy:** #grafika

> Nesplňuje standard kontrastu

### 30.5. Přidat rozsah let na trhu k hodnocení eshopu
**Priorita:** Stredna | **Figma:** [#628](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1525245500) | **Tagy:** #grafika

> Návštěvník musí vědět že nejste noví na trhu


---

## 31. Produktová karta (component)

### 31.1. Navrhnout rozšířenou produktovou kartu s parametry pod názvem (nosnost, rozměry, materiál)
**Priorita:** Vysoka | **Figma:** [#555](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-428#comment-1472447695) | [#191](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-175#comment-1464972421) | **Tagy:** #grafika, #redesign

> Testující chtěli vidět parametry přímo ve výpisu bez proklikávání na detail, priorita 5/5

### 31.2. Přidat hover efekt na sekundární foto s rozměry/parametry
**Priorita:** Stredna | **Figma:** [#54](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462783471) | [#129](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-217#comment-1463230872) | [#64](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462822194) | **Tagy:** #grafika, #redesign

> Při hoveru nad produktem zobrazit technickou fotku, inspirace z Notino/Alza

### 31.3. Celá produktová karta jako klikatelná oblast (nejen fotka a název)
**Priorita:** Vysoka | **Figma:** [#621](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1524991573) | [#232](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-196#comment-1465333594) | [#120](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-215#comment-1463208018) | **Tagy:** #grafika, #redesign

> Testující klikali vedle fotky a nic se nestalo, hover efekt sugeruje celý box je odkaz

### 31.4. Sjednotit štítky desktop/mobil (zaoblené vs ostré rohy)
**Priorita:** Nizka | **Figma:** — | **Tagy:** #grafika

> Konzistence napříč platformami

### 31.5. Prvek 'Skladem' by neměl vypadat jako tlačítko
**Priorita:** Stredna | **Figma:** [#640](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-11#comment-1548811754) | [#629](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-223#comment-1548460055) | [#662](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-134#comment-1550610660) | **Tagy:** #grafika, #redesign

> Testující na to klikali, mysleli že je to tlačítko

### 31.6. Přidat volbu počtu kusů přímo do produktové karty na mobilu (testovat)
**Priorita:** Nizka | **Figma:** [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | [#540](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-404#comment-1472423430) | [#597](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-378#comment-1473386282) | **Tagy:** #grafika

> Může intuitivně vést k přidání více kusů


---

## 32. Různé / Obecné úpravy

### 32.1. Přegenerovat AI fotky produktů novým modelem
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika

> Starý AI model, fotky nevypadají dostatečně kvalitně

### 32.2. Drobečková navigace - zobrazovat kompletní strukturu vč. nižších úrovní a ikony domečku
**Priorita:** Vysoka | **Figma:** [#577](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-338#comment-1473216818) | [#587](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-344#comment-1473309270) | **Tagy:** #grafika, #redesign

> Návštěvník musí vědět kde ve struktuře je, pomáhá SEO internímu prolinkování

### 32.3. Sjednotit ovládací prvky rozbalení/sbalení (+ -  vs šipky) napříč celým webem
**Priorita:** Stredna | **Figma:** — | **Tagy:** #grafika, #redesign

> Nekonzistentní UI mate návštěvníky

### 32.4. Křížek pro zavření modalu - dostatek prostoru od rohu, jednotný styl bez obrysu
**Priorita:** Stredna | **Figma:** [#604](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-320#comment-1473453383) | [#263](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6048-11#comment-1465504530) | **Tagy:** #grafika

> Málo prostoru kolem křížku stresuje, obrys bere zbytečně pozornost

### 32.5. Navrhnout bannery pro produktové výpisy v rámci design systému
**Priorita:** Stredna | **Figma:** [#538](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6002-406#comment-1472417360) | [#507](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-116#comment-1471390424) | [#73](https://www.figma.com/design/ZRnydfJQYihgeCcNMXZ09q/Mamutex.cz---Anal%C3%BDza-pou%C5%BEitelnosti?node-id=6001-211#comment-1462873078) | **Tagy:** #grafika, #redesign

> Bannery nad/pod produkty pro kampaně a akce, konzistentní design


---

*Celkom 200 uloh, 312 odkazov na Figma komentare.*  
*Kliknite na #cislo pre presmerovanie priamo na komentar vo Figme.*