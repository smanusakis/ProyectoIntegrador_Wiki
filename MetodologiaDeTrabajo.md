
___
- [Metodología ágil y su implementación en el equipo](#metodología-ágil-y-su-implementación-en-el-equipo)
- [Priorización del *Backlog*](#priorización-del-backlog)
- [Medición del esfuerzo](#medición-del-esfuerzo)
- [Asignación de roles y tareas](#asignación-de-roles-y-tareas)
- [Organización del Repositorio y control de versionado.](#organización-del-repositorio-y-control-de-versionado)

___

<br>

## Metodología ágil y su implementación en el equipo


Para la organización de las tareas y asegurarnos de la entrega contínua del roducto, se trabajó utilizando metodologías ágiles.

La carga de trabajo se dividió en cuatro Sprints de aproximadamente dos semanas de duración.

Siguiendo las indicaciones de la metodología, se desarrollaron a lo largo de cada *Sprint* las ceremonias de *Planning*, *Review&Demo, *Retrospective*, hacia la mitad de cada *Sprint* se tuvo un *status ckeck* para verificar los avances junto con el *Product Owner* y a diario, las *Daily meetings* donde pudimos compartir con el equipo Scrum avances, bloqueos y planificación.

[subir](#metodología-de-trabajo)

<br>

___

## Priorización del *Backlog*

En lo referido a la organización del trabajo, el equipo Scrum se autogestionó, las tareas se dividieron por temáticas, y el equipo se autoasigó tareas en base al fuerte de cada uno de los miembros y sus intereses específicos.
En cuanto a la priorización de las tareas, se consideró las interdependencias entre tareas que pudieran existir, para darle prioridad a aquellas que pudieran bloquear el trabajo y poner en riesgo la entrega requerida. 
<br>
En aquellos *Sprints* que tuvimos *Carry-Overs* de *Sprints* anteriores, la prioridad fue terminar las tareas pendientes para luego proseguir con las nuevas.

[subir](#metodología-de-trabajo)


____
## Medición del esfuerzo

Como equipo, luego de cada sesión de *Planning* se llevó a cabo la votación de esfuerzos, seguiendo la escala de Fibonacci. Los valores utilizados fueron 1, 2, 3, 5 y 8, tomando 1 y 2 para aquellas tareas que no llevaran grandes esfuerzos ni búsquedas de información adicional, tomamos 3 para aquellas que, sabiendo cómo llevarlas a cabo, sabíamos que demandarían tiempo; 5 para aquellas que además de demandar tiempo de realización, sabíamos que demandarían un gran esfuerzo y por último 8 para aquellas tareas que fueron totalmente nuevas para el equipo, que demandaron estudio, búsqueda de material, comprender conceptos absolutamente nuevos y buscar su implementación. Cabe aquí destacar que muchas de esas tareas tuvieron la etiqueta de *Carry-Over* durante uno o más *Sprints*

Adicionalmente, y a los fines de llevar un mejor control interno, el equipo desarrolló una integración entre Gitlab y Jira, eso nos permitió elaborar un *board*, tener la posibilidad de llevar una gestión más eficiente de los PBIs (*Product Backlog Items*), por ejemplo, generando separación en subtareas que estuvieran asignadas a distintos miembros del equipo, así como elaborar métrias que reflejaran el esfuerzo, velocidad, y entrega de valor del equipo.
También nos permitió llevar un mejor registro del esfuerzo que cada tarea tenía y reasignar tareas o recursos de ser requerido.

[subir](#metodología-de-trabajo)

____
## Asignación de roles y tareas
El equipo está compuesto por 5 desarrolladores, Mili, Trini, Mari, Nico y Sofi. 
Los roles entre los desarrolladores se dividieron principalmente por fortalezas y áreas de interés de cada miembro.
Mientras Mili y Trini tomaron la posta y se encargaron de las tareas de Frontend, el resto del equipo tomó las tareas de Backend, Base de Datos, Testing e infraestructura. Mari lideró los esfuerzos que permitieron desarrollar las tareas de Backend y tuvo como soporte a Nico y Sofi. Nico a su fue el encargado principal de llevar las tareas de Testing y Base de Datos y fue soporte también de Mari en Backend completando tareas y Sofi lideró los esfuerzos de infraestructura, colaborando en Backend y tomó el rol de *Scrum Master* del equipo, ayudando en la organización del *board*, métricas, y ayudando a que el equipo tuviera ceremonias más eficientes y efectivas.

___
## Organización del Repositorio y control de versionado.

En cuanto a la gestión del Repositorio del proyecto, se utilizó Gitlab, como herramienta brindada por DigitalHouse.
<br>
Se siguió un ***Feature-based branching strategy*** donde el merge se fue realizando de manera periódica la la rama compartida de ***Develop***. Esta rama, a su vez, se consolidaba con ***Main*** al menos una vez por *Sprint* y de ella se fue efectuando periódicamente el *Deploy* en **AWS**.
<br>
Para un mejor control del versionado y evitar conflictos, una sola persona fue la encargada de tener la rama principal actualizada, mientras que todos los desarrolladores tuvieron injerencia en la rama de desarrollo.

[subir](#metodología-de-trabajo)