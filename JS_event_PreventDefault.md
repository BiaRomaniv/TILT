<h2 style="text-align: center; font-weight: bold;">TILT 03/02/22</h2>

### Objeto do estudo: Javascript

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### event.preventDefault()

   Aprendi que a função event.preventDefault(); serve para prevenir o comportamento padrão de um evento. 
   O caso que estou desenvolvendo, necessita que o clique em um <a> não se comporte como link e sim como um botão, </br>
   pois o clique no link envia um valor para o endereço http na barra do navegador.
   
   Neste caso, o código ficou assim:
   
   
      function handleClick(event, check = true) {
       event.preventDefault()  
      ...
      ...
      ...
       modal.open()
      }
   
   Desta forma, o clique irá abrir a modal, sem enviar nada pro navegador. :)
   
---
E isso foi o que eu aprendi hoje! :heavy_check_mark:
