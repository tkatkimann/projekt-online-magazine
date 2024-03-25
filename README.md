# projekt-online-magazine
School assignment


Navngivning af mappe og filnavne samt struktur:

Ingen store bogstaver, ingen danske vokaler som "æ", "ø" eller "å".

Den først mappe er  "projekt-online-magazine", som indeholder denne README.md fil og en ekstra mappe med navnet, artwebtips-online-magazine. 

Mappen "artwebtips-online-magazine"  indebære mit en css fil og mit hovedfil som er index.html fil, med en masse mapper. Disse mapper er katagoriseret  efter mine 4 hovedmenuer (home er ikke indkluderet): Lær at tegne, Sjove Øvelser, Kunststile og Kunstinfluencer. Jeg har valgt at oversætte mine  4 hovedmenuer  til engelsk:

1. Mappen "page-learn", som er mit hovedmenu for "lær at tegne", indeholder undermenuerne/htmlerne: anatomi.html, digitalkunst-for-nybegyndere.html, farveteori.html, kunstmaterialer-til-nybegyndere.html og skyggeteknik.html.

2. Mappen "page-challenges", som er mit hovedmenu for "sjove øvelser", indeholder undermenuerne/htmlerne: dtiys-challenge.html, inktober-challenge.html, moodboard-challenge.html, pallete-challenge.html og  speed-drawing-challenge.html 

3. Mappen "page-artstyles", som er mit hovedmenu for "kunststile", indeholder undermenuerne/htmlerne:
characterart.html (jeg har glemt at lave et bindestreg på filen), cubism-art.html og pop-art.html .

4. Mappen "page-artinfluencers", som er mit hovedmenu for "kunststile", indeholder undermenuerne/htmlerne:
find-kunstner-paa-instagram.html og find-kunstner-paa-youtube.html .

Tilbage til mappen "artwebtips-online-magazine" er der en mappe for mine billeder. Mappen hedder "img-webp".
Alle billeder er i filformaterne WebP.

"img-webp" mappen indholder mapper til mine 5 hovemenuer: forside-billeder, artstyle-billeder, challenges-billeder, kunstinfluencer-billeder og learn-to-draw-billeder. Alle mapper har samme efternavn "billeder".

1. "forside-billeder" mappen indeholder billederne: forsidens-background (billedet er hentet gratis fra Pexels:https://www.pexels.com/da-dk/foto/kamera-skrivebord-bord-teknologi-1478477/), logo.
(Alle billeder der ikke har kilde er mine egne) 

2. "artstyle-billeder" mappen indeholder 3 mapper: charcter-art-images, cubism-art-images og pop-art-images.
hver er de 3 mapper inderholder deres billeder til html siden.

3."challenges-billeder" mappen indeholder 5 mapper: dtiys-images, inktober-image, moodboard-images (fejl ved at tilføje et ekstra s, selvom der kun er ét billed), pallet-images og speed-art-image. Jeg har valgt at lave et mønstre for mine mapper ved at give dem alle samme efternavn.

4. "kunstinfluencer-billede" mappen indeholder 2 mapper: youtube og instgram.  (her er der lavet mønster for billederne i mappen instagram med efternavnet "instagram" og billederne i mappen yotube med efternavnet "photo" (et af billederne er skrevet forkert))

5."learn-to-draw-billeder" mappen indeholder også 5 mapper: anatomi, farveteori, img-digitalkunst, img-kunstmaterialer og skygge teknik. (Her er billederne ikke organiseret ordentlig, idet de ikke har fået et efternavn)


Fremhæv dine semantiske tags samt få CSS egenskaber:

Dette er mine basale struktur af mine semantiske tags som jeg har brugt for at opbygge mit online magazine:
<!-- <html><body> <nav></nav> <main class="alle-container"> <section> <aside></aside><article></article></section></main></body></html> -->

Jeg har lavet en class for min mit tag, <!--<main = "alle-container"></main> -->
Tagget har jeg brugt i sammenhæng med det dominerende indhold på siden.

Jeg har sat en class'en ".alle-container" for mit main, fordi jeg ikke ville have at min tekster eller billeder fylder hele hjemmesidens skærm. Derfor har jeg brugt css for at skabe en ramme for alt mit indhold ved at bruge padding.

Jeg har brugt tagget section i sammenhæng med mine artikler, aside, og div. 

Jeg har få gange brugt aside i stedet for div. Jeg benyttede aside for flytte mine billeder på højre eller venstre side af min section.

Tagget article indeholder alle teksterne i form af <h3> <h4> og <p>.


Optimmeringer:
Jeg jar lavet en den fejl, at jeg har brugt for mange <br> og <hr> i mit HTML. Linjeskift bør generelt administreres gennem CSS.

Jeg har lavet den fejl, at jeg har brugt en del div-elementer i mit html filer under section. Jeg har brugt div elementet  mest til mine billeder og deres placeringer på hjemmesiden.

F.eks. har jeg brugt div til strukturen af min skyggeteknik undermenu. 
Eksempel ved brug af div: 


Eksempel på brug af semantisk tags med css. I digital-kunst-for nybegyndere har jeg uden for min article tag brugt tagget aside for at flytte et billede med tekst til højre. Det har jeg gjort så "boksen med billede og tekst" kan blive omringet af artiklen.

.image-to-rigt {
    float:right;
    margin-left:30px;
    margin-bottom:30px;
}




HTML & CSS validation:
<img src="/screenshot-of-validation/css-screenshot.JPG">
<img src="/screenshot-of-validation/index-screenshot.JPG">






















