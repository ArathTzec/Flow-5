# Flow-5
Este repositorio contiene el flow de NodeRed para obtener la informacion climatica por API


## Material necesario
Para poder realizar necesario es necesario tener instalado:
- [Node.js](https://github.com/nodesource/distributions/blob/master/README.md) Usar la versión LTS v16x e instalar los build tools.
- [Node-Red](https://nodered.org/docs/getting-started/local)
- Instalar dashboard, puedes consultar el como mediante la siguiente guía: [dashboard CodigoIoT](https://edu.codigoiot.com/mod/page/view.php?id=1080)
- [OpenWeatherMap](https://openweathermap.org). Servicio meteorológico gratuito. Se requiere cuenta, pero no se requiere ningun pago.
- [Flow-4](https://github.com/ArathTzec/Flow-4)


## Notas

>No olvides primero abrir node red desde la terminal con node-red, de igual manera, abrir el **localhost:1880** en tu navegador de preferenecia
>El mensaje mqtt usado para probar este flow es `mosquitto_pub -h localhost -t ccodigoIoT/fow5/mqtt -m '{"ID":"Hugo Vargas","temp":18,"hum":78}'`

## Instrucciones

1. Arrancar NodeRed con el comando `node-red`
2. Importar el flow del repositorio.
3. Coloca tu API Key personal en la API Call del nodo HTTP Request.
4. Actualiza la IP del broker público.
5. Hacer clic en el boton Deploy.

>Estas instrucciones fueron proporcionadas por: [Hugo-Vargas](https://github.com/hugoescalpelo/flow5-NodeRed-ClimaAPI)

## Resultados
Una vez completados los pasos anteriores te dirigirá al Dashboard, que es la interfaz donde ver la temperatura y humedad dependiendo del mensaje que envies, trata de enviar el codigo que se encuentra en notas. Tambien recíbiras los datos de los demas compañeros
![](https://github.com/ArathTzec/Flow-5/blob/main/Dashboard-Flow5.pngraw=true)
