
Projeto em node.js retirado de [site](https://betterprogramming.pub/simple-chat-application-in-node-js-using-express-mongoose-and-socket-io-ee62d94f5804)

Exemplo de dockerfile em Node.js [rep](https://github.com/BretFisher/node-docker-good-defaults/blob/main/Dockerfile)

Exemplo de dockerfile com multiplos npm para diminuir as layers da imagem [site](https://codefresh.io/docker-tutorial/node_docker_multistage/)

Exemplo de como construir URL na aplicacao, é o que possbilitou resolver o problema de Cqrs(), rotas, de maniera simples pois a versao do site estava como localhost e gerava problemas quando subia esse projeto na AWS [site](https://qastack.com.br/programming/25203124/how-to-get-base-url-with-jquery-or-javascript)


Para executar o projeto localmente deverá ter o docker instalado na sua maquina se for rodar via dockerfile ou se for rodar local sem docker deverá seguir o passo a passo do [site](https://betterprogramming.pub/simple-chat-application-in-node-js-using-express-mongoose-and-socket-io-ee62d94f5804)

Para rodar localmente no seu docker apos baixar o projeto deverá rodar os seguintes comandos.
Exemplo:

docker build -t nascimentogabriel/nomedaimagem:v1 .

docker run -d --name ezops -p 3000:3000 nascimentogabriel/nomedaimagem:v1 


Implementação de autoria minha:

Caso digitar determinadas palavras o chatbot gera uma mensagem automatica para não xingar.

Palavras:feio,bobo,idiota,chato,retardado

Tambem caso digite chat -info irá aparecer uma mensagem de informação do sistema.

