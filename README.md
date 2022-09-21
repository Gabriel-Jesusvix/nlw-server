
# NLW - Esports 

Created Api service utility the project web and mobile;


## Documentação da API

#### Return list of Game;

```http
  GET /games/
```


#### Return ads of Games;


```http
  GET /games/:id/ads
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |



#### Created ads of Game;

```http
  POST /games/:id/ads
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |



#### return discord of User;

```http
  POST /ads/:id/discord
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |




## Funcionalidades

- List of Games
- List Ads from Games
- Create Ads from Games;
- List user of discord

