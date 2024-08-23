# avaliacao-jp
# avaliacao-jp
git config --global user.name "Seu Nome"
Define o nome do usuário para commits. A opção --global aplica essa configuração a todos os repositórios no sistema.

git config --global user.email "seuemail@exemplo.com"
Define o e-mail do usuário para commits. Assim como o anterior, a opção --global aplica a todos os repositórios.

git config --global core.editor "editor"
Define o editor de texto padrão para mensagens de commit (substitua "editor" pelo editor desejado, como nano, vim, etc.).

git config --global color.ui auto
Habilita a exibição de cores nos comandos Git.

git config --global alias.cm commit
Cria um atalho para o comando commit, permitindo que você use git cm no lugar de git commit.

Comandos do Git
git init
Cria um novo repositório Git.

git clone <url>
Clona um repositório remoto para o seu ambiente local.

git status
Mostra o status dos arquivos no repositório, incluindo arquivos modificados, não rastreados, etc.

git add <arquivo>
Adiciona alterações de arquivos ao índice para serem incluídas no próximo commit.

git commit -m "Mensagem do commit"
Registra as mudanças no repositório com uma mensagem de commit.

git push
Envia as alterações locais para o repositório remoto.

git pull
Atualiza o repositório local com as alterações do repositório remoto.

git fetch
Baixa as alterações do repositório remoto, mas não as aplica imediatamente.

git branch
Lista todas as branches no repositório. Usado com um nome para criar uma nova branch: git branch <nome-da-branch>.

git checkout <branch>
Muda para a branch especificada.

git merge <branch>
Mescla as mudanças de outra branch na branch atual.

git rebase <branch>
Aplica as mudanças de uma branch sobre outra. É uma maneira de manter um histórico mais limpo.

git log
Exibe o histórico de commits.

git diff
Mostra as diferenças entre as alterações no seu repositório.

git reset <arquivo>
Remove um arquivo do índice, mas mantém as mudanças no diretório de trabalho.

git rm <arquivo>
Remove um arquivo do diretório de trabalho e também do índice para o próximo commit.

git stash
Salva temporariamente alterações não comitadas para que você possa trabalhar em outra coisa.

git stash pop
Aplica as alterações que foram salvas anteriormente com git stash.


git cherry-pick <commit>
Aplica um commit específico de uma branch diferente na branch atual.

git tag <nome-da-tag>
Marca um commit específico para identificar versões (normalmente usado para versões de lançamentos).

git remote
Gerencia repositórios remotos. Por exemplo, git remote add origin <url> adiciona um repositório remoto.

git show <commit>
Exibe detalhes sobre um commit específico.

git blame <arquivo>
Mostra quem modificou cada linha de um arquivo e em qual commit.

git reflog
Mostra um log das referências de todos os movimentos anteriores de HEAD, útil para recuperar commits perdidos.