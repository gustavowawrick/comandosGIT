## Cria um arquivo README.md com o título do repositório
```
echo "# comandosGIT" >> README.md
```

## Inicializa um novo repositório Git
git init

## Adiciona o README.md ao índice
git add README.md

## Cria o primeiro commit
git commit -m "first commit"

## Renomeia a branch padrão para 'main' (caso não seja 'main' já)
git branch -M main

## Adiciona o repositório remoto do GitHub
git remote add origin https://github.com/gustavowawrick/REPOSITORIO

## Envia os commits para o repositório remoto
git push -u origin main
