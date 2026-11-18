# Veckans insikter

**HTML – innehåll och struktur.** HTML talar om vad innehållet är. Till exempel är `<h1>` sidans huvudrubrik och `<p>` ett textstycke:

```html
<h1>Världen blir lite mjukare med en katt.</h1>
<p>Här firar vi livet med katt.</p>
```

**Bootstrap 4.6 – färdiga byggstenar.** Klasser som `container`, `row` och `col-md-6` hjälper till att ordna innehåll och anpassa layouten till olika skärmar.

**CSS – utseende.** I [style.css](style.css) styr färger, typsnitt, mellanrum och mobilanpassning.

**JavaScript – interaktion.** Knappen ”En till kattfakta” byter text när du klickar:

```js
document.getElementById("newFact").addEventListener("click", function () {
  document.getElementById("funFact").textContent = "En ny kattfakta!";
});
```

### Vibe Coding

Vibe coding innebär att skapa och förbättra kod i dialog med AI. Beskriv önskemålet, granska förslaget i webbläsaren och prova själv. Du ansvarar fortfarande för att kontrollera att innehållet fungerar och stämmer.

Öppna [index.html](index.html) i en webbläsare för att utforska sidan.