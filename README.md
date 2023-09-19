# VC_P1

En esta práctica hemos realizado diferentes tareas con el objetivo de aprender a crear imágenes de un determinado tamaño, acceder a los valores asociados a un determinado píxel, modificar dichos valores, dibujar primitivas gráficas básicas sobre una imagen, abrir una imagen de disco, así como acceder a los fotogramas de un vídeo o captura de cámara.

En la primera tarea, hemos creado una imagen de tamaño 800x800 con la textura de un tablero de ajedrez. Para ello, hemos implementado un bucle anidado en el cual recorremos las filas y columnas del tablero y pintamos cuadrados blancos en la coordenadas que corresponda, teniendo en cuenta que en las filas pares (0, 2, 4...) el primer cuadrado será blanco y en las impares (1, 3, 5...) el primer cuadrado será negro.

En la segunda tarea, hemos realizado un diseño artístico parecido a los cuadros de Mondrian.

En la tarcera tarea, hemos replicado la tarea 1, pero utilizando las funciones de dibujo de la librería Opencv.

En la cuarta tarea, hemos modificado uno de los planos de la imagen obtenida por la webcam. Para ello, igualamos el canal B a 255 para cada frame que se capturaba con la webcam, dando asi una visión azulada de la imagen.

En la quinta tarea, hemos marcado el píxel más claro y más oscuro de la imagen obtenida por la webcam. Para ello, transformamos la imagen a escala de grises, y con uso de una función que devuelve los mínimos y máximos de cada píxel pudimos obtener las zonas mas oscuras y claras de la imagen en donde dibujamos unos círculos, y esto por cada frame que recibíamos de la webcam.

En la sexta tarea, hemos elaborado una propuesta pop art en la cual mostramos una imagen en grises, que representa los 10 últimos frames obtenidos por la webcam mezclados en uno sólo.
