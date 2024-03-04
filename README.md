![image](https://github.com/javicastano77/HR-Attrition/assets/156696799/0bf4cbe1-8426-4564-b8a2-09cf8fee867b)

# Analísis del Employee Attrition


Durante la última década algo ha cambiado en la forma de entender las relaciones que se forjan entre talento y organización. En este sentido, Esapña ha asistido a un boom de un talento joven que persigue factores muy diferentes a los tradicionales: flexibilidad, agilidad, proyecto vs estabilidad, progresión y realización. Todo esto ha dificultado a las empresas la retención del talento y ha generado unos altos niveles de rotación vinculados un desgaste laboral de sus empleados.

Pero, el gran interrogante aquí es ¿que es lo que ha motivado ese desgaste laboral? 

## 1. Descripción

Los datos del proyecto provienen de [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/code/mragpavank/ibm-hr-analytics-employee-attrition-performance) un dataset de Kaggle con un registro crafteado de empleados de una firma de Life Science.

En esta dataset original podemos encontrar un detalle amplio de los empleados:

* **Dimensión clasificatoria**: género, edad, nivel de estudios, estado civil.
* **Dimensión del puesto**: departamento, role, role level, horas extras, horario standard, etc.
* **Dimensión del salario**: bruto anual, monthly rate, daily rate.
* **Dimensión del career**: vida laboral, años en la empresa, años en el role actual, años con el manager actual, etc.
* **Dimensión del performance**: performance rating, satisfacción el entorno laboral, satisfacción con el role actual, etc.

  ## 2. Objetivos

El proyecto está dividido en 3 objetivos principales:

1 - Analizar las diferencias entre aquellos empleados que afirman tener un desgaste laboral y los que no.

2 - Identificar las variables que más afectan a la clasificación de estos perfiles.

3- Desarrollar una visualización en Power BI que nos permita construir un relato de los perfiles.

## 3. Proceso

El proceso que ha marcado el proyecto sería:

* i. Limpieza de los datos: chequeo de valores nulos, duplicados y dtype.
* ii. transformación de los datos: mejora de la consistencia, normalización de datos, etc.
* iii. análisis de las variables: estudio del compartamiento del target en base a las dimensiones del empleado.
* iv. identificación de la correlación entre variables: identificar aquellos parámetros y condiciones que mayor grado de explicación tienen para la clasificación de los perfiles.
* v. construcción de visualización: diseñar el modelo de visualización que nos permita analizar en un click qué condiciona el desgaste.
* vi. análisis detallado del salario: comparativa en ambos perfiles sobre la evolución salarial y las franjas de edad en dónde más habitual es el desgaste.
* vii. aplicación de modelo de Machine Learning (in progress): entrenar al modelo para establecer una correcta clasificación de perfiles que sufren desgaste.
* viii. aplicación de nuevos parámetros para modificar las clasificación (in progress) : aplicación de variaciones en variables como salario, años en el role actual, etc. y analizar posibles variaciones en variable clasificatoria.

## 4. Uso

El dashborad puedes encontrarlo en la carpeta Visualización con 2 views diferentes:
* a. Detalle general del desgaste laboral
* b. Detalle sobre la configuración salarial

  ## 5. Conclusiones

Tras la realización del proyecto las principales conclusiones obtenidas serían:

1 - La distribución entre perfiles con desgaste laboral y perfiles que no tiene desgaste laboral no sigue normalidad, existiendo un alto porcentaje de perfiles que no muestran desgaste.

2 - Existen diferencias significativas en ambos perfiles, sobretodo si atendemos a franjas de edad, bruto anual o años acumulados en la compañía y el puesto.

3- Aplicando coeficientes estadísticos, observamos que no existen variables con un alto poder explicativo, salvo las relacionados con el salario percibido.
