## INSTRUÇÕES

Para iniciar este projeto basta ter o [docker](https://docs.docker.com/engine/install/) instalado no compoutador.
As portas `4040` e `6060` precisam estar disponíveis.

1. Renomear o arquivo `docker-compose-example.yml` para `docker-compose.yml`

2. Inserir as variaveis de ambiente faltantes no arquivo `docker-compose`
   2.1 Todas as variaveis podem ser pegas no dashboard da Auth0. Em caso de dificuldade consultar o [tutorial](https://developer.auth0.com/resources/code-samples/full-stack/hello-world/basic-role-based-access-control/spa/react-typescript/spring-java) para mais detalhes.

   - REACT_APP_AUTH0_DOMAIN
   - REACT_APP_AUTH0_CLIENT_ID
   - REACT_APP_AUTH0_AUDIENCE
   - OKTA_OAUTH2_ISSUER
   - OKTA_OAUTH2_AUDIENCE

3. Em um terminal, na pasta raiz rodar `docker compose up --build -d`
4. Acessar o `localhost:4040` para acessar o frontend
