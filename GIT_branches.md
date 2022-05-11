<h2 style="text-align: center; font-weight: bold;">TILT 11/05/22</h2>

### Objeto do estudo: GIT

Este conhecimento foi adquirido durante meus estudos via DIO - Digital Inovation One - com a orientação do intrutor Otávio Reis Perkles

---

### Branches


```
Branch (ou ramificação) significa que você diverge da linha principal de desenvolvimento e continua a trabalhar sem alterar essa 
linha principal.
```
Ou seja, as branches são uma maneira de organizar o código. A branch Main (ou Master) tem a versão oficial do código, aquela que já está 
em uso pelo usuário final, por exemplo. Quando criamos uma branch, podemos fazer uma alteração em alguma funcionalidade sem afetar o Main, 
ou o usuário final. Ao finalizar este trabalho, podemos juntá-lo ao Main, com o Merge.

![image](https://user-images.githubusercontent.com/66280875/167962816-5c6d6c45-b82a-40b2-9481-34ba352b77e9.png)


### Tag HEAD

Há também a tag Head que aponta sempre para o último commit válido. É basicamente onde Você está localizado no fluxo de trabalho.

### Movimentação entre branches

Sabe como verificar em qual branch você está ou quantas branches existem no seu projeto? (Via gitBash)
Utilizamos o comando 
```
GIT BRANCH
```
Este comando irá te mostrar uma lista de branches do projeto e a marcada com * é a que você está no momento!
![image](https://user-images.githubusercontent.com/66280875/167963380-51a67e8d-924a-45fb-9a0b-2211c2143d26.png)

No exemplo acima, estou na branch baseDados

Para nos "movermos" entre as branches, utilizamos o comando:
```
GIT CHECKOUT
```
Por exemplo, ```GIT CHECKOUT master``` (me desloco para a branch master).

Pra retornar para a branch baseDados novamente utilizo o mesmo comando:
```GIT CHECKOUT baseDados ```

### ATENÇÃO

É necessário tomar cuidado com a movimentação entre a branches, pois se não for feito o "staged" dos arquivos que estão sendo trabalhados 
na branch, ao movimentar para outra branch, esses arquivos vão junto, podendo gerar um problema maior no final do desenvolvimento.
![image](https://user-images.githubusercontent.com/66280875/167963816-f959c6d2-16c1-40a1-bdb3-395bebc80e56.png)

Neste caso o meu VsCode identificou que eu não havia feito o commit das alterações e bloqueou minha movimentação para a branch Master.

---
E isso foi o que eu aprendi hoje! :heavy_check_mark:
