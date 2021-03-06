<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

# Confia Backend

### Um painel de administração de usuários onde é possível visualizar, adcionar e buscar usuários.

## :rocket: Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js][nodejs]
- [NestJS](https://nestjs.com/)
- [Express](https://expressjs.com/)
- [TypeORM](https://typeorm.io/#/)
- [Docker](https://www.docker.com/docker-community)
- [MySQL](https://www.mysql.com/)
- [VS Code][vc] with [ESLint][vceslint], [EditorConfig][vceditconfig] and [Prettier][vcprettier]

## :information_source: Como Utilizar

Para clonar e rodar essa aplicação, você precisará do [Git](https://git-scm.com), [Docker](https://www.docker.com/docker-community), [NestJS](https://nestjs.com/), [Node.js v12.18][nodejs] ou superior + [Yarn v1.22][yarn] ou superior instalado no seu computador.
Da sua linha de comando:

```bash
# For create a Docker container with MySQL configured for this project
$ docker run --name mysql -e MYSQL_ROOT_PASSWORD=nest -p 3306:3306 -d mysql

# Clone this repository
$ git clone https://github.com/JapBastos/backend-confia.git

# Go into the repository
$ cd backend-confia

# Install dependencies
$ yarn

# Run to start the development server
$ yarn start:dev
```

Made with ♥ by João Bastos [Get in touch!](https://www.linkedin.com/in/japbastos/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[vcprettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
