# Mutant Undergångens Arvtagare

Inofficiellt karaktärsblad för Mutant Undergångens Arvtagare till Roll20. 

Detta karaktärsblad har inte blivit godkänt av ägarna av upphovsrätten för spelet, och kan därför inte publiceras på Roll20 som ett inbyggt val. 

## Hur man använder i ett spel

För att använda dessa filer måste SL ha Pro eller högre prenumeration hos Roll20, eftersom enbart de högre nivåerna har tillgång till "custom character sheet". 

I spelet på Roll20, gå först till Spelinställningarna och scrolla till botten. Där finns inställningar för vilket karaktärsblad man vill använda, välj "Custom". Detta ger möjligheten att klistra in innehållet i filerna mutantua.html, mutantua.css, och translation.json i respective textfält.

> Checkboxen för "Legacy Sanitization" ska INTE vara iklickad.

## Hur man använder som spelare

Spelledaren kommer att ge rättigheter att ändra i karaktärsbladet, som hittas i Journal-tabben. Klicka för att öppna karaktärsbladet. 

Vissa fält eller sektioner har två olika lägen, ett redigerings-läge och ett spel-läge. Man kan byta mellan lägena med hjälp av den kugghjulsikonen som dyker upp till höger när man hovrar med musen över något som går att ändra läge på. När man är i redigeringsläge så har de flesta fält en pulserande effekt för att man ska se tydligt vilket läge man är i. De flesta knappar eller klickbara delar är bara aktiva i spel-läget. 

Formuläret är indelat i olika sektioner. Högst upp finns Grundegenskaper, övriga attribut, samt information om karaktären. Under det finns färdigheter, till vänster de generella och till höger de intränade färdigheterna. Under färdigheterna så finns vapensektionen, och under den finns utrustning och skydd till vänster och förmågor till höger. 

Det finns en liten T10-ikon som visar var det går att slå tärningar. Det sker då automatiskt enligt informationen i karaktärsbladet och resulatet dyker upp i chatten. 

### Grundegenskaper och generella attribut

Dessa skrivs in i respektive fält. Det finns ågra få automatiskt uträknade fält, dessa går inte att redigera men går ofta att lägga till modifikationer i närliggande fält. Vissa fält som t ex Hälsa och Förflyttning måste alltså räknas ut och skrivas i manuellt (för tillfället). 

Vissa värden har modifikationer, som kan skrivas i för att modifiera ett annat uträknat värde. Till exmepel så har färdigheterna en kolumn med modifikationer, här kan temporära ändringar i FV åstadkommas genom att lägga till en modifikation. Mer permanenta modifikationer läggs med fördel till i själva FV värdet självt. 

Grundegenskaper har två olika typer av tärningsslag, svårighetsbaserade eller motståndsslag. Klickbara ikoner dyker upp när man hovrar över respektive grundegenskap. Den med "00" till vänster är svårighetsslag och den med "10" till höger är för motsåndsslag. Svårighetsbaserade slag är som Färdighetsslag där FV är GEx7 för enkla saker, GEx5 för normala, GEx3 för svåra, och GE för mycket svåra. Resultatet i chatten när man slår visar vilka av dessa nivåer man klarat. Motståndsslag slås med 1T10 + GE, och jämförs oftast med ett slag av motståndaren.   

Initiativbonus och Reaktionsvärde är klickbara fält, för att rulla repsektive tärningar. 

Vissa sekundära värden har modifikationer, så att du kan justera bas-värdet. 

Skadebonuns har inte en modifikation, utan snarare en override av det vanliga värdet. Detta kan användas när skadebonusen tillfälligt ändras. 

Kroppspoäng har både ett nuvarande och ett maximalt värde. När du tar skada så ändrar du enbart det nuvarande värdet. 

Bärförmågan under sekundära grundegenskaper styr hur stor bärförmåga som listas i den sektion under tränade färdigheter som även listar hur mycket bärförmåga som nyttjas. NB: Inga modifikationer sker autmoatiskt om bärfömågan överskrids.  

### Repeterande listor

Tränade färdigheter, Vapen, Rustning, Utrustning och Förmågor är alla så kallade repeterade listor som från början är tomma. Man kan lägga till nya rader i dessa genom att klicka på den lilla ikonen med en lista och ett plustecken i nedre högra hörnet av listan. Då läggs en ny rad till som blinkar sakta. Blinkandet innebär att den är i redigeringsläge, vilket stängs av eller på med den lilla kugghjulsikonen som dyker upp till höger när man hovrar med musen över ett fält. 

I redigeringsläge kan mycket av informatione uppdateras, och när man går ur det läget så låses de flesta val för raden och potentiella knappar (t ex för tärningsslag) aktiveras. 

Dessa listor kan också editeras genom att flytta runt rader eller ta bort rader, för att göra det börja med att klicka på ikonen med tre rader och en penna i det nedre högra hörnet av listan. Då ställs listan i editeringsläge, och du kan flytta rader upp och ner genom att "ta tag" i ikonen till vänster, medan soptunneikonen till höger gör att raden tas bort. 

> Notera att ingen fråga eller varning dyker upp när en rad tas bort, så var försiktig med den funktionen. 

### Färdigheter

Naturliga färdigheter har ett FV och en modifikation. Själva namnet kan användas för att slå för färdigheten. 

Tränade färdigheter är en s.k. repeterande lista (se ovan). De färdigheter som omnämns i regel- och spelar-boken finns med som en drop-down lista när man lägger till en ny rad. 

Man kan också välja att lägga till egna träande fäardigheter genom att välja det sista valet i listan, "Lägg till manuellt". Man får då skriva i ett eget namn, men i övrigt funkar det som andra färdigheter. 

