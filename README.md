<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">


# Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2024-02

<hr>

# <center>Desarrollo de Soluciones IOT</center>

## TB1 REPORT

**Sección:** WX71

**Profesor**: Marco Antonio León Baca

**StartUp Name**: GrowGenius

**Producto**: GreenGrow

### Team Members:

| Member                            |    Code    |
| :-------------------------------- | :--------: |
| Checa Apolinario, Paolo Sebastián | u202112749 |
| Lazo Tapia, Jesús Antonio         | u202019038 |
| Hinostroza Mavila, Farid Rolando  | u202014468 |
| Taype Fernandez, Leonardo         | u20201e840 |
| Arana Ramos, Jack                 | u202121875 |

<br>

Septiembre del 2023

<br><br>

</div>

# Registro de Versiones del Informe

| Versión |   Fecha    |                                                                                       Autor                                                                                        | Descripción de modificación                                                                                                                                           |
| :-----: | :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   TB1   | 28/08/2024 | Checa Apolinario, Paolo Sebastián <br><br> Lazo Tapia, Jesús Antonio <br><br> Hinostroza Mavila, Farid Rolando <br><br> Taype Fernandez, Leonardo <br><br> Arana Ramos, Jack | Se realizaron los capítulos: Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification y Capítulo IV: Solution Software Design |

<br><br>

# Project Report Collaboration Insights

- **TB1:** Para esta entrega, realizamos como equipo las actividades correspondientes a los capítulos asignados en el siguiente repositorio dentro de nuestra organización de grupo: 

    <br>

    Link del repositorio del Informe Final: [Github - Informe Final GreenGrow]()

    <br>

    A continuación, se muestran las capturas de evidencia correspondientes al desarrollo de los siguientes capítulos:

    <br>

    - **Capítulo I: Introducción**
    - **Capítulo II: Requirements Elicitation & Analysis**
    - **Capítulo III: Requirements Specification**
    - **Capítulo IV: Solution Software Design**
    
    <div align=center>
        <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149369808740163625/image.png"/>      
    </div>

    <div align=center>
        <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149370395296813166/image.png"/>
    </div>

<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)

- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. Event Storming](#411-event-storming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
    - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
    - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
    - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)

- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)

### [Conclusiones](#conclusiones)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

<br><br>

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| :------------------: | :-----------------: | :----------: |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | | |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | | |

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Description de la StartUp

Nuestra startup recibe el nombre de GrowEasy Innovators, la cual nace para ofrecer soluciones avanzadas en el monitoreo y gestión de cultivos mediante tecnología IoT. Nos dedicamos a fortalecer a los agricultores y aficionados de la hidroponía con herramientas tecnológicas que permiten un control preciso y automatizado de sus cultivos. A través de sensores inteligentes, los usuarios pueden monitorear en tiempo real parámetros críticos como la temperatura, humedad, intensidad del viento y la iluminación, optimizando el crecimiento de las plantas y garantizando cosechas de alta calidad. Además, ofrecemos una plataforma intuitiva que permite la gestión remota de estos factores, facilitando la toma de decisiones y reduciendo el margen de error.

- **Visión:** Nos proponemos ser líderes en la integración de tecnología IoT en la agricultura, facilitando el acceso a soluciones inteligentes que promuevan prácticas sostenibles y eficientes en el cultivo de alimentos, independientemente del entorno.

- **Misión:** Nuestra misión es proporcionar una solución integral que permita a los agricultores, tanto expertos como aficionados, monitorear y gestionar sus cultivos de manera eficiente y sostenible a través de tecnología IoT, mejorando así la productividad y reduciendo el impacto ambiental.


### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="4">
            <img src="https://cdn.discordapp.com/attachments/1279240789611778109/1279286307486695425/pic_1.jpg?ex=66d3e3b7&is=66d29237&hm=c1baea122f79f3959dbdd0521bf9ab8425566ce2bf773f600e36cfd1dd76a780&" alt="Paolo Checa" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Checa Apolinario, Paolo Sebastián 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U202112749
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        En la Ingeniería de Software uno consigue los instrumentos necesarios para poder desarrollar programas o aplicaciones. El camino para lograr aquello se basa en un proceso donde el ingeniero deberá analizar lo requerido, planificar el desarrollo del proceso y comprobar su funcionamiento correcto hasta que este se ejecute sin errores. Las estrategias usadas para simplificar y acelerar estos procesos serán clave en esta rama pues estas serán las soluciones innovadoras que el ingeniero deberá crear. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Poseo conocimientos en programación en el entorno del lenguaje C++, Python y Java. Estoy dispuesto a aportar nuevas ideas al equipo, tengo fácil adaptación a los roles designados y buena organización. Soy responsable y dispongo de la capacidad para aportar ideas innovadoras en beneficio de nuestro proyecto. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <img src="" alt="Jesus Lazo" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Lazo Tapia, Jesús Antonio 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U202019038
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        La Ingeniería de Software proporciona las herramientas esenciales para crear programas y aplicaciones. Este proceso involucra que el ingeniero analice las necesidades, planifique el desarrollo y verifique que todo funcione correctamente hasta asegurar que el software opere sin fallas. Las tácticas implementadas para optimizar y acelerar estos procedimientos serán fundamentales en este campo, ya que representan las soluciones innovadoras que el ingeniero debe desarrollar. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Poseo conocimientos en programación que he estado llevando desde el inicio de mi carrera, me gusta el desarrollo con tecnología inteligente y redes y comunicaciones de datos. Soy responsable y estaré apoyando a mi grupo para obtener el éxito de nuestro trabajo. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <img src="" alt="Farid Hinostroza" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Hinostroza Mavila, Farid Rolando 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U202014468
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        La Ingeniería de Software es una disciplina que combina creatividad y lógica para desarrollar soluciones tecnológicas que impacten positivamente en la sociedad. Este campo abarca desde la concepción de la idea hasta la implementación y mantenimiento de software, garantizando que las soluciones sean efectivas y eficientes. El ingeniero de software debe estar preparado para enfrentar desafíos complejos, aplicar metodologías ágiles, adaptarse a las nuevas tendencias tecnológicas, asegurando que los productos finales cumplan con los estándares de calidad y funcionalidad. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        He adquirido una base sólida en desarrollo de software, con un interés particular en la inteligencia artificial y la gestión de bases de datos. Mi enfoque es la mejora continua y la implementación de soluciones innovadoras que resuelvan problemas reales. Además, soy proactivo y colaborativo, lo que me permite trabajar eficazmente en equipo para alcanzar los objetivos propuestos, siempre con la vista puesta en la excelencia y la eficiencia del proyecto. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <img src="" alt="Fernando Taype" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Taype Fernandez, Leonardo 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U20201E840
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        En la carrera de Ingeniería de Software adquirimos conocimiento para desarrollar soluciones a través de software. Analizamos requisitos, diseñamos arquitectura, creamos código y mantenemos en funcionamiento productos de software. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Me considero una persona comprometida y responsable. Me gusta aprender y plantearme retos. Estudio la carrera de ingeniería de software, siempre me ha gustado interactuar con la computadora y ahora puedo ser un profesional haciendo lo que me gusta. Tengo conocimientos en desarrollo web, móvil y desktop. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262609047650325/arack.jpg?ex=66d770f8&is=66d61f78&hm=45ba7165dfe37418f660a851df4c8f956b719f3e8e8e8d1295c07123cca0a0b7&=&format=webp&width=421&height=633" alt="Jack Arana" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Arana Ramos, Jack 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U202121875
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        Estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. La carrera de Ingeniería de Software está diseñada para formar profesionales altamente capacitados en el diseño, desarrollo y mantenimiento de sistemas de software complejos. A lo largo del programa, se adquiere una sólida base en principios de ingeniería, metodologías de desarrollo, y buenas prácticas en la gestión de proyectos tecnológicos. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Tengo experiencia en desarrollo web full stack, manejando tanto front-end como back-end. También estoy capacitado en prácticas de DevOps, control de versiones con Git, y diseño de interfaces de usuario eficientes. Mis habilidades analíticas y de trabajo en equipo, junto con una gestión eficaz del tiempo, me permiten adaptarme rápidamente a nuevas tecnologías y resolver problemas complejos de manera eficiente. 
        </td>
    </tr>
</table>

## 1.2. Solution Profile

**Nombre del Producto:** Nuestro servicio tiene el nombre de “GrowEasy”, reflejando nuestro compromiso de facilitar el monitoreo y la gestión eficiente de cultivos para nuestros usuarios. Con la tecnología IoT, los usuarios podrán supervisar y optimizar el crecimiento de sus plantas de manera sencilla, creciendo junto con nosotros a medida que aprovechan al máximo nuestras herramientas tecnológicas.

**Descripción del Producto:** Proponemos un servicio innovador y tecnológico que permite a los usuarios monitorear y gestionar sus cultivos a través de sensores IoT que capturan datos en tiempo real sobre parámetros como temperatura, humedad, y luz. Con esta información, los usuarios pueden tomar decisiones informadas para mejorar la salud y productividad de sus plantas, ya sea en un entorno doméstico o a mayor escala. Nuestro enfoque es hacer que la tecnología sea accesible y fácil de usar, priorizando la simplicidad y la efectividad para todos los usuarios de nuestra plataforma.

