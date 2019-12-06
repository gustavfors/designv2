---
---
Laddningstider
=======================

Uppgiften syftar till att belysa att webbplatser har olika lång laddningstid samt att utvärdera hur laddningstid påverkas av webbplatsens uppbyggnad. Vidare syftar uppgiften även till att undersöka hur laddningstiden på webbplatser kan förbättras.

Urval
-----------------------

För uppgiften har tre kommuners webbplatser valts att undersökas. Urvalet är baserat på gruppmedlemmarnas hem-kommuner samt den som de båda nu bor i. De valda webbplatserna är: Helsingborgs kommun[^1] , Luleå kommun[^2]  och Karlskrona kommun[^3] . Uppgiften är baserat på att tre undersidor på respektive webbplats undersöks. För att resultaten från undersökningen ska kunna jämföras med varandra har liknande undersidor valts ut. De tre sidorna som valts ut är: index-sidan, kommun och politik samt sidan omsorg och stöd.

Metod
-----------------------

För att utföra undersökningen användes främst två verktyg. Googles analyseringsverktyg Page Insight[^4] för att ge en överblick av hur de olika webbsidorna presterade på mobila enheter såväl som desktop enheter, verktyget gav även förbättringsförslag för hur prestandan kunde förbättras. Även Google dev tools[^5] användes för att mäta sidans laddningshastighet, sidans storlek samt hur många resurser som laddades in. För att presentera och sammanställa resultatet användes verktyget Google sheets.

Resultat
-----------------------

