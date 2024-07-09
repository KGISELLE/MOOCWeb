# MOOCWeb
Repositorio para curso web-coursera-andes

## Tutorial Plunker
Para insertar un codigo base en un archivo html en el editor, oprimimos:
* Ctrl + Space
o tambien podemos escribir en el archivo:
* ! 
La diferencia entre estos dos, es que el primero me agrega la opcion en español para tildes
```html
    <meta charset='utf-8'> 
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
```
y los scripts de CSS y Javascript
```html
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
```
En cambio la segunda opcion agrega la opcion del idioma en ingles.
```html
    <html lang="en">
```

## Tutorial codespace
En elcurso se da otra opcion para trabajar y es trabajar todo en la herramiente Codespaces de Github, con la cual se puede desarrollar software en un navegador.
1. Para usar codespaces se necesita tener una cuenta de Github
2. Dentro de Github creamos un nuevo repositorio `New repostory`
3. Una vez creado el repositorio, crear un codespace haciendo click en la opcion `<> code`, en la pestaña codespaces, click en el boton `create codespaces on main`
* Asi podemos ver el editor VSC pero en una pestaña del navegador

Tener en cuenta que el codigo que hagamos en codespaces no se guardará automaticamente, hay unos paso previos que tenemos que hacer para guardar los cambios.
1. hacer click en la barra de herramientas `Control de codigo fuente` esta vista nos mostrará los archivos a los que les hicimos cambios.
2. Para agregar los archivos que queremos agregar le hacemos click a los 3 puntos `... > Changes > Stage All Changes`
3. Despues agregar un mensage de commit que describa los cambios que hemos realizado y agregamos estos cambios con el boton `commit`
4. final mente sincronizamos los cambios, haciendo click en el boton nuevamente que ahora dice `Sync Changes`, esto nos muestra un modal con un mensaje advirtiendonos que la accion hara cambios en nuestro repositorio. Hacemos click en `OK`.
5. Para previsualizar la pagina debemos instalar la extensionn `Live server` en el codespace. Lo podemos hacer igual que en VSC en la barra lateral vamos a `extensiones`y buscamos la extension.