---
title: 
    Práctica 3 - UT5
date: April 26th, 2022
export_on_save:
    puppeteer: true
puppeteer:
    scale: 0.8
    landscape: false
    format: "A4"
    printBackground: true
    margin:
        top: "1cm"
        right: "1cm"
        bottom: "2.5cm"
        left: "1cm"
    displayHeaderFooter: true
    headerTemplate: "&nbsp;"
    footerTemplate: "
    <span style=\"font-size: 9pt; display: flex;\">
        <span class=\"pageNumber\" style=\"margin-left: 1cm;\"></span>
        /
        <span class=\"totalPages\"></span>
        <span class=\"title\" style=\"margin-left: 1cm;\"></span>
    </span>
    "
---

<!--A incluir al principio del examen-->
<div>
    <div style="display: flex; padding: 10pt; width: 100%; justify-content: flex-end;align-items: center">
            <div >
                <h2 style="color:#7ba0cd">JS-OO</h2>
            </div>
            <img height="100" src="imágenes/Fondo.png" />
        </div>
    <div style="display: flex; background-color: #7ba0cd; justify-content: space-between; border-style: solid; border-width: thin;">
        <div style="text-align: center; color:white;font-weight:bold;width:100%">
            Normas generales para la práctica
        </div>
    </div>
  
</div>

<div style="font-size: 75%; border-style: solid; border-width: thin; padding: 3pt;">

**Condiciones de entrega**

* Se dispone de 1 sesión para realizar las actividades. Se entregarán en la fecha indicada. No se admitirán ejercicios entregados  después de esa fecha.
* La entrega de todas las actividades se hará a través de GitHub y Aules. 
* En GitHub, al repositorio LM subirás un directorio que deberá nombrarse con el nombre y primer apellido del alumno seguido de la frase “-práctica3-UT5”. El nombre y los apellidos deben ir separados por un guión. En aules el enlace a ese repositorio.

**Condiciones de corrección**

* Las actividades se deben realizar con un editor (Visual Studio Code por ejemplo)
* Se deben entregar los ficheros .html y .js que se generen.
* Si se detecta copia en alguna actividad se suspenderá automáticamente la unidad de didáctica a todos los alumnos implicados.
* Si se detecta copia de alguna página web de internet, automáticamente se suspenderá la actividad copiada.

**Calificación**

* Existen tres actividades. Todas tienen la misma puntuación.
* Las actividades se puntuarán dentro del apartado de procedimientos que es un 15% de la nota de la unidad. 
  
</div>

<div style="padding: 3pt; font-weight: bold; background-color: gainsboro; margin: 5pt 0pt 5pt 0pt;">
    Ejercicio 1. Mostrar Pokémon
</div>
<div style="font-size: 75%; border-style: solid; border-width: thin; padding: 3pt;">

**HTML**

* En este fichero debes incluir la card que muestre el Pokémon 
* Un botón siguiente
* Un botón anterior


**CSS**

* Utilizarás la librería BootsTrap pero también incluirás tus propios estilos en un fichero .css personal tuyo
* La página debe tener una imagen de fondo, un card con un fondo y unos botones con estilo personalizado.
  
**JS**

* Se te proporciona el fichero http.class.js que realiza la petición al servidor
* Crea un fichero llamado pokemon.class.js. En él vas a crear un objeto Pokémon. Tendrás que definir:
  * Constructor: donde te interesa almacenar la imagen del pokémon en cuestión, el nombre, la experiencia y el ataque del Pokémon.
  * Método getPokemon: 
    * Realiza la petición al servidor: 
    ```js
    return HTTP.ajax('GET', 
    `https://pokeapi.co/api/v2/pokemon/` + {númeroPokémon}).then(
        data => {...
    ```
    * Examina los datos obtenidos y busca la imagen, el nombre, la experiencia y el ataque del Pokémon. Crea el objeto Pokémon que retornarás.
  * Crea el método PintaPokémon que generará un card con la imagen y los datos del mismo. 
* Fichero index.js (o como lo hayas llamado) : En él harás la llamada a getPokémon y con el Pokémon retornado llamarás a Pintarlo.
* Fichero constant.js : En él almacenarás las constantes. En este caso la API_URL.
  
</div>


<div style="padding: 3pt; font-weight: bold; background-color: gainsboro; margin: 5pt 0pt 5pt 0pt;">
    Ejercicio 2. Api de películas
</div>
<div>
En obras... 
</div>
