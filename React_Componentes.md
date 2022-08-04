<h2 style="text-align: center; font-weight: bold;">TILT 03/08/2022 <h2>

### Objeto do estudo: REACT

Este conhecimento foi adquirido durante o Bootcamp Ignite da Rocketseat https://www.rocketseat.com.br/ 🚀 sob a orientação indireta do Instrutor Diego Fernandes.

---

### Conceito de Componentes

  Os componentes permitem que a UI seja dividida em partes independentes e reutilizáveis, ou seja, trata cada parte da aplicação como um bloco isolado, </br>
  livre de outras dependências externas.
  
  Em uma aplicação React do mundo real, é comum encontrar vários tipos de componentes distribuídos na aplicação, dentre os mais usados: componente de </br>
  classe e componente funcional sem estado.

  De modo prático, alguns componentes irão controlar o estado da aplicação e fazer chamadas em uma API externa para popular dados enquanto outros irão se </br>
  preocupar apenas com a renderização desses dados para o usuário.
  
  
 Basicamente um componente é uma função Javascript que retorna um HTML. Exemplo:

    function App() {

      return (
        <h1>Hello World!</h1>
      )
    }

    export default App
    
 Verifique acima que é necessário Exportar o componente para que seja possível utilizá-lo em outro lugar.
    
 Na aplicação React, utilizaremos a extensão JSX para todos os compoentes. JSX é JAVASCRIPT + XML *markup language*
 
 ❗ Importante ❗
 É uma boa prática, que todos os nomes de componentes iniciem com letra maiúscula, ou seja, App.jsx, Button.jsx e assim por diante.
 
 Após exportar *export default Post*, precisaremos importá-lo no App.jsx da seguinte forma:
      
      import Post from './Post';
      
 E para utilizá-lo no App.jsx, chamamos o componente como se fosse um HTML
  
      <Post/>
 
---

✖️

TO BE CONTINUED...

✖️


---
E isso foi o que eu aprendi hoje! :heavy_check_mark:
