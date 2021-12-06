---
Title: 02 Load
Description: Load.
Template: analysis
---

En analys om laddningstid på olika hemsidor:
=======================

Analysen baseras på ett urval av hemsidor där 
deras laddningstid, så kallad page speed, granskas och dokumenteras.

Urval
-----------------------

Jag valde att behålla de hemsidor som jag använde mig av i färganalysen för att fortsätta analysen av dem och se hur väl de uppfyller de olika kriterierna här.

Inför färganalysen så funderade jag på om jag skulle välja tre hemsidor inom samma bransch eller om valet bara skulle ske på "måfå" och jag valde tillslut tre olika hemsidor mer utifrån mina egna preferenser, det är hemsidor som jag känner till och själv brukar vara inne på.

Jag har valt Glimja som min första hemsida vilket är en webbshop. Den andra hemsidan jag har valt är Djurens Rätt som är en organisation som arbetar för djurens röst i samhället. Den tredje och sista hemsidan jag har valt är Holistic. Det är ett svenskt varumärke som har vitaminer, kosttillskott och liknande.

Metod
-----------------------

Analysen av hemsidornas laddningstid kommer att testas med hemsidan PageSpeed Insights. Där skriver man hemsidans url och får sedan fram information för hur laddningstiden har varit både för en mobil enhet och en desktopenhet.
Laddningstiden, antal resurser samt total storlek i megabyte kommer att hämtas utifrån googles egna dev tools-funktion, där varje sidan har körts igenom tre gånger och jag har sedan tagit genomsnittet av de olika värderna.

Resultat
-----------------------

GLIMJA:

![glimja](%assets_url%/img/glimja_load.jpg)

För mobilsidan av glimja så skulle man kunna ta bort resurser som blockerar renderingen, ta bort JavaScripts-kod som inte används samt se till så att alla bilder är i lämplig storlek för att spara mobildata och då förbättra laddningstiden. För desktop kan man även här se över lämplig storlek på bilder samt försöka förbättra svarstiden från server.

DJURENS RÄTT:

![djurens](%assets_url%/img/djurens_load.jpg)

Djurens rätt hemsida laddar redan väldigt fort och innehåller inte lika mycket resurser som glimja. Det man skulle kunna göra både för mobilsidan och desktop är att ta bort oanvänd js-kod, samt för mobilvyn skulle man även här kunna se över storleken på bilderna för att spara mobildata.

HOLISTIC:

![holistic](%assets_url%/img/holistic_load.jpg)

Samma förslag på förbättringar finns för holistic, att man sätter en mer lämplig storlek på bilderna, reducerar en tid det tar för servern att svara samt ta bort js-kod som inte används.

RÅDATA:
<iframe class="tabell" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vROm90H3iHw_SVMsmnxPmwYUHnHhXkKHXn5vrjcVu2E_Z6048Y4HsBaWC25Jg8l9rHazAGv3xz_hu4A/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

Analys
-----------------------

Dessa hemsidor har nu fått i princip likadana förbättringsförslag. Glimja är absolut långsammast på att ladda men är också den hemsida som har flest resurser. De skulle kunna tjäna många sekunder på att se över och åtgärda sådant som inte behövs och som endast förlänger laddningstiden.

Djurens rätt hemsida är absolut snabbast på att ladda vilket man också märker av, speciellt om man jämför den mot glimja. Den är även mindre än glimja så det är förståeligt att den är snabbare. Dock kan det vara intressant att jämför den mot holistic, båda sidornas startsidor ligger relativt nära varandra när man ser till den totala storleken, 2.7 MB - djurens rätt respektive 3.3 MB - holistic. Holistic har även ett färre antal resurser men laddar i princip tre gånger långsammare än djurens rätts startsida.

Jag skulle utse Djurens Rätt som vinnare om de olika sidorna ska sättas emot varandra, och tyvärr så kommer då Glimja på sista plats. 

Holistics bloggvy är den sida med störst total storlek och den landade på 470 resurser där sidan var 27.0 MB för mobil och 50.5 MB för desktop. Dessa sidor tog 3.47s respektive 3.95s att ladda. Glimjas största sida, av de analyserade, är istället deras förstasidan. De har väldigt mycket som händer på den sidan och mycket olika saker som ska laddas men om man ser till total storlek samt antal resurser så hamnar de på ungefär hälften av det antal resurser som holistic hade och en tredjedel av deras totala storlek. Däremot tar dessa sidor för glimja 5.18s för mobil enhet samt 4.64s för desktop att ladda.

RANGORDNING:
1.) Djurens Rätt
2.) Holistic
3.) Glimja

Alla vill väl att hemsidor ska ladda fort och jag gillar verkligen hur snabb djurens rätts hemsida var. Deras laddningstid höll sig under en halv sekund och man hann knappt reagera innan den var färdig. Såklart är väl en sådan tid att föredra när man väl sitter och tänker på det.
När det gäller glimja så tycker jag att den ibland kan vara lite väl långsam, så om man utgår ifrån det så skulle jag säga att glimja är lite långsam medan djurens rätt är väldigt snabb.
Så mellan 300ms upp till 1s skulle jag nog säga att hemsidan är snabb, och när det närmar sig 4-5 sekunder så börjar den upplevas som långsam.

Övrigt
-----------------------

Analys genomförd och skriven av: Isabella Wikström.
