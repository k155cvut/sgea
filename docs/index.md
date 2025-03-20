
# Stavební geodézie A &nbsp;–&nbsp; ČÁST GIS {: .page_title}

Předmět vás seznámí se základy tzv. __geografických informačních systémů__ (GIS). GIS je soubor nástrojů sloužících ke __sběru__, __správě__, __analýze__ a __vizualizaci__ geografických dat. Umožňuje efektivně pracovat s prostorovými informacemi, což zahrnuje __mapy__, __satelitní snímky__, __adresy__, __topografické údaje__ a mnoho dalšího. Dokáže provádět složité analýzy, identifikovat vzory, a tím __lépe porozumět geografickým jevům a vztahům__.

GIS má široké uplatnění, od __:fontawesome-solid-tree-city: městského plánování__{.underlined}, přes __:fontawesome-solid-hands-holding-circle: správu přírodních zdrojů__{.underlined} až po __:fontawesome-solid-triangle-exclamation: krizový management__{.underlined}. Je nepostradatelným nástrojem pro __efektivní rozhodování a řízení__ v různých odvětvích a pomáhá lépe __pochopit složité geografické souvislosti__.

V rámci předmětu __Stavební geodézie A__ budete mít ve dvou přednáškách a dvou cvičeních možnost nahlédnout do světa GIS z pohledu architekta. Dozvíte se, proč by se vám mohla geoprostorová data hodit a jak je získávat pro svůj projekt. Zatímco přednášky vás provedou základní teorií, cvičení se věnují __praktickému ovládání GIS software__ – zejména porozumění práce s daty a provádění jednoduchých analýz. Během výuky je používán webový systém __:simple-esri: ArcGIS Online__{: style="white-space: nowrap;"}.

