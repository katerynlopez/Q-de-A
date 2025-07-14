## Trabajo Final Algoritmia y Programación 2025-1
Profesor: John Heider Dávila Dávila.

Curso: Algoritmia y Programación

### INTEGRANTES
* Alexandra Vásquez Gallego
* Carolayn Restrepo Tavera
* Kateryn Lopez Serna


### VÍNCULOS ACADÉMICOS Y DESCRIPCIÓN

### Alexandra Vásquez
##### Estudiante de ingeniería industrial (virtual) sede Medellín
##### Semestre: 4

#### Habilidades y fortalezas
* Resolución de problemas
* Trabajo en equipo
* Uso de herramientas digitales

### Carolayn Restrepo Tavera
##### Estudiante de de Ingeniería Indistrial (virtual) sede Medellín
##### Semestre: 4

#### Habilidades y fortalezas
* Proactividad
* Resistencia
* Compromiso

### Kateryn López Serna
##### Estudiante de Ingeniería Industrial (virtual) sede Medellín
##### Semestre: 4

#### Habilidades y fortalezas
* Capacidad Analítica
* Adaptabilidad

[ACTA DE ENTENDIMIENTO](https://github.com/Alexandra-vasquez/Trabajo-final-_1/blob/main/ACTA%20DE%20ENTENDIMIENTO.pdf)

[ACTA DE COLABORACIÓN](https://github.com/Alexandra-vasquez/Trabajo-final-_1/blob/main/ACTA%20DE%20COLABORACI%C3%93N.pdf)


## PARQ_UDEA

![logo](https://github.com/Alexandra-vasquez/Trabajo-final-_1/blob/main/_69d15de4-b5a9-44d2-ad32-344f9d5e7cf0-removebg-preview.png?raw=true)

El parqueadero Parqudea es un espacio que presta su servicio a vehículos del sector de la Universidad de Antioquia. Este solo permite el ingreso de automóviles, el ingreso de motos no es aceptado. El parqueadero Parqudea requiere de sus habilidades como un equipo de programación de la respetada y bien ponderada Universidad de Antioquia para crear un software de consola en Python para poder gestionar usuarios, generar cobros, facturas, reportes y algo más.

El parqueadero ParqUdea cuenta con tres personas que trabajan turnos de 6 horas para atender a los usuarios que ingresan a usar el servicio y no presentar interrupciones ni contratiempos en el horario de 6:00 a.m. a 12:00 p.m. en jornada continua. El programa debe registrar usuarios, ingresar y retirar vehículos y generar reportes administrativos. 


### Esta obra está licenciada bajo CC BY-NC-ND 4.0
El software que se desarrollará permitirá llevar un registro más organizado y eficiente, con esto no solo se verán beneficiados los empleados de la zona de registro y el área administrativa, sino también los usuarios.

#### Objetivos y Beneficios
*	Simplificar el registro de ingreso y salida de vehículos: así tendremos un mejor conteo de entradas y salidas del parqueadero.
*	Calcular automáticamente el valor a pagar según el tiempo de permanencia; esto hará que este trámite sea más seguro y eficaz teniendo en cuenta que este software tiene la capacidad de generar y exportar un reporte de transacciones en un archivo plano y así tener un soporte y una contabilidad más precisa 
*	Controlar el número de espacios disponibles:  esto hará que el parqueadero tenga un mejor flujo y mayor optimización del tiempo
*	Facilitar el análisis de la información para la toma de decisiones mediante la generación de reportes con acceso sólo para administradores protegido con usuario y contraseña.
*	Validación de errores comunes en el ingreso de información para mejorar la calidad de los datos registrados

#### ¿Qué problema específico estamos tratando de resolver con esta aplicación?
Eliminar la gestión manual (en papel), reducir errores en el cobro y aumentar el control administrativo sobre los vehículos, usuarios y operaciones del parqueadero.

#### ¿Quiénes son los usuarios finales y qué necesidades específicas tienen?
* Usuarios del parqueadero: quieren ingresar/retirar sus vehículos sin complicaciones.
* Empleados que atienden: necesitan un sistema ágil, claro y rápido para registrar entradas/salidas y generar cobros.
* Administrador: requiere reportes detallados sobre la operación y estadísticas del parqueadero.

#### Gestión de accesos y permisos
El sistema contará con niveles de acceso diferenciados:
* Usuarios comunes: Pueden registrar su vehículo y consultar su información al ingresar o salir del parqueadero. Su acceso está limitado únicamente a sus propios datos y transacciones.
* Administradores o “Súper usuarios”: Acceden mediante usuario y contraseña previamente definidos en el sistema. Tienen privilegios para:
    * Consultar estadísticas operativas (total de ingresos, retiros, pagos, usuarios activos, etc.).
    * Generar y exportar reportes.
    * Visualizar tiempos promedios de permanencia y vehículos con máximos o mínimos tiempos de parqueo.

#### Proyección futura e impacto
Este proyecto no solo representa una solución puntual al problema de gestión manual en ParqUdea, sino que tiene una visión a largo plazo:
* Escalabilidad: La estructura del software está diseñada para adaptarse fácilmente a nuevas funcionalidades.
* Interoperabilidad: Los archivos CSV exportados podrán integrarse a plataformas de control financiero o sistemas de gestión administrativa más avanzados, si el parqueadero decide ampliar su infraestructura digital.

#### Impacto a la comunidad interna:
Estudiantes, docentes y administrativos contarán con un servicio más ágil, transparente y ordenado. Se reducirá el tiempo de espera, se evitarán errores en cobros y se facilitará el control del parqueo.

#### Impacto a la comunidad externa:
El proyecto fortalece la experiencia práctica de los estudiantes en el desarrollo de software con impacto real.

#### Proyección académica y profesional:
La creación del repositorio GitHub, el trabajo colaborativo, la documentación técnica y el cumplimiento de entregas parciales fomentan habilidades que alinean con las demandas del mercado laboral actual en desarrollo de software, análisis de datos y gestión de proyectos.


### DESCRIBE REQUISITOS FUNCIONALES Y NO FUNCIONALES DEL CODIGO

### REQUISITOS FUNCIONALES 

#### Registro de usuario:
* Nombre
* Apellido
* Documento
* Placa

#### Ingreso y retiro de vehículos:
* Solo se permitirá entrada vehículos de usuarios registrados
* Se cobrará la tarifa por hora, y tarifa por cuarto de hora total.
* Condición de pago mínimo (7000).

#### Acceso de administrador: 
* El programa solo permitirá acceder al espacio de administrador a quien tenga usuario y contraseña de administración.

#### Espacio de administración:
* Total de vehículos registros
* Total de vehículos retirados
* Total de vehículos sin retirar
* Total de pago de vehículos retirados
* Tiempo promedio de estancia por vehículo en el parqueadero
* Lista de usuarios
* Vehículos con tiempo de parqueo máximo y mínimo

#### Exportación de datos
* Enviar registros de ingresos, salidas y cobros a un archivo plano.
  #### ¿Qué se debe exportar?
* Ingresos de vehículos
* Usuario, placa, hora/fecha de entrada.
* Salidas de vehículos
* Usuario, placa, hora/fecha salida, duración, cobro total.
* Cobros realizados
* Placa, tiempo en parqueo, monto pagado.
* Usuarios registrados


#### REQUISITOS NO FUNCIONALES 
* Facilidad de uso
* Proteccion de datos
* Adaptabilidad para usar en diferentes equipos
* Confiabilidad


[ACTA DE RESPONSABILIDAD, DIAGRAMA DE GANNTT Y PRESUPUESTO](https://github.com/Alexandra-vasquez/Trabajo-final-_1/blob/main/ACTA%20DE%20RESPONSABILIDAD.pdf)


