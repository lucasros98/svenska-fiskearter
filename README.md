
# Databas för svenska fiskarter

Detta repository innehåller en öppen JSON-databas över svenska fiskarter. Den är avsedd att användas som en resurs för utvecklare för att exempelvis skapa fiskeapplikationer.

![gädda](https://github.com/lucasros98/svenska-fiskearter/assets/47554985/beca355f-55cc-4094-9cfd-89966236f365)

## Innehåll

JSON-filen (`swedish_fish_species.json`) innehåller information om varje fiskart, inklusive:

- Svenskt namn
- Vetenskapligt namn
- Beskrivning
- Förekomst
- Habitat (typ av vatten där fisken ofta hittas)
- Minimimått (rekommenderade eller lagstadgade minimimått för fiske)
- Svenskt fiskerekord 

## Hur man använder denna databas

Denna databas är fri att användas och kan integreras direkt i exempelvis fiskeapplikationer eller för utbildningsmaterial. Du kan enkelt importera JSON-filen i ditt projekt och använda den som en uppslagsresurs.

Exempel på kod för att läsa in JSON-filen:

```javascript
const fiskarter = require('./swedish_fish_species.json');
console.log(fiskarter);
```
