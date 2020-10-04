# Instrucciones

Configure las preferencias de ejecución del programa accediendo al archivo ./config.json,
en este encontrará el key "port" que hace referencia al puerto en el que se ejecutará el proyecto (servidor de aplicación).

Una vez esté seguro de configurar el puerto ejecute los siguientes comandos para llevar a cabo la ejecución, en consola le aparecerá un mensaje diciendo que se está escuchando en el puerto que haya configurado (Listening on http://localhost:3000) que por defecto es 3000, si el 80 está libre de preferencia configurlo en el archivo config.json.

# Arrancar el proyecto

Para ejecutar el proyecto solo bastará con ejecutar las siguientes líneas en una consola a la raiz del proyecto actual, debe asegurarse de estar posicionado en la raiz de este código fuente y ejecutar el siguiente comando para instalar las dependencias.

```string 
$ npm install 
```
Una vez terminado el comando anterior ejecute el siguiente para correr el servidor de aplicación y todo en conjunto.
```string 
$ npm start
```
# Configurar puerto COM / Conexión con Arduino
Para realizar esta configuración, solo acceda a esta línea del archivo config.json: https://github.com/Jhonjaider1000/rasberryinterface/blob/ec107fcf038f3c90e78ca3f1274be738e6c40a6c/config.json#L3 y actualice ese parámetro por el puerto al que se va a conectar por defecto.

Finalmente acceda en el navegador al http://localhost:3000 o el puerto que haya configurado.
