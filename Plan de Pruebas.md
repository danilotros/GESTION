# Plan de Pruebas


## Historial de Versiones

![](https://github.com/danilotros/GESTION/blob/master/Tabla/Tabla1.JPG)

## Informacion del proyecto

![](https://github.com/danilotros/GESTION/blob/master/Tabla/Tabla2.JPG)

## Aprobaciones 

![](https://github.com/danilotros/GESTION/blob/master/Tabla/Tabla3.JPG)

## Resumen Ejecutivo

El siguiente plan de pruebas tiene como fin presentar la metodología a emplear para asegurar que el proyecto Store Depot se ajuste al producto requerido junto a todas sus funcionalidades propuestas, de esta manera se busca diseñar un plan de pruebas que permita detectar y corregir los defectos que se generen durante su desarrollo, teniendo en cuenta los criterios de aceptación de pruebas, todo esto bajo la premisa de disminuir los riegos siguiendo el cronograma estimado y haciendo uso de los  recursos disponibles. 

## Alcance de las Pruebas

### Elementos de Pruebas

El plan de pruebas del sistema de software constará de 4 módulos de evaluación: Interfaz gráfica, Lógica del negocio, DAO y requerimientos no funcionales; en cada uno de estos se analizarán distintos aspectos correspondientes a las responsabilidades de cada módulo y de esta manera ver si cada uno de estas se esté cumpliendo (Ver tabla 5.1).    

![](https://github.com/danilotros/GESTION/blob/master/Tabla/Tabla4.JPG)

## Nuevas Funcionalidades a Probar 

Las características del software que se pondrán bajo evaluación serán:

#### Requerimientos funcionales:

Se analizará bajo unos criterios de aceptación propuestos con base a los casos de uso de cliente postulados en la documentación del proyecto y observar si el software cumple con cada uno de estos.

Para hacer estas pruebas se utilizarán los módulos de Lógica del negocio y DAO.

#### Requerimientos no funcionales:

Se realizará la evaluación de los aspectos relacionados con el cumplimiento de los requerimientos implícitos del proyecto, los cuales emergen del correcto cumplimiento de los requerimientos funcionales.

Se utilizará el módulo de requerimientos no funcionales para hacer estas pruebas.



## Pruebas de Regresión   

Las pruebas de regresión a realizar se llevarán a cabo después de la agregación de funcionalidades al sistema de software, garantizando que los defectos desencadenados por esta agregación sean ubicados rápidamente así como su origen, principalmente teniendo en cuenta los errores de regresión relacionados a la utilización de métodos lógicos desde los componentes del GUI de la aplicación.  


El nivel de pruebas de regresión será alto ya que hay que verificar que las funcionalidades ya insertadas en el sistema de software no se vean afectadas de manera significativa por la agregación de otras funcionalidades relacionadas, limitando el tiempo dedicado a esta tarea.

## Funcionalidades a No Probar 

Las funcionalidades que no se van a probar son las relacionadas con el módulo GUI de la aplicación, debido a la falta de tiempo y a la priorización a la funcionalidad lógica del sistema de software, teniendo en cuenta el riesgo de comprometer la facilidad de uso y la buena apariencia del resultado final del proyecto.


## Enfoque de Pruebas (Estrategia) 

La estrategia de pruebas del proyecto propone un orden en los tipos de pruebas a realizar en el mismo, organizando las pruebas por orden de ejecución y prioridad, siendo la primera categoría (Pruebas unitarias) las primeras a realizar, pero las menos influyentes en el proyecto (Ver figura 5.2).   

![](https://github.com/danilotros/GESTION/blob/master/Recortes/Flecha.JPG)

#### Leyenda:
1.	Pruebas unitarias
2.	Pruebas de integración
3.	Pruebas del sistema

Para la realización de las pruebas unitarias el grupo de trabajo se basará en la pirámide de Cohn, un método para organizar por importancia las pruebas unitarias automatizadas a realizar en un proyecto de software 

![](https://github.com/danilotros/GESTION/blob/master/Recortes/Piramide.JPG)

Este método postula principalmente que se deben hacer más pruebas unitarias a los bloques bases de la pirámide, empezando por Pruebas Unitarias automáticas, siendo estas las más importantes para el proyecto, hasta las Pruebas GUI automáticas, las cuales son las menos relevantes con respecto a los otros tipos de pruebas en el gráfico. 

## Criterios de Aceptación o Rechazo
### Criterios de Aceptación o Rechazo 

Los criterios de aceptación y rechazo del proyecto están enfocados principalmente al correcto cumplimiento de los requerimientos funcionales y no funcionales del proyecto, por lo que las pruebas unitarias deben ser completadas por lo menos hasta el nivel de pruebas API automáticas ubicadas en la pirámide de Cohn.   

El porcentaje de defectos corregidos debe ser del 100% con respecto a los defectos encontrados en el proceso de pruebas, además de analizar que cada componente del software cumpla con sus responsabilidades.

### Criterios de Suspensión 
Basándonos en el diagrama piramidal anterior (Fig. 5.3), cada grupo de pruebas debe cumplirse empezando por la base, sin subir de nivel hasta que la categoría de pruebas unitarias actual sea completada en su totalidad y con respecto al diagrama de flecha anterior (Fig. 5.2), se deben cumplir en orden ascendente (Es decir, 1, 2, 3) sin saltar al siguiente tipo de pruebas hasta terminar el tipo de pruebas actual.   

Si por algún motivo se encuentra que se ha salteado una parte de los tipos de pruebas anteriores, se debe suspender el proceso de pruebas actual y retornar a los tipos de pruebas inconclusos.

### Criterios de Reanudación

El proceso de pruebas suspendido por los criterios anteriores podrá ser reanudado cuando se confirme que los tipos anteriores de pruebas están completados bajo los criterios de aceptación y rechazo ya estipulados en el documento, esto con el fin de seguir un orden jerárquico con respecto a la prioridad de las pruebas.

## Entregables
### Entregables
Los documentos que se llegaran a entregar son:

+ Documento de Plan de Pruebas planeadas por el equipo de trabajo.  

+ Casos de Pruebas: se discutirá con los diferentes integrantes del equipo los distintos casos que se puedan llegar a presentar en las pruebas.

+ Especificación de Diseño de Casos  

+Evidencias de pruebas  

+Reportes emitidos por herramientas de pruebas.  

+Documentación de las correcciones que se puedan llegar a hacer al programa según los diversos resultados de las pruebas y los reportes emitidos  por estas.  

+Documentación del programa con los resultados obtenidos de las pruebas y sus diversas funcionalidades.  


## Recursos
### Requerimientos de Entornos – Hardware 
Lista de los requerimientos de equipos, hardware y red necesarios para completar las actividades del Plan de Pruebas de Software. Incluye Servidores de Aplicación, Bases de Datos, Equipos de PC que necesitan los Testers, Conectividad a la red (incluyendo accesos), entre otros. 

Los requisitos mínimos en cuanto al componente de Hardware son:

+ Procesador Intel Core i3 7100

![](https://github.com/danilotros/GESTION/blob/master/Recortes/procesador.JPG) 

+ 4 Gb en ram Ddr4     


![](https://github.com/danilotros/GESTION/blob/master/Recortes/ram.JPG)

+ Fuente De Poder Thermaltake Tr-600cus Tr2 600w        


![](https://github.com/danilotros/GESTION/blob/master/Recortes/fuente%20de%20poder.JPG)



+ mouse y teclado 


![](https://github.com/danilotros/GESTION/blob/master/Recortes/teclado.JPG)

+ Cualquier plan de internet siempre y cuando sea de 5Mb o mayor

+ chasis gabinete aerocool cruisestar advance
![](https://github.com/danilotros/GESTION/blob/master/Recortes/gabinete.JPG)

+ Board Gigabyte H110m-h Ddr4 Para Intel Lga 1151 7ma Ddr4
![](https://github.com/danilotros/GESTION/blob/master/Recortes/madre.JPG)

## Requerimientos de Entornos – Software 
Lista de los requerimientos de software necesarios para completar las actividades de prueba, puede incluir accesos a Sistemas (en entorno de pruebas) y Bases de Datos, así como instalación de software en los Computadores asignados a los Testers.  

+ Windows 10  

+ NodeJS  

+ Mocha  

+ Eset Smart Security 10  

+ Office 2017  

+ Atom  

+ Mongo (se  usa para la base de datos no relacional)  

![](https://github.com/danilotros/GESTION/blob/master/Recortes/entornos.JPG)

## Herramientas de Pruebas Requeridas 
Se utilizo el testeador MOCHA para realizar las diferentes pruebas a cada uno de los modulos que se presentan en el programa teniendo en cuenta que realizamos pruebas unitarias a cada uno de estos para tener un mejor control del programa y un control mas cercano y directo en cuanto a los diferentes errores que puedan llegar a presentar cada uno de estos modulos.


![](https://github.com/danilotros/GESTION/blob/master/Recortes/herramientas.JPG)

## Personal
 

Las personas necesarias para hacer las pruebas se vieron ubicadas dentro del grupo de trabajo lo cuales son:

+ Cristian Patiño  y Daniel Perea son los Testers.
+ Daniel Moreno líder de Pruebas.
+ Sebastian Mora,y Maycol Hernandez como los documentadores.

 
## Planificación y Organización
### Procedimientos para las Pruebas

La ejecución del plan de pruebas se regirá bajo la siguiente metodología


![](https://github.com/danilotros/GESTION/blob/master/Recortes/pasos.JPG)

1.	Planificación de Pruebas: Durante el proyecto se debe planificar las pruebas que se van a realizar, dando como resultado el presente plan de pruebas.

2.	Diseño de Pruebas: Las pruebas se diseñarán de tal manera que permitan al equipo detectar y corregir de manera oportuna algún defecto durante el desarrollo del proyecto, y de igual manera validar y verificar si se está realizando el producto correcto y si se está construyendo el producto como se debe respectivamente.

3.	Ejecución de Pruebas: Una vez se termina la etapa de diseño de pruebas, se procede a realizar la ejecución de las mismas, con el fin de obtener resultados e indicadores para ser evaluados y analizados por el equipo.

4.	Evaluación y Depuración Con el informe de resultados el equipo contrasta los resultados esperados y los evalúa, de esta manera se procede a tomar las medidas según sea necesario. Si los resultados no son lo esperado se deben plantear las correcciones para reducir o eliminar completamente el impacto del fallo encontrado.

5.	Análisis de Errores: Con el fin de reducir el riesgo se plantean actividades preventivas y se estima la fiabilidad del producto.


## Matriz de Responsabilidades

Las responsabilidades son asignadas teniendo en cuenta la metodología y cada una de las etapas planteadas en el plan de pruebas, se hará uso de una matriz RACI (responsable, aprobador, consultado e informado) para la asignación de las tareas a cada uno de los roles establecidos anteriormente en el DevOps del proyecto.

![](https://github.com/danilotros/GESTION/blob/master/Recortes/roles.JPG)


## Cronograma

Las pruebas y su tiempo estimado, se encuentran planteadas según el avance del proyecto Ver Cronograma.

## Premisas

+ Identificar defectos y problemas, formular correcciones y mejorar el producto.

+ En el cronograma se establece el tiempo destinado para las pruebas del producto teniendo en cuenta el tiempo total de la duración del proyecto.
+ El talento humano asignado para el plan de pruebas se trabaja bajo un marco de matriz RACI donde a cada rol se le asigna una tarea específica según la etapa a desarrollar.

+ En el proceso de pruebas la herramienta utilizada para tal fin es Mocha.


## Dependencias y Riesgos
+	Disponibilidad de Recursos y Tiempo
En el proceso de pruebas de software la disponibilidad de recursos representa un riesgo para su desarrollo en cualquier etapa. Un empleado puede ausentarse de su trabajo debido a varios motivos (enfermedades, calamidad doméstica o motivos de fuerza mayor). Para evitar retrasos y cruces con el cronograma, se plantean holguras que permitan la reposición del tiempo, sin embargo, teniendo en cuenta la urgencia de la tarea, esta se asignara a un miembro del equipo que se encuentre capacitado para su realización. 

## Referencias 
## Glosario
+ Calidad: el conjunto de características de una entidad, que le confieren la aptitud
para satisfacer las necesidades establecidas y las implícitas.

+ Proceso: es un conjunto de prácticas realizadas para obtener un resultado. Esto incluye herramientas, técnicas, materiales y personas.

+ Modelo de desarrollo de software:es una representación simplificada del proceso
para el desarrollo de software, presentada desde una perspectiva específica.

+Metodología de desarrollo de software: es un enfoque estructurado para el  desarrollo de software que incluye modelos de sistemas, notaciones, reglas, sugerencias de diseño y guías de procesos.

+ El modelo en cascada.
-Considera las actividades fundamentales del proceso especificación,     desarrollo, validación y evolución.
-Los representa como fases separadas del proceso, tales como la  especificación de requerimientos, el diseño del software, la implementación, las pruebas, etcétera.
-Se derivó de procesos de sistemas más generales.
+ El modelo en cascada.
-Considera las actividades fundamentales del proceso especificación, desarrollo, validación y evolución.
-Los representa como fases separadas del proceso, tales como la especificación de requerimientos, el diseño del software, la implementación, las pruebas, etcétera.
-Se derivó de procesos de sistemas más generales.

+ Configuración: La posición relativa de las partes componentes de un
sistema, ej. Las posiciones relativas de las estrellas y planetas del sistema solar.

+ Configuración Software: El estado actual del sistema software y las interrelaciones entre sus componentes constitutivos, ej. el código fuente,
datos y documentación.

+ Gestión de configuraciones:
  - Disciplina cuya misión es identificar, controlar y organizar la evolución de un sistema software. 
  
  - Conjunto de actividades desarrolladas para gestionar los cambios de un sistema software a lo largo de su ciclo de vida (se aplica a todas las fases).
  
  - Disciplina de gestión que permite controlar formalmente la evolución del software, garantizando la visibilidad en el desarrollo en el producto, y la trazabilidad en el producto.
  

+ Control de cambios: Proceso que incluye proponer un cambio, evaluarlo,aprobarlo o rechazarlo, planearlo y hacerle un seguimiento.

+ Pruebas de integración: Pruebas hechas a un grupo especifico de requerimientos.

+ Pruebas de sistema: Pruebas realizadas al sistema de software como un conjunto, teniendo en cuenta los casos de uso del diseño.

+ Necesidad:
  - Los sistemas software tienen una ‘vida larga’.
  - Todos los sistemas software cambian a lo largo de su vida (diferente versión, plataforma, etc.)
  - Hay que asegurar que los cambios producidos ocasionen el mínimo coste.

+ Mantenimiento: Proceso de modificar un sistema o componente software
después de su entrega para corregir defectos, mejorar el rendimiento u otros atributos o adaptarlo a un entorno cambiante (IEEE 1990).

