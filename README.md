# Monitoreo y Seteo de Sensores - Firebase Realtime Database

Este proyecto es una aplicación Android profesional diseñada para el **monitoreo en tiempo real** y el **control remoto (seteo)** de diversos sensores (Temperatura, Humedad, Velocidad y Presión) utilizando la infraestructura de **Firebase**.

---

## Tecnologías Utilizadas

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

---

## Características Principales

*   **Monitoreo en Tiempo Real:** Visualización instantánea de datos provenientes de Firebase Realtime Database.
*   **Seteo de Valores:** Interfaz intuitiva para enviar comandos y nuevos valores a los sensores.
*   **Interfaz Material Design:** Diseño limpio, centrado y fácil de usar, con iconos descriptivos para cada sensor.
*   **Scroll Dinámico:** Soporte para diferentes tamaños de pantalla mediante contenedores desplazables.

---

## Vista Previa del Layout

| Monitoreo en Tiempo Real | Seteo de Valores |
| :---: | :---: |
| ![Monitoreo](https://via.placeholder.com/200x400?text=Monitoreo+UI) | ![Seteo](https://via.placeholder.com/200x400?text=Seteo+UI) |

---

## Configuración e Instalación

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/JosephACS/appmovilfirebase.git
    ```
2.  **Configurar Firebase:**
    *   Crea un proyecto en [Firebase Console](https://console.firebase.google.com/).
    *   Añade una aplicación Android con el paquete `com.uteq.software.myapplication`.
    *   Descarga el archivo `google-services.json` y colócalo en la carpeta `app/`.
    *   Habilita **Realtime Database** y configura las reglas de lectura/escritura.
3.  **Compilar y Ejecutar:**
    *   Abre el proyecto en **Android Studio**.
    *   Sincroniza el proyecto con los archivos Gradle.
    *   Ejecuta en un emulador o dispositivo físico.

---

## Estructura del Proyecto

*   `MainActivity.java`: Lógica central, manejo de eventos de Firebase y listeners.
*   `activity_main.xml`: Diseño de la interfaz de usuario con ScrollView y LinearLayouts.
*   `drawable/`: Contiene los recursos visuales (`temp.png`, `water.png`, `speed.png`, `sensors.png`).

---

## Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar la aplicación o encontrar errores, siéntete libre de abrir un Issue o enviar un Pull Request.

---

## Licencia

Este proyecto está bajo la licencia MIT.

---
<p align="center"> Desarrollado para el monitoreo inteligente </p>
