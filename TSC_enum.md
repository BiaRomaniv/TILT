<h2 style="text-align: center; font-weight: bold;">TILT 22/06/22</h2>

### Objeto do estudo: Typescript - Tipo Enum

Este conhecimento foi adquirido durante o Bootcamp Santander Fullstack Developer na Digital Inovation One com o especialista João Santos. 

---

### Enum

- O enum é um dos tipos do TypeScript que nos permite declarar um conjunto de valores/constantes pré-definidos.

Exemplo: 

  ```
  // crio o tipo enum Profissao, dessa forma, deixamos as escolhas padrão para as profissões da lista
  enum Profissao {
    Atriz,
    Padeiro,
    Engenheiro
  }
  // crio o tipo Humano para declarar algumas propriedades
  type Humano = {
    nome: string,
    idade: number,
    profissao: Profissao
  }
  // assim ao criar o primeiro item com essas propriedades, posso selecionar a profissao corretamente
  let pessoa: Humano = {
    nome: 'Maria',
    idade: 25,
    profissao: Profissao.Atriz // seleciono conforme a lista enum criada acima
  }
  ```

#### Enum numérico

- Os enums numéricos armazenam strings com valores numéricos.Note que nesse enum acima nós não declaramos os seus valores. 
- Os enums numéricos são auto increment, se não for colocado valor, o primeiro assume valor 0, o segundo assume valor 1 e assim por diante.
- Podem ser indicados valores aleatórios, ou a partir de valores acima de 0 também.

    ```
    export enum DiaDaSemana {
        Segunda = 1,
        Terca = 2,
        Quarta = 3,
        Quinta = 4,
        Sexta = 5,
        Sabado = 6,
        Domingo = 7,
    }
    ```
    
  Para acessar o enum numérico, podemos acessar pelo seu valor ou pela sua declaração:
  ```
  let dia = DiaDaSemana[1]; // Segunda
  let diaNumero = DiaDaSemana[dia]; // 1
  let diaString= DiaDaSemana["Segunda"]; // 1
  ```
  
  
  ---
...to be continued...
