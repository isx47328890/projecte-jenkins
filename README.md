# Proyecto Jenkins

[![Jenkins photo][jenkins-photo]][jenkins-url]

<br><br><br><br>

**Autores:**  Christian Manalo y Mark Santiago  

**Curso:** 2º de Administración de sistemas informáticos en redes

**Centro:** INS Escola del Treball


### [Proyecto en GitHub](https://github.com/isx47328890/projecte-jenkins)

### [Proyecto en Taiga](https://tree.taiga.io/project/isx47328890-projecte-jenkins/timeline)

### [Servidor Jenkins](http://18.198.155.247:8080/)


<br><br><br><br>

# Índice

- **[Estudio inicial](#estudio-inicial)**
- **[Diseño del sistema](#diseño-del-sistema)**
- **[Análisis del sistema y conceptos](#análisis-del-sistema-y-conceptos)**
  - **[AWS](#aws)**
  - **[Jenkins](#jenkins)**
  - **[SonarQube](#sonarqube)**
- **[Desarrollo](#desarrollo)**
- **[Implantación](#implantación)**
- **[Mantenimiento](#mantenimiento)**
- **[Conclusiones](#conclusiones)**
- **[Bibliografía](#bibliografía)**

<br><br><br>

## Estudio inicial

El proyecto consistirá en el desarrollo de un sistema automatizado de entrega continua con **Jenkins**. El trabajo o "*job*" de Jenkins desplegará un repositorio **git** en un servidor y dentro de este proceso habrá diferentes etapas o "*stages*" de la cual cogerá los diferentes códigos del repositorio y será evaluada a través de **SonarQube** para saber la calidad del código, el cual devolverá un feedback.

<br><br><br>

## Diseño del sistema

![System photo][system-photo]

<br><br><br>

## Análisis del sistema y conceptos

#### AWS

<br><br><br>

#### Jenkins
Es un servidor automatizado de integración continua de código abierto, es capaz de organizar una cadena de acciones que ayudan a lograr el proceso de integración continua de manera automatizada,  está completamente escrito en **Java**.

Jenkins puede instalarse a través de un sistema de gestión de paquetes, Docker o incluso ejecutarse de forma independiente en cualquier máquina que tenga instalado Java Runtime Environment (JRE).

Las compañías de software pueden acelerar su proceso de desarrollo del código, ya que este puede automatizar, agilizar y aumentar el ritmo de toda la compilación y las pruebas de los proyectos.

<br><br><br>

### SonarQube
Es una plataforma de software libre para evaluar la calidad de nuestro código, realizando un análisis estático sobre dicho código, con el objetivo de advertirnos sobre diferentes puntos a mejorar.

Estos son los lenguajes soportados:

![Sonarqube photo][sonarqube-photo]

## Desarrollo

## Implantación

## Mantenimiento

## Conclusiones

## Bibliografía



[jenkins-photo]: img/Jenkins.png
[jenkins-url]: https://www.jenkins.io/
[taiga-url]: https://tree.taiga.io/project/isx47328890-projecte-jenkins/timeline
[system-photo]: img/system_photo.png
[sonarqube-photo]: img/lenguajes_sonarqube.jpg

