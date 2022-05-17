<h2 style="text-align: center; font-weight: bold;">TILT 16/05/2022</h2>

### Objeto do estudo: GITHUB Branches

Este conhecimento foi adquirido durante estudos via Digital Inovation One com a colaboração do especialista Otávio Reis Perkles. 

---

### Git Reset 

```
O comando reset é um dos comandos mais poderosos e ao mesmo tempo um dos menos indicados por muitos usuários Git. 
O principal motivo é o receio de que as alterações sejam perdidas de forma irreversível. 
Ocorre que muitos desses usuários não sabem que há mais de um tipo de reset, e não apenas o reset hard, 
que é o que deve ser utilizado com mais cuidado e, porém, o mais comum. Neste tutorial, veremos que, sabendo 
diferenciar os tipos de reset e utilizar o tipo mais adequado, não há nada com o que se preocupar.

[https://medium.com/@andgomes/os-tr%C3%AAs-tipos-de-reset-aa220658d9b2]
```

Com esse comando, podemos:
* apagar o último commit executado, 
* retornar o que foi adicionado para o commit de volta para a staging area, 
* ou retornar todas as alterações para o working directory.

Com o git reset + a hash do commit selecionado, apagamos o commit. (será feito o método --hard)
Com o git reset HEAD~1, vamos até o ponteiro HEAD e apagamos 1 commit atrás. Voltaremos o commit de acordo com o número após o ~.
Com o git reset --soft, não apagamos o commit, apenas retornamos as modificações para o staging area (ou seja, retira a mensagem de commit e deixa preparado para o proximo)
Com o git reset --mixed (se nada for escrito esse é o padrão), retorna para o working directory (ou seja, os arquivos retornam para a situação anterior aos commits e adds)
Com o git reset --hard, apagamos o último commit. (Crítico)


### Git Revert

O git revert adiciona um novo commit revertendo o que foi feito no commmit selecionado.

---
E isso foi o que eu aprendi hoje! :heavy_check_mark:
