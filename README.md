# Burger-api
My Burger Api

# API de hamburger com dados estaticos 

## Project setup
```
npm install
```

### Rodar o servidor:

```
json-server --watch db.json
```



Para verificar o retorno dos dados visite : (https://my-recomendations-api.herokuapp.com/Recomendations)



Para resgatar os dados da API:
```
fetch('https://my-burger-api.herokuapp.com/burgers/0')
  .then(response => response.json())
  .then(data => console.log(data));
```

