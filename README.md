# Criando documentação para estudos do git

## O que é git?

## Como surgiu?

### Clonando um novo repositório 

```
git clone <endereço do repositorio>

git clone git@github.com:jaodochurros/git-estudos.git

```

### Vendo o status do repositório

Exibe status dos arquivos que estão en working dir e stage.

```
git status
```

### Iniciando um novo repositório

```
git init
```

### Adicionando ao stage

Git add adiciona o arquivo ao stage.

```
git add <nome do arquivo>
```

Adiciona todos os arquivos ao stage

```
git add . 
```

Adiciona todos os arquivos que termina com a extenção

```
git add *.txt
```

### Commitando um arquivo

Confirma alterações feitas no arquivo e adiciona um mensagem.

```
git commit -m 'mensagem do commit'
```

Adiciona os arquivos ao stage e confirma alterações feitas no arquivo e adiciona um mensagem.

```
git commit -am 'mensagem do commit'
```


### Subindo modificações

Sobe os arquivos para o repositorio.

```
git push origin master
```

### Baixando modificações

Baixa mudança\versões do repositorio remoto para o local. 

```
git pull origin master
```

### Criando uma branch

Crie um novo branch chamado "funcionalidade_x" e selecione-o usando

```
git checkout -b funcionalidade_x
```

### Navegando entre branches

```
git checkout master
```

### Removendo branch

```
git branch -d funcionalidade_x
```

### Visualisando alteraçõe feitas no arquivo

```
git diff
```

# Referências:
https://rogerdudler.github.io/git-guide/index.pt_BR.html