
Como descargar
Para descargar se necesita el el archivo en el boton verde y dandole a descargar en .zip a momento de descargar se necesita extraer y colocar en la carpeta “mods” dentro de “Codename engine” la ruta deberia quedar asi “Codename engine\mods\modcharts” o si se quiere incluir en tu mod simplemente meter todo el contenido dentro de la carpeta mods a tu mod

Información adicional
En caso de no tener conocimiento dentro de la carpeta “data\config\modpack.ini” puedes modificar el nombre de la ventana, cambiar el icono de la aplicacion y cambiar el icono de DiscordRPC 

Como usar
Dentro de Codename Engine deberás dar Tab para cambiar y seleccionar el mod (en caso de no estar activo) luego ir a configuracion de ahi ir a mi a las opciones miscelaneas y activar las configuraciones de desarrollador luego ir a el menu principal y presionar 7 de seleccionar el Modchart editor que se encuentra hasta abajo, luego seleccionar una canción de tu mod y ya empezar a editar

En caso de querer crear un Modchart por dificultad
Para crear un Modchart diferente por dificultad será necesario ir a la carpeta de la cancion y crear un nuevo xml, la ruta normalmente sera “TuMod\songs\TuCancion\modchart.xml” aqui tendras que renombrar el “modchart.xml” a “modchart-hard.xml” y crear nuevos xml para otras dificultades a “modchart-NombreDeDificultad.xml” el modchart manager soporta dificultades persobalizadas asi que mientras sea el mismo que eo de la cancion funcionará sin problemas

Como agregar shaders/modificadores de notas/FunkinModchartModifier al modchart
Una vez en el editor presionar arriba donde dice Modchart > Timeline Items y ahi agregar los shaders o algun modificador para las notas se necesita tener los shaders en la carpeta “shaders\modchart” (Los shaders que vienen por default estan en “addons\ModchartEditor-PostProcessShader\shaders\modcharts” ahi puedes mirarlos) y los modifiers estan en la carpeta “addons\ModchartEditor-GPUNotesModchart\modifiers” en caso de querer agregar mas usar de base el shader llamado “notePerspective” ya que este es el que define las notas
