1. **Popište rozdiel medzi kybernetikou, aoutomatikou, umelou inteligenciou a robotikou.**
   
   Kybernetika je veda o riadení a komunikácii v organizmoch a strojoch. Zaoberá sa teóriou informácií, riadiacimi systémami a spôsobmi, ako systémy spracúvajú informácie a adaptujú sa na zmeny v prostredí.

   Automatika, tiež známa ako riadiaca technika alebo automatizácia, sa zameriava na používanie strojov a technológií na automatizáciu procesov a systémov, ktoré tradične vyžadovali ľudský zásah.

   Umelá inteligencia je oblasť počítačovej vedy, ktorá sa zaoberá vytváraním počítačových systémov schopných vykonávať úlohy, ktoré zvyčajne vyžadujú ľudskú inteligenciu, ako je spracovanie prirodzeného jazyka, vizuálne rozpoznávanie a rozhodovanie.
   
   Robotika je technické odvetvie, ktoré sa zaoberá návrhom, stavbou, prevádzkou a používaním robotov. Táto oblasť často používa princípy kybernetiky a automatiky na vytvorenie strojov, ktoré môžu interagovať s fyzickým svetom a vykonávať rôzne úlohy.
2. **čo robi system (zariadenie) inteligentnym (zakladne znaky).**
   - Schopnosť učenia sa: Systém musí byť schopný učiť sa z dát, či už prostredníctvom strojového učenia alebo iných metód.
   - Adaptabilita: Musí sa vedieť prispôsobiť zmenám v prostredí bez ľudského zásahu.
   - Autonómia: Schopnosť vykonávať úlohy samostatne, bez potreby neustáleho dohľadu alebo riadenia človekom.
   - Interaktivita: Sposobnosť komunikovať a interagovať s ľuďmi alebo inými systémami.
   
3. **Popište klasifikaciu, regresiu, a reinforsment learning? čo su to?.**
   - Klasifikácia je typ strojového učenia, kde model predpovedá kategóriu, do ktorej dátový bod patrí. Napríklad, rozpoznávanie, či obrázok obsahuje mačku alebo psa.
   - Regresia sa zaoberá predikciou spojitéj hodnoty. Príkladom môže byť predpovedanie ceny domu na základe rôznych atribútov ako veľkosť alebo lokalita.
   - Reinforcement learning (posilňované učenie) je metóda strojového učenia, kde agent sa učí správať sa v prostredí tak, aby maximalizoval sumu odmien. Príkladom je učenie sa robotov, ako prechádzať labyrintom.
4. 

5. **Popište rozdiel medzi pojmami: data - informacie - znalosti. Aka je štruktura znalostnych sistemov? Popište jednotlive kroky. Ako môžeme prehľadovať inferenčnu sieť.**
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

6. **Podľa akzch rôznych kriterii vieme deliť sensory a akčne členy (ku každemu kriteriu uvedte ich delenie do skupin a priklady sensorov a akčných členov)?**

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

7. **Uvedte typy uloh rešiteľných pomocou neuronovych sieti s praktickym prikladom. Uvedte typy uloh neriešitelnych pomocou neuronovych sieti. čo je universalna aproximačna teorema?**

   **Riešiteľné úlohy:**

   - Klasifikácia obrazu: Napríklad rozpoznávanie objektov na fotografii.
   - Predikcia časových radov: Napríklad predpovedanie cien akcií alebo meteorologických údajov.
   - Spracovanie prirodzeného jazyka: Preklad textu medzi jazykmi alebo generovanie textových odpovedí.

**Neriešiteľné úlohy:**

   - Úlohy, ktoré vyžadujú abstraktné uvažovanie a obrovské množstvo všeobecného svetového porozumenia, čo je aktuálne mimo schopnosti neurónových sietí.
   - Úlohy vyžadujúce precízne a záručné spracovanie dát, ako napríklad vysoko presné finančné transakcie alebo riadenie letového prevádzky, kde je potrebná 100% spoľahlivosť.

**Univerzálna aproximačná teoréma:**

Táto teoréma hovorí, že feed-forward neurónová sieť s jednou skrytou vrstvou obsahujúcou konečný počet neurónov môže s dostatočnou presnosťou aproximovať akúkoľvek spojitú funkciu na uzavretom intervale. Táto teoréma zdôrazňuje výkonnosť neurónových sietí v rôznych úlohách aproximácie funkcií.

