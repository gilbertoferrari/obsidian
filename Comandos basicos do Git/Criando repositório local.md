
## Configurações iniciais
```bash
git config --global user.name <seu nome>
git config --global user.email <seu email>
git config --global init.defaultBranch main
```

## Iniciando um repositório 

```bash
mkdir obsidian
cd obsidian
git init
echo "# Repositório para arquivos do Obsidian" > README.md
git add README.md
git commit -m "Primeiro commit"
```

## Conectando repositório local com um repositório remoto

```bash
git remote add origin https://github.com/gilbertoferrari/obsidian.git
git push -u origin main
```

