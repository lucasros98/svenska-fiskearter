# Svenska fiskarter

Detta repository innehåller en öppen JSON-databas över svenska fiskarter. Den är avsedd att användas som en resurs för utvecklare för att exempelvis skapa fiskeapplikationer.

## Innehåll

JSON-filen (`fiskarter.json`) innehåller information om varje fiskart, inklusive:

- Svenskt namn
- Vetenskapligt namn
- Beskrivning
- Förekomst
- Habitat (typ av vatten där fisken ofta hittas)
- Minimimått (rekommenderade eller lagstadgade minimimått för fiske)
- Svenskt fiskerekord 

## Hur man använder denna databas

Denna databas är fri att användas och kan integreras direkt i fiskeapplikationer, utbildningsmaterial eller forskningsprojekt. Du kan enkelt importera JSON-filen i ditt projekt och använda den som en uppslagsresurs.

Exempel på kod för att läsa in JSON-filen:

```javascript
const fiskarter = require('./fiskarter.json');
console.log(fiskarter);
```
