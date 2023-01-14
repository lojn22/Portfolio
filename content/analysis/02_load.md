---
Title: Load
Description: This is report analys page for loading time on websites.
Template: analysis
---

Webbsidors laddningstid
=======================

Syftet med uppgiften är att mäta tre olika webbsidor hur snabbt de laddas och om det finns förbättringsmöjligheter angående laddningstid och användbarhet.

Urval
-----------------------

Mina val av webbplatser blev inom resebrachen. Ving, Tui och Apollo. Laddningstid av hemsidor kanske kan påverka användarens val av vilket företag de väljer att boka sina resor med och därför tyckte jag det kunde vara kul och jämföra de tre större namnen i Sverige inom charterresebranchen.

Metod
-----------------------

Google Pagespeed för mätning av webbsidorna, delas in i fyra kategorier prestanda, tillgänglighet, bästa metoder ovh SEO. Färger grön orange och röd och en skala 1-100 för att betygsätta mätvärdena. grönt 90-100 är de bästa värdena organge 50-89 medel och rött 0-49 sämre. 
Google kalkylark för samling av datan jag fick fram av mätningen
Devtools - network för att se laddningstid, antalet resurser som laddas och sidornas totala storlek.

Resultat
-----------------------

**[Ving](https://www.ving.se/)**  
***
![Ving](%base_url%/assets/img/ving.png)
<sub><sup>besöksdatum 23-01-06</sup></sub>  
Pagespeed   
[Dator](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.ving.se%2F&form_factor=desktop) <sub><sup>analys utförd 23-01-06</sup></sub>   
Godkänt vid test av viktiga webbvärden

Tillgängligeten är Vings svaghet enligt mätningarna på Pagespeed som visar orange. Det de kan förbättra inom tillgänlighet är att namge sina knappar och länkar bättre. Ha större kontrast på bakgrund och förgrunds färg. Rubrikelement behövs ordnas i fallande följd och ordning för att få en bättre navigering.


[Mobilt](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.ving.se%2F&form_factor=mobile) <sub><sup>analys utförd 23-01-06</sup></sub>  
Godkänt vid test av viktiga webbvärden

När det kommer till den mobila enheten så får de även orang färg i prestanda och SEO.
Möjligheter för förbärrting är reducera JavaScript som inte används, minska serverns första svarstid och skjuta upp inlässningen av bider som inte visas på skärmen. Ge sökrobotar tillgång till appen om den ska kunna visas i sökresultaten. Mobilanpassa sidorna så att användaren kan läsa dem utan att behöva nypa eller zooma in.

<iframe class="analys" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQYJBXFILKRwyWGwL1pdS6q0GBZ7wvYLsAUrONik-zXQozBgTmIzxV9NUoTVrYjNaB-OrnqBxANA725/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

**[Tui](https://www.tui.se/)**  
***
![Tui](%base_url%/assets/img/tui.png)
<sub><sup>besöksdatum 23-01-06</sup></sub>  
Pagespeed  

[Dator](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.tui.se%2F&form_factor=desktop) <sub><sup>analys utförd 23-01-06</sup></sub>   
Inte godkänt vid test av viktiga webbvärden

Tui har orange färg i alla fyra kategorier 
Prestanda: Ta bort resurser som blockerar renderingen, läsa in bilden i förväg för största uppritning av innehåll, reducera Java Script som inte används.  
Tillgänlighet: Ändra så att alla attributen av aria stämmer med elementets roll. Se till att alla bildelement har ett [alt]-attribut och namnge sin alänkar bättre. Förbättre kontrasten av bakgrundsfärg och förgrundsfärg. Ordna rubrikelemnt i följd och fallande ordning.
Bästa metoder: Utfasade API:er används, webbläsarfel loggades i konsolen, saknars källkartor för stor JavaScript från första part.  
SEO: Länkarna är inte genomsöksbara, Alla bilder har inte [alt] -attribut.  

[Mobilt](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.tui.se%2F&form_factor=mobile) <sub><sup>analys utförd 23-01-06</sup></sub>   
Inte godkänt vid test av viktiga webbvärden
 
Mobilt format får de röd färg på prestanda och en lång lista på saker som kan förbättras. använd bilder med rätt storlek, undvik att skicka äldre JavaScript till moderna webbläsare, reducera CSS som inte används.

<iframe class="analys" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQYJBXFILKRwyWGwL1pdS6q0GBZ7wvYLsAUrONik-zXQozBgTmIzxV9NUoTVrYjNaB-OrnqBxANA725/pubhtml?gid=594605576&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

**[Apollo](https://www.apollo.se/)**  

***
![Apollo](%base_url%/assets/img/apollo.png)
<sub><sup>besöksdatum 23-01-06</sup></sub>  
Pagespeed  
[Dator](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.apollo.se%2F&form_factor=desktop) <sub><sup>analys utförd 23-01-06</sup></sub>   
Godkänt vid test av viktiga webbvärden

prestanda och bästa metoder ornage 
Prestanda: Reducera JavaScript som inte används, använd bilder med rätt storlek, skicka bilder i modernare bildformat, ta bort resurser som blockerar renderingen, koda bilder effektivt
Bästa metoder: innehåller JavaScript-bibliotek på klientsidan med kända säkerheter, Utfasade API:er används, Det Saknas källkartor för stor JavaScript från första part.

[Mobilt](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.apollo.se%2F&form_factor=mobile)  <sub><sup>analys utförd 23-01-06</sup></sub>  
Godkänt vid test av viktiga webbvärden

Prestanda rött, SEO orange.
reducera CSS som inte används, skjut upp inläsningen av bilder som inte visas på skärmen, undvik att skicka äldre JavaScript till moderna webbläsare.
SEO: Länkarna är inte genomsökningsbara, Tryckmålen har inte lämplig storlek.

<iframe class="analys" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQYJBXFILKRwyWGwL1pdS6q0GBZ7wvYLsAUrONik-zXQozBgTmIzxV9NUoTVrYjNaB-OrnqBxANA725/pubhtml?gid=1275206422&amp;single=true&amp;widget=true&amp;headers=false"></iframe>


Analys
-----------------------

Reducering av JavaScript som inte används verkar vara det vanligaste förbättringsområdet. Alla tre webbsidorna får sämmre resultat på pagespeed gällande mobilanpassning.

Ving är vinnaren som har bäst resultat på pagespeed både gällande desktop och mobilenhet. Deras genomsnittliga laddningstid är någon ms saktare än Apollos men skiljer inte mycket. 

Apollo kommer på en andra plats med den snabbaste laddningshastigheten men dock inte lika bra resultat på pagespeed som Ving har.

Tui har längst laddningstid och sämst resultat på pagespeed och kommer därför på en tredjeplats.

0-3 sekunder uppfattar jag som en relativt snabb laddning för en hemsida och där klara Ving och Apollo sig och verkar till att vara väldigt användaranvänliga och lätta att navigera på.


Övrigt
-----------------------
Länkar:  
https://www.ving.se/  
https://www.tui.se/  
https://www.apollo.se/  

Författare av rapporten  
Louise Jönsson

Referenser
-----------------------
https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.ving.se%2F&form_factor=desktop  
https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.tui.se%2F&form_factor=desktop  
https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.apollo.se%2F&form_factor=desktop
