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

## Titulos
En HTML se pueden crear titulos que van desde el h1 hasta el h6.
<h1>h1 - Titulo de primer nivel</h1>
<h2>h2 - Titulo de segundo nivel</h2>
<h3>h3 - Titulo de tercero nivel</h3>
<h4>h4 - Titulo de cuarto nivel</h4>
<h5>h5 - Titulo de quinto nivel</h5>
<h6>h6 - Titulo de sexto nivel</h6>

## Párrafos
Es un bloque de texto y entre párrafo y párrafo el navegador se encargará de dejar un espacio vertical.

Nota: VSC nos permite agregar texto generico de relleno, para hacer esto no situamos donde queremos agregar el texto y excribimos lorem*1.
+ El numero que va despues del asterisco es equivalente alnumero de lineas que queremos insertar

Un aspecto interesante de los parrafos es que los espacios adicionales, las tabulaciones y los saltos de linea se eliminan en el documento final.

<p>Párrafo1 - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
<p>Párrafo2 - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>

## Listas
HTML prove tres tipos diferentes de listas:
* Lista Numerada: Donde cada elemento de la lista esta precedido por un número
    * Para hacer una lista numerada utilizamos la etiqueta ol(Order List) y cada uno de los elementos de la lista se incluyen dentro de una etiqueta li(List Item).
    ```html
    <ol>
        <li>Enter Sandman<li>
        <li>Master of Puppets</li>
    </ol>

    ```
   1. Enter Sandman
   2. Master of Puppets
   * Se puede modificar la lista para que el orden de los numeros sea descendente, para hacer esto hay que colocar dentro de la etiqueta ol el atributo ***reversed*** asignandole el valor true.
* Lista de Viñetas: Donde cada elemnto esta precedido por una viñeta que usualmente es un circulo
* Lisa de Definiciones: Donde cada elemento de la lista es un termino junto con su definición.