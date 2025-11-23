# PROJETO INTEGRADOR PART II

Pequeno projeto web com `index.html`, pasta `src` e recursos em `img/`.

## Objetivo
Colocar este projeto no GitHub e compartilhar o código.

## Passos recomendados (Windows / PowerShell)

1) Instalar Git (se ainda não):

- Baixe e instale Git para Windows: https://git-scm.com/download/win

2) (Opcional) Instalar GitHub CLI `gh` para criação automática do repositório:

- https://cli.github.com/

3) Inicializar repositório local e push para GitHub (comandos):

```powershell
cd "C:\Users\Gabriel Angelino\PROJETO INTEGRADOR PART II"
# inicializa
git init
# adiciona todos os arquivos
git add .
git commit -m "Initial commit"
# garante que a branch principal se chame main
git branch -M main

# opção A: criar repositório com GitHub CLI (recomendada se tiver gh autenticado):
# gh repo create NOME-DO-REPO --public --source=. --remote=origin --push

# opção B: criar repositório no GitHub via web, então conectar remote e enviar:
# git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPO.git
# git push -u origin main
```

4) Depois de subir, verifique no GitHub se os arquivos aparecem.

## Observações
- Se preferir, eu posso gerar o comando `gh repo create` pronto, ou instruções passo-a-passo para criar o repo no site do GitHub.
- No momento o `git` não está disponível neste ambiente; siga os passos acima localmente e me diga se quer que eu gere o comando `gh` ou faça outros ajustes.
