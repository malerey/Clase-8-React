# Clase 8 React
## Styled components

### Consignas

Hoy haremos una copia de un perfil de instagram en React con styled components siguiendo este modelo:

![img](https://www.robinwieruch.de/static/611b371f42ff49efaad46bc4464f7341/a9a89/stylagram.webp)

1. Crear un proyecto nuevo de create-react-app
2. Instalar styled-components 
3. Crear tres componentes (como mínimo: si necesitan mas, haganlo!): 
  * Barra de navegacion
  * Informacion de perfil
  * Seccion con las fotos
  
4. Todo el estilo debe hacerse con styled-components. 

5. Para la foto de perfil, usen una imagen de su computadora. Recuerden las diferencias entre trabajar con imagenes locales y con imagenes sacadas de internet en React :) 
  
6. Las fotos deben hacerse recorriendo el siguiente array de objetos. Como ven, hay mucha informacion en los objetos que por ahora no usaremos (por ahora solo usamos las imagenes). Eso es normal trabajando con data de un fetch. Ignoren toda la info que no necesiten. 

```js
const feedsource = [
  {
    source: 'https://www.viajejet.com/wp-content/viajes/una-laguna-unica-en-jamaica-650x366.jpg',
    likes: '43',
    comments: '3',
    id: 0,
  },
  {
    source: 'https://www.viajejet.com/wp-content/viajes/los-arrecifes-de-coral-de-bunaken-indonesia-650x366.jpg',
    likes: '313',
    comments: '10',
    id: 1,
  },
  {
    source: 'https://www.viajejet.com/wp-content/viajes/paisaje-nevado-en-el-parque-nacional-deogyusan-corea-del-sur-650x366.jpg',
    likes: '29',
    comments: '2',
    id: 2,
  },
  {
    source: 'https://www.viajejet.com/wp-content/viajes/un-paisaje-de-vertigo-en-ronda-malaga-espana-650x366.jpg',
    likes: '18',
    comments: '2',
    id: 3,
  },
  {
    source: 'https://www.viajejet.com/wp-content/viajes/El-increible-paisaje-de-Semuc-Champey-Guatemala-650x366.jpg',
    likes: '30',
    comments: '4',
    id: 4,
  },
];
```