**Monetización:** Nuestro servicio generará ingresos a través de la venta de hardware IoT (sensores y dispositivos de control) y suscripciones a la plataforma que ofrecen acceso a funcionalidades avanzadas, como análisis de datos y recomendaciones personalizadas. Además, consideramos alianzas con empresas de insumos y equipamiento agrícola para ofrecer publicidad dirigida y relevante dentro de nuestra aplicación, brindando a los usuarios acceso a productos y servicios que complementen su experiencia de cultivo.

### 1.2.1. Antecedentes y problemática

Para este segmento, utilizamos la técnica 5W y 2H, lo que nos permite identificar los aspectos clave relacionados con nuestro proyecto.

- **Who**

Nuestros usuarios son agricultores, tanto aficionados como expertos, interesados en utilizar tecnología avanzada para monitorear y optimizar sus cultivos. Están comprometidos con la adopción de soluciones innovadoras que les permitan mejorar la eficiencia y la sostenibilidad de sus procesos agrícolas.

- **What**

El desafío principal para nuestros usuarios radica en la falta de herramientas accesibles y fáciles de usar que les permitan monitorear en tiempo real y gestionar eficientemente los diferentes factores que afectan el crecimiento de sus cultivos, como la temperatura, humedad, viento e iluminación.

- **Where**

Este problema surge principalmente en áreas rurales y urbanas donde los agricultores y aficionados a la hidroponía no tienen acceso a soluciones tecnológicas integradas, lo que dificulta el control eficiente de las condiciones de cultivo.

- **When**

La dificultad se presenta constantemente, especialmente cuando los usuarios buscan maximizar la productividad y la calidad de sus cultivos, pero no cuentan con los medios para monitorear y ajustar las variables ambientales de manera precisa y en tiempo real.

- **Why**

Los usuarios suelen enfrentar obstáculos debido a la falta de soluciones IoT asequibles y comprensibles que les permitan realizar un monitoreo continuo y automatizado de sus cultivos. Esto los obliga a recurrir a métodos tradicionales o manuales que no siempre son eficaces para asegurar un crecimiento óptimo.

- **How**

Para abordar esta problemática, hemos desarrollado una plataforma IoT que integra sensores inteligentes con una aplicación móvil y web. Esta solución permite a los usuarios monitorear en tiempo real las condiciones de sus cultivos, recibir alertas y recomendaciones, y ajustar automáticamente los parámetros necesarios para asegurar un crecimiento saludable y sostenible.

- **How much**

De acuerdo con información del Instituto Nacional de Estadística e Informática (INEI), el sector agrícola en el Perú mostró un aumento significativo en la tasa de empleo durante el segundo y tercer trimestre de 2020. En el segundo trimestre, el empleo en este sector creció un 22.6%, y en el tercer trimestre, un 20.5%. Esto es especialmente destacable si se considera que, en esos mismos periodos, la población empleada a nivel nacional disminuyó en un 39.6% y un 17.1%, respectivamente, en comparación con 2019. Además, según El Comercio (2019), la hidroponía se considera el futuro de la agricultura sostenible, ya que requiere un 90% menos de agua que las técnicas agrícolas tradicionales. Esto representa una gran ventaja para quienes desean iniciar su propio proyecto, ya que la hidroponía permite el cultivo en espacios reducidos, optimizando tanto el espacio como los recursos.

<br>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

De acuerdo con El Comercio (2019), la hidroponía es el futuro de la agricultura sostenible, utilizando un 90% menos de agua que los métodos tradicionales y adaptándose eficientemente a espacios reducidos, lo que permite un crecimiento más rápido de los cultivos. Sin embargo, muchos agricultores, tanto aficionados como expertos, enfrentan barreras para acceder a soluciones tecnológicas integradas que faciliten el monitoreo y la optimización de sus cultivos. Como startup, nuestro objetivo es abordar la siguiente interrogante: ¿Cómo podemos emplear tecnologías IoT para ofrecer un servicio innovador que brinde herramientas accesibles y avanzadas, permitiendo a los aficionados y expertos en hidroponía gestionar sus cultivos de manera eficiente?

#### 1.2.2.2. Lean UX Assumptions

**Business outcomes:**

- Los usuarios están interesados en monitorear y optimizar sus cultivos utilizando tecnología IoT.
- Los usuarios buscan orientación y soporte para configurar y utilizar sensores IoT en sus proyectos agrícolas.
- Los usuarios desean una interfaz intuitiva y fácil de usar para configurar sensores, visualizar datos en tiempo real, y recibir alertas.
- Los usuarios deben poder interpretar los datos de manera clara y precisa para tomar decisiones informadas sobre sus cultivos.
- Las aplicaciones deben ser compatibles con los múltiples dispositivos y navegadores actuales.

