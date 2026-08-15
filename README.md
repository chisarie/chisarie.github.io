# Eugenio Chisari's [Website](https://chisarie.github.io/)

Have a look at my personal projects at <https://chisarie.github.io/>

## Local preview

Do **not** preview by double-clicking `index.html`. Opening the file over `file://`
gives the page a null origin, so the YouTube embeds fail with
*"Error 153: Video player configuration error"* — the embed player needs a real
HTTP origin to validate against.

Serve the folder over HTTP instead:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>. The videos load normally from there.

## Template: [Start Bootstrap - Scrolling Nav](https://startbootstrap.com/template-overviews/scrolling-nav/)

[Scrolling Nav](http://startbootstrap.com/template-overviews/scrolling-nav/) is an unstyled one page starter template with a collapsing, smooth scrolling navigation bar for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/).

### Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-scrolling-nav/blob/gh-pages/LICENSE) license.
