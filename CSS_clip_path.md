<h2 style="text-align: center; font-weight: bold;">TILT 21/02/22</h2>

### Objeto do estudo: CSS

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### Clip-path

```
The clip-path CSS property creates a clipping region that sets what part of an element should be shown. 
Parts that are inside the region are shown, while those outside are hidden.
(https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
```
Com essa propriedade, podemos criar regiões em formatos geométricos.

Por exemplo, eu preciso criar uma região circular atrás do ícone de usuário, para destacá-lo:

![2022-02-21](https://user-images.githubusercontent.com/66280875/155045730-cbfc8853-dd04-4026-8e8a-094edfdd4e38.png)

Para isso, criamos um clip-patch:

```
".question-wrapper .question-content .user{
    background: var(--blue);
    clip-path: circle();
    padding: 1.4rem;
}"
```

Há também um site que ajuda a criar Clip-paths automaticamente:

[Bennett Feely](https://bennettfeely.com/clippy/)

---
E isso foi o que eu aprendi hoje! :heavy_check_mark:

