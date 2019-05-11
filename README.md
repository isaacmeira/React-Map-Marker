# App React Map

#### Aplicativo criado para estudo de funcionamento do React + Redux + ReduxSaga


- App criado no desafio 03 do módulo de ReactJS no bootcamp Rocketseat

  O aprendizado foi em como funciona o redux, bem como redux sarga para o armazenamento de state, junto com a arquitetura Duck na criação do sistema.
  
  Além disso, tivemos o uso da lib [MAPBOX](https://www.mapbox.com/) para fazer o retorno do mapa dentro do nosso componente principal, além das várias funcionalidade programadas dentro da mesma, tais como posição inicial, zoom e etc, você pode saber mais dentro da documentação da mesma.
  Foi usado também a api do github, para armazenar os dados de usuário dentro do conteúdo do marcador do mapa.
  
 ### COMO USAR:
 
 Você poderá testá-lo [Aqui](https://projects.isaacmeira.dev), mas, caso queira implementálo você irá precisar do [YARN](https://yarnpkg.com/pt-BR/) para instalar todas as dependências do projeto.
 
  - No projeto usar `yarn install` para instalar todas as dependências do projeto.
  - Após, executar `yarn start`.
  
  ** Pode ser necessário ter que buscar o token para acesso do MAPBOX, ele é facilmente encontrado no site, e você consiguirá editálo em SRC/COMPONENTS/MAP/INDEX.JS - na parte do render onde está `mapboxApiAccessToken`
  
  ### SCREENSHOTS:
      Tela Inicial
  <img src="https://s3.us-east-2.amazonaws.com/gitmap/Screenshot_3.png" height = "600" width = "800" />

      Modal Adição de usuário
  <img src="https://s3.us-east-2.amazonaws.com/gitmap/Screenshot_4.png" height = "600" width = "800" />
  
      Adicionando um usuário
  <img src="https://s3.us-east-2.amazonaws.com/gitmap/Screenshot_5.png" height = "600" width = "800" />
     
      Adicionando vários usuários
  <img src="https://s3.us-east-2.amazonaws.com/gitmap/Screenshot_2.png" height = "600" width = "800" />
