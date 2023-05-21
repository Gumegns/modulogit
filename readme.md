Passos do git para memorizar

NB: Basicamento usa-se o git para monitorar. depois de condificar preciso dar adicionar alterações que foram feitas no meu sitema (ou projecto  que estou criando) e em seguida, comentar essas alterções para que possa melhorar o entendimento de quem está programando comigo o projecto ou para que eu saiba o que fou feito naquela novo monitoramento que adicionei ao git.

git status (Este comando mostra o status do meu projecto, algo de novo que chegou no git.)
git add -A (Ele adiciona todas alerações que foram feitas até alí no meu projecto)
git commit  -m (Este comando seguido de Aspas, usa-se para comentar a alterção feita no projecto e adicionando ao histórico do git)
     " o git add -A andam sempre juntos, assim que o usamos o comando '.. add -A' (Para adicionar alterações ao projecto) seguimos com o comando '.. commit -m' para comentar aquelas alterações para que possamos saber do que se trata aquele monitoramento "

-

O git é um sistema que vai monitorar meu projecto localmente e o github monitora virtualmente. A sincronização do GIT e GITHUB nos permite monitorar o projecto/sistema localmente e compartilhar virtualmente.

-

git reset  - O git reset é um comando que usa-se para apagar um monitoramento ou histórico de um commit. Basicamente ele funciona com três parâmetros 

    -git reset --soft (Volta para o estado antes do commit)
    -git reset --mixed (volta para o estado antes da adição das alterações no git)
    -git reset --hard (Apaga tudo que foi feito naquele has do commit)

- 

git branch -b (Cria um novo e já entra no novo branch)
git branch -d (Deleta um branch)

-

git diff (Este comando permite visualizar o que foi alterado no antes do commit)
git diff --name-only (Me mostra o nome dos arquivos que foram alteradas)
git diff nome-do-arquivo (Este comando me permite ver só alterações de um arquivo que foi alterado)

-

git remote add origin (Com este comado seguido da URL do seu repositório, adicionamos a origin no project)
git push -u origin (Usamos este comando seguido por nome de branch para empurar os arquivo do projecto no GIT para GITHUB)

