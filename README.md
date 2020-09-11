# informacoes
Repositório destinado as informações referente ao projeto integrador.

## GIT WORKFLOW - Design de fluxo de trabalho Git - Projeto Integrador

### ⚠️ Seguir para os repositório de back-end e front-end: ⚠️

- Ao realizar uma tarefa nomear sua branch no seguinte padrão:
````
seunome-tarefa-versao
````
exemplo:
````
giselly-construcaogitflow-1.0
````
<hr>

- Pois, caso precise alterar algo nessa tarefa depois de ja ter mandado para develop podera utilizar

exemplo:
````
giselly-construcaogitflow-1.1
````
<hr>

- Ao terminar o desenvolvimento utilize o seguinte comando para manter sua branch alinhada com a develop:
````
git pull origin develop
````
- Se houver conflitos os resolva e depois utilize os comandos:

````
git add .
````

````
git commit -m "Resolução de conflitos após merge master"
````
<hr>
- Após isso, abra o navegador no github e solicite um "Pull Request"

````
base: develop
source: suabranch
````
<hr>
- Após criar o PR enviar o link do PR para outro membro revisar e aprovar, assim nos mantemos alinhados.

<hr>
- Após aprovação do PR delete a sua branch.

