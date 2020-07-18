# Aplicación de música con React

## Funcionalidades

● Mostrar varios listados con música recomendada, resultados de búsqueda y otra información. 
● Incluir una barra en la zona superior para facilitar la navegación. 
● Incluye una vista de reproducción. 
● Incluir distintas vistas en el proyecto. 
● Almacenar en el store de Redux información relevante cómo el usuario. 
● Almacenar en el store de Redux el histórico de canciones escuchadas y álbumes visitados. 
● Almacenar en el store de Redux la información de las respuestas del servidor. 
● Buscar música 
● Implementar el reproductor de audio 


## Vistas

● Inicio: se muestra el listado de música recomendada 
● Álbums: muestra los distintos álbums disponibles. 
● Álbum: muestra información sobre el álbum actual como el listado de canciones, tiempo total, imagen del álbum… 
● Reproductor: muestra el proceso de reproducción actual. Se activa cuando el usuario hace click en una canción. 
● Inicio de sesión: esta pantalla muestra un formulario para iniciar sesión. No hace falta que conectes este formulario con el backend, sino que lo que el usuario agregue al formulario valide directamente y se almacene dicha información en el store de Redux. 
● Perfil de usuario: almacena información privada del usuario por lo que sólo se puede acceder a esta vista si el usuario ha iniciado sesión.
● Búsqueda: muestra un listado con los resultados de búsqueda. 
● Reproductor flotante: Incluye el reproductor como parte de las otras vistas para que el usuario pueda seguir escuchando música aunque no se encuentre en la vista del reproductor


## Iniciar el proyecto

El proyecto se inicia directamente con `yarn start`.

Este comando hace uso de `npm-run-all` que ejecuta el servidor y el cliente al mismo tiempo. El servidor estará escuchando en el puerto 3001 y la aplicación en el 3000. No obstante, la aplicación ya viene preconfigurada con un proxy que redirige cualquier llamada al servidor. Por ejemplo:

```/albums -> http://localhost:3001/albums```


## Créditos

* Fotografía de la carátula de los álbums por [James Owen](https://unsplash.com/photos/c-NBiJrhwdM)
* Audio compuesto por [Kevin MacLeod](https://twitter.com/kmacleod)

