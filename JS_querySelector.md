<h2 style="text-align: center; font-weight: bold;">TILT 24/02/22</h2>

### Objeto do estudo: JAVASCRIPT

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### Seleção de elementos dentro do HTML no JS
        
#### querySelector
        
        Retorna o primeiro elemento dentro do documento (usando ordenação em profundidade, 
        pré-ordenada e transversal dos nós do documento) que corresponde ao grupo especificado de seletores.
        
        https://developer.mozilla.org/pt-BR/docs/Web/API/Document/querySelector

##### querySelectorALL
        Retorna uma lista de elementos presentes no documento (usando ordenação em profundidade, 
        pré-ordenada e transversal dos nós do documento) que coincidam com o grupo de seletores especificado.
        
        https://developer.mozilla.org/pt-BR/docs/Web/API/Document/querySelectorAll

#### Sintaxe querySelector:
        element = document.querySelector(selectors);(retorna o primeiro elemento correspondente ao seletor especificado)
        
#### Sintaxe querySelectorAll:
        elementList = document.querySelectorAll(selectors); (A NodeList retornada irá conter todos os elementos do documento que 
        coincidam com os seletores especificados.)
      
### Exemplo:
Tenho a necessidade de buscar dentro do HTML do meu elemento Modal, todos os botões com a classe "check" para que quando clicados </br>
eles abram a modal perguntando se Desejo marcar a questão como lida. Segue abaixo:
        
        // seleciono todos os botões do tipo "a" com a classe "check"
        "const checkButtons = document.querySelectorAll("a.check")" 
        
        // verifico em todos eles se houve o evento de clique do mouse para abrir modal
        "checkButtons.forEach(button => {
             button.addEventListener("click", event => {
             modal.oper() 
         })
           })"


---        
E isso foi o que eu aprendi hoje! :heavy_check_mark:
