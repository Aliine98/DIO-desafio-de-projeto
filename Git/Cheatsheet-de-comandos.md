### Listar todas configurações
```bash
git config --list
```
### Definir nome
```bash
git config --global user.name [nome]
```
### Definir email
```bash
git config --global user.email [email]
```
### Iniciar repositório
```bash
git init
```
### Clona repositório
```bash
git clone [url]
```
### Mostra estado do diretório(arquivos modificados, untracked, unstaged, para serem comitados)
```bash
git status
```
### Cria branch
```bash
git branch [nome-da-branch]
```
### Renomeia branch
```bash
git branch -m [nome-antigo] [novo-nome]
```
### Move para a branch especificada
```bash
git checkout [nome-da-branch]
```
### Adiciona arquivos pra ser comitado
```bash
git add [arquivo]
```
```bash
git add .
```
### Remove arquivos do estado "staged"
```bash
git reset [arquivo]
```
### Faz o commit com mensagem
```bash
git commit -m "[mensagem]"
```
### Faz o merge de branchs (da especificada para a atual)
```bash
git merge [nome-da-branch]
```
### Adiciona repositório remoto
```bash
git remote origin[alias] [url]
```
### Puxa arquivos do repositório remoto
```bash
git pull
```
### Empurra arquivos da branch especificada para o repositório remoto
```bash
git push origin[alias] [nome-da-branch]
```
