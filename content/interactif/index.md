---
title: Exemples interactifs

#event: Wowchemy Conference
#event_url: https://example.org

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# summary: An example talk using Wowchemy's Markdown slides feature.
# abstract: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam.'

# # Talk start and end times.
# #   End time can optionally be hidden by prefixing the line with `#`.
# date: '2030-06-01T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# # Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

# authors: []
# tags: []

# # Is this a featured talk? (true/false)
# featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# # Markdown Slides (optional).
# #   Associate this talk with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: example

# # Projects (optional).
# #   Associate this post with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
# #   Otherwise, set `projects = []`.
# projects:
#   - example
---

Un exercice pour illustrer la simplicité d'usage des fonds de carte du projet [`cartiflette`](https://github.com/InseeFrLab/cartiflette)

<br> 
<div class="alert alert-warning" role="alert" style="color: rgba(0,0,0,.8); background-color: white; margin-top: 1em; margin-bottom: 1em; margin:1.5625emauto; padding:0 .6rem .8rem!important;overflow:hidden; page-break-inside:avoid; border-radius:.25rem; box-shadow:0 .2rem .5rem rgba(0,0,0,.05),0 0 .05rem rgba(0,0,0,.1); transition:color .25s,background-color .25s,border-color .25s ; border-right: 1px solid #dee2e6 ; border-top: 1px solid #dee2e6 ; border-bottom: 1px solid #dee2e6 ; border-left:.2rem solid #ffc10780;">
<h3 class="alert-heading"><i class="fa-regular fa-lightbulb"></i> Hint</h3>
<br>

Le projet s'enrichit progressivement de fonctionnalités, n'hésitez pas à __consulter régulièrement cette page__.
<br>
<br>
Pour le moment, [`cartiflette`](https://github.com/InseeFrLab/cartiflette) est fourni principalement 
sous forme de 
_package_ `Python` <i class="fa-brands fa-python"></i>. Quelques fonctionnalités sont portées en `JavaScript` <i class="fa-brands fa-square-js"></i> avec le 
présent _notebook_. 
<br>
<br>
Le développement d'une API pour offrir de la flexibilité dans la récupération des fichiers tout
en laissant la liberté à l'utilisateur est prévue. N'hésitez pas à proposer de l'aide sur 
[`Github` <i class="fa-brands fa-github"></i> `inseefrlab/cartiflette`](https://github.com/InseeFrLab/cartiflette)

</div>

<br>

<div id="observablehq-prez_package-68f6179f"></div>

<iframe width="100%" height="760" frameborder="0"
  src="https://observablehq.com/embed/@linogaliana/cartiflette-demo?cells=grid"></iframe>

<div id="observablehq-partie_2-c01a9e44"></div>

<iframe width="100%" height="711" frameborder="0"
  src="https://observablehq.com/embed/@linogaliana/cartiflette-demo@1140?cells=grid_departement"></iframe>

<div id="observablehq-partie_3-00fa3604"></div>

<iframe width="100%" height="838" frameborder="0"
  src="https://observablehq.com/embed/@linogaliana/cartiflette-demo@1140?cells=grid_multiple_departement"></iframe>


<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
import define from "https://api.observablehq.com/@linogaliana/cartiflette-demo@1149.js?v=3";
new Runtime().module(define, name => {
  if (name === "prez_package") return new Inspector(document.querySelector("#observablehq-prez_package-68f6179f"));
  if (name === "partie_2") return new Inspector(document.querySelector("#observablehq-partie_2-c01a9e44"));
  if (name === "partie_3") return new Inspector(document.querySelector("#observablehq-partie_3-00fa3604"));
});
</script>