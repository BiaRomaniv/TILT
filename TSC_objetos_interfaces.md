<h2 style="text-align: center; font-weight: bold;">TILT 21/06/22</h2>

### Objeto do estudo: Typescript

Este conhecimento foi adquirido durante o Bootcamp Santander Fullstack Developer na Digital Inovation One com o especialista
João Santos. 

---

### Typescript

- É um superset do Javascript;
- Compila para JS;
- Adiciona Features.
```
Porque usar TS?
  - Adiciona definição estática de tipos (TIPAGEM);
  - Funcionalidades no código mais explícitas;
  - Maior segurança durante o desenvolvimento (Tipo certo);
  - Detecta erros durante a compilação que só seriam percebidos em execução no JS puro;
  - Compila um JS mais resiliente;
  - Ajuda a desenvolver boas práticas de programação.
```
### Everyday Types

```
JavaScript has three very commonly used primitives: string, number, and boolean. 
Each has a corresponding type in TypeScript. As you might expect, these are the same names 
you’d see if you used the JavaScript typeof operator on a value of those types:

      string represents string values like "Hello, world"
      number is for numbers like 42. JavaScript does not have a special runtime value for integers, 
        so there’s no equivalent to int or float - everything is simply number
      boolean is for the two values true and false
 ```
 
 - Object Type;
 - Array Type;
 - Enun Type;
 - Any Type;
 - Void Type;
 - Function Type;
 - List Type...

### Formas de representar em TS um objeto :
  ```
  // os tipos estão implícitos, code é Number e name é String
    let employee = {
      code: 10,
      name:"John"
    };
  ```
  OU
  ```
  // os tipos estão explícitos
    let employee2 : {code: number; name: string} = {
      code: 10,
      name:"John"
    };
  ```
  OU
  ```
    interface Employee {
    code: number; 
    name: string
    }
    // criamos o tipo Employee e utilizamos na const funcionario
    const funcionario : Employee = {
    code: 10,
    name:"John"
    }
    // ou podemos utilzar desta forma
    const funcionarioObj = {} as Employee;
      funcionarioObj.code = 10;
      funcionarioObj.name = 'João';
  ```
  
  Após alterar o editor app.ts, no terminal utilizamos o comando TSC para compilar.
---

E isso foi o que eu aprendi hoje! :heavy_check_mark:
