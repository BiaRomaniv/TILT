<h2 style="text-align: center; font-weight: bold;">TILT 01/08/2022 <h2>

### Objeto do estudo: REACT

Este conhecimento foi adquirido durante o Bootcamp Ignite da Rocketseat https://www.rocketseat.com.br/ 🚀 sob a orientação indireta do Instrutor Diego Fernandes.

---

### O que é o REACT?
  
  React é uma biblioteca JavaScript, então é necessário um entendimento básico da linguagem. </br>
     ```A JavaScript library for building user interfaces ```

  O menor exemplo de React é o a seguir:
  
  ```
      ReactDOM.render(
        <h1>Hello, world!</h1>,
         document.getElementById('root')
      );
  ```
  
  Ao invés de separar tecnologias artificialmente colocando markup e lógica em arquivos separados, </br>
  o React separa conceitos com unidades pouco acopladas chamadas “componentes” que contém ambos. 
  Para isso, utilizar o JSX é uma ótima opção.
  
  O React não requer o uso do JSX. Porém, a maioria das pessoas acha prático como uma ajuda visual </br>
  quando se está trabalhando com uma UI dentro do código em JavaScript. 
  Ele permite ao React mostrar mensagens mais úteis de erro e aviso.
  
  ❗ Observação: Como JSX é mais próximo de JavaScript que do HTML, o React DOM usa camelCase como convenção </br>
                para nomes de propriedades ao invés dos nomes de atributos do HTML. Por exemplo, class se transforma em <strong> className </strong> em JSX.
              
              
   
   Com o JSX, podemos escrever os elementos HTML dentro do JavaScript e adicioná-los ao DOM sem utilizar métodos como createElement() ou appendChild(). </br>
   o JSX é uma alternativa para escrevermos nosso código que mescla a estrutura do DOM com a lógica da aplicação.
   
   
   ### Bundlers e Compilers
     
  Nem sempre todos os browsers conseguem acompanhar a evolução da tecnologia para dar suporte à sintaxe mais moderna.
  Para isso existem os compilers, como o Babel https://babeljs.io/ que convertem o código moderno para uma sintaxe mais antiga que os browsers reconhecem, e os bundlers como </br>
  o Webpack https://webpack.js.org/ que faz um bundling de todos os arquivos da nossa aplicação de uma forma que todos os browsers reconheçam.
  
  
  Atualmente podemos contar com o Vite https://vitejs.dev/, que irá substituir os bundlers e compilers tradicionais (como babel e webpack) e entender como ele tira proveito das funcionalidades </br>
  mais modernas dos navegadores para ter uma melhor performance de compilação e execução.
  
  
  ### Criando um projeto React com Vite
  
    npm create vite@latest
  
    npm run dev
  
                 
---

E isso foi o que eu aprendi hoje! :heavy_check_mark:

