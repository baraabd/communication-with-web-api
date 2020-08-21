# communication-with-web-api

Introduktion
Första del:
Den här webbplatsen innehåller ett gränssnitt i webbläsaren där användaren ger sin plats bakom. Jag har kommit att kommunicera med tredje parts tjänster för att konvertera den platsen till en forecast.
Jag har skickat sedan tillbaka forecast till webbläsaren så att jag kan återge data för användaren att se.

Andra del:
Följande knapp fungerar:
Get: Använd Get-funktionen för att hämta forecast via återuppringning i forecast filen och spara sedan  forecast i objektvariabeln.

Addl: Den här knappen sparar data i ett objekt via post

Delete: med delete funktionen

Update: uppdatera stadens namn med uppdate funktionen

Dependencies 
Det jätte fikigt att instalera Dependencies för att webbplatsen funkar
    "debug": "^2.6.9",
    "express": "^4.17.1",
    "hbs": "^4.1.1",
    "mime-db": "^1.44.0",
    "mime-types": "^2.1.27",
    "ms": "^2.0.0",
    "request": "^2.88.2",
    "safer-buffer": "^2.1.2",
    "uuid": "^3.4.0"
    
 Teknologier som används på webbplatsen
i min applikation använde jag weatherstackK.com, som är en gratis webbplats som ger väderdata med API, sedan började jag använda express, och förresten gick jag tillbaka till några föreläsningar om hur man navigerar på sidor med Express, och det var Detta är användbart för mig eftersom jag har hämtat min gamla information, jag använde också mabbox.com för att hämta latitud och longitud och skicka den sedan till ett inlägg som heter forecast.
 
 
 Delar fungerar inte:
Att hämta data från väderwebbplatsen fungerar bra, men den andra delen av webbplatsen fungerar inte ännu eftersom jag inte har tid att slutföra den.
I allmänhet har den fått mycket erfarenhet av hur man använder API.


 
