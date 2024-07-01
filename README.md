# Learning compromise.js (for NLP)

Just one of the things I'm learning. https://github.com/hchiam/learning

Live minimal compromise.js `adjectives()` demo: https://codepen.io/hchiam/pen/XWwQypE?editors=1000

```html
<p id="output"></p>

<script src="https://unpkg.com/compromise@14.13.0/builds/compromise.js"></script>
<script>
  const doc = nlp("The flavour of the food was very tasty, fresh, and sweet.");
  document.body.querySelector("#output").innerText = doc.adjectives().text();
</script>
```

Skip to API sections: https://github.com/spencermountain/compromise?tab=readme-ov-file#api