**User assumptions:**

- **¿Quién es el usuario?**

Los usuarios son agricultores, tanto aficionados como expertos, que buscan mejorar la gestión de sus cultivos mediante la implementación de tecnología IoT. Incluye tanto a aficionados que están aprendiendo sobre agricultura tecnológica como a expertos que desean optimizar sus procesos.

- **¿Dónde encaja nuestro producto en su trabajo o vida?**

Nuestra aplicación puede ser una herramienta esencial para la gestión diaria de cultivos hidropónicos, permitiendo a los usuarios monitorear factores críticos como temperatura, humedad y luz, optimizando el uso de recursos y mejorando la productividad.

- **¿Qué problema tiene nuestro producto? ¿Cómo se resuelve?**

El problema es la falta de herramientas accesibles para monitorear cultivos en tiempo real, lo que puede llevar a ineficiencias en el uso de recursos. Se resuelve ofreciendo una plataforma que permite la configuración y monitoreo de sensores IoT, proporcionando alertas y recomendaciones basadas en datos.

- **¿Cuándo y cómo es usado nuestro producto?**

Nuestro producto es utilizado tanto en tiempo real como de forma periódica, permitiendo a los usuarios revisar el estado de sus cultivos, recibir notificaciones y ajustar configuraciones según las necesidades cambiantes de sus plantas. Los expertos pueden usar la plataforma para gestionar múltiples cultivos simultáneamente.

- **¿Qué características son importantes?**

Las características más importantes incluyen la capacidad de conectar y configurar múltiples sensores IoT, visualización de datos en tiempo real, alertas automáticas ante condiciones adversas, y un sistema de recomendaciones basado en análisis de datos históricos.

- **¿Cómo debe verse nuestro producto y comportarse?**

El producto debe ser visualmente atractivo y fácil de usar, con una interfaz que permita a los usuarios navegar y configurar sensores rápidamente. Debe ser robusto, eficiente, y garantizar un rendimiento estable incluso al manejar grandes volúmenes de datos.

#### 1.2.2.3. Lean UX Hypothesis Statements

En esta sección, presentaremos hipótesis que proponen soluciones a las problemáticas identificadas previamente en nuestro proyecto enfocado en el monitoreo de cultivos mediante tecnología IoT. Estas hipótesis serán específicas y contarán con métricas claras para garantizar que el éxito pueda ser evaluado de manera objetiva. Las métricas utilizadas se basan en promedios generales de aplicaciones y sistemas IoT existentes en el sector agrícola.

**Hipótesis 1:**

Creemos que nuestra aplicación y sistema IoT serán una herramienta invaluable para aficionados en el cultivo hidropónico, permitiéndoles monitorear y gestionar eficientemente sus cultivos. Sabremos que tuvimos éxito cuando más del 70% de los usuarios aficionados reporten mejoras significativas en la salud y rendimiento de sus cultivos.

Métricas:

1. Porcentaje de usuarios aficionados que reportan mejoras en sus cultivos

    - Métrica actual: 0%
    - Métrica deseada: 70%

<br>

2. Número de sesiones de monitoreo activas por usuario aficionado por semana

- Métrica actual: 1
- Métrica deseada: 5

<br>

**Hipótesis 2:**

Creemos que la contribución de expertos en agricultura será fundamental para optimizar las funcionalidades avanzadas de nuestra plataforma. Sabremos que tuvimos éxito cuando más del 75% de los expertos utilicen y recomienden nuestras herramientas analíticas y de personalización avanzada.

Métricas:

1. Porcentaje de expertos que utilizan funcionalidades avanzadas

    - Métrica actual: 0%
    - Métrica deseada: 75%

<br>

2. Número de configuraciones personalizadas creadas por expertos

    - Métrica actual: 0
    - Métrica deseada: 50 por mes

<br>

**Hipótesis 3:**

Creemos que nuestra aplicación será utilizada principalmente por personas mayores de 18 años, siendo este nuestro segmento objetivo principal. Sabremos que tuvimos éxito cuando el 85% de nuestros usuarios activos pertenezcan a este grupo de edad.

Métricas:

1. Porcentaje de usuarios mayores de 18 años

    - Métrica actual: 0%
    - Métrica deseada: 85%

<br>

2. Tasa de retención de usuarios mayores de 18 años

    - Métrica actual: 0%
    - Métrica deseada: 70% mensual

<br>

**Hipótesis 4:**

Creemos que nuestra aplicación será sencilla y fácil de usar para todos nuestros usuarios. Sabremos que tuvimos éxito cuando más del 85% de los usuarios reporten una alta satisfacción con la usabilidad de la aplicación en encuestas periódicas.

