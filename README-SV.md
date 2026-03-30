# Mutant Undergångens Arvtagare

Inofficiellt karaktärsblad för Mutant Undergångens Arvtagare till Roll20. 

Detta karaktärsblad har inte blivit godkänt av ägarna av upphovsrätten för spelet, och kan därför inte publiceras på Roll20 som ett inbyggt val. 

## Hur man använder i ett spel

För att använda dessa filer måste SL ha Pro eller högre prenumeration hos Roll20, eftersom enbart de högre nivåerna har tillgång till "custom character sheet". 

I spelet på Roll20, gå först till Spelinställningarna och scrolla till botten. Där finns inställningar för vilket karaktärsblad man vill använda, välj "Custom". Detta ger möjligheten att klistra in innehållet i filerna mutantua.html, mutantua.css, och translation.json i respective textfält.

> Checkboxen för "Legacy Sanitization" ska INTE vara iklickad.

## Hur man använder som spelare

Spelledaren kommer att ge rättigheter att ändra i karaktärsbladet, som hittas i Journal-tabben. Klicka för att öppna karaktärsbladet. 

Formuläret är indelat i olika sektioner. Högst upp finns Grundegenskaper, övriga attribut, samt information om karaktären. Under det finns färdigheter, till vänster de generella och till höger de intränade färdigheterna. Under färdigheterna så finns vapensektionen, och under den finns utrustning och skydd till vänster och förmågor till höger. 

Det finns en liten T10-ikon som visar var det går att slå tärningar. Det sker då automatiskt enligt informationen i karaktärsbladet och resulatet dyker upp i chatten. 

### Grundegenskaper och generella attribut

Dessa skrivs in i respektive fält. Det finns ågra få automatiskt uträknade fält, dessa går inte att redigera men går ofta att lägga till modifikationer i närliggande fält. Vissa fält som t ex Hälsa och Förflyttning måste alltså räknas ut och skrivas i manuellt (för tillfället). 

Vissa värden har modifikationer, som kan skrivas i för att modifiera ett annat uträknat värde. 

Initiativbonus och Reaktionsvärde är klickbara fält, för att rulla repsektive tärningar. 

Vissa sekundära värden har modifikationer, så att du kan justera bas-värdet. 

Kroppspoäng har både ett nuvarande och ett maximalt värde. När du tar skada så ändrar du enbart det nuvarande värdet. 

### Repeterande listor

Tränade färdigheter, Vapen, Rustning, Utrustning och Förmågor är alla så kallade repeterade listor som från början är tomma. Man kan lägga till nya rader i dessa genom att klicka på den lilla ikonen med en lista och ett plustecken i nedre högra hörnet av listan. Då läggs en ny rad till som blinkar sakta. Blinkandet innebär att den är i redigeringsläge, vilket stängs av eller på med den lilla kugghjulsikonen som dyker upp till höger när man hovrar med musen över ett fält. 

I redigeringsläge kan mycket av informatione uppdateras, och när man går ur det läget så låses de flesta val för raden och potentiella knappar (t ex för tärningsslag) aktiveras. 

Dessa listor kan också editeras genom att flytta runt rader eller ta bort rader, för att göra det börja med att klicka på ikonen med tre rader och en penna i det nedre högra hörnet av listan. Då ställs listan i editeringsläge, och du kan flytta rader upp och ner genom att "ta tag" i ikonen till vänster, medan soptunneikonen till höger gör att raden tas bort. 

> Notera att ingen fråga elelr varning dyker upp när en rad tas bort, så var försiktig med den funktionen. 

### Färdigheter

Naturliga färdigheter har ett FV och en modifikation. Själva namnet kan användas för att slå för färdigheten. 

Tränade färdigheter är en s.k. repeterande lista (se ovan). De färdigheter som omnämns i regel- och spelar-boken finns med som en drop-down lista när man lägger till en ny rad. 

Man kan också välja att lägga till egna träande fäardigheter genom att välja det sista valet i listan, "Lägg till manuellt". Man får då skriva i ett eget namn, men i övrigt funkar det som andra färdigheter. 

### Vapen

Vapen är också en repeterande lista. Det viktiga är att välja rätt Färdighet i rullisten "Färd.", så att slagen med vapnet sker på rätt sätt. 

Speciellt för vapen är att det går att slå för vapnets träff genom att klicka på vapnets namn. Från resultet i chatten kan man sen slå för skadan, vilket räcknar in kritiska träffar baserat på färdigheten man använder. När man slagit skada i chatten får man även möjlighet att slå träffområde. 

Vapen har också betydelse för turordningen, och initiativet kan slås med värdet som lagts in under Init. OM man samtidigt markerar sin egen ikon på spelfältet, så kommer initiativet läggas in i Roll20 initiative tracker. 

Skada kan slås via träffresulatet i chatten, men också direkt ifrån formuläret. När skadan slås direkt från formuläret så räknas inget extra skada ut pga potentiella perfekta slag, men det gör det om man först slår för vapnets attack (knappen vid vapnet namn).

### Rustning

Rustning har värden både för Begränsning och Vikt. Det är bara vikt som räknas ut och läggs till värdet mot bärförmågan, men bara om den inte är påtagen (knappen till vänster är ett V). Om rustningen är avtagen så klickar man bort det (och visar istället ett X). Detta påverkar den använda Bärförmågan.

> Notera att inga automatiska avdrag görs (ännu) för rustningar med Begränsningar. 

### Utrustning

Utrustningslistan och dess antal och vikt läggs samman gentemot den utnyttjade bärförmåga. Notera att om en sak avmarkeras så räknas den inte som buren och därför inte heller gentemot bärförmågan. 

### Förmågor

Denna lista visar de förmågor, dvs, mutationer, optioner eller talanger som är relevanta för typen av karaktär. 

Notera att tärningsslaget inte är ett färdighetsslag. Om en förmåga skulle behöva ett vanligt T100 färdighetsslag öven om det kan läggas in som en T100, det är bättre attlägga till såna som i listan med Tränade färdigheter med valet "Lägg till Manuellt". 



