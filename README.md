# test-react-redux

El siguiente ejercicio consiste en crear un directorio de peliculas.

Para lograrlo deberás seguir los siguientes pasos:

### 1. Crear una aplicacion en react usando:

```
npx create-react-app movies
cd movies
npm start

```

### 2. Crear el modelo necesario donde se almacenarán las peliculas:

   para esto solo necesitarás un solo model ``movieModel.js``

### 3. La base de datos tendra que ser creada en mongoDB

   Actualmente para crear los squemas de la base de datos estoy usando Mongoose http://mongoosejs.com/docs/guide.html
   el lugar donde alojarás la informaciónes en mongo atlas ingresa a https://www.mongodb.com/cloud/atlas y abre una cuenta. Es gratis.
   para visualizar tu base de datos te recomiendo usar compass lo puedes descargar desde aqui: https://www.mongodb.com/products/compass

   Una vez tu base de datos este lista y conectada a la aplicacion de react.js

### 4. Procede a trabajar en la aplicacion:
    El directorio de peliculas contará con dos paginas.

    Primera Pagina: Aqui mostrarás todos los nombres de las peliculas con un link hacia la segunda página de descripcion.
    Segunda Pagina: Esta pagina mostrara la descripcion de la pelicula ala que se le dio click en la pagina de inicio.
    Tercera Pagina: Fomrulario para añadir movies - este debe de contar con 3 campos Nombre, Año de publicacion y descripcion.
    
### 5. Procede a implementar Redux Thunk O Saga:    
    Usa redux saga o Thunk para manejar el estado de la siguiente funcionalidad.
    Una vez el usuario esta en el formulario y procede a darle click a -grabar movie-, debera aparecer un loading mientras se graba la movie a la base de datos. Ejemplo de loading image:https://www.google.com/search?biw=1257&bih=718&tbm=isch&sa=1&ei=uSg1W-63MsSz5gKEi5bYAQ&q=loading+animateg+gift&oq=loading+animateg+gift&gs_l=img.3...2098.7367.0.7503.0.0.0.0.0.0.0.0..0.0....0...1c.1.64.img..0.0.0....0.RI3XqQd_weI#imgrc=uZRuZN4WxsnOLM: 
   
   Una vez el usuario guarda la movie debera aparecer un mensaje diciendo "Su pelicula fue agregada correctamente"
   
### 6. Para poder revisar tu aplicación
    Crea tu propio repositorio y amedida que implementes cambio porfavor hacer commit para ver los avances.
    tambien deberas de hacerle ``npm run build`` y este folder tambien debera de ser parte de tus commits.
    
    Nota: no poner uno o dos commits con 10 files cambiados, es importante ver commit por implementacion.

 ### Nota: el proposito de este ejercicio es poder mostrar el conocimiento de React redux y mongoDB asi como la comunicación entre tu y yo.
 para esto me puedes escribir en cualquier momento desde las 9:00AM hasta las 7:PM.

 Mi email es: gcomLnk@gmail.com