Métricas:

1. Porcentaje de usuarios satisfechos con la usabilidad

    - Métrica actual: 0%
    - Métrica deseada: 85%

<br>

2. Tiempo promedio para configurar el sistema IoT por parte de nuevos usuarios

    - Métrica actual: 60 minutos
    - Métrica deseada: 20 minutos

<br>

**Hipótesis 5:**

Creemos que la función de comunidad será una característica significativa donde los usuarios puedan compartir experiencias, consejos y soluciones relacionadas con sus proyectos de cultivo. Sabremos que tuvimos éxito cuando más del 65% de los usuarios activos participen regularmente en la comunidad.

Métricas:

1. Porcentaje de usuarios activos que participan en la comunidad

    - Métrica actual: 0%
    - Métrica deseada: 65%

<br>

2. Número de publicaciones y comentarios en la comunidad por mes

    - Métrica actual: 0
    - Métrica deseada: 100 publicaciones y 300 comentarios

<br>

#### 1.2.2.4. Lean UX Canvas

En esta sección, presentaremos nuestro Lean UX Canvas, que resume los aspectos clave de nuestro proyecto y las estrategias para abordarlos de manera efectiva. Este canvas se basa en los principios de Lean UX, que enfatizan la colaboración, la iteración y la validación continua para lograr resultados exitosos.

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1279338931485151233/image.png?ex=66d414ba&is=66d2c33a&hm=eda6fcf9fdd0619ef2cbb611db62e1eef037b59963db975df2ea38789a8ba078&=&format=webp&quality=lossless&width=1356&height=676"/>
</div>

## 1.3. Segmentos objetivos

| Tipo de Usuario | Personas que deseen iniciar en la hidroponía                                                                                                                                                                                                                                 | Expertos que desean brindar sus conocimientos a los principiantes                                                                                                                                                                                                |
| :-------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Geográfico      | País: Perú <br><br> Zona residencial: No es relevante, ya que pueden ser de diferentes zonas del país.                                                                                                                                                                                      | País: Perú <br><br> Zona residencial: No es relevante, ya que pueden ser de diferentes zonas del país.                                                                                                                                                                          |
| Psicográfico    | Clase Social: Principalmente de clase media a clase media alta, interesados en aprovechar tecnologías accesibles para mejorar sus cultivos. <br><br> Estilo de vida: Personas interesadas en la agricultura y sostenibilidad, que buscan aprender a utilizar tecnologías IoT para mejorar sus cultivos, pero carecen del conocimiento técnico necesario para comenzar por su cuenta. | Clase Social: Desde clase media hasta clase alta, con recursos para invertir en tecnologías avanzadas. <br><br> Estilo de vida: Agricultores con experiencia que buscan optimizar sus procesos de cultivo mediante herramientas IoT. |
| Demográfico     | Edad: Personas mayores de 18 años. <br><br> Nivel de Ingreso: Varía según la capacidad de inversión en tecnologías IoT, desde ingresos medios a altos. <br><br> Nacionalidad: Principalmente peruanos; extranjeros pueden acceder al servicio con identificación válida, como pasaporte.                                                    | Edad: Preferiblemente mayores de 30 años. <br><br> Nivel de Ingreso: Ingresos medios a altos, con capacidad para invertir en tecnología avanzada. <br><br> Nacionalidad: Principalmente peruanos; extranjeros deben identificarse con pasaporte. <br><br> Estudios: Secundaria completa o estudios superiores, idealmente con formación en agricultura o tecnología.                          |

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se han formulado las preguntas para nuestro segmento objetivo, con la finalidad de obtener información cualitativa como opiniones o descripciones. Esta información nos será de gran ayuda en el desarrollo de nuestra solución.

**Adquisición de información general**

1. ¿Cómo te llamas?
2. ¿Cuántos años tienes?
3. ¿Cuál es tu ocupación?
4. ¿En qué lugar resides actualmente?

**Segmento 1: Aficionados a la hidroponía**

1. ¿Por qué estás interesado en empezar un proyecto de hidroponía casero con tecnología IoT?
2. ¿Cómo imaginas que sería tu proyecto de hidroponía con monitoreo automatizado?
¿Cuáles son los principales desafíos que enfrentas al buscar información sobre hidroponía y tecnología IoT?
3. ¿Qué beneficios esperas obtener al integrar sensores IoT en tu proyecto de hidroponía?
4. ¿Te resultaría útil una aplicación que ofrezca monitoreo en tiempo real y guías de expertos en IoT para hidroponía?
5. ¿Qué características o herramientas crees que serían esenciales en una aplicación de este tipo?

**Segmento 2: Expertos en hidroponía**