### Vapen

Vapen är också en repeterande lista. Det viktiga är att välja rätt Färdighet i rullisten "Färd.", så att slagen med vapnet sker på rätt sätt. Om det inte finns en passande färdighet, så välj det sista valet, "Manuellt". När man går ur redigeringsläge så visas istället för färdighetens namn ett fält där man manuellt kan lägga in ett färdighetsvärde. 

Speciellt för vapen är att det går att slå för vapnets träff genom att klicka på vapnets namn. Från resultet i chatten kan man sen slå för skadan, vilket räcknar in kritiska träffar baserat på färdigheten man använder. När man slagit skada i chatten får man även möjlighet att slå träffområde. 

Det finns många orsaker till att chansen att lyckas modifieras när man strider, och det finns därför ett specifikt MOdifikations+fält för vapnet som kan användas temporaärt när vapnet ska användas. 

Vapen har också betydelse för turordningen, och initiativet kan slås med värdet som lagts in under Init. OM man samtidigt markerar sin egen ikon på spelfältet, så kommer initiativet läggas in i Roll20 initiative tracker. 

Skada kan slås via träffresulatet i chatten, men också direkt ifrån formuläret. När skadan slås direkt från formuläret så räknas inget extra skada ut pga potentiella perfekta slag, men det gör det om man först slår för vapnets attack (knappen vid vapnet namn).

### Rustning

Rustning har värden både för Begränsning och Vikt. Det är bara vikt som räknas ut och läggs till värdet mot bärförmågan, men bara om den inte är påtagen (knappen till vänster är ett V). Om rustningen är avtagen så klickar man bort det (och visar istället ett X). Detta påverkar den belastningen gentemot Bärförmågan.

> Notera att automatiska avdrag görs för rustningar och hjälmars Begränsning på när de är burna (checkboxen iklickad), detta återspeglar sig när man slår för de påverkade färdigheterna. Detta gör det viktigt att markera rätt typ av rustning i redigeringsläget för rustningen. När de inte är burna så räknas de däremot med i belastningen.

### Utrustning

Utrustningslistan och dess antal och vikt läggs samman gentemot den utnyttjade bärförmågan. Notera att om en sak avmarkeras så räknas den inte som buren och därför inte heller gentemot bärförmågan. Det som skiljer sig från den regeln är Rustning, som inte räknas mot bärförmåga då den bärs men gör det om den inte är påtagen. 

### Förmågor

Denna lista visar de förmågor, dvs, mutationer, optioner eller talanger som är relevanta för typen av karaktär. När en förmåga inte är i redigeringsläge så kommer den att visa de fält som har fyllts i. Vill man inte se detta så kan den informationen istället läggas till i beskrivningsfältet. 

Det finns ett fält för Färdighetsslag där ett färdighetvärde kan läggas in. Detta dyker sen upp som ett klickbart val för förmågan, och slås som ett vanligt färdighetsslag. När förmågan inte är i redigeringsläge så visas färdighetsvärdet förkortat till FV och följs av en fält för att lägga till en modifiering (Mod.).  

Notera att Tärningsslaget inte är ett färdighetsslag, utan används för andra slag som t ex 2T10+1/10 av ett färdighetsvärde. I dessa specifika fall får man räkna ut 1/10 och lägga in som t e 2T10+3. 

Om tärningsslag för Skada har lagt in så kan det slås direkt från normalläget för förmågan, men kommer också dyka upp som en knapp i resultatet av Färdighetsslaget eller Tärningsslaget i chatten.  

Förmågor har ett val kallat Resonans i redigeringsläget, denna bör enbart klickas i för PSI-mutationer och gör att en Resonans-sektion visas ovanför Förmågorna. När en sådan mutation misslyckas så läggs 1 till den nuvarande REsonansen för karaktären, och resultatet i chatten kommer att ha en Resonans-knapp man kan använda för att slå ett Resoans-test med 2T6 + Resonansvärdet - VIL. Det går även att slå direkt från Resonans-fältet, men slår man från resultatet i chatten så tas även fummel (+5 på slaget) med i beräkning. 

### Rolltemplate och Macron

Notera att i rollformuläret kan man skriva tärningar på det svenska viset med T, ex 1T10, men när man använder rolltemplate direkt måste man använda D.  

I exemplen beh;ver man byta ut texten som b;rjar med __ och slutar med __. 

#### Vanliga färdighetsslag

```
   &{template:mutantua} {{character_name=__karaktärsnamn__}} {{roll-name=__namn på slaget__}} {{roll1=[[1d100cs<__perfekt__cf100]]}} {{target=[[__FV__]]}}
```

Exempel:

```
   &{template:mutantua} {{character_name=Jerry}} {{roll-name=SKJUTA}} {{roll1=[[1d100cs<5cf100]]}} {{target=[[55]]}}
```

#### Skada

Notera att {{calcdamage=[[0]]}} på slutet måste vara med för att det ska funka

```
   &{template:mutantua} {{character_name=__karaktärsnamn__}} {{roll-name=__namn på slaget__}}  {{damage=[[__skadetärningar__[Skada]__+skadebonus__[Skadebonus]__+annan bonus__[bonus]]]}} {{target-area=[[1D6]]}} {{calcdamage=[[0]]}}
```

Exempel:

```
   &{template:mutantua} {{character_name=Jerry}} {{roll-name=ELDSKADA}}  {{damage=[[1T6+2[Eld]+1T4[Hetta] ]]}} {{target-area=[[1D6]]}} {{calcdamage=[[0]]}}
```