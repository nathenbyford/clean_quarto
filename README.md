# Clean reveal.js Theme for Quarto

Clean and minimal Quarto template for revealjs presentations. Modified and simplified template from my [Baylor theme](https://github.com/nathenbyford/baylor_theme).

## Edits made

-   Gray heading accents,
-   no logo,
-   blue and orange bullet points,
-   Roboto font default, and
-   Jetbrains mono font (no ligatures) for code blocks.
-   Image zoom on click (Radovan Miletić, [here](https://stackoverflow.com/questions/75922380/how-to-zoom-on-graph-in-slide-revealjs-quarto))

## Photos

Coming soon.

## Usage notes

-   To use the template in for a new document use the following code in the terminal.

```         
quarto use template nathenbyford/clean_quarto
```

-   To use the template on a preexisting quarto document and just add the theme you can use the following code in the terminal within the working directory,

```         
quarto add nathenbyford/clean_quarto
```
Then after running the line of code in your terminal you'll need to change your header to include
```
---
title: "Title"
author: Author
footer: Author
format: 
    clean-revealjs
---
```
More formatting arguments can still be included after this ti customize the document/presentation to your liking and needs.