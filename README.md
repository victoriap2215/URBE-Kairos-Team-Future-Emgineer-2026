# Índice

# Índice

* [1. Nuestro Equipo](#1-nuestro-equipo)
  * [1.1 Integrantes](#11-integrantes)
  * [1.2 Nuestro Objetivo](#12-nuestro-objetivo)
  * [1.3 Contenido de la carpetas](#13-contenido-de-las-carpetas)
* [2. El Robot y Diseño Mecánico](#2-el-robot-y-diseño-mecánico)
  * [2.1 Chasis y Estructura](#21-chasis-y-estructura)
  * [2.2 Sistema de Dirección](#22-sistema-de-dirección)
  * [2.3 Sistema de Tracción](#23-sistema-de-tracción)
  * [2.4 Impresión 3D y Piezas](#24-impresión-3d-y-piezas)
* [3. Apartado Electrónico](#3-apartado-electrónico)
  * [3.1 Microcontrolador y Sensores](#31-microcontrolador-y-sensores)
  * [3.2 Controlador de Motores](#32-controlador-de-motores)
  * [3.3 Baterías y Alimentación](#33-baterías-y-alimentación)
  * [3.4 Esquemas de Conexión](#34-esquemas-de-conexión)
* [4. Software y Control](#4-software-y-control)
  * [4.1 Visión Artificial](#41-visión-artificial)
  * [4.2 Algoritmo de Navegación](#42-algoritmo-de-navegación)
* [5. Estructura del Repositorio](#5-estructura-del-repositorio)
  * [5.1 Contenido de Carpetas](#51-contenido-de-carpetas)
* [6. Demostración y Pruebas](#6-demostración-y-pruebas)
  * [6.1 Videos del Robot](#61-videos-del-robot)
* [7. Archivos de Fabricación y Diseño](#7-archivos-de-fabricación-y-diseño)
  * [7.1 Archivos CAD y 3D](#71-archivos-cad-y-3d)
  * [7.2 Esquemas Electrónicos](#72-esquemas-electrónicos)
  * [7.3 Slicer Files](#73-slicer-files)

---

## 1. Nuestro Equipo
Somos Kairos, un grupo de estudiantes universitarios dedicados a la robótica, la automatización y la innovación tecnológica. 
### 1.1 Integrantes
<table>
  <tr>
    <td width="30%" valign="top">
      <img src="T-photos/rosa.jpg" width="100%" alt="Rosalba Rodríguez">
    </td>
    <td valign="top">
      <h3>Rosalba Rodríguez</h3>
      <p>🎂 <b>Edad:</b> [21] años</p>
      <p>🧑‍💻 <b>Rol:</b> Hardware / Electrónica</p>
      <hr>
      <p>🔩 <b>Habilidades:</b></p>
      <ul>
        <li>Estudiante de Ing. Electrónica (Mención Automatización y Control).</li>
        <li>Desarrollo de sistemas de control para robótica autónoma.</li>
      </ul>
      <p>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td width="30%" valign="top">
      <img src="T-photos/vic.jpg" width="100%" alt="Victoria Perozo">
    </td>
    <td valign="top">
      <h3>Victoria Perozo</h3>
      <p>🎂 <b>Edad:</b> [20] años</p>
      <p>🧑‍💻 <b>Rol:</b> Documentación y Hardware / Electrónica</p>
      <hr>
      <p>🔩 <b>Habilidades:</b></p>
      <ul>
        <li>Estudiante de Ing. Electrónica (Mención Telecomunicaciones).</li>
        <li>Diseño y simulación de circuitos electrónicos.</li>
        <li>Desarrollo de sistemas de control para robótica autónoma.</li>    </td>
  </tr>
</table>
<table>
  <tr>
    <td width="30%" valign="top">
      <img src="T-photos/ayrtong.jpg" width="100%" alt="Ayrton Mrarcano">
    </td>
    <td valign="top">
      <h3>Ayrton Marcano</h3>
      <p>🎂 <b>Edad:</b> [19] años</p>
      <p>🧑‍💻 <b>Rol:</b> Programación / Electrónica</p>
      <hr>
      <p>🔩 <b>Habilidades:</b></p>
      <ul>
        <li>Estudiante de Ing. Informatica.</li>
        <li>Programación de microcontroladores y sensores.</li>
        <li>Desarrollo de sistemas de control para robótica autónoma.</li>
    </td>
  </tr>
</table>

### 1.2 Nuestro Objetivo
Este proyecto tiene como objetivo diseñar, construir y programar un robot autónomo capaz de superar una serie de desafíos de obstáculos para la competición WRO Future Engineers. El equipo Kairos se inspiró en la aplicación de principios de ingeniería y en la resolución creativa y eficiente de problemas, impulsados por la pasión por la innovación y el aprendizaje práctico. 

Buscamos desarrollar un sistema fiable y eficiente que muestre nuestras competencias técnicas y de trabajo en equipo, y que además ofrezca una experiencia formativa profunda. Para lograrlo seguimos un proceso sistemático: investigación, prototipado, pruebas de laboratorio e iteraciones continuas. Mantenemos documentación detallada para facilitar la transferencia de conocimiento y asegurar un flujo de trabajo ordenado a lo largo del proyecto

### 1.3 Contenido de las carpetas
Contenido (Github) 
*t-photos* contiene fotos del equipo

*v-photos* contiene 6 fotos del vehículo desde varios ángulos

*video* contiene el archivo video.md con el enlace a nuestro canal de YouTube y los vídeos correspondientes


*models* es para los archivos 3D que usamos para imprimir nuestras piezas

*other* incluye otros archivos que pueden usarse para entender cómo preparar el vehículo para la competición. Incluye documentación, conjuntos de datos, especificaciones de hardware, protocolos de comunicación, descripciones, etc.

*schemes* contiene diagramas esquemáticos de los componentes electromecánicos que ilustran todos los elementos (componentes electrónicos y motores) utilizados en el vehículo y cómo se conectan entre sí.

*src* contiene código de software de control para todos los componentes programados para participar en la competición

## 2. El Robot y Diseño Mecánico

### 2.1 Chasis y Estructura
Detalles de la estructura del vehículo.

### 2.2 Sistema de Dirección
Mecanismo de dirección (Ackermann).

### 2.3 Sistema de Tracción
### Motor: Motorreductor DC

<table>
  <tr>
    <td width="30%" valign="top" align="center">
      <br>
      <img src="Schemes/Motorreductor-con-caja-reductora-6V-1-48-1.jpg" width="100%" alt="Motorreductor DC">
    </td>jp
    <td valign="top">
      <h4>Especificaciones:</h4>
      <table>
        <tr><td><b>Voltaje</b></td><td>12v DC</td></tr>
        <tr><td><b>Velocidad sin carga (RPM)</b></td><td>200rpm</td></tr>
        <tr><td><b>Par de motor de pérdida</b></td><td>1.7 kg-cm</td></tr>
        <tr><td><b>Par máximo de eficiencia</b></td><td>0.34 kg-cm</td></tr>
        <tr><td><b>Relación de cambios</b></td><td>1:100</td></tr>
        <tr><td><b>Corriente nominal</b></td><td>0.04 A</td></tr>
        <tr><td><b>Corriente de pérdida</b></td><td>0.67 A</td></tr>
        <tr><td><b>Material de engranajes</b></td><td>metálico</td></tr>
        <tr><td><b>Datasheet</b></td><td><a href="https://www.bolanosdj.com.ar/MOVIL/ARDUINO2/MotoresConRuedasArd.pdf" target="_blank">MotoresConRuedasArd.pdf</a></td></tr>
      </table>
    </td>
  </tr>
</table>

### Dimensión mecánica
<img width="669" height="459" alt="dig moto" src="https://github.com/user-attachments/assets/3a24ec77-5204-483f-bd6a-a0ccbd2641f5" />

*Motivo de la elección*

El motorreductor amarillo DC fue seleccionado por su diseño ligero, económico y su facilidad de integración dentro de nuestro chasis. Su caja reductora integrada permite una transmisión directa y eficiente hacia las ruedas, proporcionando el par necesario para mantener una buena tracción en pistas planas dentro de una arquitectura modular.

Al no contar con un encoder (codificador) integrado para el conteo de vueltas, se incorporó un giroscopio que ofrece una retroalimentación de movimiento precisa. Esto asegura que los desplazamientos del robot sean exactos, compensando la ausencia de sensores de efecto Hall y reduciendo el margen de error al tomar curvas cerradas.

*Justificación técnica* 

Elegimos el motorreductor amarillo DC con su relación de reducción interna (1:48) porque nos ofrece el balance ideal entre torque, velocidad de respuesta y consumo energético. Esta configuración permite alcanzar la velocidad requerida en las ruedas para que los sensores de visión artificial y los sensores ultrasónicos ejecuten la captura y el procesamiento de datos en tiempo real con alta estabilidad, evitando desincronizaciones en las lecturas durante los giros.

Utilizando los modelos de transferencia de torque y considerando el peso total del chasis junto con la fricción de los ejes, los cálculos determinan que el torque requerido para vencer la fricción estática inicial y poner en marcha el robot se encuentra muy por debajo del torque máximo de pérdida especificado para estos motores. Este margen garantiza un factor de seguridad óptimo sobre el torque mínimo de arranque, asegurando que los motores operen de forma continua en su zona de mayor eficiencia sin sobrecalentamiento.

*Diferencial de engranaje (Diseño principal)*

Originalmente se diseñó un sistema de engranajes diferencial impreso en 3D para ser acoplado al conjunto del motorreductor amarillo. Este mecanismo permitiría que las ruedas traseras (izquierda y derecha) giraran a velocidades independientes durante las curvas, optimizando el desplazamiento fluido y mejorando la estabilidad del robot en giros exigentes. Sin embargo, debido a fallos en la manufactura de las piezas mecánicas, no fue posible su implementación en el prototipo final.
Solución del diseño

Durante la fase de ensamblaje se identificó un error de tolerancia en la impresión de los engranajes internos del diferencial (el anillo y los piñones satélite). Ante la imposibilidad de reimprimir estas piezas a tiempo para las pruebas, se sustituyó la caja del diferencial por un sistema de transmisión de eje rígido directo.

Aunque esta modificación elimina la capacidad mecánica de variar la velocidad entre ambas ruedas al girar, el efecto se compensa a través de código: el software utiliza los datos del giroscopio para ajustar la aceleración y gestionar electrónicamente la trayectoria del vehículo en las curvas.

### 2.4 Impresión 3D y Piezas
Descripción de piezas diseñadas e impresas.

## 3. Apartado Electrónico

### 3.1 Microcontrolador y Sensores
Cámara, MPU6050, sensores ultrasónicos, etc.

### 3.2 Controlador de Motores
Drivers de motores utilizados.

### 3.3 Baterías y Alimentación
Sistema de energía y regulación.

### 3.4 Esquemas de Conexión
Diagramas de cableado.

## 4. Software y Control

### 4.1 Visión Artificial
Procesamiento de imagen y detección de señales/líneas.

### 4.2 Algoritmo de Navegación
Lógica de esquivar obstáculos y recorrido.

## 5. Estructura del Repositorio

### 5.1 Contenido de Carpetas
Explicación de carpetas como models, schemes, t-photos, v-photos, video, etc.

## 6. Demostración y Pruebas

### 6.1 Videos del Robot
Enlaces a pruebas y funcionamiento en pista.

## 7. Archivos de Fabricación y Diseño

### 7.1 Archivos CAD y 3D
Archivos .step o .stl ubicados en la carpeta models.

### 7.2 Esquemas Electrónicos
Diagramas esquemáticos en PDF o imagen.

### 7.3 Slicer Files
Archivos de laminación (.gcode, .3mf o .3fd) listos para impresión 3D.
---

#### 2.2.1 Impresión 3D
Detalles sobre impresión 3D.

# Introducción
En este repositorio se encuentra la documentación completa de nuestro trabajo para la categoría Future Engineers: desde el diseño mecánico y la selección de componentes, hasta el desarrollo del software, los protocolos de prueba y la evolución de nuestro prototipo.
