# PokeApp
Es una aplicación Single Page elaborada con Angular y la API PokeApi, que permite al usuario visualizar una tabla paginada con información acerca de los diferentes pokémon. La tabla cuenta con una barra de búsqueda que muestra instantáneamente la compatibilidad con los términos buscados y también emite una alerta en caso de que la búsqueda no coincida con la lista de pokémon disponibles. Al seleccionar un pokémon, se muestra una tarjeta con detalles del elegido de la lista, que incluye un botón para agregarlo a los favoritos. Al seleccionar un pokémon como favorito, se destina a un botón para almacenar la elección del usuario, y al hacer clic en el botón, se abre un modal con la información del pokémon seleccionado como favorito. Además, la aplicación incluye una tabla que muestra tarjetas con la cantidad de pokémon que comienzan con cada letra del abecedario.

## Tecnologías 
- Angular 15   
- Bootstrap 5   
- Angular Material  
- API [PokeAPI](https://pokeapi.co/)

## Deploy 
 [POKE-APP](https://pokedexpablirou.netlify.app/)

## Aspectos relevantes 
 La Aplicación esta compuesta por un modulo principal, que contiene las siguientes carpetas:
 
- `SERVICES` se implementó dos servicios, uno para la conexion e  interacción con la API y el segundo, destinado a la manupulación de los datos obtenidos para poder interactuar entre los componentes y pasar datos entre ellos.                                                                             
- `PIPES` se implementó pipes que permitieron realizar la paginación de la lista de pokemons, la busqueda  y filtro, al igual que para el conteo necesario para el Poke-ABC.
- `MODELS` en esta carpeta de implementaron las interfaces necesarias para la estructura de los datos proveniendte de la api, como los necesario para la aplicación.
- `MODULES` se denfinio un modulo donde concentrar las exportaciones, importaciones y modulos necesario para la aplicación. Al igual que un componente principal que permitia generar un template para unir los componentes necesarios en la aplicación. 

### Para descargar e instalar Aplicación
```
git clone
npm install
ng serve
```


