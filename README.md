<p align="center">
  <a title="node.js authors / Public domain" href="https://commons.wikimedia.org/wiki/File:Node.js_logo.svg"><img width="175" alt="Node.js logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/512px-Node.js_logo.svg.png"></a>

# node-inicio
Desafio utilizando conceitos Node onde a aplicação armazenar repositórios, permite a criação, listagem, atualização e remoção dos repositórios e permite que os repositórios possam receber "likes".

### Rotas da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo app.js, e completar onde não possui código com o código para atingir os objetivos de cada rota.

- **`POST /repositories`**: A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: `{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }`; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.

- **`GET /repositories`**: Rota que lista todos os repositórios;

- **`PUT /repositories/:id`**: A rota deve alterar apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

 - Repositories able to create a new repository
 - Repositories able to list the repositories
 - Repositories able to update repository
 - Repositories not able to update a repository that does not exist
 - Repositories not able to update repository likes manually
 - Repositories able to delete the repository
 - Repositories able to delete a repository that does not exist