8. **Definujte fuzzy množiinu, demonštrujte  na konkretnom priklade. Ake zakladne operacie s fuzzy Množinami poznate? čo je defuzzifikacia?**

**Fuzzy** množina je typ množiny, kde príslušnosť k množine nie je iba binárna (príslušník/nie je príslušník), ale každý element má stupňovitú príslušnosť k množine, ktorá sa vyjadruje hodnotami medzi 0 a 1. To umožňuje oveľa nuansovanejšie zaobchádzanie s neistotou a neurčitosťou.

Príklad fuzzy množiny:

Predstavme si množinu "Teplé dni". V klasickej množinovej teórii by deň buď bol teplý, alebo by nebol. V prípade fuzzy množiny by každý deň mal priradenú hodnotu príslušnosti k množine teplých dní, napríklad:

   - 15 °C môže mať príslušnosť 0.3
   - 20 °C môže mať príslušnosť 0.7
   - 25 °C môže mať príslušnosť 1.0

**Základné operácie s fuzzy množinami zahŕňajú:**

   - Zjednotenie (Union): Maximálna hodnota príslušnosti prvkov k jednotlivým množinám.
   - Prienik (Intersection): Minimálna hodnota príslušnosti prvkov k jednotlivým množinám.
   - Komplement (Complement): Doplnok príslušnosti, teda 1 - μ(x), kde μ(x) je stupeň príslušnosti prvku x.

**Defuzzifikácia:**

Defuzzifikácia je proces, pri ktorom sa fuzzy hodnota transformuje na presnú, jednoznačnú hodnotu. Tento proces je dôležitý, najmä keď chceme z fuzzy systémov získať konkrétne výstupy, ktoré môžu riadiť akčné členy alebo iné systémy. Bežné metódy defuzzifikácie zahŕňajú:

   - Centroidná metóda: Vypočíta "ťažisko" fuzzy množiny, čím poskytne výstupnú hodnotu reprezentujúcu strednú hodnotu.
   - Bisector metóda: Nájde vertikálnu čiaru, ktorá rozdeľuje plochu pod grafom fuzzy množiny na dve rovnaké časti.

