Este proyecto tiene la siguiente arquitectura:
- La carpeta TENSORFLOW, contiene los códigos de las pruebas que se realizaron para el capítulo de Redes Neuronales de este TFG.
- El archivo 'transformacionjson.ipynb', contiene el código python necesario para pasar los archivos .json de nuestro dataset de imágenes, al formato necesario para YOLO.
- La carpeta YOLO que contiene los códigos y los resultados obtenidos en las pruebas realizadas para el capítulo de desarrollo. Dentro de este también tenemos la siguiente arquitectura:
  - La carpeta PRUEBA1, contiene el código python utilizado para la primera prueba realizada, correspondiente con un entrenamiento de un modelo YOLOv8 nuevo con el dataset coco128.
  - La carpeta PRUEBA2, contiene el código python utilizado para la segunda prueba realizada, correspondiente con un entrenamiento de un modelo YOLOv8 ya preentrenado y posteriormente reentrenarlo con el dataset coco128.
  - La carpeta PRUEBA3, contiene:
    - El código python utilizado para la tercera prueba realizada, correspondiente con un entrenamiento de un modelo YOLOv8 ya preentrenado, posteriormente se reentrena con un dataset propio y finalmente se
        hacen predicciones de detección de vehículos en un video. 
    - Una carpeta donde tenemos almacenado el dataset propio utilizado para estas pruebas.
    - Dos carpetas con los resultados obtenidos.
