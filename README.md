# example-slides-quarto
Examples for creating slides/presentations

Develop locally using VSCode and use the quarto extension. Make sure to enable "Reload on Save" in the settings.

## Present

* Make sure to have "media", "slides_files" and slides.html, then everything should be working offline. 

### Important keys

(See also in the quarto menu)

* F - full screen
* S - speaker view (requires live server)
* ESC - slide overview (and ending fullscreen, typically)
* Q - enable virtual laser pointer

## Convert to PDF

```
docker run --rm -t -v `pwd`:/slides astefanutti/decktape slides.html slides.pdf
```

## References

* https://quarto.org/docs/presentations/revealjs/

### Pointer

``
quarto add quarto-ext/pointer
``