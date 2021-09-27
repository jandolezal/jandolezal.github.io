---
title: "Python rulez!"
date: 2021-09-26
description: "Tohle měl být původně jeden odstavec do klubu Junior Guru. Chtěl jsem psát o tom, jak jsem se tento týden seznamoval s API od sluzby Datawrapper."
socialImage: "map.png"
tags: ["programovani", "data"]
---

Tohle měl být původně jeden odstavec do klubu [Junior Guru](https://junior.guru/club/). Chtěl jsem psát o tom, jak jsem se tento týden [seznamoval](https://github.com/jandolezal/organic) s API od služby [Datawrapper](https://www.datawrapper.de/). Jen jsem nevěděl, jestli má jít spíš do kanálu #motivace, #til (*Today I Learned*) nebo #python. Nakonec to píšu tady, abych si ještě navíc vyzkoušel vložení HTML od Datawrapper na statický web vytvořený s pomocí Hugo (a měl tu nějaký ten obsah).

## Python

Pro Python by mluvilo, jaký je to skvělý nástroj. Před pár dny jsem zjistil, že Datawrapper, který mi přijde jako výborná služba pro tvorbu interaktivních vizualizací, má [API pro vývojáře](https://developer.datawrapper.de/docs/getting-started). To si musím vyzkoušet!

O API jsem se sice dozvěděl z [blogu](https://blog.datawrapper.de/datawrapper-python-package/), který představuje Python balíček [datawrapper](https://datawrapper.readthedocs.io/en/latest/), ale řekl jsem si, že pro začátek to zkusím s  pomocí [Requests](https://2.python-requests.org/en/master/), ať jdu blíže ke zdroji. Moje žena mi zrovna ukazovala [statistiky](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Organic_farming_statistics) Eurostatu k ekologickému zemědělství, tak jsem jako cvičná data použil rozlohu ekologických farem v Evropě a zpracoval je pomocí Pandas a Jupyter notebook. Výsledné CSV jsem poslal do Datawrapper API, stejně jako pár instrukcí, jak se mají data zobrazit na mapě. Výsledkem je jednoduchá [vizualizace](https://www.datawrapper.de/_/kBxZS/).

{{< datawrapper id="kBxZS" title="Organic farms in Europe" >}}

Překvapil mě docela vysoký 15% podíl rozlohy ekologických farem v Česku, za který jsou zodpovědné ale hlavně trvalé travní porosty.

## Motivace

Kanál #motivace by taky dával smysl. Díky podobným zkušenostem mě programování baví. Trošku víc porozumět tomu, jak fungují webové technologie a jak pracovat s daty.

Pro někoho je to možná banalita, pro jeden graf rozhodně *overkill*, ale mě pořád přijde skvělý si vyzkoušet, že můžu ke stejnému výsledku – interaktivnímu grafu – dojít dvěma cestami: přes grafické rozhraní nebo s pomocí Pythonu a knihoven [Pandas](https://pandas.pydata.org/) a Requests.

Mohl jsem si stáhnout tabulky z Eurostatu, upravit je ručně v Google Tabulkách nebo Excelu a mapu naklikat přímo ve webové aplikaci Datawrapper. Přesto si myslím (a doufám), že o ztracený čas nejde. Zas o malinko víc toho vím o REST APIs, Hugo a využívání [shortcodes](https://gohugo.io/templates/shortcode-templates/). Datawrapper a automatizace podobných věcí se může hodit i v současný práci, kde často pracuji se statistikami, a přemýšlím, jak je komunikovat dál. Užitečná bude dokumentace přípravy grafu a automatizace tvorby většího počtu vizualizací.

## TIL

#til by dávalo smysl taky, jenže bych trošku kecal. Věnoval jsem se tomu víc dní, jak jen to šlo. Spíš by to bylo něco jako TWIL, *this week I learned*.
