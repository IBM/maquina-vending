# Parte 3: Configurar el dialogo para que el asistente funcione correctamente

## Paso 1: Hacer click en el propio diálogo

![Diálogo](../images/dialogo.png)

## Paso 2: Acceder a los nodos de dialogo y pinchar en el nodo llamado Codigo de acceso

![NodoCodigo](../images/nodoCodigo.png)

## Paso 3: Acceder a Customize para así activar las llamadas al webhoook

![Customize](../images/customize.png)

## Paso 4: Una vez dentro, activar las llamadas al webhoook y aplicar los cambios

![ActivarWebhook](../images/activarWebhook.png)

Activando esta opción se va a permitir enviar peticiones HTTP POST a la URL del webhook que se define en la parte de opciones. Esta URL corresponde a la URL pública de la función, la cuál va a leer de una base de datos Cloudant el código que devuelve el chat-bot cuando se solicita.

![Opciones](../images/opciones.png)
