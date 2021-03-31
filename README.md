# AngularApiMarvel
* Projeto de avaliação técnica para empresa .add. 
* Desenvolvimento de uma aplicação Angular com conexão a API da Marvel.
* Versão do [Angular CLI](https://github.com/angular/angular-cli) 8.2.0.

## Bootstrap
* Instalação do bootstrap na pasta raiz do projeto `npm install bootstrap --save`.
* Adicionado o import `@import '~bootstrap/dist/css/bootstrap.min.css';` no arquivo de estilo global `src/styles.css` para aplicação do framework de responsividade.
* Versão do [Bootstrap](shttps://www.npmjs.com/package/bootstrap) 4.6.0.

### ngx-bootstrap
* Adicionado `ngx-bootstrap` biblioteca que dá suporte ao boostrap em sua versão 3 e 4.
* O legal dele é que utiliza os mesmos estilos, todos os componentes foram recriado e contém o mesmo comportamento, podendo utiliza as tags e classes do css bootstrap porém com código angular.
* Comando de instalação: `npm install ngx-bootstrap --save`.

## Desafio
1. Crie uma conta em `https://developer.marvel.com`;

2. Obtenha as Keys para serem usadas nas requisições http;

3. A URL base da API é `http(s)://gateway.marvel.com`;

4. Os recursos disponíveis se encontram na página `https://developer.marvel.com/documentation/generalinfo`;

5. Dentre os recursos disponíveis abaixo, escolha 2 para implementação, Retornando collections (HTTP.GET) de cada um dos dois;

6. Mapear as Entidades disponíveis na documentação da API para o retorno das informações de acordo com os dois recursos escolhidos;

7. Crie pelo menos 1 modulo com 2 rotas para exibir as informações, uma rota para cada recurso disponível;

8. Use injeção de dependências no angular para injeção do serviço de consumo da API;

9. Use bootstrap para deixar o design responsivo;