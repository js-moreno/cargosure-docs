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


## Funcionalidades

La plataforma presenta un conjunto de herramientas enfocadas en los diferentes roles que prentende facilitar y centralizar el modelo de negocio de las pólizas de carga, permitiendo una completa gestión de *pólizas generales* teniendo en cuenta las dínamicas de negocio, la emisión de *pólizas específicas* previas validaciones para asegurar el cumplimento de parametros, el seguimiento de los diferentes datos relevantes a partir de metricas y graficos del tablero de control, la descarga de información de interés y una completa trazabilida de la información desde un enfoque de autogestión bajo los pilares de la seguridad informática y la experienca de usuario. 

??? important "Tip"
    La plataforma no realiza eliminaciones de ningún registro o archivo manupulado por los usuarios, en su lugar se manejan inactivaciones, lo que permite llevar una completa trazabilidad de acciones y retrotraer acciones equivocadas. 

## Acceso

El acceso a la plataforma es gestionado por los Administradores, quienes como primera medida serán los encargados de la creación del actor (la organización con uno de los roles previamente descritos) luego de la solicitud formal de un representante de la compañía tras su correspondiente validación. Paso seguido, con una solicitud similar serán creados los diferentes usuarios que se requieran bajo la figura del actor previamente creado.

Las acciones de edición restringida o inactivacion de cuentas ya sea corporativas (actor) o individuales (usuario) se realizarán tambien con una solicitud formal del representante del a organización.
