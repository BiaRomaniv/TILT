<h2 style="text-align: center; font-weight: bold;">TILT 10/03/22</h2>

### Objeto do estudo: JAVASCRIPT

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### array.forEach()

```
The forEach() method calls a function for each element in an array.
https://www.w3schools.com/jsref/jsref_foreach.asp
```
Com essa propriedade, podemos percorrer um array e executar a função para cada elemento do array.
Uma forma diferente de realizar um loop e mais eficiente dependendo da aplicação.

Por exemplo:
  Criada a função no controller, para buscar informações no banco de dados e armazenar no questions:
  
    const questions = await db.all(`SELECT * FROM  questions WHERE room = ${roomId}`)  // seleciono tudo da tabela questions onde o Id da Sala corresponde com a sala atual.
    
  Dentro do HTML onde vou precisar das informações eu defino (estou usando EJS para as implementações de JS no HTML):
    
    <% questions.forEach(question => { %>   //no array questions, para cada elemento, buscar o tittle armazenado  de cada um e mostrar no parágrafo da div question.                         
        <div class="question">
            <p><%= question.title %></p>
        </div>                               
    <% }) %>

  Desta forma, terei uma lista com todas as questões e seus títulos sendo exibidos no HTML.
---

E isso foi o que eu aprendi hoje! :heavy_check_mark:
