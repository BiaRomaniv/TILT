<h2 style="text-align: center; font-weight: bold;">TILT 02/08/2022 <h2>

### Objeto do estudo: REACT

Este conhecimento foi adquirido durante o Bootcamp Ignite da Rocketseat https://www.rocketseat.com.br/ 🚀 sob a orientação indireta do Instrutor Diego Fernandes.

---

### Criando um projeto React com Vite
  
```Vite is a build tool that aims to provide a faster and leaner development experience for modern web projects```

  Para iniciarmos um projeto React, antes de mais nada é necessária a intalação do Node.js (https://nodejs.org/en/). </br>
  :exclamation: Recomenda-se instalar a versão LTS.
 
  O Node.js pode ser definido como um ambiente de execução Javascript server-side.
  Isso significa que com o Node.js é possível criar aplicações Javascript para rodar como uma aplicação </br>
  standalone em uma máquina, não dependendo de um browser para a execução, como estamos acostumados.
  
  Com o node instalado, já podemos iniciar o projeto React com Vite. Seguindo a sequencia abaixo:
    
  * npm create vite@latest

  * npm install
  
  * npm run dev

  A partir deste último comando, a aplicação React+Vite já estará rodando na porta disponível.
  
  Uma das vantagens do uso do Vite, é o fast refresh. Significa que as alterações feitas durante o desenvolvimento, são
 automaticamente espelhadas no browser de maneira rápida, sem necessidade de atualizar a página.
 
 ---
 
 Com essa aplicação padrão que foi criada, já podemos ter uma idéia dos conceitos do React e componentes.
![image](https://user-images.githubusercontent.com/66280875/182729827-18a2706e-c412-4872-9c3d-b699ab478751.png)
 
 ---
 
 Veja abaixo a ordem de criação do projeto React com Vite, conforme aparece no terminal.
 
 :exclamation: Comando para criar o projeto com o Vite
 
      npm create vite@latest   
      npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead.
      √ Project name: ... vite-project
      √ Select a framework: » react
      √ Select a variant: » react
      
:exclamation: No terminal após a instalação ele já sugere os próximos passos:

    Done. Now run:

    cd vite-project
    npm install
    npm run dev

:exclamation: Entrando na pasta do projeto criada, digitamos o comando NPM INSTALL para que todas os pacotes sejam instalados automaticamente.

    npm install
    npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead.

    added 86 packages, and audited 87 packages in 26s

    8 packages are looking for funding
      run `npm fund` for details

    found 0 vulnerabilities
    
 :exclamation: Agora já podemos iniciar o projeto com o comando NPM RUN DEV
 
      npm run dev
      npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead.

    > vite-project@0.0.0 dev
    > vite

      VITE v3.0.4  ready in 931 ms

      ➜  Local:   http://127.0.0.1:5173/
      ➜  Network: use --host to expose
 
 :exclamation: Podemos clicar no endereço exibido acima, com a porta correspondente, e temos uma aplicação exemplo já em funcionamento no browser.
 
  ![image](https://user-images.githubusercontent.com/66280875/182728892-4cc4dffb-16fc-42b6-8355-f9359041c562.png)
 
---
E isso foi o que eu aprendi hoje! :heavy_check_mark:
