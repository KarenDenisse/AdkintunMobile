# AdkintunMobile
**Adkintun** es un proyecto que busca medir la calidad del acceso a Internet en distintas plataformas, estableciendo métricas dependiendo las características inherentes a la tecnología utilizada para la conexión. El proyecto surge el año 2011 [[1]](https://www.fayerwayer.com/2012/04/chile-adkintun-el-proyecto-para-medir-la-calidad-de-la-banda-ancha-en-el-pais/) usando sondas de monitoreo en conexiones particulares, realizando mediciones activas para examinar la velocidad de conexión, latencia a distintos sitios, entre otras características de las conexiones fijas.

**Adkintun Mobile** es una aplicación *Android*, corresponde a la continuación del proyecto Adkintun el cual por medio de mediciones que no observan el tráfico, permite analizar la cantidad de datos enviada y recibida durante el día, la calidad de la señal en las antenas y el tipo de conexión percibida (2g, 3g, etc), entre otros datos útiles. Entrega al usuario información respecto al estado de su conexión móvil, además de informes diarios respecto a la conectividad, tipo de señal recibida y consumo de datos por aplicación.

## Código Público
El proyecto Adkintun Mobile está desarrollado en diferentes módulos:

- [AdkintunMobile-AndroidClient](https://github.com/niclabs/AdkintunMobile-AndroidClient) Aplicación móvil para dispositivos con sistema operativo Android.
- [AdkintunMobile-Server](https://github.com/niclabs/AdkintunMobile-Server) Servidor del sistema responsable de la recepción y procesamiento de eventos reportados por los clientes móviles.
- [AdkintunMobile-FrontEnd](https://github.com/niclabs/AdkintunMobile-FrontEnd) Aplicación web para la visualización de reportes generados con los datos agregados procesados.
