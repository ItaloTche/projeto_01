# Projeto 01

Este é meu primeiro projeto em **Git** e **Github**.

- Instruções básicas sobre o Git / Github (Git):
    * Ao iniciar um projeto, criar o **"repositório"** na pasta que fica o projeto na sua máquina. Para isso, utilizar, no terminal, o comando ***git init***. Seria um repositório por pasta (projeto)
    * Agora faz-se necessário colocar as credencias para conexão junto ao "Remote" do Github. Para isso, utilizar o terminal e digitar os comandos: 1. ***git config --global user.name 'Seu Fulano'*** (isso já deixa credenciado para todos os projetos / para o caso de credenciar apenas esse projeto, retirar o "--global") e 2. ***git config --global user.email 'o email cadastrado na conta do Github'*** (aqui o "--global" tem a mesma finalidade do user)
    * O comando ***git status***, como o nome diz, mostra o status de infomrações variadas do projeto.
    * O comando ***git ls*** lista os arquivos desse projeto/repositório
    * O comando ***git add arquivo*** faz com que o arquivo passe a ser "trackeado". Para adicionar na "stage" todos os arquivos de uma vez, utilizar o comando ***git add .***
    * O comando ***git commit -m "comentário"*** adciona os "commit's" que são os comentários informativos quando o arquivo é alterado
    * Caso esteja na **branch** "master", alterar para "main" usando o comando ***git branch -M main***
    * Adcionar o caminho, no Git, do repositório criado no Github. Para isso usar o comando, informado ao criar, ***git remote add origin https://github.com/user.name/caminhodorepositoriocriado***. O termo "origin" seria o apelido, que pode ser qualquer coisa, dado ao repositório local. Por padrão, e boas práticas, é chamado de "origin"
    * Para incluir os arquivos "commitados" no Github, é necessário realizar o "push" utilizando o comando ***git push -u origin main***. Esse "-u" faz-se necessário na primeira vez que é feito o login. Depois não é mais necessário nesse repositório, mas, por boas práticas, é bom sempre informar
    * Sempre que preciar carregar os arquivos adicionados à stage e "commitados", faz-se necessário usar o comando "push" (***git push origin main***)
    * Comando para mudar de **"branch"** é o ***checkout***, mas usando "-b" em seguida, implica na criação de uma nova **"branch"**. Dessa forma ficaria ***git checkout -b 'nova_branch'***
- Instruções básicas sobre o Git / Github (Github):
    * Criar um repositório onde será informado o nome e descrição, como boas práticas
    * Add "Readme" apenas se já não tiver feito no Git
    * É dado o caminho do repositório no Github para que seja vinculado ao repositório do Git
    * Feito o login com o "push" é aberto uma pagina para efetuar o logon no portal Github