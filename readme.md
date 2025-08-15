# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos basicos para utilização de git e Github

## Configuraçao inicial
Rode os comandos abaixo no terminal do seu computador.
```bash
git config --global user.name "Joao Vitor Freitas de Sousa"

git config --global user.email jovifre2@gmail.com
```

## Comando do git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
**Importante** só é executado uma vez
```bash
git init

```

Para verificar a situação do repositório(pasta)
usamos o status a qualquer momento
```bash
git status
```

Quando o status mostrar arquivos em vermelho é necessario rodar o add para adicionar os arquivos a serem salvos.
Obs: "." adiciona todos os arquivos da pasta atual
```bash
git add .
```

Para salvar uma versão dos arquivos na situação atual usamos o commit.
O -m adiciona uma mensagem do porque estes arquivos estao sendo salvos
```bash
git commit -m "Mensagem"
```

Para baixar as alterações que estão apenas no Github utilizamos o pull <br>
**IMPORTANTE:** Sempre deve baixar a ultima versão da nuvem antes de enviar o atual do computador
```bash
git pull
```

Para enviar os commits do pc para o Github utilizamos o push.
```bash
git push
```
