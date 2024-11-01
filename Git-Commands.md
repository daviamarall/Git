### 1. **Configuração**
- `git config`: Configura opções e variáveis do Git.
  - `git config --global user.name "Seu Nome"`: Define o nome do usuário globalmente.
  - `git config --global user.email "seuemail@example.com"`: Define o e-mail do usuário globalmente.
  - `git config --list`: Lista todas as configurações do Git.

### 2. **Criação de Repositório**
- `git init`: Inicializa um novo repositório Git.
- `git clone <url>`: Clona um repositório remoto para o local.

### 3. **Comandos Básicos de Controle de Versão**
- `git status`: Mostra o status dos arquivos no repositório.
- `git add <arquivo>`: Adiciona arquivos à área de stage.
- `git add .`: Adiciona todos os arquivos modificados à área de stage.
- `git commit -m "mensagem"`: Faz o commit das mudanças com uma mensagem.
- `git commit -am "mensagem"`: Adiciona e faz commit em uma única etapa.
- `git diff`: Mostra as diferenças entre o diretório de trabalho e a área de stage.
- `git diff <branch1> <branch2>`: Compara diferenças entre branches.

### 4. **Visualização de Histórico**
- `git log`: Exibe o histórico de commits.
- `git log --oneline`: Exibe o histórico de commits em uma linha por commit.
- `git log --graph`: Mostra o histórico de forma gráfica.
- `git show <commit>`: Exibe detalhes de um commit específico.

### 5. **Trabalhando com Branches**
- `git branch`: Lista as branches locais.
- `git branch <nome>`: Cria uma nova branch.
- `git checkout <branch>` ou `git switch <branch>`: Muda para uma branch existente.
- `git checkout -b <branch>` ou `git switch -c <branch>`: Cria e muda para uma nova branch.
- `git merge <branch>`: Faz o merge de uma branch com a branch atual.
- `git branch -d <branch>`: Deleta uma branch local.

### 6. **Sincronização com Repositórios Remotos**
- `git remote add origin <url>`: Adiciona um repositório remoto.
- `git push origin <branch>`: Envia commits para o repositório remoto.
- `git push`: Empurra todas as branches para o repositório remoto.
- `git pull`: Puxa e incorpora as mudanças de um repositório remoto.
- `git fetch`: Baixa dados do repositório remoto sem mesclar automaticamente.

### 7. **Manipulação de Commits**
- `git reset <arquivo>`: Remove um arquivo da área de stage.
- `git reset --soft <commit>`: Desfaz commits, mantendo as mudanças staged.
- `git reset --hard <commit>`: Desfaz commits e descarta as mudanças permanentemente.
- `git revert <commit>`: Reverte um commit específico, criando um novo commit.
- `git cherry-pick <commit>`: Aplica um commit específico em outra branch.

### 8. **Armazenamento Temporário**
- `git stash`: Armazena mudanças temporariamente.
- `git stash apply`: Aplica as mudanças armazenadas de volta ao diretório de trabalho.
- `git stash drop`: Remove as mudanças armazenadas.
- `git stash pop`: Aplica e remove as mudanças armazenadas.

### 9. **Tags e Versionamento**
- `git tag <nome>`: Cria uma tag leve.
- `git tag -a <nome> -m "mensagem"`: Cria uma tag anotada.
- `git push origin <tag>`: Envia uma tag específica para o repositório remoto.
- `git tag -d <nome>`: Deleta uma tag local.
- `git push origin --delete <nome>`: Deleta uma tag do repositório remoto.

### 10. **Comandos Avançados**
- `git rebase <branch>`: Reaplica commits da branch atual sobre outra branch.
- `git bisect`: Encontra o commit que introduziu um bug.
- `git blame <arquivo>`: Mostra quem modificou cada linha de um arquivo.
- `git reflog`: Mostra o histórico de referências do repositório.

### 11. **Ganchos (Hooks)**
- Configuráveis no diretório `.git/hooks` e podem automatizar tarefas como pré-commit (`pre-commit`), pós-commit (`post-commit`), etc.

### 12. **Outros Comandos Úteis**
- `git clean -f`: Remove arquivos não rastreados do diretório de trabalho.
- `git archive`: Cria um arquivo compactado de uma versão do projeto.
- `git mv <arquivo1> <arquivo2>`: Renomeia ou move um arquivo.

