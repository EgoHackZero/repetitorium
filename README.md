1. **Popište rozdiel medzi kybernetikou, aoutomatikou, umelou inteligenciou a robotikou.**
   
   Kybernetika je veda o riadení a komunikácii v organizmoch a strojoch. Zaoberá sa teóriou informácií, riadiacimi systémami a spôsobmi, ako systémy spracúvajú informácie a adaptujú sa na zmeny v prostredí.

   Automatika, tiež známa ako riadiaca technika alebo automatizácia, sa zameriava na používanie strojov a technológií na automatizáciu procesov a systémov, ktoré tradične vyžadovali ľudský zásah.

   Umelá inteligencia je oblasť počítačovej vedy, ktorá sa zaoberá vytváraním počítačových systémov schopných vykonávať úlohy, ktoré zvyčajne vyžadujú ľudskú inteligenciu, ako je spracovanie prirodzeného jazyka, vizuálne rozpoznávanie a rozhodovanie.
   
   Robotika je technické odvetvie, ktoré sa zaoberá návrhom, stavbou, prevádzkou a používaním robotov. Táto oblasť často používa princípy kybernetiky a automatiky na vytvorenie strojov, ktoré môžu interagovať s fyzickým svetom a vykonávať rôzne úlohy.
3. **čo robi system (zariadenie) inteligentnym (zakladne znaky).**
   - Schopnosť učenia sa: Systém musí byť schopný učiť sa z dát, či už prostredníctvom strojového učenia alebo iných metód.
   - Adaptabilita: Musí sa vedieť prispôsobiť zmenám v prostredí bez ľudského zásahu.
   - Autonómia: Schopnosť vykonávať úlohy samostatne, bez potreby neustáleho dohľadu alebo riadenia človekom.
   - Interaktivita: Sposobnosť komunikovať a interagovať s ľuďmi alebo inými systémami.
   
5. **Popište klasifikaciu, regresiu, a reinforsment learning? čo su to?.**
   - Klasifikácia je typ strojového učenia, kde model predpovedá kategóriu, do ktorej dátový bod patrí. Napríklad, rozpoznávanie, či obrázok obsahuje mačku alebo psa.
   - Regresia sa zaoberá predikciou spojitéj hodnoty. Príkladom môže byť predpovedanie ceny domu na základe rôznych atribútov ako veľkosť alebo lokalita.
   - Reinforcement learning (posilňované učenie) je metóda strojového učenia, kde agent sa učí správať sa v prostredí tak, aby maximalizoval sumu odmien. Príkladom je učenie sa robotov, ako prechádzať labyrintom.
6. 

7. **Popište rozdiel medzi pojmami: data - informacie - znalosti. Aka je štruktura znalostnych sistemov? Popište jednotlive kroky. Ako môžeme prehľadovať inferenčnu sieť.**
   - *Dáta* sú surové, neorganizované fakty, ktoré sú zvyčajne neštrukturované.
   - *Informácie* sú spracované dáta, ktoré majú určitý význam alebo účel.
   - *Znalosti* sú komplexné súbory informácií, ktoré sú organizované a aplikované tak, aby boli užitočné.
     
**Štruktúra znalostných systémov**

Znalostné systémy sa zvyčajne skladajú z nasledujúcich komponentov:

   - Dátová báza: Súbor dát alebo informácií.
   - Znalostná báza: Súbor pravidiel alebo heuristík, ktoré definujú, ako sa majú dáta používať.
   - Inferenčný motor: Mechanizmus, ktorý aplikuje pravidlá na dáta, aby generoval závery.
   - Používateľské rozhranie: Umožňuje ľuďom interagovať so systémom.

Inferenčnú sieť môžeme prehľadávať pomocou rôznych metód grafovej analýzy, kde každý uzol predstavuje tvrdenie alebo koncept, a hrany predstavujú logické spojenia alebo odvodenia.

