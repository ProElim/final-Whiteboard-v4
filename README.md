
FRONTEND:

La aplicacion fue construida con el comando 
npx create-react-app "clientei"

Los objetivos de ésta son:
1.- Ser capaz de realizar dibujo libre.
2.- Dibujar y/o agregar figuras geometricas como: ciculos, lineas rectas y  figuras rectangulares.  Para poder plasmar una de las figuras geometricas se debe selección entre los botones que se ofrece en el panel de herramientas para elegir el recurso a ser empleado en la pizarra.
3.- De igual forma a traves del cuadro ubicado en la parte inferior del panel de herramientas se puede generar Texto sobre el lienzo.
    3.1 Para insertar texto primero se ingresa las letras en el input  ubicado debajo del icono .
    3.2 Posteriormente se aprieta el icono de ingresar texto.
    3.3 Finalmente se selecciona el lugar del lienzo en el que se quiere posicionar para luego colocarlo.
4.- La aplicación tiene la capacidad de cambiar el color del lapiz de dibujo a traves tanto de la elección de colores a través de botones situados en la parte inferior del lienzo como de escoger la gama de colores (paleta de colores) vinculada al primer botón.
5.- Para establecer el Grosor del lapiz, si puede cambiarlo a traves de una barra deslizable situada en la parte inferior del panel de herramientas.
6.- Con el Boton "Limpiar", se puede limpiar el lienzo en su totalidad con un solo click obteniendo asi un nuevo lienzo.
7.- Se puede guardar el dibujo generado a traves del boton "Guardar". Este almacenara el lienzo en la base de datos del navegador.
Una vez guardado el dibujo inmediatamente se podra visualizar lo guardado en la parte izquierda de la pantalla, donde estan el historial de lienzos.
8- Asimismo, se puede guardar el contenido del lienzo como un archivo de imagen en el dispositivo a traves del boton "Descargar"
9. El lado derecho muestra el panel donde se muestra las imagenes que se tiene guardadas en la base de datos.
    9.1 Para cargar una imagen primero se debe elegir uno.
    9.2 Una vez la imagen fue seleccionado, se da click al boton de cargar.
    9.3 La imagen se carga en el área de trabajo (lienzo) .
    9.4 Si se quiere quitar la imagen que se coloco en el área de trabajo se hace click en el boton quitar.É
10. conectarse en tiempo real desde varios navegadores desde el puerto 3001


BACKEND:
1. la aplicacion se encuentra en docker.
2. antes de iniciar el servidor se debe correr el docker con el siguiente comando: 
docker-compose build
3. Seguido por el siguiente comando
docker-compose up
con esto se podra trabajar desde los contenedores. 
