<h1>Sistema de cadastro de jogos</h1>

>Status do projeto: Em desenvolvimento

Para rodar esse projeto na sua máquina, por favor digite:
```
node app.js
```

#Comandos git

Visualizar todos os commits, um em cada linha com o comando:
```
git log --oneline
```
Se, em vez de menos informações, quisermos ver mais como as alterações do commit, podemos usar:
```
git log -p
```
Também podemos pesquisar as informações do autor daquele commit com o comando:
```
git log --author="user_name"
```
E pesquisar informações por data:
```
git log --since=1.month.ago --until=1.day.ago
```
No comando acima, estamos buscando as informações do commit desde um mês atrás até um dia atrás.

Você também pode formatar a visualização das informações de commit com o comando:
```
git log --pretty="format:%h %s"
```
Para fazer o commit de alguma alteração:
```
git commit nome_do_arquivo.ex -m "mensagem de commit
```
Para fazer commit de todo o código trocar o nome do arquivo por um ponto. Ex:
```
git commit . -m "mensagem de commit
```
Depois de fazer o commit você deve mandar o código pro repositório usando o comando:
```
git push
```
Para verificar se teve alterações no repositório local ou remoto, usar o comando:
```
git status
```
Para trazer alterações do repositório remoto pro repositório local usar o comando:
```
git pull
```