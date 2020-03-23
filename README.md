# Back-end

1. Regras de negócio;
2. Conexão banco de dados;
3. Envio de e-mail;
4. Comunicação com webservices;
5. Autenticação do usuário;
6. Criptografia e segurança;

## Conecta com:

- Front-end web
- Front-end mobile
- Serviços externos

As conexões serão realizadas em formato `{ JSON }`

## API RESTfull

Segue algumas regras.

# Entendendo React

## Abordagem tradicional

A cada requisição o servidor retorna todo o conteúdo da página com HTML e CSS.  
Isto limita o front-end para o browser já que o aplicativo mobile ou serviços externos não vão conseguir interpretar o HTML.

## Abordagem de SPA

As requisições trazem apenas dados como resposta para preencher as informações em tela.  
A página não recarrega, otimizando a performance. Retornando apenas JSON podemos ter quantos front-ends quisermos.

# Entendendo o React Native

## Abordagem tradicional

Cria-se uma aplicação para iOS e outra para Android, e nesses casos, o trabalho se torna repetido tanto para criação quando para as alterações.

## Abordagem no React Native

Todo código feito é em JavaScript, ele não é convertido em código nativo, melhor que isso, o dispositivo passa a entender o código JavaScript e a interface gerada é totalmente nativa.

## Por que utilizaremos o Expo?

Sem o expo, precisaria instalar em nosso sistema tanto o Android Studio para ter o SDK de desenvolvimento Android, e o Xcode para obter o SDK do iOS.  
Nesse caso, a iniciação no desenvolvimento fica mais penosa, já que essas SDK's não são extremamente simples de instalar e livres de erros.  
Com o expo, instala o aplicativo no celular. Nele já tem tudo para podermos desenvolver. APIs de mapas, geolocalização, câmera, sensores, calendário etc.