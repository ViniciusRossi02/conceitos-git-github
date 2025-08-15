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

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lista de comandos que aparece no site.
**IMPORTANTE**: Depois do remote deve ser executados os outros 2 comandos da pagina.
```bash
    git remote add origin < url_repositorio_github >
```

Para verificar a situação do repositório (pasta) usamos o status a qualquer momento.

```bash
    git status
```

Prepara o arquivo para ser salvo.

```bash
    git add . 
```

Para salvar as modificações feitas.

```bash
    git commit -m "mensagem que deseja"
```

Para salvar as alterações que estão no Github utilizamos o pull <br>.
**IMPORTANTE**: sempre deve baixar a ultima versão da nuvem antes de enviar a atual do computador 

```bash
    git pull 
```
Para enviar os commits do pc para o GitHub utilizamos o push.

```bash
    git push 
```



