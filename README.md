<p align="center">
  <a title="node.js authors / Public domain" href="https://commons.wikimedia.org/wiki/File:Node.js_logo.svg"><img width="175" alt="Node.js logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/512px-Node.js_logo.svg.png"></a>


**Desafio utilizando conceitos Node**

- Aplicação permite que um repositório seja criado, e retorna um json com o projeto criado.

- Aplicação permite que seja retornado um array com todos os repositórios que foram criados até o momento.

- Aplicação deve permitie que sejam alterados apenas os campos `url`, `title` e `techs`.

- Validação na rota de update se o id do repositório enviado pela url existe ou não. Caso não exista, retorna um erro com status `400`.

- Não permite que a rota de update altere diretamente os likes desse repositório, mantendo o mesmo número de likes que o repositório já possuia antes da atualização. O único lugar atualiza essa informação é a rota responsável por aumentar o número de likes.

- Permitir que a rota de delete exclua um projeto, e ao fazer a exclusão, ele retorna uma resposta vazia, com status `204`.

- Realiza validação na rota de delete se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status `400`.

- A aplicação permite que um repositório com o id informado possa receber likes. O valor de likes é incrementado em 1 a cada requisição, e como resultado, retornar um json contendo o repositório com o número de likes atualizado.

- Aplicação não permite likes em repositórios que não existem, para isso, ocorre validação na rota de like caso o id do repositório enviado pela url exista ou não. Caso não exista, retorna um erro com status `400`.


