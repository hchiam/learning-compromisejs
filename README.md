# Learning compromise.js

Just one of the things I'm learning. https://github.com/hchiam/learning

Do modest NLP (Natural Language Processing) in your browser (no neural network model, no cloud 3rd party processing your data).

Consider the [pros and cons](https://dev.to/charlesdlandau/natural-language-processing-in-the-browser-52hj) of this.

Live minimal compromise.js `adjectives()` demo: https://codepen.io/hchiam/pen/XWwQypE?editors=1000

```html
<p id="output"></p>

<script src="https://unpkg.com/compromise@14.13.0/builds/compromise.js"></script>
<script>
  const doc = nlp("The flavour of the food was very tasty, fresh, and sweet.");
  document.body.querySelector("#output").innerText = doc.adjectives().text();
</script>
```

See official README for intro: https://github.com/spencermountain/compromise/blob/master/README.md

Skip to API sections: https://github.com/spencermountain/compromise?tab=readme-ov-file#api

Skip to gentle intro/docs and more concepts not always overlapping with the API sections: https://github.com/spencermountain/compromise/blob/master/README.md#docs
