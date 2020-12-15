#Github 

Escrevendo os comandos basicos do Git

-- Terminal --
git init -> inicializa git


Ciclo de vida dos Status dos arquivos

1 - Untracked
    - o arquivo acabou de ser adicionado no rep, mas o git não conhece ele no repositório

2- unmodified
    - Apos adicionado, ele existe no git, mas não teve modificação

3- modified
    -o arquivo existe, e foi modificado

4 - stage 
    - o arquivo vai para o controle de versão( ao fazer o commit os arquivos passam para o estado 2)


Comandos

git status - lista o estado do git no momento   
git add [nome do arquivo] - adiciona o arquivo para o git

git commit - Git cria uma imagem do pacote de alteraçãoes

git commit -m "mensagagem de envio "

git log - apresenta os logs de commit