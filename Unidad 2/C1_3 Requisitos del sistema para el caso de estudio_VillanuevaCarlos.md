# Inicio del proyecto

## :trophy: C1.3 Reto en clase

Elaboración de requisitos del sistema para el caso de estudio

### :blue_book: Instrucciones

- De acuerdo con la información presentada por el asesor referente al tema, y basado en el caso de estudio, realizar un listado de quince requisitos funcionales y cinco no funcionales del sistema.
- Toda actividad o reto se deberá realizar utilizando el estilo **MarkDown con extension .md** y el entorno de desarrollo VSCode, , o puede utilizar alguna plataforma por ejemplo **Notion**, debiendo ser elaborado como un documento **single page**, es decir si el documento cuanta con imágenes, enlaces o cualquier documento externo debe ser accedido desde etiquetas y enlaces.
- Es requisito que el archivo .md contenga una etiqueta del enlace al repositorio de su documento en Github, por ejemplo **Enlace a mi GitHub**
- Al concluir el reto el reto se deberá subir a github el archivo .md creado.
- Desde el archivo **.md** se debe exportar un archivo **.pdf** con la nomenclatura **C1.3_NombredelaActividad_NombreAlumno.pdf**, el cual deberá subirse a classroom dentro de su apartado correspondiente, para que sirva como evidencia de su entrega; siendo esta plataforma **oficial** aquí se recibirá la calificación de su actividad por individual.
- Considerando que el archivo .pdf, fue obtenido desde archivo .md, ambos deben ser idénticos y mostrar el mismo contenido.
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

___

## :pencil2: Desarrollo

1. Enliste los requisitos funcionales del sistema
   
    Identificador | Nombre | Descripción | 
    :--|:--|:--
    RFN-01|Disponibilidad|El sistema sera desarrolladocomo plataforma en línea.
    RFN-02|Inicio de sesión|Se utilizaran como credenciales de acceso los datos col los que cuenta la empresa.
    RFN-03|Perfil de usuario|Establecer un perfil de usuario de acuerdo al rol que cumple dentro de la empresa.
    RFN-04|Catalogo de cursos|Presentación de los cursos disponibles en los cuales se puede inscribir el usuario.
    RFN-05|Inscripcion a curso|Se requerira la aprobacion de inscripción por parte de uno de los cordinadores.
    RFN-06|Finalizacion de curso|La evaliacion final sera revisada y evaluada por uno de los coordinadores.
    RFN-07|Certificación de curso|El sistama enviará a los usuarios el certificado del curso por medio de correo electronico.
    RFN-08|Expiración de certificado|El sistema enviara una notificación al usuario dos semanas antes de la expiracion de algun certificado.
    RFN-09|Recertificación|El sistema debera permitir una reevaluacion del curso y de ser necesario tomar todo el curso de nuevo.
    RFN-10|Material de apoyo|El sisema debera soportar distintos formatos de archivos para los matriales de los cursos.
    RFN-11|Avance de curso|El sistema presentara al usuario los avances obtenidos durante los cursos tomados.
    RFN-12|Categorias|Los cursos presentadoa al usuario deberan estar segmentados por categorias de interes.
    RFN-13|Roles|El sistema debera contar con dos roles, uno para los corrdinadores y otro para los empleados.
    RFN-14|Estatus de cursos|El sistema presentara al usuario la situacion actual del curso, si se esta inscrito a el o ya ha sido completado.
    RFN-15|Análisis de los datos|El sistema almacenara los datos relacionados entre cursos y usuarios para poder realizar un alasisi sobre ellos.
 
2. Enliste los requisitos no funcionales del sistema
   
    Identificador | Nombre | Descripción
    :--|:--|:--
    RNFN-01|Seguridad|Los datos de inicio de sesión solo deben ser visibles para el administrador y el propio usuario.
    RNFN-02|Interfaz|La interfaz del sistema debe ser sencilla e intuitiva para cualquier usuario que no tenga conocimientos es sistemas similares.
    RNFN-03|Accesibilidad|La plataforma debe estar disponible para su uso en cualquier momento.
    RNFN-04|Respaldo|El sistema realizara periodicamente respaldos de la información obtenida.
    RNFN-05|Usuarios simultaneos|El sistema debe ser capaz de operar adecuadamente con hasta 15000 usuarios con sesiones simultaneas.

___

### :bomb: Rubrica

| Criterios     | Descripción                                                                                  | Puntaje |
| ------------- | -------------------------------------------------------------------------------------------- | ------- |
| Instrucciones | Se cumple con cada uno de los puntos indicados dentro del apartado Instrucciones?            | 20 |
| Desarrollo    | Se respondió a cada uno de los puntos solicitados dentro del desarrollo de la actividad?     | 80      |

:house: [Ir a inicio](https://github.com/CarlosVillanueva1721/Analisis-avanzado-de-software "Github")