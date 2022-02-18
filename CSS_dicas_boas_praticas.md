<h2 style="text-align: center; font-weight: bold;">TILT 17/02/22</h2>

### Objeto do estudo: CSS/HTML

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### Boas práticas de acessibilidade 
        
#### O que é acessibilidade na web?
        De acordo com a W3c, a acessibilidade na Web serve como auxílio para sites, ferramentas e tecnologias serem projetados 
        e desenvolvidos para que pessoas com ou sem deficiência possam usar, navegar, interagir e entender o conteúdo, com autonomia.

Sabendo esse conceito, devemos sempre aplicar ao máximo as boas práticas de programação para que atendam o mínimo dos requisitos </br>
de acessibilidade.

Uma dica de acessibilidade é utilizar a classe "sr-only" (ou, screen only).  
```
  "sr-only" means "this content is visible only to screen readers" . The .sr-only content is meant to aid users without vision.
```
Essa classe dá a possíbilidade do conteúdo estar presente na tela, porém sem estar aparente. Sendo utilizada apenas por leitores de tela.
É uma solução para ser aplicada em labels de textareas, inputs e outros elementos que solicitem uma ação do usuário.
Exemplo:

```
"<form action="">
        <label class="sr-only" for="room-id">Código da Sala</label>
        <input type="number" placeholder="Código da sala" id="room-id">
        <button>
          <img src="assets/enter-room.svg" alt="Entrar na sala">
          Entrar na Sala
        </button>
</form>"
```
Para tratá-la dentro do CSS utilizaremos a seguinte sequência de propriedades:

```
.sr-only {
    position: absolute;
    height: 1px;
    width: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip-path: rect (0,0,0,0);
    white-space: nowrap;
    border-width: 0;   
}
```
 - Position: absolute -> essa propriedade deixa o elemento sobreposto a todos os outros, ele não pertence a mais nenhuma div ou section. </br>
 - Height e Width: 1px -> nesse valor o elemento vai ocupar apenas 1px da tela.</br>
 - Padding: 0 -> zeramos o padding para não ficar espaço em torno do elemento.</br>
 - Margin: -1px -> essa margem negativa, com o conjunto do Clip-path (0,0,0,0) irá deslocar o elemento para fora da tela no canto esquerdo superior.</br>
 - Overflow: hidden -> significa que não haverá possibilidade de rolagem no elemento.</br>
 - White-space: nowrap -> Recolhe os espaços em branco e suprime as quebras de linha no texto.</br>
 - Border-width: 0 -> largura de borda zerada</br>

---

E isso foi o que eu aprendi hoje! :heavy_check_mark:

