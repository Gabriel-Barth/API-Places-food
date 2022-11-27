# burger-api
My Burger Api


## Project setup
```
npm install
```

### Rodar o servidor:

```
json-server --watch db.json
```

API de hamburger com dados estaticos 

Para verificar o retorno dos dados visite : (https://my-recomendations-api.herokuapp.com/Recomendations)



Para resgatar os dados da API:
```
fetch('https://my-burger-api.herokuapp.com/burgers/0')
  .then(response => response.json())
  .then(data => console.log(data));
```

