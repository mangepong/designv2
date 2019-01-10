---
---
Rapport för laddningstid kmom05
=========================

I denna uppgiften ska man välja ut tre stycken hemsidor som man ska göra en undersökning på. Undersökningen går ut
på att mäta laddningstider på hemsidorna och jämföra och se om man kan förbättra tiderna på dem.


Urval
-----------------------
Jag valde att fortsätta att undersöka dem hemsidor som jag använde i min förra rapport om färgpalleter dvs Inet, Komplett och Dustin Home.
Tyckte att det kunde vara spännande att fortsätta på samma spår som innan och ta reda på mer om dessa sidor.

**Webbplatserna som jag har valt:**

* <a href="https://www.inet.se/">Inet</a>
* <a href="https://www.komplett.se/">Komplett</a>
* <a href="https://www.dustinhome.se/">Dustin Home</a>

Metod
-----------------------

När jag utförde undersökningen så använde jag mig utav flera olika verktyg som <a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed Insight</a>, Google Chromes egna <a href="https://developers.google.com/web/tools/chrome-devtools/">Devtool</a> som är inbyggd i webbläsaren, det sista verktyget jag använde mig utav va <a href="https://gyazo.com/captures">Gyazo</a> som är ett gratis program som man kan ladda ner för att ta "screenshots" på datorn. Jag använde även Googles egna och gratis online verktyg <a href="https://docs.google.com/spreadsheets/u/0/">Google Kalkylark</a> för att spara all data som jag fick fram.

<a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed Insight</a> är ett webbbaserat program som google har skapat för att analysera webbplaster på datorer och mobila enheter. Den ger sedan ett betyg på både mobil och dator versionen och sedan så ger den feedback på vad man kan göra för att förbättra webbplatsen.

Det andra verktyget <a href="https://developers.google.com/web/tools/chrome-devtools/">Devtool</a> kan man använda för att övervaka nätverks aktiviteten på webbplasten och ser vad som händer medans man laddar in sidan. Man kan se hur många requests som sker och t.ex hur lång tid det tar för DOM att ladda in.

<a href="https://gyazo.com/captures">Gyazo</a> som jag har använt tidigare är ett gratis program som man kan ladda ner för att ta screenshot på datorn och sen spara på datorn för att använda. Det fungerar så att man startar programmet och drar musen över det du vill spara och sedan släppa musklicket så laddas din bild direkt upp på ditt konto på <a href="https://gyazo.com/captures">Gyazo</a> som du sedan alltid kan komma åt.

Det sista vertyget jag använde mig utav var <a href="https://docs.google.com/spreadsheets/u/0/">Google Kalkylark</a> som är vad det låter som, ett kalkylark som sparas automatiskt online så fort du skriver nått. Det fungerar och liknar Microsoft Office egna version av kalkylark.

Resultat
-----------------------

<a href="https://docs.google.com/spreadsheets/d/1M6DgTiNc_s4Ov0kHsHDER0sznoUJzPof7hUHa9PCNGI/edit#gid=0">Här finns kalkylarket för alla sidorna och deras analyser.</a>

#### Inet

[FIGURE src="image/inet2.jpg?w=1000"]

Jag blev faktiskt väldigt besviken på Inet denna gången. Har alltid tyckt om deras sida och hur de har byggt upp den. Men i undersökningen så får jag se att deras hastighet på mobilen var väldigt dåligt på alla tre olika sidorna på Inet. På mobilen låg det mellan 30-40 utav 100 poäng och det är väldigt dåligt för att vara en så pass stor sida. Dator sidan på andra sidan var mycket bättre och visade betyg på mellan 90-96 vilket är ett stort hopp ifrån 30-40. Om Inet hade minskat belastningen på modertrådarna så hade man kunnat spara nästa 5 sekunder på mobil versionen samt att man hade kunnat skjuta upp inläsningen av olika saker som inte används.

#### Komplett

[FIGURE src="image/komplett2.jpg?w=1000"]

Lik Inet så har inte komplett levererat som jag hade hoppats på gällande betyget på PageSpeed Insight. På deras startsida så lyckades dem få en full pott på PageSpeed med 100 poäng och med ett bättre betyg än Inet på mobilen med 52 poäng. Inget som är jättebra med det är ett mycket bättre betyg än Inet. Komplett lyckas hålla sig inom 95-100 på dator versionen och 50 på mobil versionen på de flesta sidor men de sjönk ner ganska så markant på deras "guide" sida. Där gick dator versionen ner till 70 och mobilen sjönk ner till Inets prestanda på 30. Kompletts störta hopp om att snabba upp sidan är att aktivera en textkomprimering som skulle spara nästan 2 sekunder.

#### Dustin Home

[FIGURE src="image/dustin2.jpg?w=1000"]

Dustin Home liksom Inet lyckas hålla en stabil hastighet utöver hela webbplasten med 95-97 på datorn och 44-48 på mobilen. Inga höjdar betyg på mobilen men de lyckas hålla det stadigt. Detta är ändå ett betydligt bättre betyg än vad Inet fick men ändå inte riktigt på Kompletts nivå med mobil versionen. Hade dem liksom komplett aktiverat textkomprimering så hade de kunnat spara 3 sekunder på bara det. Det som Dustin gör bättre än dem andra är att hålla sig på ett bra betyg på alla deras sidor som jag testade och inte variera mycket med betyget.

Analys
-----------------------

Dem tre sidorna som jag har analyserat är gjorda för samma sak, dvs dem ska sälja sina produkter. Både Komplett och Dustin har samma problem med att inte ha aktiverat textkomprimering som skulle ha förbättrat deras sidor ganska så markant enligt PageSpeed iallafall. Inet tycker jag faller tillbaka en hel del då deras mobil version är så pass dålig att den inte kan jämföras med de andras versioner. Både Komplett och Dustin hade mellan 10-20 poäng högre än Inet på mobilen. Så jag skulle vilja påstå att Dustin är den bättre sidan generellt med allt. Mellan Komplett och Dustin är det ganska jämnt men eftersom Dustin lyckas hålla sig vid samma siffror och att det är ett bra betyg så kommer dem lite högre upp än Komplett. Hade inte Kompletts dator och mobil version sjunkt så pass mycket på en sida så hade dem kanske tagit första platsen. Något som dock Dustin också gör väldigt bra om man jämför med de andra så är det att Dustin laddningstid är mellan 1-3 sekunder vilket jag tycker är snabbt om man kollar på de andra webbplatser som har ibland uppåt 10+ sekunder. I mina ögon så är en snabb hemsida under 5 sekunder och allt över det så blir det en långsam hemsida. Alla webbplatserna generellt är bra gjorda och bekväma att använda så det är lite synd att Komplett och Inet va så pass dåliga som de va.

Referenser
-----------------------


* <a href="https://www.inet.se/">Inet</a>
* <a href="https://www.komplett.se/">Komplett</a>
* <a href="https://www.dustinhome.se/">Dustin Home</a>
* <a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed Insight</a>

Övrigt
-----------------------

__Skriven av: Emil Magnusson__