# Minha experiencia com Git

## Init Config

```
git config --global user.name <NAME>
git config --global user.email <EMAIL>
git config --global init.defaultBranch main
git config --global credential.helper store
git config --global core.editor <CODE_EDITOR>
```

## Clonar Repo

```
git clone <URL> <NAMEFOLDER>
git clone <URL> --branch <BRANCH> --single-branch
```

## Init Repo

```
git init
git status
git add <FILE> | git add .
```

## Remote Repo

```
git remote -v
git remote add origin <URL>
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