9. **Podľa akzch rôznych kriterii vieme deliť sensory a akčne členy (ku každemu kriteriu uvedte ich delenie do skupin a priklady sensorov a akčných členov)?**

   - Podľa funkcie:
      - Senzory: Zariadenia, ktoré detekujú zmeny v prostredí a transformujú ich na elektrický signál. Napríklad teplotné senzory, tlakové senzory, fotocely.
      - Akčné členy (aktuátory): Zariadenia, ktoré prevádzajú elektrický signál na mechanickú akciu. Napríklad elektromotory, pneumatické alebo hydraulické válce.
   - Podľa vstupu/výstupu:
      - Analógové senzory a aktuátory: Prevádzajú nepretržité (analógové) signály, ako je napríklad zmena napätia alebo prúdu.
      - Digitálne senzory a aktuátory: Pracujú s digitálnymi signálmi, zvyčajne vo forme binárnych dát (zapnuté/vypnuté).
   - Podľa použitého princípu:
      - Piezoelektrické senzory: Využívajú piezoelektrický efekt na detekciu zmien, ako sú vibrácie alebo tlak.
      - Termočlánky: Generujú elektrický prúd pri zmene teploty.
      - Optické senzory: Zahrnujú fotočlánky, ktoré reagujú na svetlo.
      - Elektromagnetické aktuátory: Využívajú elektromagnetické pole na pohon alebo kontrolu mechanizmov.

10. **Uvedte typy uloh rešiteľných pomocou neuronovych sieti s praktickym prikladom. Uvedte typy uloh neriešitelnych pomocou neuronovych sieti. čo je universalna aproximačna teorema?**

   **Riešiteľné úlohy:**

   - Klasifikácia obrazu: Napríklad rozpoznávanie objektov na fotografii.
   - Predikcia časových radov: Napríklad predpovedanie cien akcií alebo meteorologických údajov.
   - Spracovanie prirodzeného jazyka: Preklad textu medzi jazykmi alebo generovanie textových odpovedí.

**Neriešiteľné úlohy:**

   - Úlohy, ktoré vyžadujú abstraktné uvažovanie a obrovské množstvo všeobecného svetového porozumenia, čo je aktuálne mimo schopnosti neurónových sietí.
   - Úlohy vyžadujúce precízne a záručné spracovanie dát, ako napríklad vysoko presné finančné transakcie alebo riadenie letového prevádzky, kde je potrebná 100% spoľahlivosť.

**Univerzálna aproximačná teoréma:**

Táto teoréma hovorí, že feed-forward neurónová sieť s jednou skrytou vrstvou obsahujúcou konečný počet neurónov môže s dostatočnou presnosťou aproximovať akúkoľvek spojitú funkciu na uzavretom intervale. Táto teoréma zdôrazňuje výkonnosť neurónových sietí v rôznych úlohách aproximácie funkcií.

11. **Definujte fuzzy množiinu, demonštrujte  na konkretnom priklade. Ake zakladne operacie s fuzzy Množinami poznate? čo je defuzzifikacia?**

12. **Rozdelte typy mobilnych robotov a uvedte rozdiel medzi lokalizaciou a navigaciou (pri navigacii a lokalizacii uvedte aj technologie a algoritmy ktore ich zabezpečuju**

13. **Aky je rozdiel medzi priestorom pojmov, priznalov7m priestorom a stavov7m priestorom? Kedy uviazneme v lokalnom minime a ako z neho von?**

14. **Ake techniky segmentacie obrazu pozname? Popište**

15. **Zakreslite a popište uyavretý regulačný obvod. Aky je rozdiel medzi riadenim, regulaciou (URO) a ovladani, (ORO)?**

16. **Charakterizujte pojem Industry 4.0 a uvedte priklady konceptov a technoloii, ktore ho tvoria, spolu s ich vyznamom.**

17. **Aky bol prinos nasledovnych ludi:**
    - Mohamed AI-Chorezmi
    - James Watt
    - Ada Lovelace
    - Blaise Pascal
    - Anre-Marie Ampere
    - Alan Turing
    - Nikola Tesla
    - Jochn McCarthy
    - Frank Rosenblatt
    - Lotfi Zadeh
    - John von Neumann
    - Isaac Asimon
    - Grace Hopper
    - Walter Pitts
    - Norber Wiener
    - Werner von Siemens
