# Minha experiencia com Git

## Init Config

```
git config --global user.name <NAME>
git config --global user.email <EMAIL>
git config --global init.defaultBranch main
git config --global credential.helper store | git config --global credential.helper cache
git config --global core.editor <CODE_EDITOR>
```

## Clonar Repo

```
git clone <URL> <NAME_FOLDER>
git clone <URL> --branch <BRANCH> --single-branch
```

## Init Repo

```
git init
git status
git add <FILE> | git add .
git commit -m "Message"
git log
```

## Remote Repo

```
git remote -v
git remote add origin <REPO_URL>
git push -u origin main
git pull
```

## Changes Repo

```
git restore <FILE>
git commit --ammend -m "Message" | git commit --ammend
git rest <HASH/FILE> | git reset --soft <HASH> | git reset --mixed <HASH/FILE> | git reset --hard <HASH>
git reflog
```

## Branch Management Repo

```
git checkout -b <NEW_BRANCH> | git checkout <BRANCH>
git branch | git branch -v
git merge <ALT_BRANCH>
git branch -d <DEL_BRANCH>
git fetch origin <BRANCH>
git diff main origin/main
git stash | git stash list | git stash pop | git stash apply
```

## Commit Organization
### Credits: [Antoni Matheus](https://www.linkedin.com/posts/antonimatheus_git-commits-django-activity-7373373792015761408-jjRy?utm_source=share&utm_medium=member_desktop&rcm=ACoAAElQtnwBLzO4_IbxPXU_4NWcZqvHBuVWPfY)

```
feat: Nova funcionalidade
fix: Correção de bugs
docs: Alterações apenas na documentação
style: Alterações de estilo em geral
test: Criar ou ajustar testes
ci: Alterações em pipelines de CI/CD
chore: Tarefas de infra, deps, scripts, configs
build: Alterações em sistema de build
perf: Melhorias de perfomance real
```

## Knowledge

```
.gitignore: ignora arquivos/pastas de um repositorio
.gitkeep: reconhecer diretorio mesmo que nao tenha nenhum arquivo
rm -rf .git: desfazer git init
```

## References

[DIO.ME REPO](https://github.com/elidianaandrade/git-github-learning-quest)
[DIO.ME SLIDES](https://hermes.dio.me/files/assets/7ba5b596-708a-4b6f-882f-e1114b869fb5.pptx)

