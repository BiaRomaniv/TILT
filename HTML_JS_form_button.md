<h2 style="text-align: center; font-weight: bold;">TILT 08/03/22</h2>

### Objeto do estudo: Javascript / HTML

Este conhecimento foi adquirido durante a NLW - Trilha Discover com a instrutora [Jakeliny Gracielly](https://github.com/jakeliny). 

---

### form method="POST"

   Aprendi que um formulário com o Method POST para que receba o valor digitado pelo usuário e envie corretamente para o banco, utilizando </br>
   o req.body.password, necessariamente o seu botão de envio, precisa do type SUBMIT. Sem o type, o password do meu formulário estava undefinded.
   Desta forma, o banco não entendia o dado enviado e gerava o seguinte erro no terminal:
   
       node:internal/process/promises:246
              triggerUncaughtException(err, true /* fromPromise */);
              ^

    [Error: SQLITE_ERROR: no such column: undefined] {
      errno: 1,
      code: 'SQLITE_ERROR'
    }
    [nodemon] app crashed - waiting for file changes before starting...
    
    
   Pelo console.log consegui identificar que estava undefined:
   
         console.log(pass)
         
         undefined
   
   Alterado o HTML do botão :
   
               <section>
                    <h2>Crie sua própria sala</h2>
                    <form action="/create-room" method="POST">
                        <label class="sr-only" for="room-pass">Insira uma senha</label>
                        <input type="password" name="password" id="room-pass" placeholder="Insira uma senha" >
                       
                       <button type="submit"> // ALTERAÇÃO REALIZADA PARA TYPE SUBMIT
                       
                            <img src="/images/enter-room.svg" alt="Entrar na sala">
                            Criar Sala</button>
                    </form>
                </section>
                
     
---
E isso foi o que eu aprendi hoje! :heavy_check_mark:
