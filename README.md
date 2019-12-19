Det här projektet bygger på en grund genererad av [Create React App](https://github.com/facebook/create-react-app).

## Hur du installerar
Klona ner koden från master-branchen, eller ladda ner den. "Master" utgör den mall övningen utgår från.

Verifiera att Node finns på din dator, så att du kan köra npm och node-kommandon från terminalen.

Installera alla beroenden med "npm install". Det här är över 100Mb nedladdningar, varför det rekommenderas att du laddar ner dessa innan övningstillfället, så vi inte laddar ner alla beroenden samtidigt och gör oss beroende av en fungerande lina där och då.

### `npm start`

Kör appen i utvecklarläge, och öppnar en flik för [http://localhost:3000](http://localhost:3000) i din standardwebbläsare.
Du kan stänga ner fliken, men hålla igång utvecklingsservern, vilket kan vara praktiskt om du konfigurerat Visual Studio Code att köra med sin debugger (F5 på PC)<br />
Create React App använder webpacks Hot Module Reloader-plugin, vilket laddar om sidan åt oss efter att ha sparat förändrad kod.</br>

### `npm test`

Kör "test runner"n i sitt bevakningsläge. Grunden kommer med ett test packeterat från början, så att du kan verifiera att testerna kör innan du skriver egna.<br />
Vi kan också sätta Jest i watch mode, så att testerna kör varje gång den eller webpack upptäcker kodförändringar. Detta kan vara mycket praktiskt vid avlusning</br>
Se Create React Apps dokumentation om [att köra tester](https://facebook.github.io/create-react-app/docs/running-tests) for mer information.

## Om du vill fördjupa dig i Create React Apps mall
Create React App har runt 56 egna beroenden, allt från byggen med Webpack till testköraren Jest. För den som vill fördjupa i verktyget föreslår jag att söka på "create-react-app"