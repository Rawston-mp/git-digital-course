# Curso Digital: Git

# Cosfigurações
 git config --global user.name "Fulano de Tal"
 git config --global user.email "fulanodetal@exemplo.com"

# Primeiro commit
git add . && git commit -m "Primeiro commit" && git push -u origin main

## Gravando mudanças no repositório
### Git diff e commit
bash
git add .
git diff --staged
git commit -m "Mudanças no arquivo"

#### Git log e restore
bash
git log
git restore --staged arquivo.txt

#### Repositórios remotos
bash
git remote add origin https://github.com/fulanodetal/repositorio.git
git push -u origin main

## Salvando alterações no Git
git pull
git push
git fetch

### Git branch
bash
git branch nome-da-branch
git log --oneline --decorate   
git checkout nome-da-branch
