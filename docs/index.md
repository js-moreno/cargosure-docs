# Cargosure

Esta es la documentación oficial de [Cargosure](https://www.cargosure.co), una plataforma web especializada en la gestión de certificados de seguro para mercancias en operaciones logísticas, funcionando como un mercado en el que convergen *aseguradoras*, *intermediarios*, *tomadores* y *generadores*.

## Especificaciones

Cargosure esta desarrollada desde el modelo BFF a partir de Angular 9 para Frontend y una restful API desarrollada desde Laravel 7 para el Backend, lo que desde sus estándares permite garantizar un elevado nivel de servicio  en terminos de desempeño, mantenibilidad, escalabilidad y seguridad, asi como su potencial integración con otras aplicaciones web

## Terminología

Para el uso de esta plataforma es importante tener en cuenta las terminoligía empleada, por lo cual, se presenta a continuación un breve glosario con los términos de negocio mas relevantes:

#### Usuarios

>Son las cuentas personales desde la que un individuo tienen acceso a la plataforma. Los usuarios están asociados a un sujeto denominado *Actor* desde el cual le son conferidos los permisos que tendrá dentro de la plataforma

#### Actores

 > Son las cuentas corporativas desde la que se definen los permisos que tendrán los usuarios asociados a estas. Estos actores son clasificados en un rol especifico que podrá ser; *administrador* *aseguradora* , *intermediario* o *tomador*, dependiendo con su papel en el negocio.

#### Administrador

> Actor responsable de la administración de la plataforma, realizando actividades como creación, modificación e inactivación de actores y usuarios

#### Aseguradora

> Actor encargado de la gestión directa de pólizas generales, asi como la supervisión de los certificados de seguro emitidos desde sus polizas generales. 

#### Intermediario

> Representación de la figura que media entre *aseguradora* y  *tomador*. Este rol es solo representativo, no cuenta con acceso a la plataforma.


#### Tomador

> Actor que representa los agentes de carga o transportistas que ofrecen servicios de aseguramiento de carga amparados por una aseguradora. 

#### Generador

> Organización que funge como cliente final, aquella que es solicitante y beneficiaria del seguro que ampara su carga. Este rol es solo representativo, no cuenta con acceso a la plataforma.

#### Póliza General

> Documento digital generado por una *aseguradora* que ampara la emisión de certificados de seguro bajo una serie de restricciones y con unas tarífas pactadas.

#### Certificado de Seguro

> Documento digital emitido por un tomador que basado en una poliza general proporciona la cobertura de riesgos previamente estipulados para la carga transportada cuyo beneficiario es el *generador*

## Funcionalidades

La plataforma presenta un consjunto de herramientas que prentende facilitar y centralizar el modelo de negocio de las polizas de carga, permitiendo una completa gestión de *pólizas generales* teniendo en cuenta las dínamicas de negocio, la emisión de certificados de seguro previas validaciones para asegurar el cumplimento de parametros, la carga de registros masivos de expediciones en gran número y el seguimiento de los diferentes datos de interés a partir de metricas y graficos del tablero de control.

## Acceso

El acceso a la plataforma es suministrado por los Administradores y solo permitido para Administradores, aseguradoras y tomadores. Sin embargo hay opciones de consulta que no requiere de autenticacion cono es el caso de la validación de certificados de seguro.