# Instrucciones:
En el github hay dos .zip, estos se deben descomprimir.
En la carpeta de ChatServer esta el projecto para ejecutar el servidor, en la otra carpeta "Tarea What" estara el codigo
para abrir los clientes.

# Para ejecutar los projectos hay dos opciones:

## Primera y mas segura:

Desde el visual studio se abrira el projecto "ChatServer", luego se ejecutara con el boton de play del visual, luego
de eso se abrira una terminal el cual sera el servidor.

Luego se debe hacer lo mismo con "Tarea What", el cual sera la interfaz del cliente,
### Para abrir mas clientes se tienen que abrir nuevamente desde el Visual Studio.

Luego de abrir los clientes tendremos las interfaz, ya que no pude encontrar la forma de añadir un puerto especifico al
que enviar los mensajes, agregue en el primer cuadro de texto la opcion de ponerse un nombre, luego en el cuadro de texto
de abajo podremos escribir los mensajes que queramos.

## Segunda opcion:

Abriremos un terminal y escribiremos dotnet run --project "La ruta donde este la carpeta de ChatServer.cs"
#### Importante ejecutar primero el server

Luego abriremos otro terminal y escribiremos dotnet run --project " "Ruta donde esta Tarea What.csproj" "
y se abrira la interfaz del cliente, para abrir otro cliente haremos los mismo nuevamente, pero solo con el cliente.


### Datos Importantes
Es indispensable abrir primero el servidor antes del cliente, por que si no se hace dara un error.
El projecto no trae para especificar el puerto al que se quiere enviar el mensaje.
El github esta de esa forma (con dos carpetas zip) ya que no encontre la forma de subir dos projectos diferentes en el
mismo respositorio.