Pokud by vás geomatika (obor zabývající se geografickými informačními systémy) zaujala a chtěli byste se dozvědět více, lze si zapsat navazující nepovinný předmět [__ArcGIS (155YGIS)__](https://kos.cvut.cz/course-syllabus/155YGIS/ "stránka předmětu v KOS"){.color_def .underlined_dotted .external_link_icon target="_blank"}, který se problematice věnuje hlouběji.

<h2 style="text-align:center;">Naučíte se</h2>
<!-- styl je zde pridany HTML tagem (ne pomoci '##'), aby se text neobjevil v tabulce obsahu vlevo na strance -->

<div class="grid cards grid_icon_info smaller_padding" markdown> <!-- specificky format gridu (trida "grid_icon_info") na miru uvodni strance predmetu -->

-   :material-database-import-outline:{ .xl }

    __získávat geoprostorová data__ vhodná pro svůj projekt

-   :octicons-gear-16:{ .xl }

    __základní zpracování__ a __analýzu__ geoprostorových dat

-   :material-brush-variant:{ .xl }

    základy __mapové symbologie__

-   :octicons-share-16:{ .xl }

    __sdílet__ vlastní data (mapy) prostřednictvím webu

</div>
<!--
<div class="gallery_container" markdown>
![](./assets/index/01.jpg){: .no-filter }
![](./assets/index/02.jpg){: .no-filter }
![](./assets/index/03.jpg){: .no-filter }
![](./assets/index/04.jpg){: .no-filter }
![](./assets/index/05.jpg){: .no-filter }
![](./assets/index/06.jpg){: .no-filter }
![](./assets/index/07.jpg){: .no-filter }
![](./assets/index/08.jpg){: .no-filter }
![](./assets/index/09.jpg){: .no-filter }
![](./assets/index/10.jpg){: .no-filter }
![](./assets/index/11.jpg){: .no-filter }
![](./assets/index/12.jpg){: .no-filter }
</div>
-->
<!-- ## Doporučená literatura

1. Kolář, J.: Geografické informační systémy 10. Vydavatelství ČVUT, Praha 1998.
2. Rapant, P. (2006): Geoinformatika a geoinformační technologie. VŠB-TU Ostrava, 500 str. ISBN 80-248-1264-9.
3. Břehovský, M., Jedlička, K. (2005): Přednáškové texty pro Úvod do GIS. ZČU Plzeň, 116 s.
4. Hrubý M.: Geografické Informační Systémy (GIS) - Studijní opora. VÚT v Brně, 91 str.
5. Tuček J.: Geografické informační systémy, Praha Computer Press, 1998. -->

---

## Přednášky :material-lectern:{style="clip-path: circle(); color:var(--md-default-bg-color); background-color:var(--md-default-fg-color); padding:6px; font-size:120%; vertical-align:-.1em"} {: style="margin-bottom:0;"}

účast doporučená
{: style="opacity:50%;margin-top:0;"}

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/03-edit_export@0.5x-1.jpg){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"}
__prof. Ing. Jiří Cajthaml, Ph.D. [:fontawesome-solid-square-envelope:](mailto:jiri.cajthaml@fsv.cvut.cz "jiri.cajthaml@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__{style="padding-right:1rem;"}
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/iconmonstr-user-male-thin.png){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"} __Ing. Tomáš Janata, Ph.D. [:fontawesome-solid-square-envelope:](mailto:tomas.janata@fsv.cvut.cz "tomas.janata@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

4. __GIS__: základní pojmy GIS, vektorová a rastrová data, topologie, atributová data, webové mapové služby, zdroje dat (OSM, RÚIAN, WMS), geoprostorové analýzy, 3D GIS, cloudové řešení ArcGIS Online. [:material-file-pdf-box:](# "stažení prezentace"){style="color:var(--md-default-fg-color);"}
5. __Kartografie__: základní pojmy v kartografii, znakový klíč a jazyk mapy, polohopis, výškopis, popis, kartografická generalizace, státní mapové dílo středního měřítka (civilní i vojenské), tematická kartografie, webová kartografie. [:material-file-pdf-box:](# "stažení prezentace"){style="color:var(--md-default-fg-color);"}

Ostatní přednášky zajišťuje Katedra speciální geodézie (K154).

---

## Cvičení :material-human-male-board:{style="clip-path: circle(); color:var(--md-default-bg-color); background-color:var(--md-default-fg-color); padding:6px; font-size:120%; vertical-align:-.1em"} {: style="margin-bottom:0;"}

účast povinná (s možnými náhradami)
{: style="opacity:50%;margin-top:0;"}

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/iconmonstr-user-male-thin.png){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"}
__Ing. Tomáš Janata, Ph.D. [:fontawesome-solid-square-envelope:](mailto:tomas.janata@fsv.cvut.cz "tomas.janata@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__{style="padding-right:1rem;"}
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/iconmonstr-user-male-thin.png){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"}
__Ing. Jaroslav Šedina, Ph.D. [:fontawesome-solid-square-envelope:](mailto:jaroslav.sedina@fsv.cvut.cz "jaroslav.sedina@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__{style="padding-right:1rem;"}
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/03-edit_export@0.75x-4.jpg){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"}
__Ing. František Mužík [:fontawesome-solid-square-envelope:](mailto:frantisek.muzik@fsv.cvut.cz "frantisek.muzik@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__{style="padding-right:1rem;"}
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/03-edit_export@0.5x-16.jpg){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"}
__Mgr. Petra Justová, Ph.D. [:fontawesome-solid-square-envelope:](mailto:petra.justova@fsv.cvut.cz "petra.justova@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__{style="padding-right:1rem;"}
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

![](https://geomatics.fsv.cvut.cz/wp-content/uploads/2022/01/03-edit_export@0.3x.jpg){: .off-glb .no-filter style="height: 1.5em; vertical-align: -.4em; clip-path: circle();"}
__Ing. Vojtěch Cehák [:fontawesome-solid-square-envelope:](mailto:vojtech.cehak@fsv.cvut.cz "vojtech.cehak@fsv.cvut.cz"){style="color:var(--md-default-fg-color);"}__{style="padding-right:1rem;"}
{style="display:inline; white-space: nowrap; line-height:2;"}
<!-- kvuli zobrazovani na mobilu -->

4. __Práce s webovými mapovými službami:__ Připojením webových vrstev z různých zdrojů do jedné mapy získáte základní informace o zadané lokalitě (např. příslušnost ke katastrálnímu území či obci, nejbližší pobočka pošty či geologické podloží). V rámci cvičení jsou vytvořeny dvě tematické mapové kompozice (typ krajinného pokryvu v okolí zadané lokality a nejbližší chráněné území). Výstupem cvičení je technická zpráva s grafickými přílohami.

5. __Tvorba webové mapy, export dat:__ Využití základních funkcí prostorové analýzy (překryv a sloučení vrstev) a vybraných metod tematické kartografie (aplikace barevných stupnic pro zobrazení kvalitativních dat či aplikace metody pro zobrazení intenzity jevu). Výstupem cvičení jsou dvě tematické webové mapy v prostředí ArcGIS Online.

Ostatní cvičení zajišťuje Katedra speciální geodézie (K154).

---

## Harmonogram :material-calendar:{style="clip-path: circle(); color:var(--md-default-bg-color); background-color:var(--md-default-fg-color); padding:6px; font-size:120%; vertical-align:-.1em"} {: style="margin-bottom:0;"}

[![](./assets/index/schedule_light.svg#only-light){.off-glb .no-filter}](https://kos.cvut.cz/schedule/course/154SGEA/semester/B242){target="_blank"}
[![](./assets/index/schedule_dark.svg#only-dark){.off-glb .no-filter}](https://kos.cvut.cz/schedule/course/154SGEA/semester/B242){target="_blank"}

---

<figure markdown>
![](./assets/Harmonogram_3-4_2025.png){ width="100%" }
    <figcaption>Přiřazení učeben a učitelů k paralelkám</figcaption>
</figure>

<hr>

[Stránka předmětu v :custom-kos-logo-img-BW:{.middle style="margin-left:3px;"} :custom-kos-logo-BW:{.xl .middle}](https://kos.cvut.cz/course-syllabus/154SGEA/){ .md-button .md-button--primary target="_blank"}
{align=center}

<br>
