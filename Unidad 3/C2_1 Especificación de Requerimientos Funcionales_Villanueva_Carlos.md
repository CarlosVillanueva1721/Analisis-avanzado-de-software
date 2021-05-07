# Inicio del proyecto

## :trophy: C2.1 Reto en clase

Requerimientos funcionales del sistema

### :blue_book: Instrucciones

- De acuerdo con la información presentada por el asesor referente al tema, y basado en el caso de estudio indicado responder la sesión indicada en el desarrollo de la actividad.
- Toda actividad o reto se deberá realizar utilizando el estilo **MarkDown con extension .md** y el entorno de desarrollo VSCode, debiendo ser elaborado como un documento **single page**, es decir si el documento cuanta con imágenes, enlaces o cualquier documento externo debe ser accedido desde etiquetas y enlaces, y debe ser nombrado con la nomenclatura **C2.x_NombredelaActividad_NombreAlumno.pdf.**
- Es requisito que el .MD contenga una etiqueta del enlace al repositorio de su documento en GITHUB, por ejemplo **Enlace a mi GitHub** y al concluir el reto se deberá subir a github.
- Desde el archivo **.md** exporte un archivo **.pdf** que deberá subirse a classroom dentro de su apartado correspondiente, sirviendo como evidencia de su entrega, ya que siendo la plataforma **oficial** aquí se recibirá la calificación de su actividad.
- Considerando que el archivo .PDF, el cual fue obtenido desde archivo .MD, ambos deben ser idénticos.
- Su repositorio ademas de que debe contar con un archivo **readme**.md dentro de su directorio raíz, con la información como datos del estudiante, equipo de trabajo, materia, carrera, datos del asesor, e incluso logotipo o imágenes, debe tener un apartado de contenidos o indice, los cuales realmente son ligas o **enlaces a sus documentos .md**, _evite utilizar texto_ para indicar enlaces internos o externo.
- Se propone una estructura tal como esta indicada abajo, sin embargo puede utilizarse cualquier otra que le apoye para organizar su repositorio.

```
| readme.md
| | blog
| | | Cx.1_NombredelaActividad.md
| | | Ax.1_NombredelaActividad.md
| | diagrams
| | docs
| | html
| | img
| | pdf    
```


## :pencil2: Desarrollo

1. Identifique como mínimo 10 requisitos funcionales del sistema, dándoles un identificador, nombre, detalle o descripción de su funcionalidad, pre-condiciones, secuencia normal, post-condiciones y excepciones.
2. Se propone utilizar la siguiente tabla, sin embargo puede utilizar cualquier otro formato considerando que se deben incluir los elementos solicitados en el punto anterior.


|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-02 |
|Nombre:          |Inicio de sesión |
|Detalle:         |Los usuarios accederán a la plataforma mediante una interfaz utilizando las credenciales proporcionadas por la empresa. |
|:triangular_flag_on_post: **Pre-condiciones**  | El registro del usuario se ha realisado desde la base de  datos de la empresa, por lo cual no requiere de registro manual. |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El usuario accederá a la interfaz de inicio de sesión.|
|Paso 2|El usuario ingresará sus datos en los campos correspondientes.|
|Paso 3|El sistema validara los datos.|
|:triangular_flag_on_post: **Post-condición** |La plataforma redirigirá al usuario a la página de inicio  a la que pertenecen los datos de su registro.|
|:runner: **Excepciones**|Acción|
|Paso 1|Si el usuario no se encuentra registrado, dirigirse con su supervisor.|
|Paso 2|Si los datos ingresados son incorrectos, aparecerá un mensaje notificándolo para volver a intentar.|

#


