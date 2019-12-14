This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify


This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
***

#### [História de usuário 1] Garçom/Garçonete deve poder anotar o seu pedido

Eu como garçom/garçonete quero poder anotar o meu pedido saber o valor de cada 
produto e poder enviar o pedido para a cozinha para ser preparado.

##### Critérios de aceitação

O que deve acontecer para satisfazer as necessidades do usuário?

* Anotar o nome e mesa.
* Adicionar produtos aos pedidos.
* Excluir produtos.
* Ver resumo e o total da compra.
* Enviar o pedido para a cozinha (guardar em algum banco de dados).
* Funcionar bem e se adequar a um _tablet_.

##### Definição de pronto

O acordado abaixo deve acontecer para dizer que a história está terminada:

* Você fez _testes_ de usabilidade e incorporou o _feedback_ do usuário.
* Você deu deploy de seu aplicativo.

***

#### [História de usuário 2] Chefe de cozinha deve ver os pedidos

Eu como chefe de cozinha quero ver os pedidos dos clientes em ordem, poder marcar que estão prontos e poder notificar os garçons/garçonetes que o pedido está pronto para ser entregue ao cliente.

##### Critérios de aceitação

* Ver os pedidos à medida em que são feitos.
* Marcar os pedidos que foram preparados e estão prontos para serem servidos.
* Ver o tempo que levou para preparar o pedido desde que chegou, até ser marcado como concluído.

##### Definição de pronto

* Você fez _testes_ de usabilidade e incorporou o _feedback_ do usuário.
* Você deu deploy de seu aplicativo.

***

#### [História de usuário 3] Garçom/Garçonete deve ver os pedidos prontos para servir

Eu como garçom/garçonete quero ver os pedidos que estão prontos para entregá-los rapidamente aos clientes.

##### Critérios de aceitação

* Ver a lista de pedidos prontos para servir.
* Marque os pedidos que foram entregues.

##### Definição de pronto

* Você fez _testes_ de usabilidade e incorporou o _feedback_ do usuário.
* Você deu deploy de seu aplicativo.
* Os dados devem ser mantidos intactos, mesmo depois que um pedido terminado. Tudo isso para poder ter estatísticas no futuro.

***

## 6. Hacker Edition 

As seções chamadas Hacker Edition são opcionais. Se você terminou tudo e ainda sobrou tempo, faça essa parte. Assim você poderá aprofundar e exercitar mais sobre os objetivos de aprendizagem do projeto.

* Siga as recomendações para PWAs (Progressive Web Apps), para criar uma aplicação offline. Para orientá-las sobre este tema,recomendamos que você use Lighthouse, que é uma ferramenta do Google que nos ajuda a garantir que nossos aplicativos web sigam "boas práticas".

* Faça testes que cubram 100% de statements, functions, lines e branches.

* Implemente a seguinte história de usuário: 

#### [História de usuário 4] Usuário deve ter seu perfil (login/senha) para acessar o sistema.

Eu como funcionário do restaurante quero entrar na plataforma e ver apenas a tela importante para o meu trabalho.

##### Critérios de aceitação

O que deve acontecer para satisfazer as necessidades do usuário?

* Criar login e senha.
* Criar tipo de usuário (cozinha / salão).
* Entrar na tela correta para cada usuário.

##### Definição de pronto

O acordado abaixo deve acontecer para dizer que a história está terminada:

* Você fez testes de usabilidade e incorporou o feedback do usuário.
* Você deu deploy de seu aplicativo.

***

## 7. Dicas e leituras complementares

### Primeros passos

* Faça um _fork_ deste repositório (no GitHub).

* Clone seu _fork_ no seu computador:

*  Crie um projeto usando `create-react-app`

* Crie um projeto no [Firebase](https://firebase.google.com/)

* Converta o menu descrito pelo cliente em uma coleção no Firebase.

***

### Outros recursos

#### Framework / biblioteca

* [React Hooks](https://reactjs.org/docs/hooks-intro.html)

#### React Hooks

* [Entendendo React Hooks](https://medium.com/@higornevesmarques/entendendo-react-hooks-2c0efae276a3)
* [React Hooks - Rocketseat](https://blog.rocketseat.com.br/react-hooks/)
* [Habemus React Hooks](https://willianjusten.com.br/habemus-react-hooks/)

#### Ferramentas

* [npm-scripts](https://docs.npmjs.com/misc/scripts)
* [Babel](https://babeljs.io/)
* [webpack](https://webpack.js.org/)
* [Aphrodite](https://github.com/Khan/aphrodite)

#### PWA

* [Seu primeiro Progressive Web App - Google
  developers](https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/?hl=es)
* [Progressive Web Apps -
  codigofacilito.com](https://codigofacilito.com/articulos/progressive-apps)
* [offlinefirst.org](http://offlinefirst.org/)
* [Usando Service Workers -
  MDN](https://developer.mozilla.org/pt-BR/docs/Web/API/Service_Worker_API/Using_Service_Workers)
* [Como habilitar dados sem conexão - Firebase
  Docs](https://firebase.google.com/docs/firestore/manage-data/enable-offline?hl=es-419) 

#### Serverless

* [Serverless Framework 1.0 - Pagar.me Talks](https://www.youtube.com/watch?v=2oNovfw3V08)
* [Firebase](https://firebase.google.com/)
* [Serverless Architectures - Martin
  Fowler](https://www.martinfowler.com/articles/serverless.html)
 
## Checklist

### `README.md`

* [ ] Documentação do processo de design.
* [ ] Inclui informações para desenvolvedores (dependências, instalação, uso, testes...)

#### HU

#### HU 1: Anotar pedidos

* [ ] Digitar o nome do cliente e mesa.
* [ ] Filtrar _menu_ para _café da manhã_ e _almoço/jantar_.
* [ ] Adicionar item ao pedido.
* [ ] Excluir item do pedido.
* [ ] Mostrar _resumo_ do pedido com todos os itens e o total.
* [ ] Enviar para a cozinha (isso deve salvar o pedido).

#### HU 2: Ver pedidos na cozinha

* [ ] Visualizar pedidos pendentes para produção.
* [ ] Marcar pedido como pronto para entrega.
* [ ] Ver histórico dos pedidos.

#### HU 3: Entrega de pedidos

* [ ] Visualizar pedidos pendentes para entrega.
* [ ] Marcar pedido como entregue ao cliente.

### UX

* [ ] Funciona bem em tablets.
* [ ] Fácil utilização em telas sensíveis ao toque.
* [ ] Status atual do pedido sempre visível enquanto fazemos um pedido.

### Hacker Edition

* [ ] Segue as recomendações de PWAs.
* [ ] Funciona bem offline.

#### HU 4: Perfil do Usuário

* [ ] Criar login e senha.
* [ ] Criar tipo de usuário (cozinha / salão).
* [ ] Entrar na tela correta para cada usuário.

#### Testes

* [ ] 100% de cobertura de _statements_.
* [ ] 100% de cobertura de _functions_.
* [ ] 100% de cobertura de _lines_.
* [ ] 100% de cobertura de _branches_.