9. **Rozdelte typy mobilnych robotov a uvedte rozdiel medzi lokalizaciou a navigaciou (pri navigacii a lokalizacii uvedte aj technologie a algoritmy ktore ich zabezpečuju**

   **Typy mobilných robotov:**

   - Kolesové roboty: Využívajú kolesá na pohyb, čo je vhodné pre stabilné a rovné povrchy.
   - Pásové roboty: Majú pásové systémy, ktoré zabezpečujú lepšiu trakciu na nerovnom teréne.
   - Legged roboty: Roboty s nohami, ktoré môžu chodiť alebo behať, vhodné pre komplexné prostredia s prekážkami.

**Lokalizácia vs. Navigácia:**

   - Lokalizácia: Proces, pri ktorom robot určuje svoju polohu v prostredí. Využíva senzory a mapy prostredia na to, aby sa "našiel" v predom definovanom priestore.
   - Navigácia: Proces, kde robot nielenže určuje svoju polohu, ale tiež plánuje a vykonáva pohyb od jedného miesta k druhému. Zahrnuje lokalizáciu, ako aj plánovanie trasy a vyhýbanie sa prekážkam.

**Technológie a algoritmy pre lokalizáciu a navigáciu:**

   - Lokalizácia:
      - GPS (Global Positioning System): Využíva sa na určenie globálnej polohy v otvorenom priestore.
      - SLAM (Simultaneous Localization and Mapping): Vytvára mapu prostredia a súčasne určuje polohu robota v tomto prostredí.
      - Odometria: Využíva enkódery na kolesách alebo senzory pohybu na odhadnutie zmeny polohy na základe pohybu.
   - Navigácia:
      - Plánovanie cesty (Path Planning): Algoritmy ako A*, Dijkstra alebo RRT (Rapidly-exploring Random Tree) na nájdenie najlepšej trasy medzi dvoma bodmi.
      - Obchádzanie prekážok (Obstacle Avoidance): Senzorické systémy a algoritmy, ktoré umožňujú robotom identifikovať a vyhýbať sa prekážkam na ceste.
      - Vizualizácia a spracovanie obrazu: Roboti používajú kamery a ďalšie vizuálne senzory na získanie informácií o svojom okolí, ktoré pomáhajú pri navigácii.

10. **Aky je rozdiel medzi priestorom pojmov, priznalov7m priestorom a stavov7m priestorom? Kedy uviazneme v lokalnom minime a ako z neho von?**

   - Priestor pojmov (Concept Space): Abstraktný priestor, kde každý rozmer predstavuje jeden pojem alebo kategóriu, ktorú systém rozpoznáva a používa na klasifikáciu alebo rozlišovanie medzi rôznymi prvkami alebo situáciami.
   - Príznakový priestor (Feature Space): Predstavuje množinu všetkých možných hodnôt príznakov, ktoré môžu byť použité na opis objektov alebo udalostí. V strojovom učení je to priestor, kde každá dimenzia predstavuje jednu charakteristiku alebo vlastnosť, ktorá sa meria alebo pozoruje.
   - Stavový priestor (State Space): V dynamických systémoch alebo pri modelovaní procesov zahŕňa všetky možné stavy, v ktorých sa môže systém nachádzať, a popisuje, ako tieto stavy interagujú alebo sa menia časom.

*Kedy uviazneme v lokálnom minime a ako z neho von*

V kontexte optimalizácie a strojového učenia, lokálne minimum je bod, kde hodnota funkcie je nižšia než u susedných bodov, ale môže existovať iný bod (globálne minimum), kde je hodnota ešte nižšia. Uviaznutie v lokálnom minime znamená, že metóda optimalizácie prestane robiť pokroky, pretože sa domnieva, že našla minimum, hoci globálne minimum je inde.

*Stratégie na vyjdenie z lokálneho minima:*

   - Použitie momentu (Momentum): Pomáha "vytlačiť" optimalizačný proces z lokálneho minima vďaka pridanému impulzu, ktorý zohľadňuje predchádzajúce kroky.
   - Simulované žíhanie (Simulated Annealing): Náhodný proces, ktorý dovolíva občasné zhoršenia riešenia, čo môže pomôcť uniknúť z lokálnych miním.
   - Zmena parametrov učenia alebo použitie rôznych počiatočných podmienok: Experimentovanie s rôznymi hodnotami učebného tempa alebo začínajúc s rôznymi počiatočnými váhami môže viesť k odlišným trajektóriám v procese učenia, čo môže pomôcť vyhnúť sa uviaznutiu v lokálnych minímách.
   - Gradient Clipping: Orezávanie veľkých gradientov počas tréningu, ktoré môže pomôcť zabezpečiť stabilnejšiu konvergenciu a zabrániť výbuchom gradientov, ktoré môžu spôsobiť zaseknutie v lokálnych minímách.
   - Použitie komplexnejších optimalizačných algoritmov: Napríklad Adam alebo RMSprop, ktoré upravujú učebnú mieru adaptívne podľa historických gradientových aktualizácií, čo môže pomôcť efektívnejšie nájsť globálne minimum.

11. **Ake techniky segmentacie obrazu pozname? Popište**

   - Pragovanie (Thresholding): Jednoduchá, ale efektívna metóda, kde sa pixel považuje za súčasť objektu, ak jeho hodnota prekročí určitý práh.
   - Metóda Otsu: Automaticky vypočíta optimálny prahový bod pre binárnu segmentáciu na základe rozloženia intenzít pixelov.
   - Segmentácia na základe rastu oblasti (Region Growing): Začína od 'semennej' oblasti a rozširuje ju pridávaním susedných pixelov, ktoré spĺňajú určité kritériá podobnosti.
   - Watershed algoritmus: Využíva analogiu s hydrologickými povodiami pre oddelenie objektov v obraze, ktoré sa dotýkajú alebo prekrývajú.
   - Grafové metódy: Založené na teórii grafov, kde pixel alebo skupina pixelov predstavuje uzly a hrany definujú ich vzájomné vzťahy na základe podobnosti.

12. **Zakreslite a popište vyavretý regulačný obvod. Aky je rozdiel medzi riadenim, regulaciou (URO) a ovladani, (ORO)?**

   - Uzavretý regulačný obvod (URO), tiež známy ako spätnoväzbový obvod, je systém riadenia, ktorý neustále monitoruje výstup systému a automaticky upravuje vstup na základe rozdielu medzi aktuálnym výstupom a požadovaným cieľom alebo nastavením.
   - Riadenie/Regulácia (URO): Zameriava sa na udržanie výstupu systému blízko k požadovanému nastaveniu prostredníctvom neustálej spätnej väzby, ktorá automaticky koriguje chyby.
   - Ovládanie (ORO): Zameriava sa na manuálne alebo automatické ovládanie systému bez neustálej spätnej väzby, čo môže viesť k menej presnému dosahovaniu cieľov kvôli nedostatku korekcie v reálnom čase.

13. **Charakterizujte pojem Industry 4.0 a uvedte priklady konceptov a technoloii, ktore ho tvoria, spolu s ich vyznamom.**

Industry 4.0, známa aj ako štvrtá priemyselná revolúcia, je koncept, ktorý zahŕňa automatizáciu, využívanie dát, konektivitu a pokročilé výrobné technológie. Zahrnuje nasledujúce kľúčové aspekty:

   - Internet vecí (IoT): Pripojenie strojov a zariadení k internetu, umožňujúce zdieľanie dát a efektívnejšiu kontrolu procesov.
   - Cyber-fyzikálne systémy (CPS): Integrácia počítačových algoritmov a fyzických procesov. V týchto systémoch sú fyzické a softvérové komponenty hlboko prepojené a interagujú s okolitým svetom cez senzory a aktuátory.
   - Cloud Computing: Využívanie cloudových technológií pre ukladanie a spracovanie dát, čo umožňuje flexibilnejšie a škálovateľné výrobné systémy.
   - Big Data a Analýza Dát: Rozsiahle spracovanie dát z rôznych zdrojov na získanie hlbších poznatkov a optimalizáciu procesov.
   - Umelá inteligencia a strojové učenie: Aplikácia AI na automatizáciu rozhodovania a zlepšenie efektivity.
   - Aditívna výroba (3D tlač): Použitie 3D tlače pre rýchlu prototypovanie a výrobu, čo umožňuje vyššiu mieru prispôsobenia produktov na požiadanie.

14. **Aky bol prinos nasledovnych ludi:**
    - Mohamed AI-Chorezmi - Základy algebry, jeho práca na algoritme položila základy modernej informatiky
    - James Watt - Vylepšenia parného stroja, ktoré mali zásadný vplyv na priemyselnú revolúciu.
    - Ada Lovelace - Považovaná za prvú programátorku, napísala algoritmy pre Babbageov analytický stroj.
    - Blaise Pascal - Vynálezca jedného z prvých mechanických počítačov, Pascaline.
    - Anre-Marie Ampere - Zakladateľ elektrodynamiky, formuloval Ampérov zákon.
    - Alan Turing - Otec moderného počítača, rozvinul koncepciu univerzálneho Turingovho stroja.
    - Nikola Tesla - Vynálezy v oblasti elektromagnetizmu, vrátane striedavého prúdu a Teslovej cievky.
    - Jochn McCarthy - Jeden zo zakladateľov umelé inteligencie, vyvinul Lisp.
    - Frank Rosenblatt - Vynález perceptrónu, jedného z prvých modelov neurónových sietí.
    - Lotfi Zadeh - Zakladateľ teórie fuzzy množín, ktorá umožňuje lepšie zaobchádzanie s neistotou a neurčitosťou v dátach.
    - John von Neumann - Významný prínos v mnohých oblastiach matematiky a fyziky, vrátane teórie hier a počítačovej architektúry.
    - Isaac Asimon - Populárny spisovateľ, ktorý propagoval vedecké a technologické koncepty prostredníctvom svojej sci-fi literatúry, známy svojimi "Zákonmi robotiky".
    - Grace Hopper - Pionierka v oblasti počítačových vied, ktorá vyvinula jeden z prvých kompilátorov a bola kľúčovou postavou vo vývoji programovacieho jazyka COBOL.
    - Walter Pitts - Spolu s Warrenom McCullochom formuloval jednu z prvých teoretických modelov neurónových sietí.
    - Norber Wiener - Zakladateľ kybernetiky, disciplíny študujúcej reguláciu a ovládanie systémov v biologických a mechanických kontextoch.
    - Werner von Siemens - Významný priekopník v oblasti elektrotechniky, založil Siemens AG a prispel k rozvoju telegrafných a elektrických systémov.
