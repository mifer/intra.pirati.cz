---
typ:  podpůrný
manažer: administrativní odbor
---

# Zakládání dokumentů do spisové služby

## Úvod

* Tento dokument podrobně definuje proces zakládání dokumentů do spisů ve
  spisové službě.

* Založení dokumentu do spisové služby předchází jednak tvorba dokumentů a
  jednak [založení spisu][postup-spisy].

* Tento proces je součástí [vedení spisové služby][postup-spisovka]. Pokud není uvedeno či z
  kontextu nevyplývá něco jiného, platí pro něj totéž, co pro
  nadřízený proces.

## Definice procesu

Účelem zakládání dokumentů do spisové služby v listinné i elektronické
podobě je, abychom

* zamezili ztrátě jeho originálu,
* zajistili autenticitu elektronické podoby,
* zrychlili sdílení dokumentu mezi lidmi v organizaci (každý dokument je k dispozici jak lokálně, tak i na serveru s vlastním URL) a
* usnadnili orientaci ve věci spisu a tedy zastupitelnost a audit a
* usnadnili pozdější vyhledání dokumentu.

## Cíle procesu

**Cílem** tohoto procesu je, aby byl

* každý dokument řádně založen do spisové služby,
* byla o něm dostatečně a prokazatelně informována osoba, která ho má vyřídit,
* byly nastaveny termíny pro jeho vyřízení, které lze hlídat.

## Typické vstupy procesu

Tj. odkud nám chodí dokumenty, které zakládáme do spisů Spisové služby?

* Datová schránka (evidujeme každý příchozí i odchozí dokument)
* Poštovní schránka (evidujeme každý příchodzí i odchozí dopis).
* E-mailová komunikace (jedná-li se o relevantní případ, např. na žádost odeslanou datovou schránkou odpoví e-mailem, obdržíme podnět od občana e-mailem apod). 
* Jakýkoliv jiný způsob, kdy obdržíme relevantní dokument, který přísluší danému spisu (např. úředník přinese písemnost osobně).

### 1. Kam ten dokument patří?

Každý dokument, který je zařazen do spisové služby musí mít právě jednu:

* Vlastní složku na githubovém repozitáři, která existuje rovněž i lokálně.
* Vlastní úkol v příslušném projektu v Redminu.

Podrobně: [postup pro založení spisu][postup-spisy].

### 2. Jaký spis je k dané věci správný?

Související spis se pokuste dohledat vždy

