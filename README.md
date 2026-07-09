# Monitoreo y Seteo de Sensores - Firebase Realtime Database

Este proyecto es una aplicación Android profesional diseñada para el monitoreo en tiempo real y el control remoto (seteo) de diversos sensores (Temperatura, Humedad, Velocidad y Presión) y el rastreo de ubicación mediante mapas utilizando la infraestructura de Firebase.

---

## Tecnologías Utilizadas

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Google Maps" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## Modulos Implementados

### Monitoreo de Sensores
Visualización de datos de temperatura, humedad, velocidad y presión directamente desde Firebase Realtime Database con actualización automática.

### Seteo de Valores
Interfaz para modificar los parámetros de los sensores de forma remota, permitiendo el control del sistema desde la aplicación móvil.

### Rastreo GPS y Mapas
Implementación de Google Maps SDK para visualizar la ubicación actual de un vehículo (GPR250) en tiempo real. El marcador se desplaza automáticamente siguiendo las coordenadas recibidas de Firebase.

### Script de Simulación (Python)
Desarrollo de un script externo en Python para simular el envío de coordenadas GPS y datos de sensores a Firebase mediante peticiones REST, facilitando las pruebas de movimiento en el mapa.

---

## Características Principales

* Monitoreo en Tiempo Real: Visualización instantánea de datos provenientes de Firebase Realtime Database.
* Seteo de Valores: Interfaz intuitiva para enviar comandos y nuevos valores a los sensores.
* Seguimiento en Mapa: Marcadores dinámicos y animación de cámara para seguimiento de activos.
* Interfaz Material Design: Diseño limpio, centrado y fácil de usar con iconos descriptivos.

---

## Configuración e Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/JosephACS/appmovilfirebase.git
   ```

2. Configurar Firebase:
   * Crea un proyecto en Firebase Console.
   * Añade una aplicación Android con el paquete com.uteq.software.myapplication.
   * Descarga el archivo google-services.json y colócalo en la carpeta app/.
   * Habilita Realtime Database.

3. Configurar Google Maps:
   * Obtén una API KEY desde Google Cloud Console.
   * Agrégala en el archivo AndroidManifest.xml del proyecto.

4. Ejecución del Simulador Python:
   * Instala las dependencias: `pip install requests`
   * Ejecuta el script: `python scripts.py`

---

## Estructura del Proyecto

* MainActivity.java: Manejo de sensores y seteo de valores.
* ActividadMapa.java: Implementación de Google Maps y rastreo en tiempo real.
* scripts.py: Simulador de datos en Python.
* activity_actividad_mapa.xml: Interfaz del mapa con soporte para fragmentos de Google.

---

## Licencia

Este proyecto está bajo la licencia MIT.

---
<p align="center"> Desarrollado para el monitoreo inteligente </p>
