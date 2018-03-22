IGJ. Autoridades género
=======================

Este dataset contiene el recurso de las autoridades de la Inspección General de Justicia (IGJ) con el agregado del tipo de sociedad a la que pertenece y el dato de sexo de la autoridad asignado automáticamente en base al nombre de la autoridad, a los efectos de realizar análisis estadísticos de género.

http://datos.jus.gob.ar/dataset/igj-autoridades-genero

Características
---------------

-   **Fecha de Primera Publicación:** 21/03/2016

-   **Tags o Etiquetas:** IGJ, asociaciones civiles, autoridades, entidades, fundaciones, genero, personas jurídicas, sociedades, sociedad de responsabilidad limitada, sociedades anónimas, sociedades extranjeras

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Grupo:** Género

-   **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Entidades

-   **Nombre del archivo:** igj-autoridades-genero-AAAA-MM.csv

-   **Descripción del contenido:** contiene los datos de las autoridades de la Inspección General de Justicia (IGJ) con el agregado del tipo de sociedad a la que pertenece y el dato de sexo de la autoridad asignado automáticamente en base al nombre de la autoridad, a los efectos de realizar análisis estadísticos de género. Se estudió el subconjunto de autoridades en los que se logró identificar automáticamente sexo de los siguientes tipos de entidades: Sociedad Anónima, Sociedad de Responsabilidad Limitada, Sociedad Extranjera, Asociaciones Civiles y Fundaciones. Sobre un total de 1.568.220 autoridades, 1.535.970 corresponden a los tipos societarios estudiados, y de ellos se logró asignar automáticamente sexo a 1.512.322

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero\_correlativo (int):** número correlativo que identifica la entidad

-   **apellido\_nombre (string):** apellido y nombre de la autoridad

-   **descripcion\_tipo\_documento (string):** descripción del tipo de documento de la autoridad

-   **numero\_documento (string):** número de documento de la autoridad

-   **sexo\_autoridad (string):** sexo de la autoridad. Toma valores "M" para masculino y "F" para femenino. Este campo fue asignado automáticamente en base al nombre de la autoridad, a los efectos de realizar análisis estadísticos de género (1)

-   **descripcion\_tipo\_societario (string):** descripción del tipo societario<span id="domicilios" class="anchor"><span id="campos-del-recurso-1" class="anchor"></span></span>

### Notas

1.  Para asignar el valor del campo sexo\_autoridad se cruzaron los datos de apellido\_nombre de la table provista por la IGJ con una tabla de nombres permitidos aprobados por el Registro Civil obtenido de la página de la Ciudad de Buenos Aires <https://data.buenosaires.gob.ar/dataset/nombres-permitidos>
