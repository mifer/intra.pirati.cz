---
typ:  podpůrný
manažer: administrativní odbor
---

# Zakládání spisů do spisové služby

## Úvod

* Tento dokument podrobně definuje proces zakládání spisů ve
  spisové službě.

* Odhadovaná doba na založení spisu bez založení dokumentu jsou 3 minuty.

* Po založení spisu ve spisové službě následuje
  [zakládání jednotlivých dokumentů do spisu][postup-dokumenty].

* Tento proces je podprocesem [vedení spisové služby][postup-spisovka]. Pokud není uvedeno či z
kontextu nevyplývá něco jiného, platí pro tento podproces totéž, co pro
nadřízený proces.


[postup-dokumenty](zakladani-dokumentu.md)

## Definice procesu

Účelem zakládání spisů v listinné i elektronické podobě je, abychom

* měli pohromadě související dokumenty týkající se jedné věci,
* usnadnili orientaci ve věci spisu a tedy zastupitelnost a audit,
* usnadnili pozdější vyhledání dokumentu,
* zjednodušili operace se spisem týkající se více dokumentů (např. vyřizování
  jedné věci jednou osobou, skartace spisu apod.)

## Cíle procesu

**Cílem** tohoto procesu je, aby byly všechny dokumenty v jednom spisu
ve spisové službě. Spisem rozumíme souhrn dokumentů, které postupně vznikají
při vyřizování jedné věci (např. žádosti) na naší straně a na straně toho,
s kým komunikujeme (např. úřadu).

## Typické vstupy procesu

### Potřebné informace

požadavek na založení nového spisu:

* v případě **odchozího** dokumentu potřeba zajistit si novou spisovou značku,
  abychom ji mohli napsat do textu dokumentu, nebo
* první **příchozí dokument** doručený do datové schránky, poštovní schránky, případně
  v odůvodněných případech e-mailové pošty.

[spisy]: https://github.com/pirati-byro?q=spisy

## Typické kroky během postupu

* Přijde mi požadavek na založení spisu (viz výše).

### 1. Posouzení režimu dokumentu

* Spisy se nazakládají k věcem, které stačí vyřešit po e-mailu (každý si
  archivuje své e-maily a úřední e-maily nemaže!) či u kterých není nutné
  archivovat dokumenty (např. pozvánky, letáky, informace na vědomí apod.),
  soukromých zprávách či jinak interně.
* Do spisovky se nezakládají ani spisy archivované jinde (např. smlouvy v
  registru smluv, objednávky a doklady zveřejňované u žádostí o proplacení).
* Do spisovky není nutné zakládat ani jakékoliv dokumenty, které mají velmi nízkou
  relevanci pro další fungování strany, např. děkovné dopisy občanů apod.
  Rozhodnutí a související zodpovědnost je vždy na tom, kdo dokument vyřizuje.

### 2. Založení spisu v úkolovníku

Související spis založíme v projektu toho týmu, kterého se spis týká, viz
[seznam projektů](https://redmine.pirati.cz/projects) na úkolovníku. Jde
o nový úkol, který má nastaven pole fronta na ``Spis``. Každý spis má
následující náležitosti:

* **název spisu** = název úkolu v úkolovníku – musí výstižně popisovat, oč jde,
  aby se podle něho dobře hledalo (např. „Odměny Moniky Krobové Hášové –
  žádost o informace“) a aby to bylo dobře popisné,

* **spisová značka** – má nově tvar ``ZK Pha #1234`` nebo ``RP #123``
  (zkratka týmu a číslo úkolu v redmine), starší byla ve tvaru pořadového
  čísla ``ZK Pha 12/2000`` a uváděla se v poli spisová značka, teď už toto
  pole není třeba vyplňovat (viz podrobně
  [vyhláška o spisové značce](https://www.pirati.cz/ao/pravidla/spisova_znacka)),

* **uzavřít do** = termín pro reakci – upravuje se při vložení každého dalšího
  nového dokumentu do spisu,

Na úložišti spis zakládáme až současně s vložením prvního dokumentu,
viz [zakládání jednotlivých dokumentů do spisu][postup-dokumenty].

### 3. Založení fyzické kopie do spisu

* Pokud dojde dokument v papírově podobě jako dopis do schránky nebo na poštu,
  případně pokud výjimečně posíláme dokument v papírové podobě (např. u žádosti
  firmě, která nemá datovou schránku), je třeba založit spis v papírové podobě.
* Do spisu v papírové podobě se zakládají pouze papírové dokumenty anebo
  papírové kopie elektronických dokumentů, pokud byly vytištěny (např. kvůli
  rešerši nebo účasti na soudním jednání). Podle počtu papírových dokumentů má
  spis buď podobu papírů stažených svorkou, papírů ve fólii či v [odkládací mapě][mapa].
* Spis v papírové podobě je uložen v papírové spisové službě daného týmu, typicky
  v jeho skříni.

[mapa]: https://www.sevt.cz/obchod/kancelarske-potreby/archivace-trideni/odkladaci-mapy/

### 4 Založení prvního dokumentu

Po založení spisu lze do něj vložit první dokument, viz popis pro
[založení dokumentu do spisu][postup-dokumenty].

[prehled-ss]: https://redmine.pirati.cz/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=~&v%5Bsubject%5D%5B%5D=spisov%C3%A1+slu%C5%BEba&f%5B%5D=&c%5B%5D=project&c%5B%5D=subject&c%5B%5D=assigned_to&group_by=&t%5B%5D=

## Typický výstup procesu

* Založený spis v úkolovníku

## Rizika

### Nezaložení spisu

* Riziko je středně pravděpodobné a může být vážné, protože spis nebude dohledatelný v okamžiku, kdy ho potřeba.
* Ke zmírnění rizika slouží jednotný a centrální systém zakládání spisů v rámci daného týmu a dobrý výcvik referentů spisové služby.

### Duplicita spisu

* Riziko je vysoce pravděpodobné a je málo závažné, neboť typicky může vést při nejhorším k přehlédnutí určitých dokumentů při předchozím vyřizování věci a při změně osoby věc vyřizující.
* Ke zmírnění rizika je potřeba, aby v odchozích dokumentech byla dostatečně
výrazná výzva pro druhou stranu, aby uvedla naši spisovou značku. Dále je potřeba,
aby referent text důkladně přečel, a aby se v případě zjištění duplicit spisy slučovaly.

### Ztráta papírové podoby spisu

* Riziko je středně pravděpodobné a může být velmi závažné, pokud jsou ve spise
  založeny jedinečné dokumenty.
* Ke zmírnění rizika je snížen počet osob lidí přistupujících do spisové služby.

## Související

* [Vedení spisové služby][postup-spisovka]
* [Zakládání dokumentů][postup-dokumenty]
* [Zakládání spisu][postup-spisy]
* Přiřazení spisové značky

[postup-spisovka]:  README.md
[postup-spisy]: zakladani-spisu.md
[postup-dokumenty]:  zakladani-dokumentu.md
