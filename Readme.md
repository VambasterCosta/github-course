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

git show [hash] -  apresenta detalhes de mudanças do commit escolhido

git diff - mostra as modificações do arquivo atual do ultimo commit

git diff --name-only -  mostra apenas os nomes dos aquivos que forma modificados

 git checkout [nome do arquivo] - reverte modificações antes de adicionar para o git

 git reset HEAD - retorna para o estagio anteriro a adição permitindo executar o arquivo acima.


 git reset --soft --mixed --hard [hash] - (reverte para o comit escolhido mas mantem as modificalções, para o estagio stage) (reverte para o comit escolhido mas mantem as modificalções, para o estagio modified) (Reverte tudo, bom pra fazer numa sexta feira no  fim do expediente."segura na mão de Deus e vai")


 git remote - apresenta o repositorio remoto que esta vinculado o projeto

 git clone [repositoiro remoto] - clona o projeto remoto para o diretório local