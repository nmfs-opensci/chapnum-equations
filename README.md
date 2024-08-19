# chapnum-equations

Minimal example the components to make equations like 3.1 in a Quarto book

* mathjax.html -- the mathjax config with tagformate needed for chapter numbers
* chapnum.lua -- a lua filter to add `<script>MathJax.config.section=chap-num</script>` to the html.

## Status

It is kind of working but adds `<script>MathJax.config.section=chap-num</script>` every where including the sidebar and I need it to only be in the `<header>` tag.
