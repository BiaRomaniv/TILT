<h2 style="text-align: center; font-weight: bold;">TILT 16/02/22</h2>

### Objeto do estudo: CSS

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### Unidades relativas no CSS

Para definir a largura de um elemento, o tamanho do texto, a espessura da borda e outras coisas, o padrão mais utilizado é o pixel.
Porém o pixel é uma medida fixa, isso quer dizer que, mesmo que eu mude o tamanho do navegador, os elementos permanecerão com aquele tamanho definido. O que para termos de responsividade, não é o mais coerente.

Podemos resolver essa questão de maneira simples, utilizando a unidade rem ("root em"), que é o tamanho de fonte do elemento-raiz do documento. Ou seja, 1 rem é igual a uma quantidade de pixel padrão do navegador - User Agent - (no caso, 16px). 

E como nós utilizamos essa unidade?
Como ela é relativa, precisamos calcular conforme a quantidade de pixels que desejamos.
```
Por exemplo, no modelo enviado pelo designer feito no Figma, temos que o título da página inicial tem o tamanho de 28px.
```

![2022-02-16 (2)](https://user-images.githubusercontent.com/66280875/154378441-deb3c164-6192-4400-a8aa-218c5080cb37.png)

```
Para que eu chegue no valor em rem preciso dividir 28px por 16px, totalizando 1.75rem.
Dessa forma eu poderia usar o font-size: 1.75rem;
```
Mas, para todo valor eu vou precisar fazer essa conta na calculadora?</br>
Calma...</br>

A nossa instrutora Jakeliny deu o "pulo do gato" nesta situação. 
Vejamos como facilitar essas contas:

Se 16px equivalem a 100% da font-size do navegador padrão, vamos buscar quanto vale 10px em %? </br>

Com uma regra de três simples:
  ```     
        16px - 100%
        10px - X
        
        16X = 100*10
        
        X = 1000/16
        
        X = 62,5%
  ```
Não entendeu nada? </br>
Calma...</br>

Se no nosso CSS Global (aquele que será padrão para toda a aplicação), estipularmos que a partir de agora o valor padrão da font-size é 62,5% (ou seja, 10px), basta sempre dividirmos o valor que queremos por 10! </br>
Ou seja, os mesmos 28px do nosso Figma, seriam agora 28/10 = 2.8rem </br>

<i> Então, você só precisa entender que para utilizar a medida relativa rem, no CSS global defina font-size: 62,5%; e no restante já pdoemos utilizar tudo como se o padrão fosse 10px.</i>

E assim fica muito mais fácil utilizar dessa forma, já dividir por 10 é muito mais fácil do que por 16, não é mesmo? :sweat_smile:

---

E isso foi o que eu aprendi hoje! :heavy_check_mark:


