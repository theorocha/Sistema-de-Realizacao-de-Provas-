# Projeto Final Engenharia de Software

Feito por **_Theo Rocha, Matheus Lopes, Mateus de Paula e Oseias Romeiro._**

## Sobre

Desenvolvimento de uma plataforma online de realização e controle de exames.

## Ferramentas

Projeto foi desenvolvido com o microframework Flask e SQLite.

## Venv

Para utilizar esse projeto é necessário a utilização de um ambiente virtual.
No diretório principal, use os seguintes comandos para criar e ativar o venv:

```
$ python3 -m venv .venv
$ . .venv/bin/activate
```

Para sair do venv:

`deactivate`

## Iniciando o projeto

Já dentro do .venv, utilize o seguinte comandos para baixar as dependências do projeto:

`pip install -r requirements.txt`

## Iniciando o banco de dados (É necessário a criação)

Para iniciar o banco de dados, utilize os seguintes comandos:

```
     flask db init
     flask db migrate -m "init"
     flask db upgrade
```

Para adicionar os dados já pré criados pelo projeto utilize:

```
flask seed all
```

## Rodando o projeto

Para rodar o projeto basta utilizar:

```
(para linux)
export FLASK_APP=run 
(para windows)
set FLASK_APP=run 
flask run --debug
ou flask --app run run --debug
```
