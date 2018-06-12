# MusicHammer-Herramienta

MusicHammer-Herramienta

Es un programa para la edicion de niveles del juego MusicRush  el cual nos permite editar las pistas musicales, cargando una cancion y generando una linea de tiempo a partir de esta, para posteriormente escojer una secccion de la cancion donde se quiere 
trabajar. 


## Funcionalidad

En base a la linea de tiempo y las posiciones marcadas en esta, se creara un array  el cual contendra los siguientes datos por cada objeto:

```java

Data.add(new Shape(1,2,3,4,5)); 
//Array Data

//1-Tipo de objeto.

//2-Tiempo de aparicion.

//3-Posicion del objeto.

//4-Tamaño del objeto.

//5-Color.

```



### Estructura del Json

```java
"SongName": "Viva_la_vida", // Nombre de la cancion
  "Length": 60, // Duracion de la cancion
  "basckground":[100,111,111,], //Color del fondo
  "Level": [
    {
      "Shape": 1,// Tipo de objeto
      "Time": 29, // Tiempo de aparicion
      "Position": 4, // Posicion
      "Size" : 5,// Tamaño del objeto
      "Color": [200,150,150,] // Color
    },
    {
      "Shape": 2,
      "Time": 15,
      "Position": 2,
      "Size" : 9,
      "Color": [255,255,255,]
      ]
    },
   
  ]
  ```

  [Repositorio de github](https://github.com/AngelMalaga/AudioEditor)