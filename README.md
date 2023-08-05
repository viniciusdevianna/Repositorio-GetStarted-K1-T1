# Acelera ZG
![Logo Zg Soluções](https://www.google.com/url?sa=i&url=https%3A%2F%2Fzgteam.gupy.io%2F&psig=AOvVaw01EStRY2PviBbfl26EFG5K&ust=1691349797225000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCOjx15WfxoADFQAAAAAdAAAAABAE)
**Projeto introdutório da trilha K1-T1**

***

## Comandos básicos de Git
Esta é uma lista com os 10 comandos básicos de _Git_ para iniciantes.

### git init

Inicia um novo repositório Git.
```
git init
```

### git clone

Cria uma cópia de um repositório git existente.
```
git clone https://github.com/{alguma-url}
```

### git add

Adiciona arquivos ao repositório, sejam eles novos ou arquivos modificados. Para adicionar todos os arquivos do local utilizamos _git add ._ .
```
git add .
```

### git commit

Salva as alterações nos arquivos que foram adicionados com o comando anterior no repositório e cria um novo ponto no histórico de versões.
```
git commit -m "Novo commit"
```

### git branch

Trabalha com ramificações no histórico de versões, podendo criar uma nova ramificação, listar as ramificações existentes, deletar ramificações, etc.
```
git branch branch_nova
```

### git checkout

Vai para um commit ou uma branch específicos em um histórico de versões.
```
git checkout branch_nova
```

### git push

Sobe as alterações locais para o repositório remoto.
```
git push origin main
```

### git pull

Puxa as alterações de um repositório remoto para o local.
```
git pull
```

### git fetch

Puxa as alterações de um repositṕrio, porém sem aplicar, para que o desenvolvedor possa analisar as mudanças antes de alterar seu histórico local.
```
git fetch
```

### git merge

Mescla uma ramificação à atual, tornando-as uma única _branch_.
```
git merge outra_branch
```

***