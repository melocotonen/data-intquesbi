## SQL

Supongamos que tenemos el siguiente esquema de Base de Datos

* Pólizas
* status podrá ser activo o inactivo
* Siniestros
* claim_type podrá ser telemático, presencial o mixto
* Usuarios

<img src="E-R test.png" />

Write SQL queries to extract the following information:

**1)** Número de pólizas activas

<br/>


**2)** Todas las campañías activas. Una compañia está activa si al menos hay una poliza activa (company_id)

<br/>

**3)** Número de compañías activas

<br/>

**4)** Numero de siniestros por cada poliza desglosado por tipo de siniestro

<img src="Q4.png" />

<br/>

**5)** Número de siniestros por compañía y por tipo de evento

<img src="Q5.png" />

<br/>

**6)** ¿Cómo crearias la tabla para relacionar usuarios y polizas?

**7)** Número de polizas por usuario y por estado de la poliza teniendo en cuanta que puedes usar la tabla de la relación anterior
