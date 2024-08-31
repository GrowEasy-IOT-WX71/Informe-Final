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
            <img src="" alt="Jack Arana" style="margin-bottom: 5px;" width="800"/>
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



#### 1.2.2.3. Lean UX Hypothesis Statements




#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

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

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Event Storming

#### 4.1.1. Candidate Context Discovery

#### 4.1.2. Domain Message Flows Modeling

#### 4.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

# Conclusiones

# Bibliografía

# Anexos