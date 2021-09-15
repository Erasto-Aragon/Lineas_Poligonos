## 2A: Cuadricula. Pantalla completa, cada cuadro deberá medir 30 unidades por lado, como se muestra en el ejemplo. Deberá realizar la cuadricula UTILIZANDO SOLAMENTE PUNTOS, NO LINEAS, NO POLIGONOS, NO FIGURAS. El color de fondo y color de los puntos es libre.
![Captura de pantalla 2021-09-14 214700](https://user-images.githubusercontent.com/71147346/133362085-b30de54f-76c0-4c0e-abee-35f90ec2f70c.jpg)

Iniciamos el programa declarando las variables y el main añadimos las lineas de codigo que corresponde a tamaño, ubicacion del JFrame, al igual que el Canvas:

![Captura de pantalla 2021-09-14 215625](https://user-images.githubusercontent.com/71147346/133362892-7965d21b-8857-41a4-9c05-1e687b3e2b4c.jpg)

Siguiendo con el codigo en el metodo Display generamos un for dentro de un for, esto nos va ir generado las cuadriculas repetitivas hasta llegar a los bordes, mediante los puntos al estar tan juntos se generan lineas a la vista:

![Captura de pantalla 2021-09-14 220022](https://user-images.githubusercontent.com/71147346/133363442-dfebcd32-7ee7-46a8-ba0e-79e2cddfca3a.jpg)

Ejecutando el programa nos queda de la siguiente forma:

![WhatsApp Image 2021-09-14 at 8 26 16 PM](https://user-images.githubusercontent.com/71147346/133362496-d8e9861e-ebad-4be0-95e2-6f80de682368.jpeg)
.
.
.
## 2C: Ejercicio: Trazo de líneas y polígonos. Construir una aplicación en la que se pueda trazar la línea recta que une dos puntos, que trace las líneas rectas que unan puntos sucesivos marcados con el ratón y dado el valor del número de lados (n), dibujar el polígono correspondiente de n lados.

El ejercicio se realizo en el lenguaje Java, mediante el IDE de Netbeans Apache.
Creamos un nuevo proyecto, utilizando el IDE y las herramientas que nos facilita se creo una clase JFame

![Captura de pantalla 2021-09-10 191435](https://user-images.githubusercontent.com/71147346/132929739-ca982819-8981-45d1-89db-ec97148a7880.jpg)

Ya que el ejercicio es parecido a una pizarra, procedemos a introducir la linea de codigo MAXIMIZED_BOTH permite maximizar la pantalla y adaptarse al correr el programa

![Captura de pantalla 2021-09-10 191456](https://user-images.githubusercontent.com/71147346/132929815-b6f70d04-3d90-4c8b-b30c-3f34c102c0d7.jpg)

Lo siguiente es crear un arreglo el cual guarde la ubicación de los puntos, pasamos a crear los puntos que cada vez que se presione el mouse se creara un punto el cual sera unido con lineas a traves de la captura de ubicacion del ultimo punto.

![Captura de pantalla 2021-09-10 191539](https://user-images.githubusercontent.com/71147346/132929859-06ab8b8a-d9b7-48f5-84ab-679069cb4619.jpg)

Agregamos un boton para que el usuario vuelva abrir una nueva ventana en blanco y pueda dibujar

![Captura de pantalla 2021-09-10 191600](https://user-images.githubusercontent.com/71147346/132931603-4c093762-2b7e-4a6d-81f3-10b584a8d90b.jpg)

El programa siendo ejecutado queda de la siguiente manera:

![20210910-180806_xU1lKbyc_Vo6R (1)](https://user-images.githubusercontent.com/71147346/132927296-40948d0a-96f0-4131-9cd1-d0eb62066950.gif)


