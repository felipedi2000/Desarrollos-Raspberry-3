# Proyecto de Ejercicios con Raspberry Pi 3 y Proteus

Este repositorio contiene una serie de ejercicios realizados utilizando una **Raspberry Pi 3** y el software **Proteus** para simular circuitos electrónicos. Los ejercicios incluyen el uso de diversos componentes electrónicos como **pantallas LCD**, **LEDs**, **pulsadores**, y **conversores analógicos a digitales (ADC)** para medir voltajes.
Ademas se incluye un archivo en el cual se tienen los ejercicios mas basicos de logica en python

## Ejercicios Realizados

Se realizaron 4 ejercicios prácticos que permiten aprender y aplicar los conceptos de electrónica y programación utilizando la Raspberry Pi 3. Los ejercicios incluyen la integración de hardware y software para implementar funcionalidades específicas:

### 1. **Control de LEDs con Pulsadores**
   - En este ejercicio se utilizó un pulsador para encender y apagar un LED conectado a la Raspberry Pi 3. La lógica de encendido y apagado fue controlada mediante el uso de entradas y salidas digitales.

### 2. **Lectura de Voltaje con ADC**
   - Este ejercicio implicó el uso de un conversor analógico a digital (ADC) para medir el voltaje de una señal analógica y mostrar el valor en la pantalla LCD. La Raspberry Pi 3 se utilizó para leer los valores del ADC y convertirlos a una lectura digital.

### 3. **Visualización de Datos en Pantalla LCD**
   - En este ejercicio, se conectó una pantalla LCD a la Raspberry Pi para mostrar los valores de voltaje leídos desde un ADC, así como otros datos de sensores. La interfaz LCD se actualiza en tiempo real con los datos proporcionados por los sensores.

### 4. **Simulación en Proteus**
   - Para realizar pruebas y simulaciones, se utilizó **Proteus** para crear los circuitos electrónicos de los ejercicios antes de implementarlos en hardware real. Las simulaciones en Proteus ayudaron a verificar el funcionamiento de los componentes y la lógica antes de la implementación física.

## Requerimientos de Hardware

- **Raspberry Pi 3**
  - La Raspberry Pi 3 es utilizada para el control y procesamiento de datos en los ejercicios.
- **Pantalla LCD**
  - Se utiliza para mostrar información de los sensores y mediciones.
- **LEDs**
  - Se utilizan como indicadores de estado o para visualizar la activación de funciones.
- **Pulsadores**
  - Se utilizan para interactuar con el sistema, activando o desactivando funciones específicas.
- **Conversor Analógico-Digital (ADC)**
  - Se utiliza para medir señales de voltaje analógicas y convertirlas a formato digital.

## Requerimientos de Software

- **Proteus**:
  - Software de simulación utilizado para diseñar y simular los circuitos electrónicos antes de implementarlos físicamente.
- **Sistema Operativo Raspberry Pi** (Raspbian recomendado):
  - Se utiliza para ejecutar los programas escritos en Python que controlan los circuitos y componentes de hardware conectados a la Raspberry Pi.
- **Python**:
  - Lenguaje de programación utilizado para interactuar con los componentes de hardware de la Raspberry Pi y controlar los LEDs, pulsadores y la pantalla LCD.

## Instalación

1. **Configura la Raspberry Pi**:
   - Instala el sistema operativo **Raspbian** en tu Raspberry Pi 3.
   - Asegúrate de que la Raspberry Pi esté conectada a internet para instalar las dependencias necesarias.

2. **Simulación en Proteus**:
   - Abre el archivo de simulación de Proteus que contiene los circuitos de cada ejercicio.
   - Ajusta las configuraciones de la Raspberry Pi y otros componentes según sea necesario.

3. **Cargar el código en Raspberry Pi**:
   - Descarga lospryectos desde este repositorio y accede a los Scripts cárgalos en tu Raspberry Pi.