1. ¿Cómo empezaste en la hidroponía y qué te llevó a integrar tecnología avanzada en tus proyectos?
2. ¿Qué herramientas y datos específicos utilizas actualmente para optimizar tus cultivos hidropónicos?
3. ¿Cuáles son los principales desafíos que enfrentas al analizar y utilizar los datos de sensores IoT en tu sistema hidropónico?
4. ¿Qué tipo de datos adicionales o específicos te gustaría tener para mejorar la eficiencia de tu sistema?
5. ¿Te resultaría útil una aplicación que ofrezca análisis avanzados de datos y opciones personalizadas para gestionar tu cultivo?
6. ¿Qué funcionalidades consideras esenciales en una plataforma que te permita acceder y analizar datos complejos de tus cultivos en tiempo real?

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

| # Orden | User Story Id | Título                                                                           | Descripción                                                                                                                                                      | Story Points (1 / 2 / 3 / 5 / 8) |
| :------ | :------------ | :------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------- |
| 1       | US01          | Registro de Usuario                                                             | Como aficionado y/o experto Quiero registrarme en la página Para observar todo lo que ofrece el producto inteligente.                                                                   | 3                                |
| 2 | US02 | Visualización del Landing Page | Como aficionado y/o experto Quiero visualizar toda la información de las funcionalidades del producto inteligente Para conocer a fondo los beneficios para mis cultivos. | 2 |
| 3 | US19 | Validación de datos ingresados | Como aficionado y/o experto, quiero que los datos ingresados en la aplicación sean validados automáticamente para evitar errores | 2 |
| 4 | US03 | Visualización de las funcionalidades que ofrecen en el landing page | Como aficionado y/o experto Quiero visualizar los beneficios del producto inteligente, Para entender las funcionalidades que esta ofrece | 2 |
| 5 | US10 | Seguridad de datos | Como aficionado y/o experto, quiero asegurarme de que mis datos personales y de cultivos están protegidos contra accesos no autorizados. | 8 |
| 6 | US05 | Monitoreo en tiempo real de los parámetros del cultivo | Como aficionado, quiero monitorear en tiempo real los parámetros de mi cultivo (como temperatura, humedad y luz), para poder ajustar las condiciones y asegurarme de que mis plantas crezcan saludables. | 8 |
| 7 | US07 | Gestión de dispositivos IoT | Como aficionado y/o experto, quiero poder gestionar los dispositivos IoT vinculados para optimizar la supervisión de mis cultivos. | 5 |
| 8 | US06 | Configuración avanzada de alertas personalizadas para parámetros del cultivo | Como experto en el cuidado de cultivos, quiero configurar alertas personalizadas basadas en rangos específicos de temperatura, humedad y luz, para optimizar el rendimiento de mis plantas y prevenir problemas antes de que ocurran. | 5 |
| 9 | US20 | Gestión de múltiples cultivos | Como aficionado y/o experto, quiero gestionar múltiples cultivos dentro de la misma aplicación para centralizar toda la información. | 5 |
| 10 | US09 | Análisis de datos históricos | Como aficionado y/o experto, quiero acceder a datos históricos de mis cultivos para analizar tendencias y tomar mejores decisiones. | 5 |
| 11 | US15 | Integración de nuevos sensores IoT | Como aficionado y/o experto, quiero poder integrar nuevos sensores IoT en mi sistema para ampliar la supervisión de diferentes parámetros en mis cultivos. | 5 |
| 12 | US12 | Comparación de datos históricos | Como aficionado y/o experto, quiero comparar los datos actuales de mis cultivos con datos históricos para identificar tendencias. | 5 |
| 13 | US08 | Personalización de dashboard | Como aficionado y/o experto, quiero personalizar mi panel de control para visualizar solo la información más relevante. | 3 |
| 14 | US14 | Visualización de datos en gráficos | Como aficionado y/o experto, quiero visualizar los datos de mis cultivos en gráficos intuitivos para comprender mejor la información. | 3 |
| 15 | US16 | Exportación de datos históricos | Como aficionado y/o experto, quiero exportar los datos históricos de mis cultivos para analizarlos fuera del sistema o compartirlos con otros. | 3 |
| 16 | US18 | Exportación de datos | Como aficionado y/o experto, quiero poder exportar los datos de mis cultivos en diferentes formatos para análisis externo. | 3 | 
| 17 | US11 | Desvinculación de dispositivos | Como aficionado y/o experto, quiero poder desvincular dispositivos IoT que ya no utilizo para mantener mi panel de control limpio y organizado. | 3 |
| 19 | US04 | Visualización de los testimonios de personas sobre la landing page | Como aficionado y/o experto Quiero visualizar los testimonios de distintas personas acerca del producto inteligente para saber si cumple con su objetivo. | 1
| 20 | US13 | Gestión de energía de sensores | Como aficionado y/o experto, quiero monitorear el consumo de energía de mis sensores IoT para optimizar su uso y prolongar la vida útil. | 8 |


# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Event Storming

#### 4.1.1. Candidate Context Discovery

En esta sección, abordaremos el proceso de **Descubrimiento del Contexto del Candidato**, un componente crucial para la identificación y análisis de contextos relevantes en el desarrollo de aplicaciones y sistemas. Este proceso implica la exploración y recopilación de información clave que permite comprender los escenarios y necesidades de los usuarios o stakeholders involucrados. Utilizando la herramienta Miro, hemos mapeado visualmente los diversos contextos candidatos, integrando imágenes de referencia para proporcionar una visión clara y estructurada. A través de este enfoque, buscamos establecer una base sólida para la toma de decisiones informadas y el diseño eficaz de soluciones tecnológicas que se ajusten a los requerimientos identificados.

A continuación, se presenta la imagen de referencia del mapeo realizado en [Miro](https://miro.com/app/board/uXjVKnyuUYc=/):

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262690048311296/image.png?ex=66d7710b&is=66d61f8b&hm=f3ce999eaebae7a636ffb714abe5200ba721e8acc7a094721d7b0a931d8089cb&=&format=webp&quality=lossless&width=700&height=633"/>
</div>

#### 4.1.2. Domain Message Flows Modeling

En esta sección, abordaremos el **Modelado de Flujos de Mensajes de Dominio**, una técnica crucial para la representación de cómo los mensajes y datos se transmiten dentro de un sistema o entre diferentes dominios. Este modelado es fundamental para entender las interacciones entre componentes, servicios y entidades del dominio, lo que permite identificar dependencias, optimizar procesos y mejorar la arquitectura del sistema.

Para la creación de los diagramas de flujos de mensajes, hemos utilizado la herramienta Figma, que facilita el diseño colaborativo y la representación visual detallada de los flujos de mensajes. Figma nos ha permitido desarrollar diagramas precisos y fácilmente editables, proporcionando una visión clara de cómo los mensajes se intercambian y procesan en el sistema.

A continuación, se presenta las imágenes de referencia del modelado realizado en [Figma](https://www.figma.com/board/Hqho4dHjN1knvm4cqb4FLY/Domain-Message-Flows-Modeling?node-id=0-1\&t=UJPsVYgekUVI6V6A-1):

**Login and Register Context**
<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262831048097854/image.png?ex=66d7712d&is=66d61fad&hm=f3080371b96acbcc458d72836f69ae152048d3b07f739546593e3c5a36edbe34&=&format=webp&quality=lossless"/>
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262831446691944/image.png?ex=66d7712d&is=66d61fad&hm=11d88a4733a68803369e7ce76ac5ded7f190fa75906000817f4c6195352ae6c0&=&format=webp&quality=lossless"/>
</div>

**Monitoring Context**  
<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262831681310760/image.png?ex=66d7712d&is=66d61fad&hm=b830a92a2386abec4928cf5722e9347aeb6372f7abf50c14556f2beb6564ecbf&=&format=webp&quality=lossless"/>
</div>

**Notification Context**  
<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262831991820390/image.png?ex=66d7712d&is=66d61fad&hm=005eefdde36aae47de13b17b9a3e8fdf5778027d2a44dc8de4fbe26175c7f9fc&=&format=webp&quality=lossless"/>
</div>

**Report Context**  
<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262832289484800/image.png?ex=66d7712d&is=66d61fad&hm=24252bcafc1733a44bf4266afdc588303bca292a92be465230637f77e3ab8abf&=&format=webp&quality=lossless"/>
</div>

**Recommendation Context**  
<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280262832503390271/image.png?ex=66d7712d&is=66d61fad&hm=132168d65eaf20eed4afe6b7885f5cefde5f523691c4783ca92a54956694d11c&=&format=webp&quality=lossless"/>
</div>

#### 4.1.3. Bounded Context Canvases

En esta sección, examinaremos los **Bounded Context Canvases**, una herramienta fundamental en el diseño y análisis de arquitecturas de sistemas complejos. Los Bounded Context Canvases son utilizados para definir y visualizar los límites contextuales dentro de un sistema, permitiendo una comprensión clara de cómo se dividen y organizan los distintos dominios o contextos dentro de la solución.

El objetivo de los Bounded Context Canvases es identificar y documentar los límites entre diferentes contextos, así como las interacciones y relaciones entre ellos. Esto ayuda a asegurar que cada contexto tenga una definición clara y que las interacciones entre contextos sean gestionadas de manera efectiva, facilitando la integración y la coherencia en el sistema global.

A continuación, se presenta las imágenes de referencia del canvas de contextos realizado en [Miro](https://miro.com/welcomeonboard/V1h4alVMNXVwb1FpWHhlYnJXRnhYT0RuY3dUUlpPVDFIbllPR1prZFZrSGVGZ2RpSDc2ZWdaSzMydGJ0Um5ka3wzNDU4NzY0NTkzNDI3ODE3NjA2fDI=?share\_link\_id=388280836822):

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280263309077254237/image.png?ex=66d7719f&is=66d6201f&hm=9d3033aaf1774e5d348a1c48fea13fa46f3c27232aca1ed7637299f3f9c20782&=&format=webp&quality=lossless"/>
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280263309332844669/image.png?ex=66d7719f&is=66d6201f&hm=3cc78c5d4cf9e4b03c326c6aef69236481aa2546e9b306d9f0c7775c6e26fc53&=&format=webp&quality=lossless" />
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280263309593153566/image.png?ex=66d7719f&is=66d6201f&hm=e27b24fd5095b55a841088600ed89df86c6f5a3614f7d86bf7f807a322ecadb6&=&format=webp&quality=lossless" />
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280263309853065390/image.png?ex=66d7719f&is=66d6201f&hm=fb63e81abf782deda06e288423932ccd9bc9e7c48c9ec1558f7b97092b22d56f&=&format=webp&quality=lossless" />
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280263310188478474/image.png?ex=66d7719f&is=66d6201f&hm=8721f28a87614b130f021badeb2d51ff661b5b80090d4713a0bcbcc7ec384d05&=&format=webp&quality=lossless&width=1094&height=633" />
</div>

### 4.1.2. Context Mapping

En esta sección, exploraremos el **Context Mapping**, una técnica esencial para el diseño y análisis de arquitecturas de sistemas complejos. El Context Mapping se centra en la representación visual y la documentación de las interacciones y relaciones entre diferentes contextos o dominios dentro de un sistema. Esta técnica es crucial para identificar las dependencias, flujos de información y puntos de integración entre los contextos, ayudando a clarificar la estructura y facilitando una integración eficiente.

Utilizando la herramienta Lucidchart, hemos desarrollado un diagrama detallado que ilustra estos contextos y sus interacciones de manera clara y estructurada. Lucidchart permite crear diagramas precisos y colaborativos que facilitan la comprensión y comunicación de las relaciones entre los distintos dominios.

A continuación, se presenta la imagen de referencia del mapeo realizado en [Lucidchart](https://lucid.app/lucidchart/bd13a4a3-1ff1-461e-bd38-8dd32358d38d/edit?viewport\_loc=-221%2C69%2C2155%2C1115%2C0\_0\&invitationId=inv\_f25e463d-9272-4a27-93f5-a9dc1d179113):

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1280263375091273841/image.png?ex=66d771ae&is=66d6202e&hm=8cc3aaf3d78222cd1e8d0f36b5428a516bda29491ef213f03b266f6250ad5f78&=&format=webp&quality=lossless"/>
</div>

### 4.1.3. Software Architecture

En esta sección mostraremos los diagramas C4 donde se visualiza la arquitectura de nuestra solución.

#### 4.1.3.1. Software Architecture System Landscape Diagram

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1279342958021185546/1.png?ex=66d4187a&is=66d2c6fa&hm=1affe2358f3364003bc6561e8b1d0497c2986ef799d9d3577715ec0ff69bab66&=&format=webp&quality=lossless&width=904&height=676"/>
</div>

#### 4.1.3.2. Software Architecture Context Level Diagrams

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1279342958461714512/2.png?ex=66d4187a&is=66d2c6fa&hm=b5991f1ee3ed0ec3a9ed51987e73437471db6746e0516512aac429216672d270&=&format=webp&quality=lossless&width=865&height=676"/>
</div>

#### 4.1.3.3. Software Architecture Container Level Diagrams

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1279342959111962694/3.png?ex=66d4187a&is=66d2c6fa&hm=514b82be13447248484845bc096040b1178648491356fcac20264ce22bff374e&=&format=webp&quality=lossless&width=845&height=676"/>
</div>

#### 4.1.3.4. Software Architecture Deployment Diagrams

<div align="center">
    <img src="https://media.discordapp.net/attachments/1279240789611778109/1279342957417332798/4.png?ex=66d4187a&is=66d2c6fa&hm=84992093039c40e61f392e9f5d7a13141216f1b9a66cc203117092831e67b647&=&format=webp&quality=lossless&width=1440&height=637"/>
</div>

## 4.2. Tactical-Level Domain-Driven Design

# Conclusiones

# Bibliografía

# Anexos