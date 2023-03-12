# Registreringsskyltsgeneratorn för bilar

Nyckelord: Datastrukturer, filhantering

## Uppgiften

### Lydelse

I Sverige, likt många andra länder, så har vi ett nationellt register för bilar. Dessa består av tre bokstäver följt av tre siffror. (Sen några år tillbaka går det även att få tre bokstäver följt av två siffror och sen en bokstav igen. Det g år också att få ett personligt registreringsnummer.)

Ditt program ska generera nya godkända registreringsnummer som du sedan skriver ut på fil. Användaren ska ange önskat antal nummer som ska skrivas till filen med registreringsnummer. Dina registreringsnummer ska följa följande regler:

- Bokstäverna väljs utifrån delmängden av det svenska alfabetet: A B C D E F G H J K L M N O P R S T U W X Y Z
- Siffrorna kommer från en slumptalsgenerator som slumpar allt i registreringsnumret.
- Vissa kombinationer är olämpliga och är inte tillåtna, dessa finns på en fil som du kan utöka hur du vill.

För högre betyg önskas att programmet ÄVEN genererar registreringsnummer av den nya sorten.

Tips: Lagra samtliga registreringsnummer i ett dictionary för att ta reda på om det existerar krockar.

### Krav för olika betyg

För C räcker det att programmet genererar gamla registreringsnummer, läser in tagna registreringsnummer samt sparar ner nya på fil.

För A krävs det att nya registreringsnummer också går att generera.

## Dokumentation & Planering

### Loggbok

Under arbetet förväntas du föra loggbok. Varje inlägg bör innehålla vad du gjort under passet och hur det gått. Skriv även gärna om du uppnått någon av milstolparna i projektplaneringen, använd gärna då ID:n för referens. Få gärna med eventuella problem du stött på och hur du löst dem (ifall du gjort det).

### Projektplan

Du påbörjar ditt projekt med att planera. Detta görs genom en projektplan med milstolpar och grindhål som ska uppnås under arbetets gång. Din projektplan bör revideras minst tre gånger under arbetet för att nå högsta bedömning. Projektplanen ska vara utförlig med detaljerade mål och uppgifter samt när deadline för dessa sker och vad som ska göras.

Projektplanen är det Google Sheet-arket som finns på classroom.

### Flödesschema

I första stadiet av projektet bör du även skissa upp ett flödesschema i förslagsvis draw.io som ska tillhöra ditt program. Tänk på vad de olika symbolerna betyder, samt att du inte har överflödiga punkter i schemat, eller att det är oläsbart.

## Författare

Niclas Lund

## Disclaimer

Uppgiften (eller inspiration till den) är ärligt stulen från EECS-skolan (gamla CSC) och kursen DD1314.