* v projektu toho týmu, kterého se spis týká, viz
  [seznam projektů](https://redmine.pirati.cz/projects) na úkolovníku,

* v repozitáři toho týmu, kterého se spis týká, viz
  [seznam spisových repozitářů][spisy] v úložišti Githubu.

Klíčovými informacemi k dohledání konkrétního spisu jsou:
    
    1. Spisová značka, kterou tvoří zkratka orgánu Pirátské strany (např. RP pro Republikové předsednictvo, ZK Pha pro zastupitelský klub v Praze). Spisová značka je unikátní pro uvedený spis a má odpovídající úkol se stejným číslem na Redminu.
    2. Subjekt, se kterým je vedena komunikace: Najděte případy, kdy příslušný orgán komunikoval s druhou stranou (např. s Českou televizí, Magistrátem města Brna apod). Vylučte poté ty případy, kde je předmět komunikace odlišný.
    3. Datum odeslání dokumentu: Pokud Vám zašle protistrana dokument, ve kterém Vaší spisovou značku neuvede, je dobré dohledat datum odeslání dokumentu, na který druhá strana odkazuje. 

První spis lze většinou dohledat podle kroku č. 1. Pokud se to nepovede, postupujte podle dalších bodů postupně. Nedokážete-li odpovídající spis najít, založte nový. 

### 3. Jak digitalizujeme dokumenty v papírové podobě? 

* Na obdržený dopis napište odpovídající číslo úkolu v Redminu a datum obdržení.

* Poté jej naskenujte/vyfoťte a převeďte do PDF. Body 7.2 a následující se týkají pouze elektronické
podoby dokumentu.

* Papírový originál dokumentu založte do papírového spisu, který je uložen v papírové
spisové službě daného týmu, typicky v jeho skříni, viz
[postupu pro založení spisu][postup-spisy]. Papírový spis je kopií digitálního; pouze však pro ty dokumenty, které mají papírový originál. Netiskněte dokumenty, které přicházejí elektronicky!

### 4. Jak digitalizované dokumenty nahrajeme do úložiště?

Digitalizovaný dokument (buď PDF, které jste získali z datové schránky, nebo ten, který jste naskenovali apod). nahrajte na odpovídající githubový repozitář do odpovídající složky. 

Adresářová struktura na repozitáři má jasně daná pravidla: 

* Název složky je tvořen číslem úkolu, spojovníkem a zkráceným názvem bez diakritiky (např. ``1234-odmeny-krobove-hasove``).

* V každé složce vytvářejte obdobné podsložky pro jednotlivé dokumenty
  (např. ``02-odvolani``). Ve složkách jsou i přílohy.

* Dokument je třeba nahrát do podsložky daného spisu, která je nazvána podle

  * čísla úkolu a věci ve spisu, např. ``4558-metodika-finance/`` a dále
  * podle pořadového čísla dokumentu v daném spisu, např. ``04-odpoved-psp`` (viz obrázek).

![Seznam dokumentů na githubu](img/seznam-dokumentu.png)

* Pořadové číslo dokumentu
se uvádí s uvozovacími nulami vždy na 2 cifry, aby se dokumenty řadily chronologicky. První zařazený dokument má nejnižší číslo; poslední má číslo nejvyšší. Čísla přidělujte podle data obdržení dokumentu. 

* Pokud máte pochybnost, zda je v zájmu Pirátů nebo v souladu se
zákonem určitou věc zveřejnit, zeptejte se vedoucího týmu nebo jeho zástupce,
případně použije soukromou poznámku či vložte spis do soukromého úložiště.

### 5. Jak určíme termín, do kdy danou věc vyřešit?

* Pro určení termínu pro uzavření je podstatné
datum, kdy nám byl dokument doručen nebo byl odeslán (podle údajů v datové
schránce nebo vyzvednutí na poště).

* Datum doručení nebo
odeslání a výpočet lhůty je potřeba průkazně zaznamenat. Datum doručení
je určeno [pravidly pro doručování](http://www.mvcr.cz/clanek/obcane-tretich-zemi-prubeh-rizeni-prijimani-a-dorucovani-pisemnosti.aspx). Na správné určení data doručení je potřeba
si dát velký pozor, protože právě od něho se lhůty odvíjejí.

Lhůta je určena věcí, o kterou jde, a typicky vyplývá ze zákona
nebo ze standardního obchodního styku. Vypočtěte tedy den lhůty,
do kdy je třeba spisu věnovat pozornost:

* V případě **příchozího dokumentu** je nezbytné očekávat, že budete muset odpovědět, a to v odpovídající lhůtě. V případě úřední komunikace bude k Vaší škodě, když prošvihnete zákonnou lhůtu. Tuto lhůtu hlídejte velmi důsledně.

* v případě **odchozího dokumentu** je termínem pro reakci den, kdy uplyne
druhé straně zákonná nebo jiná přiměřená lhůta (plus případně několik dní k dobru),
a kdy tedy bude případně nutné urgovat vyřízení naší žádosti, pokud
nedostaneme žádnou odpověď (např. podat stížnost kvůli nečinnosti).

### 6. Jak zaznamenáme co se stalo do Redminu? 

* Nyní je potřeba vložit poznámku o založeném dokumentu do příslušného úkolu
  v [Redminu](https://redmine.pirati.cz).

* Najděte si příslušný úkol v Redminu podle čísla a klikněte na tlačítko ``Upravit`` v horní liště.

* Přidejte také hypertextový odkaz na
  konkrétní dokument v úložišti (pokud možno rovnou na náhled příslušného
  pdf dokumentu). Tento hypertextový odkaz najdete přímo po rozkliknutí
  struktury souborů ve spisovém repozitáři. Jednotlivé dokumenty nenahrávejte přímo na Redmine. 

* Napište do textového pole
  poznámku, kdy byl dokument doručen nebo odeslán, co a kdy je
  potřeba udělat, tj. termín pro reakci (viz obrázek níže). Pokud byl originál
  dokument také fyzicky založen do papírového spisu, uveďte to v poznámce také.

* Lhůta se zároveň nastaví do pole ``Uzavřít do`` u daného úkolu.

* Pokud byl dokument, zařazený do spisové služby,:
    
    a) odeslán (poštou, datovou schránkou apod). a čekáte na vyjádření druhé strany, nastavte hodnotu ``stav`` na **čeká se-oni**
    b) přijat (obdrželi jste novou zprávu v datové schránce, přišla pošta) a připravujete reakci za Piráty, nastavte hodnotu ``stav`` na **čeká se-my**
    
 ![Poznámka redmine](img/poznamka-redmine.png)

### 7. Jak zaúkolujeme odpovědného člověka?

Pokud věc vyřizuje někdo jiný než Vy, informujte tohoto člověka
o tom, že byl založen dokument a sdělte mu:

* o co v daném úkolu jde, jak je třeba jej řešit a do kdy tak musí být učiněno.
* pošlete mu e-mail, kde bude prvotní dokument přiložen/odkázán.
* v úkolu v Redminu osobu přiřaďte k odpovídajícímu úkolu.

Vyřizujte věci obratem, je-li to možné. Počítejte s tím, že ten, komu práci předáváte, potřebuje mít také dodatek času pro formulaci správné odpovědi. Zasílání úkolů na konci lhůty vede k zbytečnému napětí a možným chybám ve spisové službě.  Zasílejte proto potřebné informace vždy včas!

[prehled-ss]: https://redmine.pirati.cz/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=~&v%5Bsubject%5D%5B%5D=spisov%C3%A1+slu%C5%BEba&f%5B%5D=&c%5B%5D=project&c%5B%5D=subject&c%5B%5D=assigned_to&group_by=&t%5B%5D=

## Typický výstup procesu

* Přijatý, či odeslaný dokument je evidován v spisové službě 
* V Redminu je založen odpovídající úkol a nastaven termín pro reakci v dané věci. 
* Osoba, která má danou věc vyřídit, byla o záležitosti prokazatelně informována. 

## Rizika

### Nezaložení dokumentu

* Riziko je středně pravděpodobné a může být vážné, protože dokument nebude dohledatelný v okamžiku, kdy ho potřeba.
* Ke zmírnění rizika slouží jednotný a centrální systém zakládání dokumentů v rámci daného týmu, dobrý výcvik osob, které vedou spisovou službu, a informovanost všech lidí o povinnosti zakládat podstatné dokumenty do spisové služby (např. zastupitelů, hospodářů apod.).

### Chybná data

* Riziko chybného založení termínu či chybný výpočet lhůty je středně pravděpodobné a může být vážné, pokud prošvihneme lhůtu pro důležité odvolání nebo stížnost.
* Ke zmírnění rizika je potřeba, aby odpovědná osoba dobře znala mechanismus výpočtu lhůt při komunikaci s úřady. Lhůty, které jsou složitěji vypočítávané, je nezbytné v příslušné poznámce v odpovídajícím úkolu v Redminu rozepsat (např. ``7 dní pro předání + 15 dní pro odpověď``, tj. čas máme do 13. prosince 2022) apod. 

## Související

* [Vedení spisové služby][postup-spisovka]
* [Zakládání dokumentů][postup-dokumenty]
* [Zakládání spisu][postup-spisy]
* Zadávání úkolů
* Kontrola pošty

[postup-spisovka]:  README.md
[postup-spisy]: zakladani-spisu.md
[postup-dokumenty]:  zakladani-dokumentu.md