|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-03  |
|Nombre:          |Perfil de usuario |
|Detalle:         |Los empleados cuentan con un rol dentro de la empresa, lo que afectará los cursos que tendrá más al alcance en el catálogo.  |
|:triangular_flag_on_post: **Pre-condiciones**  | El empleado debe haber iniciaco sesión. |
|:smile: **Secuencia normal**| Acción|
|Paso 1|	El empleado navegará al inicio de la plataforma.|
|:triangular_flag_on_post: **Post-condición** |Los cursos que se verán principalmente en el catálogo serán a los que el empleado debera darles prioridad.|
|:runner: **Excepciones**|Acción|
|Paso 1|De no contar con cursos específicos se desplegará una vista general de los cursos.|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-04  |
|Nombre:          |Catalogo de cursos|
|Detalle:         |Se debe presentar a los usuarios un catálogo que cuente con todos los cursos a los que pueden inscribirse, con filtros y búsquedas. |
|:triangular_flag_on_post: **Pre-condiciones**  |El usuario debe haber iniciado sesión y deben haber cursos registrados.  |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El usuairo navegará a la pantalla de inicio.|
|Paso 2|El usuario ingresará texto en el campo de búsqueda.|
|:triangular_flag_on_post: **Post-condición** |El catálogo cambiará los cursos mostrados de acuerdo a la búsqueda del usuario.|
|:runner: **Excepciones**|Acción|
|Paso 1|Si la búsqueda no arroja resultados se le notificará al usuario.|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-05  |
|Nombre:          |Inscripcion a curso |
|Detalle:         |Los empleados seleccionarán un curso del catálogo y solicitarán su inscripción, el coordinador a cargo debe aceptar las solicitudes para completar el registro.  |
|:triangular_flag_on_post: **Pre-condiciones**  |Los usuarios deben haber iniciado sesión. |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El empleado seleccionará un curso y presionará el botón de inscripción.|
|Paso 2|El empleado llenará los campos del formulario.|
|Paso 3|El sistema enviará la solicitud de inscripción al coordinador.|
|Paso 4|El coordinador revisará la solicitud y enviará la aprobación al solicitante.|
|:triangular_flag_on_post: **Post-condición** |La inscripción se verá reflejada en los cursos del empleado|
|:runner: **Excepciones**|Acción|
|Paso 1|Si no se llenan correctamente los campos no se completará el registro.|
|Paso 2|Si la solicitud es rechazada se le notificará al empleado correspondiente.|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-06  |
|Nombre:          |Finalizacion  de curso |
|Detalle:         |Tras realizar las lecciones del curso el empleado debera de realizar unaa evaluación la cual sera enviada la coordinador para ser aprobada o no acreditada.  |
|:triangular_flag_on_post: **Pre-condiciones**  |El empleado debe estar inscrito a un curso y cumplido con todas sus lecciones. |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El empleado realizara su evaluación.|
|Paso 2|El coordinador la recibirá y revisará la evaluación.|
|Paso 3|El coordinador responderá al empleado con su calificación y el estatus del curso.|
|:triangular_flag_on_post: **Post-condición** |El empleado completó su curso y podrá solicitar su certificación|
|:runner: **Excepciones**|Acción|
|Paso 1|Si la evaluación es reprobatoria, también se notificará al empleado y podría repetir la prueba|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-07  |
|Nombre:          |Certificación de curso |
|Detalle:         |Cuando el empleado completó un curso satisfactoriamente puede solicitar un certificado del mismo. |
|:triangular_flag_on_post: **Pre-condiciones**  |El empleado debe haber terminado un curso y recibido una calificación aprobatoria en su evaluación.  |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El empleaddo ingresara al curso completado.|
|Paso 2|El empleado presionará en el botón para solicitar la certificación.|
|Paso 3|El sistema verificará y recopilará los datos para generar el documento.|
|Paso 4|El sistema enviará el certificado al empleado.|
|:triangular_flag_on_post: **Post-condición** |El empleado recibirá su certificado en un formato con la posibilidad de guardarlo o imprimirlo.|
|:runner: **Excepciones**|Acción|
|Paso 1|Si el curso no fue acreditado no podrá solicitar su certificación.|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |[RFN-08 ] |
|Nombre:          |[Expiración de certificado] |
|Detalle:         |El empleado debera recibir una notificacion sobtre la proxima expiracion de certificacion de cursos.|
|:triangular_flag_on_post: **Pre-condiciones**  |El empleado debera haberse certificado en por lo menos un curso.|
|:smile: **Secuencia normal**| Acción|
|Paso 1|El sistema verificara la fecha de expiracion de los certificados que tiene el empleado.|
|Paso 2|El sistema enviara una notificacion de vencimiento de curso al empleado.|
|:triangular_flag_on_post: **Post-condición** |El empleado tgendrea la opcion de revalidar su certificación.|
|:runner: **Excepciones**|Acción|
|Paso 1|Si el curso no esta proximo a verncerse y se recive una notificación contactarse con el coordinador.|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-09  |
|Nombre:          |Recertificación |
|Detalle:         |Cuando el certificado de un curso se expire, el empleado puede solicitar una renovación del mismo. |
|:triangular_flag_on_post: **Pre-condiciones**  |Debe haber pasado un año desde la expedición del certificado correspondiente, dos semanas antes de esto el empleado recibirá una notificación de la expiración.  |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El empleado entrará al curso del certificado expirado.|
|Paso 2|El empleado realizará de nuevo la evaluación final del curso.|
|Paso 3|El coordinador la recibirá y revisará su puntaje.|
|Paso 4|El coordinador responderá al empleado con su calificación y el estatus del curso.|
|Paso 5|El empleado solicitará la renovación de su certificado.|
|:triangular_flag_on_post: **Post-condición** |El empleado recibirá su certificado renovado por otro año más.|
|:runner: **Excepciones**|Acción|
|Paso 1|Dependiendo de el curso, se deshabilitará la opción de enviar evaluación y el empleado tendrá que repetir todas las lecciones.|
|Paso 2|Si el empleado consigue una calificación no aprobatoria en su renovación, deberá repetir el curso.|

