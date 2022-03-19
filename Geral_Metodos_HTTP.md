<h2 style="text-align: center; font-weight: bold;">TILT 19/03/22</h2>

### Objeto do estudo: Métodos HTTP

Este conhecimento foi adquirido durante o desenvolvimento de um projeto pessoal. 

---

### Métodos HTTP
    O protocolo web HTTP (Hypertext Transfer Protocol) é a forma mais popular de receber e enviar arquivos e informações. 
    Esse protocolo é utilizado principalmente em softwares e serviços que precisam de dados que não podem ser alocados na 
    aplicação local do usuário, sendo assim necessário armazenar em um servidor, e então, por meio do HTTP, o software 
    cliente irá requisitar e exibir essas informações.
  
  Existem dois conceitos fundamentais que englobam e sustentam o funcionamento do protocolo: requisição e resposta:
          
    Requisição: Na requisição, é onde será feito o envio e/ou a requisição de dados para o servidor. 
    Por exemplo, enviar o login e a senha de um usuário e o servidor retornará através da Resposta se aquele usuário é válido 
    ou não. 
    
    Resposta: A resposta do servidor servirá apenas para orientar a camada de cliente (frontend). 
    Sempre que uma requisição é feita, a resposta é separada em duas partes, uma é composta pelo Http Status Code, que são 
    códigos para definir o sucesso ou a falha de uma operação e a outra pelo corpo da resposta, que contém os arquivos e
    dados solicitados. Por exemplo, caso você esteja executando um GET para uma lista de usuários, o corpo da requisição 
    retornará essa lista em formato JSON.
    
   
   ![image](https://user-images.githubusercontent.com/66280875/159131203-8449a899-d985-4ab3-ad62-0b3a21dc0232.png)

 ### Método GET
    Tem a função de solicitar ou requisitar algum recurso ao servidor. 
    É geralmente usado para o retorno de informações sobre uma entidade especificamente ou uma lista delas.
    
 ### Método POST
    Método usado para enviar informações ao servidor, é utilizado de forma mais popular em cadastros de dados retirados 
    de um formulário, e também quando enviamos um arquivo para o servidor: seja isso uma foto de perfil, um post no 
    Instagram, tudo isso é usado o método POST.
    
 ### Método PUT
    O PUT é responsável por editar arquivos e informações já existentes. Esse método usa-se juntamente com um parâmetro 
    na URL da requisição, que ajudará a identificar através de uma chave única (id) qual elemento ele está referenciando.
    
 ### Método DELETE
    Esse método é bem autoexplicativo, deleta arquivos ou informações presentes no banco de dados. Igual o PUT, 
    é recomendável que utilize-o usando um parâmetro na URL da requisição, para que evite problemas de deletar dois 
    arquivos/informações ao mesmo tempo.
---

    Fonte: https://medium.com/@renejr03/m%C3%A9todos-http-quais-s%C3%A3o-e-qual-a-funcionalidade-deles-491b1cc5d5b4

---

E isso foi o que eu aprendi hoje! :heavy_check_mark:
