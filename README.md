
# Snap Clima

Esse projeto é uma página de informação sobre o clima em diversas cidades ou na cidade em que o usuário está.


## Demonstração

https://jmaurojr.github.io/snapClima/assets


## Referência

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - [Breno Cupertino](https://www.youtube.com/@brenocuper/videos)


## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `dt` | `string` | Data da consulta |
| `name` | `string` | Nome da Cidade |
| `weahter` | `string` | Clima |
| `main` | `string` | Temperatura, sensação térmica, Umidade |
| `wind` | `number` | Velocidade do vento |
| `sys` | `number` | Horários do nascer e do pôr do sol |





## Autores

- [@jmaurojr](https://www.github.com/jmaurojr)
- [@brenocuper](https://www.github.com/brenocuper)


## Feedback

Se você tiver algum feedback, por favor nos deixe saber por meio de jmaurojr@gmail.com


## Funcionalidades

- Localização do usuário
- Busca manual por cidades
- Responsivo
- Multiplataforma
- Mobile first


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maurocardosojr/)



## Rodando localmente

Clone o projeto

```bash
  git clone https://link-para-o-projeto
```

Entre no diretório do projeto

```bash
  cd my-project
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run start
```

