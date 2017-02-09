# Verifiquese Listas
Aplicación que permite gestionar listas blancas o negras a partir del escaneo de los códigos de barras de los documentos de identidad hechos por la Aplicación [Verifíquese Cédula](https://play.google.com/store/apps/details?id=se.verifique.app.cedula).
El servicio Premium de la Aplicación Verifquese Cédula permite ejecutar un llamado HTTP a una dirección o nombre DNS (URL). Luego de reconocer el código de barras del documento de identidad se ejecuta el llamado HTTP dentro de un WebView, enviando en el llamado GET, como parámetros, los datos obtenidos del código de barras escaneado del documento de identidad.
Este servicio permite una variedad de aplicaciones de uso para negocios, eventos, entradas a lugares restringidos, toma de datos de clientes para calidad de datos, etc.
## Aplicaciones
Una de esas aplicaciones es el control de acceso a un lugar restringido mediante el uso de Listas Blancas (https://es.wikipedia.org/wiki/Lista_blanca).
Las Listas Blancas contienen los datos de las identificaciones que tienen permitido el acceso, eso quiere decir que si la identificación obtenida del documento se encuentra en la lista blanca, SÍ se le da acceso, de lo contrario, si no está en la lista, NO se le da acceso al lugar que se está controlando.
## Ejemplos
Ejemplos de listas blancas son eventos en los cuales debe estar registrado para poder entrar (Capacitaciones, presentaciones privadas, eventos donde se requiere pagar para entrar, etc)
## Funcionalidades
Esta aplicación desarrollada en Java EE permite:
- Si está en la lista, se despliega un HTML con color VERDE con un mensjae de aceptado
- Si NO está en la lista, se despliega un HTML con color ROJO con un mensjae de rechazado
- Si se intenta verificar por segunda vez la misma identificación, se despliega un HTML con color AMARILLO con un mensjae de YA fue registrado!
Esta aplicación puede ser instalada en la Intranet o en la Nube para que mejore el desempeño en casos de uso masivo de eventos

## Como servicio
Este servicio también se presta en modalidad SaaS.  Para mayor información ir a: http://verifique.se
> Fecha de actualización: 2017/02/08
