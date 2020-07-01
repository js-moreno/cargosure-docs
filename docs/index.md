# Cargosure

Esta es la documentación oficial de [Cargosure](https://www.cargosure.co), una plataforma web especializada en la gestión de pólizas de seguro para carga en operaciones logísticas, funcionando como un mercado en el que convergen oferentes, mediadores y demandantes.

## Especificaciones

Cargosure esta desarrollada desde el modelo BFF a partir de Angular 9 para Frontend y una restful API desarrollada desde Laravel 7 para el Backend, lo que desde sus estándares permite garantizar un elevado nivel de servicio  en terminos de desempeño, mantenibilidad, escalabilidad y seguridad, asi como su potencial integración con otras aplicaciones.

## Terminología

Para el uso de esta plataforma es importante tener en cuenta las terminoligía empleada, por lo cual, se presenta a continuación un breve glosario con los términos de negocio mas relevantes:


#### Actores

 > Son las cuentas corporativas desde la que se definen los permisos que tendrán los usuarios de la plataforma. Estos actores son clasificados en un rol especifico que podrá ser; *administrador*, *aseguradora* , *intermediario* o *tomador*, segun su papel en el negocio.

#### Cuentas

> Es la representación de un sujeto dentro de la aplicación, en ella se almacena la información de identificación para garantizar una adecuada autenticación y correspondiente autorización de acceso a los recursos permitidos disponibles.

#### Generador

> Organización que funge como cliente final, aquella que es solicitante y beneficiaria del seguro que ampara su carga. Si bien es una figura cororativa que hace parte de del modelo de negocio, su papel es simplemente representativo y su participación pasiva, por lo que no es considerado como un actor.

#### Interesados

> Conjunto de entidades o individuos involucradas con el negocio pero que solo son representadas simbolicamente en la plataforma.


#### Póliza General

> Documento generado por una aseguradora que ampara la emisión de pólizas específicas bajo una serie de restricciones y con unas tarífas pactadas.

#### Póliza Específica

> Documento emitido por un tomador o intermediario que basado en una póliza general proporciona la cobertura de riesgos previamente estipulados para un cargamento transportado por solicitud de un generador

#### Tomador

> Tipo de actor que representa los agentes de carga o transportistas que ofrecen servicios de aseguramiento de carga amparados por una póliza general. 

#### Usuarios

>Son las cuentas personales desde la que un individuo tienen acceso a la plataforma. Los usuarios están asociados a un sujeto denominado *actor* desde el cual le son conferidos los permisos que tendrá dentro de la plataforma a modo de rol.


## Objetivo

La plataforma presenta un conjunto de herramientas enfocadas en los diferentes roles, con lo que prentende facilitar y centralizar el modelo de negocio de las pólizas de carga, permitiendo una completa gestión de *pólizas generales* teniendo en cuenta las dínamicas de negocio, la emisión de *pólizas específicas* previas validaciones para asegurar el cumplimento de parametros, el seguimiento de los diferentes datos relevantes a partir de métricas y gráficos del tablero de control, la descarga de información de interés y una completa trazabilida de la información desde un enfoque de autogestión bajo los pilares de la seguridad informática y la experienca de usuario. 

Del mismo modo el sistio web tiene funcionalidades públicas a las cuales puede acceder sin requerir de un usuario en la platafarma; como es el caso de la *consulta expresa*