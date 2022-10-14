# InformationLeakage-UTSLP
POC de como filtrar informacion de estudiantes de la Universidad Tecnologica de San Luis Potosi sin estar autenticado en la plataforma, mediante una consulta con la matricula que otorga la universidad a los estudiantes podemos acceder a informacion del estudiante como:

-Domicilio \n
-Numero celular
-Correo electronico
-Codigo Postal de Residencia

**Paso 1:**
Lo primero que debemos hacer para poder explotar esta brecha de seguridad es dirigirnos a la siguiente URL: http://sito.utslp.edu.mx/ y damos click en el boton "Seguimiento" como se muestra en la siguiente imagen:

<img src="https://github.com/GuilleX69/InformationLeakage-UTSLP/blob/main/images/Discover1.png">

**Paso 2:**
Una vez dado click en el boton seguimiento, nos aparecera un campo para introducir datos, en el cual se introduce la matricula del estudiante que deseas saber su informacion.
<img src="https://github.com/GuilleX69/InformationLeakage-UTSLP/blob/main/images/Discover2.png">

**Paso 3:**
Una vez insertada la matricula del alumno la plataforma te reportara algunos campos con informacion sensible como se muestra en la siguiente imagen. 
<img src="https://github.com/GuilleX69/InformationLeakage-UTSLP/blob/main/images/Discover3.png">

Con esto podemos saber informacion de alumnos de la universidad tecnologica, ya sean ex-alumnos o alumnos activos.