Resultatet av undersökningen presenteras i ett [Google Kalkylark.](https://docs.google.com/spreadsheets/d/1yxLLUJDSbl-XuTF_kHJq95kEtqYZc-g0nUuPAmotJfY/edit?usp=sharing) Här kan även länkar till de tre undesidorna som undersökts hittas.

Nedan följer en sammanfattning av sidorna som undersöktes samt förbättringsförslag för hur sidorna kan prestera bättre. Rekommendationerna är baserade på data från verktyget Page Insight.[^4]

#### Sammanfattning av resultat

Enligt Googles analyseringsverktyg Page Insight fick samtliga av de valda webbplatserna ett okej betyg för desktop versionerna av deras hemsidor. Luleå kommun var den webbplats som presterade bäst, samtliga sidor fick 95 av 100 i betyg vilket klassas som ett bra betyg. Karlskrona kommuns sidor presterade något sämre, i spannet 86-94 vilket klassas som ett godkänt betyg. Sämst presterade Helsingborgs kommun som hamnar i spannet 85- 91.

I testerna av mobila versionerna presterade dock webbplatserna sämre. Även här presterade Luleå bäst med 61 av 100 på samtliga sidor. I rangordningen kommer sedan Karlskrona som presterade i spannet 49  - 51. Slutligen hamnade Helsingborg i spannet 26 - 45.

I devtools testen som mätte laddningstid, antalet resurser som laddas in samt sidans storlek var resultaten varierande. Luleå kommuns webbplats presterade även här bäst med lägst laddningstid, följt av Karlskrona och slutligen Helsingborg kommun. Helsingborg har dock dubbelt så många resurser och därmed även dubbelt så stor storlek än Luleå.

### Helsingborg

![Helsingborg kommun](img/helsingborgkommun.jpg)

<table>
<thead>
<tr>
  <th>Sida</th>
  <th>PI-Mobile</th>
  <th>PI-Desktop</th>
  <th>Laddningstid</th>
  <th>Resurser</th>
  <th>Storlek</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Index</td>
  <td>26</td>
  <td>91</td>
  <td>4.12 s</td>
  <td>84</td>
  <td>11.4 MB</td>
<tr>
  <td>Kommun-politik</td>
  <td>41</td>
  <td>86</td>
  <td>4.11 s</td>
  <td>92</td>
  <td>7.1 MB</td>
</tr>
<tr>
  <td>omsorg-stod</td>
  <td>45</td>
  <td>85</td>
  <td>3.98 s</td>
  <td>94</td>
  <td>7 MB</td>
</tr>
</tbody>
</table>


##### Förbättringsmöjligheter

Webbplatsen kan förbättras genom användning av videoformat för animationer istället för GIF, användning av modernare bildformat och bilder i rätt storlek samt skjuta upp inläsning av bilder som inte visas på skärmen.

### Luleå

![Luleå kommun](img/luleakommun.png)

<table>
<thead>
<tr>
  <th>Sida</th>
  <th>PI-Mobile</th>
  <th>PI-Desktop</th>
  <th>Laddningstid</th>
  <th>Resurser</th>
  <th>Storlek</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Index</td>
  <td>61</td>
  <td>95</td>
  <td>1.68 s</td>
  <td>37</td>
  <td>3.4 MB</td>
</tr>
<tr>
  <td>Kommun-politik</td>
  <td>61</td>
  <td>95</td>
  <td>1.46 s</td>
  <td>33</td>
  <td>3.2 MB</td>
</tr>
<tr>
  <td>omsorg-stod</td>
  <td>61</td>
  <td>95</td>
  <td>1.65 s</td>
  <td>33</td>
  <td>3.2 MB</td>
</tr>
</tbody>
</table>

##### Förbättringsmöjligheter

Webbplatsen kan förbättras genom att minifiera JavaScript filer, använda bilder i rätt storlek, ta bort oanvänd CSS, använda  modernare bildformat samt genom att ta bort resurser som blockerar sidredigering.


### Karlskrona

![Karlskrona kommun](img/karlskronakommun.jpg)

<table>
<thead>
<tr>
  <th>Sida</th>
  <th>PI-Mobile</th>
  <th>PI-Desktop</th>
  <th>Laddningstid</th>
  <th>Resurser</th>
  <th>Storlek</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Index</td>
  <td>49</td>
  <td>86</td>
  <td>2.76&nbsp;s</td>
  <td>52</td>
  <td>4.5&nbsp;MB</td>
</tr>
<tr>
  <td>Kommun-politik</td>
  <td>50</td>
  <td>90</td>
  <td>2.72&nbsp;s</td>
  <td>46</td>
  <td>3.4&nbsp;MB</td>
</tr>
<tr>
  <td>omsorg-stod</td>
  <td>51</td>
  <td>94</td>
  <td>2.76&nbsp;s</td>
  <td>47</td>
  <td>3.4&nbsp;MB</td>
</tr>
</tbody>
</table>

##### Förbättringsmöjligheter
Webbplatsen kan förbättras genom att skjuta upp inläsning av bilder som inte visas på skärmen. Användning av modernare bildformat samt borttagning av oanvänd CSS kan också bidra till att webbplatsen presterar bättre.





Analys
-----------------------

Samtliga webbsidor som undersöktes presterade bra i desktop testet och relativt dåligt i mobil testet enligt page insight. Detta är något som bör åtgärdas då det redan nu är fler som besöker webbplatser via mobilen än desktopen och trenden fortsätter att öka. Enligt statisk från Statista.com[^6] stod mobiler för över 50% av webtraffiken år 2017 och år 2018 var siffran 52.2%.

En anledning till varför vi tror att webbplatserna presterar så dåligt i mobil testerna kan vara för att kan ha utvecklats för ett antal år sedan. Då den mobil trenden är relativt ny kan det helt enkelt vara så att de inte var värt att designa utifrån dessa enheter när webbplatserna sattes i bruk och inga stora uppdatering skett sedan dess.

Baserat på resultatet rangordnas Luleå kommun som etta, då sidan presterat bäst i alla de utförda testerna. Tvåa kommer Karlskrona kommun och slutligen Helsingborgs kommun.
Laddningstiderna skilde mycket, där de större webbplatserna med fler resurser hade en längre laddningstid än de mindre. Detta är förväntat då mängden data som användaren behöver hämta hem är större.  

Det mest vanligt förekommande förbättrings åtgärderna för webbplatserna verkar relatera till bildhantering och CSS. De åtgärder som kan vidtas är användning av så kallad lazy loading där inläsningen av bilder som inte visas på skärmen skjuts upp, bildkomprimering, användning av modernare filformat för bilder exempelvis PEG 2000, JPEG XR och WebP över PNG och JPEG samt borttagning av oanvänd CSS kod.


Vi uppfattar personligen att gränsen för om en sida är snabb alternativt långsam går vid två sekunder. Utifrån denna parametern är det endast Luleå kommun av de undersökta sidorna som klassas som snabb.


Referenser
-----------------------

[Helsingborg kommun](https://helsingborg.se)

[Luleå kommun](https://www.lulea.se)

[Karlskrona kommun](https://www.karlskrona.se)

[Googel page insight](https://developers.google.com/speed/pagespeed/insights/)

[Googel page devtools](https://developers.google.com/web/tools/chrome-devtools)

[Statista.com](https://www.statista.com/statistics/241462/global-mobile-phone-website-traffic-share/)


Övrigt
-----------------------

Rapport av Gustav Fors [(Me-sida)](http://www.student.bth.se/~gufo19/dbwebb-kurser/design/me/redovisa/htdocs/) och Emma Öhrwall [(Me-sida)](http://www.student.bth.se/~emoh19/dbwebb-kurser/design/me/redovisa/htdocs/)


[^1]: [Helsingborg kommun](https://helsingborg.se)

[^2]: [Luleå kommun](https://www.lulea.se)

[^3]: [Karlskrona kommun](https://www.karlskrona.se)

[^4]: [Googel page insight](https://developers.google.com/speed/pagespeed/insights/)

[^5]: [Googel page devtools](https://developers.google.com/web/tools/chrome-devtools)

[^6]: [Statista.com](https://www.statista.com/statistics/241462/global-mobile-phone-website-traffic-share/)
