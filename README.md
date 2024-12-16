# GoRestaurant

GoRestaurant é uma plataforma web e móvel que foi desenvolvida no Bootcamp da GoStack 14 da [Rocketseat](https://rocketseat.com.br/). A plataforma permite a exibição, criação, remoção e atualização (CRUD) de pratos e pedidos de comida.

![](https://imgur.com/j2124oL.png)

![](https://imgur.com/Vz73FFK.png)

![](https://imgur.com/H325xG8.png)

## 🚀 Tecnologias

Este projeto foi desenvolvido para portfólio com as seguintes tecnologias:

- [reactjs](https://reactjs.org)
- [axios](https://github.com/axios/axios)
- [@unform/web](https://unform.dev/)
- [react-modal](https://www.npmjs.com/package/react-modal)
- [styled-components](https://styled-components.com/)
- [yup](https://github.com/jquense/yup)
- [react-native](https://reactnative.dev/)
- [json-server](https://github.com/typicode/json-server)
- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)

## ℹ️ Executando

Para clonar e executar este projeto, você precisará de [Git](https://git-scm.com), [Node.js v12.13][nodejs] ou superior + [Yarn v1.19][yarn] ou superior instalados no seu computador.

Na sua linha de comando execute:

### 👨🏻‍💻 Web

```bash
# Clonando este repositório
$ git clone https://github.com/augustocesarfmo/gorestaurant-web.git

# Acessando o repositório
$ cd gorestaurant-web

# Instalando as dependências
$ yarn install

# Inicializando o servidor da fake API
$ yarn json-server server.json -p 3333

# Executando o app
$ yarn start
```

### 📱 Mobile

```bash
# Clonando este repositório
$ git clone https://github.com/augustocesarfmo/gorestaurant-mobile.git

# Acessando o repositório
$ cd gorestaurant-mobile.

# Instalando as dependências do projeto
$ yarn install

# Inicializando o servidor da fake API
$ yarn json-server server.json -p 3333

# Instalando as dependências nativas (apenas iOS)
$ cd ios/ && pod install

# Executando o app
$ yarn ios | yarn android
```

## 📝 Licença

Este projeto está sob a licença MIT. Consulte a [LICENÇA](https://github.com/augustocesarfmo/gorestaurant/blob/main/LICENSE.md) para obter mais informações.

---

by Augusto César Oliveira 👐🏼

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
