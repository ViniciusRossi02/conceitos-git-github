# Conceitos de Git e Github 
Este arquivo tem como objetivo armazenar os comandos báiscos para utilização de git e Github

# Configuração inicial
Rode os comandos abaixo no terminal(cmd) do seu computador

```bash
git config --global usar.name "Vinicius Rossi"

git config --global user.email rossivini1010@gmail.com
```

## Comando do Git 
Para iniciar o GIT em uma pasta do computador utiizamos o init.
**IMPORTANTE**: Só é executado uma vez.

```bash
    git init 
```

Para verificar a situação do repositório (pasta) usamos o status a qualquer momento.

```bash
    git status
```

Prepara o arquivo para ser salvo

```bash
    git add . 
```

Para salvar as modificações feitas

```bash
    git commit -m "mensagem que deseja"
```

Para enviar ao Github as adicições ou midificações 

```bash
    git push origin main/master
```
