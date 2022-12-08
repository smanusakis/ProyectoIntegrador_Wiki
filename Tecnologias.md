En esta sección se detallarán las distintas tecnologías utilizadas para el desarrollo y gestión del proyecto.

## [Tecnologías utilizadas](#tecnologías-utilizadas)

- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Servicios o herramientas utilizadas en el Proyecto](#servicios-o-herramientas-utilizadas-en-el-proyecto)
  - [Gestión del proyecto](#gestión-del-proyecto)
  - [Desarrollo del proyecto](#desarrollo-del-proyecto)
- [Desarrollo del sitio](#desarrollo-del-sitio)



----------
## Servicios o herramientas utilizadas en el Proyecto
### Gestión del proyecto
Para la gesión del proyecto en cuanto a tareas, se utilizó la herramienta de <span style="color:orange">**Gitlab**</span>, brindada por DigitalHouse. Ante la imposibilidad de adaptar el *board* y generar **reportes de métricas**, el equipo generó una integración con <span style="color:orange">**Jira**</span>. Al ser una herramienta adicional, el equipo se encargó de mantener ambos *boards* al día con el status de tareas y miembros asignados.
Como se mencionó anteriormente, Jira permitió al equipo obtener métricas, como *velocity*, *commited vs. done*, generar etiquetas personalizadas que nos permitieran destacar **interdependencias**, así como llevar un mejor registro de ***Carry-Overs*** y subdividir aquellas tareas complejas en ***Tasks*** dando mayor granularidad al *Sprint* y dando lugar a que la colaboración iterna pudiera reflejarse.


[subir](#tecnologías-utilizadas)

<br>

### Desarrollo del proyecto

Para el desarrollo del Proyecto el equipo utilizó diferentes IDEs (*Integrated Development Environment*). 
El área de *Front end* eligió 
<span style="color:orange">***Visual Studio Code* (VSC)**</span> se trabajaron, mientras que el área de *Back end* e infraes optó por <span style="color:orange">**IntelliJ IDEA**</span>.
<br> El área de infraestructura utilizó ambos *IDEs*.
<br> En el caso de *Testing* 


Para trabajar con la Base de Datos, inicialmente se utilizó <span style="color:orange">**MySQL Workbench**</span> y posteriormente se exportó a una <span style="color:orange">**RDS** *(Relational database)*</span> en <span style="color:orange">**AWS** *(Amazon Web Services)*</span>.

En lo que respecta a Infraestructura, se trabajó en <span style="color:orange">**AWS**</span>. Dentro de ése entorno, se creó un servidor en  **EC2** (*Amazon Elastic Compute Cloud*) y dos *buckets* **S3**, el *deploy* de estos elementos se hizo a través de <span style="color:orange">**Terraform**</span>.

El versionado del proyecto se realizó íntegramente en <span style="color:orange">**Gitlab**</span>.

[subir](#tecnologías-utilizadas)

----

## Desarrollo del sitio


| Área | Tecnologías |
| ------- | ---------- |
| ***Front end*** | **Lenguajes** <br>- HTML <br>- CSS <br>-JavaScript  <br> **Librerías** <br>- React <br>- Librería 2 <br> **Recursos** <br>- Recurso 1 |
| ***Back end*** |**Lenguajes** <br>- Java <br> ***Frameworks*** <br>- Springboot <br>**Herramientas de gestión** <br>- Maven <br>**Gestión de Seguridad** <br>- JWT (*Jason Web Tokken*) |
| **Base de Datos** | **Lenguajes** <br>- SQL |
| **Infraestructura** | **Lenguajes** <br>- HCL (*HashiCorp configuration language*) <br>- *Bash scripting*|
| ***Testing*** |***Automation Suite*** <br>- Selenium WebDriver <br>**OtrasTecnologías** <br>- Tecnología 2 |
| **Wiki** | **Lenguajes** <br>- Markdown | 


[subir](#tecnologías-utilizadas)
