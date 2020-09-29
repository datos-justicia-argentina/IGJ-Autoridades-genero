IGJ. Autoridades género
=======================

Este dataset contiene el recurso de las autoridades de la Inspección General de Justicia (IGJ) con el agregado del tipo de sociedad a la que pertenece y el dato de género de la autoridad asignado automáticamente en base al nombre de la autoridad, a los efectos de realizar análisis estadísticos de género.

http://datos.jus.gob.ar/dataset/igj-autoridades-genero

Características
---------------

-   **Fecha de Primera Publicación:** 21/03/2018

-   **Tags o Etiquetas:** IGJ, asociaciones civiles, autoridades, entidades, fundaciones, genero, personas jurídicas, sociedades, sociedad de responsabilidad limitada, sociedades anónimas, sociedades extranjeras

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Grupo:** Género

-   **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### IGJ. Autoridades de entidades por género - AAAAMM

-   **Nombre del archivo:** igj-autoridades-genero-AAAAMM.csv

-   **Descripción del contenido:** contiene los datos de las autoridades de la Inspección General de Justicia (IGJ) con el agregado del tipo de sociedad a la que pertenece y el dato de género de la autoridad asignado automáticamente en base al nombre de la autoridad, a los efectos de realizar análisis estadísticos de género. Se estudió el subconjunto de autoridades en los que se logró identificar automáticamente género de los siguientes tipos de entidades: Sociedad Anónima, Sociedad de Responsabilidad Limitada, Sociedad Extranjera, Asociaciones Civiles y Fundaciones.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** Autoridades de las entidades por género desde septiembre de 2016 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero_correlativo (int):** número correlativo que identifica la entidad

-   **apellido_nombre (string):** apellido y nombre de la autoridad

-   **descripcion_tipo_documento (string):** descripción del tipo de documento de la autoridad
        -D.N.I.: documento nacional de identidad
        -L.E.: libreta de enrolamiento
        -L.C.: libreta cívica
        -C.I.: cédula de identidad
        -OTROS: otros tipos de documento

-   **numero_documento (string):** número de documento de la autoridad

-   **genero_autoridad (string):** género de la autoridad. Toma valores "M" para masculino y "F" para femenino. Este campo fue asignado automáticamente en base al nombre de la autoridad, a los efectos de realizar análisis estadísticos de género (1)

-   **descripcion_tipo_societario (string):** descripción del tipo societario

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

1.  Para asignar el valor del campo genero_autoridad se cruzaron los datos de apellido_nombre de la table provista por la IGJ con una tabla de nombres permitidos aprobados por el Registro Civil obtenido de la página de la Ciudad de Buenos Aires <https://data.buenosaires.gob.ar/dataset/nombres-permitidos>
