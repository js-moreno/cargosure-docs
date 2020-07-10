# Cargosure

Esta es la documentación oficial de [Cargosure](https://www.cargosure.co), una plataforma web especializada en la gestión de certificados de pólizas de seguro específicas para trnasporte de carga en operaciones logísticas.

## Objetivo

La plataforma presenta un conjunto de herramientas enfocadas en los diferentes roles, con lo que prentende facilitar y centralizar el modelo de negocio de las pólizas de carga. Esto permite una completa gestión de *pólizas generales* teniendo en cuenta las dínamicas de negocio, la emisión de *pólizas específicas*, el cumplimento de parametros, el seguimiento de los diferentes datos relevantes a partir de métricas y gráficos del tablero de control, la descarga de información de interés y una completa trazabilida de la información desde un enfoque de autogestión bajo los pilares de la seguridad informática y la experienca de usuario. 

## Especificaciones

Cargosure esta desarrollada desde el modelo BFF a partir de Angular para Frontend y una restful API desarrollada desde Laravel para el Backend, lo que desde sus estándares permite garantizar un elevado nivel de servicio  en terminos de desempeño, mantenibilidad, escalabilidad y seguridad, asi como su potencial integración con otras aplicaciones.

## Terminología

Para el uso de esta plataforma es importante tener en cuenta las terminoligía empleada, por lo cual, se presenta a continuación un breve glosario con los términos de negocio mas relevantes:


#### Actores

 > Son las cuentas corporativas desde la que se definen los permisos que tendrán los usuarios de la plataforma. Estos actores son clasificados en un rol especifico según su papel en el negocio.


#### Generador

> Organización que funge como cliente final, aquella que es solicitante y beneficiario del seguro que ampara su carga. Si bien es una figura cororativa que hace parte de del modelo de negocio, su papel es simplemente representativo y su participación es pasiva dentro de la plataforma, por lo que no es considerado como un actor.


#### Póliza General

> Documento generado por una aseguradora que ampara la emisión de pólizas específicas bajo una serie de condiciones y segpun las tarífas pactadas.

#### Póliza Específica

> Documento emitido por un tomador o intermediario que basado en una póliza general proporciona la cobertura de riesgos previamente estipulados para un cargamento transportado por solicitud de un generador

#### Tomador

> Tipo de actor que representa al contratante de la póliza general el cual ofrece los servicios de aseguramiento de carga amparados por la misma. 

#### Usuarios

>Son las cuentas personales donde un individuo tienen acceso a la plataforma. Los usuarios están asociados a un sujeto denominado *actor* desde el cual le son conferidos los permisos que tendrá dentro de la plataforma a modo de rol.