#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-10 |
|Nombre:          |Material de apoyo |
|Detalle:         |La plataforma permitira distitos formatos de archivos para proporsionalr las lecciones de los cursos ofrecidos. |
|:triangular_flag_on_post: **Pre-condiciones**  |El coordinador debe haber iniciado sesión  |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El coordinador debera ingresar a cursos.|
|Paso 2|El coordinador debera crear un nuevo curso y llenar la informacion general del curso.|
|Paso 3|El corrdinador agregar el maetial de apoyo en el formato mas optimo para hacer comprencible la lección.|
|Paso 4|El coordinador publbicara el curso para  ser tomado por los empleados.|
|:triangular_flag_on_post: **Post-condición** |El curso se encontrara disponible para ser seleccionado por los empleados|
|:runner: **Excepciones**|Acción|
|Paso 1|La informacion del curso esta incompleta se le notificara al coordinador y no sera publicado el curso.|


#

|:pencil: **Requisito**  | **Descripción**|
|----------------------|---| 
|Identificador:   |RFN-11  |
|Nombre:          |Avance de curso |
|Detalle:         |El empleado podrá revisar el estatus y avances de sus cursos. |
|:triangular_flag_on_post: **Pre-condiciones**  |El empleado debe haberse registrado por lo menos a un curso. |
|:smile: **Secuencia normal**| Acción|
|Paso 1|El empleado entrara a su perfil.|
|Paso 2|El empleado presionará en el enlace a sus cursos.|
|Paso 3||
|:triangular_flag_on_post: **Post-condición** |El sistema mostrará todos los cursos del empleado con su estatus  así como su  avance  con la posibilidad de filtrar y buscar.|
|:runner: **Excepciones**|Acción|
|Paso 1|Si el estatus de un curso es erróneo debe dirigirse con un supervisor.|

#

### :bomb: Rubrica

| Criterios     | Descripción                                                                                  | Puntaje |
| ------------- | -------------------------------------------------------------------------------------------- | ------- |
| Instrucciones | Se cumple con cada uno de los puntos indicados dentro del apartado Instrucciones?            | 20 |
| Desarrollo    | Se respondió a cada uno de los puntos solicitados dentro del desarrollo de la actividad?     | 80      |


:house: [Ir a inicio](https://github.com/CarlosVillanueva1721/Analisis-avanzado-de-software)