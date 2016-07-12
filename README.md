# AdkintunMobile
Adkintun es un proyecto que busca medir la calidad del acceso a Internet en distintas plataformas, estableciendo métricas dependiendo las características inherentes a la tecnología utilizada para la conexión. En su versión móvil permite, a través de mediciones pasivas, caracterizar la infraestructura de la red móvil de los distintos operadores proveedores del servicio. Por otro lado, en su versión fija, realiza mediciones activas para examinar la velocidad de conexión, latencia a distintos sitios, entre otros.

Adkintun mobile es una aplicación Android, que realiza mediciones sin observar el tráfico, analizando la cantidad de datos enviada y recibida durante el día, la calidad de la señal en las antenas y el tipo de conexión (2g, 3g, etc), entre otros datos útiles. Entrega al usuario información respecto al estado de su conexión móvil, además de informes diarios respecto a la conectividad, tipo de señal recibida y consumo de datos por aplicación. Ejemplo de estas funcionalidades pueden verse en las imágenes a continuación.

## Código Público
El proyecto Adkintun Mobile está desarrollado en diferentes módulos:

- [AdkintunMobile-AndroidClient](https://github.com/niclabs/AdkintunMobile-AndroidClient) Aplicación móvil para dispositivos con sistema operativo Android.
- [AdkintunMobile-Server](https://github.com/niclabs/AdkintunMobile-Server) Servidor del sistema responsable de la recepción y procesamiento de eventos reportados por los clientes móviles.
- [AdkintunMobile-FrontEnd](https://github.com/niclabs/AdkintunMobile-FrontEnd) Aplicación web para la visualziación de reportes generados con los datos agregados procesados.
