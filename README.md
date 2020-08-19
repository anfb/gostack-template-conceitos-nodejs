## :recket: Node.js Basic concepts

### Resolution of the challenge **[Rocketseat](https://github.com/rocketseat-education/bootcamp-gostack-desafios/blob/master/desafio-conceitos-nodejs/README.en.md)**

### About application routes

- **`POST /repositories`**: The route must receive `title`, `URL` and `techs` inside of request body. It must be stored inside an object in the sollowing format: `{id:" uuid ", title: 'Desafio Node.js', URL: 'http: //github.com /anfb/...' , techs: ["Node.js", "express", "..."], likes: 0} `.
- **`GET /repositories`**: This route lists all repositories. 
- **`PUT /repositories/:id`**: The route only change the `title`, `URL` and `techs` of the repository that has the` id` parameter.
- **`DELETE /repositories/:id`**: The route that delete a repository with the `id` present in the route parameters;
- **`POST /repositories/:id/like`**: The route must increase the number of likes from the specific repository chosen through the `id` param present in the route parameters, at each call of this route, the number of likes will be increased by 1;
