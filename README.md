# Resumo de Git e GitHub

Repositório para armazenar resumos sobre Git e Github.

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/en)

## 📝 Comandos

### ⚙️ Configuração

| Comando | Função |
| ----- | ------- |
| git init | Inicializa um repositório git |
| git clone ___URL___ ___repoName___ | Clona um repositório remoto com um nome de sua escolha|
| git clone ___URL___ --branch ___branchName___ --single-branch | Clona um repositório remoto com uma branch específica |
| git remote -v | Lista os repositórios remotos |
| git remote add ___name___ ___URL___ | Adiciona um repositório remoto |

### ✅ Salvando alterações

| Comando | Função |
| ----- | ------- |
| git add ___file___ | Adiciona um arquivo ao stage |
| git add . | Adiciona todos os arquivos ao stage |
| git commit -m "___message___" | Salva as alterações no repositório local |

### ❌ Desfazendo alterações

| Comando | Função |
| ----- | ------- |
| git restore ___file___ | Desfaz as alterações de um arquivo |
| git restore --staged ___file___ | Remove um arquivo do stage |
| git commit --amend -m "___message___" | Altera a mensagem do último commit |
| git commit --amend | Adiciona arquivos ao último commit |
| git reset --soft ___hash___ | Desfaz o último commit, mas mantém as alterações |
| git reset --mixed ___hash___ | Desfaz o último commit e mantém as alterações como untracked (comportamento padrão do git reset) |
| git reset --hard ___hash___ | Desfaz o último commit e as alterações |
| git reset ___file___ | Remove um arquivo do stage |

### ⬆️ Atualizando repositório remoto

| Comando | Função |
| ----- | ------- |
| git push (-u / --set-upstream) ___remote___ ___branch___ | Envia as alterações para o repositório remoto |

### ⬇️ Atualizando repositório local

| Comando | Função |
| ----- | ------- |
| git pull ___remote___ ___branch___ | Atualiza o repositório local com as alterações do repositório remoto |
| git fetch ___remote___ ___branch___ | Atualiza o repositório local com as alterações do repositório remoto, mas não faz merge |


### 🔎 Monitorando alterações

| Comando | Função |
| ----- | ------- |
| git status | Mostra o status do repositório |
| git log | Mostra o histórico de commits |
| git reflog | Mostra o histórico de commits e operações |
| git diff ___localBranch___ ___remoteBranch___ | Mostra as diferenças entre duas branches |

### 🌳 Branches

| Comando | Função |   
| ----- | ------- |
| git branch | Lista as branches |
| git branch -v | Lista as branches com os últimos commits |
| git branch -d ___branchName___ | Deleta uma branch |
| git checkout ___branchName___ | Muda para uma branch |
| git checkout -b ___branchName___ | Cria uma nova branch e muda para ela |
| git merge ___branchName___ | Faz o merge de uma branch com a branch atual |



## 📁 Arquivos/Pastas específicos do Git

- .git - Pasta que contém todos os arquivos e metadados do git.

- .gitignore - Arquivo que contém os arquivos e diretórios que devem ser ignorados pelo git.

- .gitkeep - Arquivo que permite manter diretórios vazios no git.

## 🔀 Atalhos

"." (na página do repositório no Github) - Abre editor de código no navegador.


