<h3 align="center">
  Aplicação para criação de pedidos em restaurante: Projeto REACT NATIVE
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/ejcosta12/studying-relations-database?style=flat-square">
  <img alt="javaScript" src="https://img.shields.io/github/languages/top/ejcosta12/studying-relations-database">
  <img alt="Size" src="https://img.shields.io/github/repo-size/ejcosta12/studying-relations-database">
</p>

## Sobre
Versão mobile de aplicação para criação de pedidos em restaurante, ao acessar o dashboard é possível ver todos os pratos disponíveis, filtrar por categorias ou através
de um campo para pesquisa pelo nome do prato. Criada página para listagem de pedidos e outra para listagem de favoritos. Ao tocar em algum prato será direcionado para a criação
do pedido, podendo alterar a quantidade e adicionar ingredientes extras, exbindo o total a ser pago.

<p align="center" >
<img alt="Home" src="https://res.cloudinary.com/dggw1b0tr/image/upload/c_scale,w_236/v1594124067/studying-react-native-project-restaurant/Home_teypzl.png">
</p>

### Tecnologias

- React Native
- Axios
- Styled Components

### Scripts CLI

#### yarn
Instalação de todas as dependências necessárias.

#### yarn json-server server.json -p 3333
Este projeto foi criado com o Json Server para fornecimento de dados Fake API. A configuração default está no endereço localhost, caso vá utilizar outro endereço IP para
testes no ambiente de desenvolvimento utilize o comando:
```yarn json-server server.json -p 3333 -H 192.168.0.2```
192.168.0.2 é um endereço de exemplo. Será necessário alterar a baseURL de acesso em src\services\api.ts.

#### yarn android OU yarn android OU yarn start
Dependendo da vizualização em dispositivo físico ou emulador, utilize um dos comandos.
