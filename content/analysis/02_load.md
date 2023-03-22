---
Title: Laddningstid
Description: Analys av laddningstid
Template: index
---

Analys av tre olika webbsidors laddningstid
============================================

Rapportens syfte är att undersöka skillnaden på laddningstid och

dataförbrukning hos tre olika webbplatser samt analysera vad som kan förbättras.

Urval
--------

De tre webbplatser som valts är:

1. [Ikea](https://www.ikea.com/se/sv/)
2. [Jysk](https://jysk.se/)
3. [Mio](https://www.mio.se/)

Anledningen till detta urvalet är att möjligtvis få insikt i hur tre 

olika hemsidor inom samma branch och med liknande målgrupp kan variera 

sig i laddningshastighet och dataförbrukning samt om det finns en 

gemensam faktor ifall sådana brister uppkommer.

Metod
-------

Tre hemsidor väljs ut och mäts med Google Pagespeed där både mobile och desktop 

undersöks. Utöver detta undersöks sidans laddningstid, sidans totala storlek och

antalet resurser som laddas med hjälp av Devtools. Värdena noterades efter 30s då

sidorna skickade requests en längre period. försöket upprepas tre gånger per hemsida 

för att få ut ett genosnittligt värde.

Resultat
----------
[Länk till Rådata](https://docs.google.com/spreadsheets/d/1ejk4hpvGB7ETBcVutnVvA9qFqtTVmnUu_IaXWid90uI/edit?usp=sharing)

<iframe title="Raw data for the analysis" class="spreadsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRfHOI6PdfUQ9T_vgmcbpa3YfOb51n0TmbERGK5ochS54CLDTHOdoOosjsaH1hwK4l5dzfJaaLl2byA/pubhtml?widget=true&amp;headers=false"></iframe>

Ikea
------

![En bild på Ikeas hemsida](../image/IKEASmall.webp?w=600&h=600 "ikea.se"){.limit-size}

<table style="border-spacing: 0.5em; border-collapse: separate">
    <thead>
        <tr>
            <th>IKEA</th>
            <th style="text-align: right;">Prestanda</th>
            <th style="text-align: right;">Tillgänglighet</th>
            <th style="text-align: right;">Bästa Metoder</th>
            <th style="text-align: right;">SEO</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="td-analysis">Desktop</td>
            <td class="td-analysis">76</td>
            <td class="td-analysis">76</td>
            <td class="td-analysis">92</td>
            <td class="td-analysis">92</td>
        </tr>
        <tr>
            <td class="td-analysis">Mobil</td>
            <td class="td-analysis">22</td>
            <td class="td-analysis">76</td>
            <td class="td-analysis">92</td>
            <td class="td-analysis">93</td>
        </tr>
    </tbody>
</table>

Jysk
------

![En bild på Mios hemsida](../image/JYSKSmall.webp?w=600&h=600 "jysk.se"){.limit-size}

<table style="border-spacing: 0.5em; border-collapse: separate">
    <thead>
        <tr>
            <th>JYSK</th>
            <th style="text-align: right;">Prestanda</th>
            <th style="text-align: right;">Tillgänglighet</th>
            <th style="text-align: right;">Bästa Metoder</th>
            <th style="text-align: right;">SEO</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="td-analysis">Desktop</td>
            <td class="td-analysis">79</td>
            <td class="td-analysis">91</td>
            <td class="td-analysis">100</td>
            <td class="td-analysis">83</td>
        </tr>
        <tr>
            <td class="td-analysis">Mobil</td>
            <td class="td-analysis">30</td>
            <td class="td-analysis">85</td>
            <td class="td-analysis">100</td>
            <td class="td-analysis">86</td>
        </tr>
    </tbody>
</table>

Mio
------

![En bild på Mios hemsida](../image/MIOSmall.webp?w=600&h=600 "mio.se"){.limit-size}

<table style="border-spacing: 0.5em; border-collapse: separate">
    <thead>
        <tr>
            <th>MIO</th>
            <th style="text-align: right;">Prestanda</th>
            <th style="text-align: right;">Tillgänglighet</th>
            <th style="text-align: right;">Bästa Metoder</th>
            <th style="text-align: right;">SEO</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="td-analysis">Desktop</td>
            <td class="td-analysis">99</td>
            <td class="td-analysis">70</td>
            <td class="td-analysis">100</td>
            <td class="td-analysis">92</td>
        </tr>
        <tr>
            <td class="td-analysis">Mobil</td>
            <td class="td-analysis">66</td>
            <td class="td-analysis">70</td>
            <td class="td-analysis">100</td>
            <td class="td-analysis">93</td>
        </tr>
    </tbody>
</table>

Bäst genomsnittligt laddningstid:
----------------------------------
1. Mio, 1.2s
2. Jysk, 1.5s
3. Ikea, 2.9s

Bäst presterande genomsnittligt överförd data:
------------------------------------------------

1. Mio, 987kB
2. Jysk, 2.9MB
3. Ikea, 3.6MB

Bäst presterande desktop-hemsida med kombinerat medelvärde av Prestanda, Tillgänglighet, Bästa metoder och SEO:
--------------------------------------

1. Mio, 90.25
2. Jysk, 88.25
3. Ikea, 84

Bäst presterande mobil-hemsida med kombinerat medelvärde av Prestanda, Tillgänglighet, Bästa metoder och SEO:
--------------------------------------

1. Mio, 82.25
2. Jysk, 75.5
3. Ikea, 70.75

Analys
-------

Utifrån resultaten kan det noteras att alla tre hemsidor presterar för det mesta relativt bra på SEO,

bästa metoder och tillgänglighet till både desktop och mobil. Den största bristen är väldigt

tydlig vid prestandan vid mobila användning hos nästan alla hemsidorna där det kan noteras en markant

nedgång i prestanda. Enligt PageSpeed Insights kan en reducering av oanvända JavaScripts ge en förbättring

i dataförbrukningen samt spara över 3s på varje hemsida. På den sämst presterande hemsidan, Ikea, är 

det användningen av icke-responsiva bilder och för stora bilder för de mobila enheterna som är orsaken

till dubbelt så lång laddningstid jämfört med Jysk och Mio.

En möjlig förklaring till varför Ikea är dåligt anpassad till mobila enheter är för att de har en mobilapp

som är anpassad för detta behovet. Det kan därav bedömts onödigt att anpassa bl.a. hemsidans bilder för att

möjligtvis spara resurser.

Resultaten i undersökningen ger ett tydligt svar att Mio har bäst prestanda och dataförbrukning jämfört med 

Jysk som har näst bäst betyg och Ikea som är sist.

Personligen så tycker jag att en laddningstid under 3-3.5 sekunder är godkänt vilket alla hemsidor klarade

förutom Ikea i ett av försöken. Vid generell användning av alla tre hemsidorna upplevs dock inte

laddningshastigheten som ett besvär på någon av sidorna, men det är ändå en tydlig skillnad i hur snabbt 

Mio laddar jämfört med Ikea. 

Referenser
-----------

[PageSpeed Insights](https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect)

[Ikea](https://www.ikea.com/se/sv/)

[Jysk](https://jysk.se/)

[Mio](https://www.mio.se/)

Övrigt
--------

Författare: Jonathan Bengtsson Linnér