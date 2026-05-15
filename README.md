# Detector Messi vs. Cristiano ⚽🤖

Este proyecto es una aplicación web sencilla que utiliza inteligencia artificial para identificar si una imagen cargada corresponde a **Lionel Messi** o a **Cristiano Ronaldo**.

## 📝 Descripción

La aplicación permite al usuario subir una foto o usar la cámara para que un modelo de clasificación determine, en tiempo real, cuál de los dos astros del fútbol aparece en la imagen.

## 🧠 Entrenamiento del Modelo

Para el desarrollo del cerebro de esta aplicación, utilizamos **Teachable Machine** de Google. El proceso de entrenamiento consistió en:

* **Clase Messi:** Se utilizaron 50 imágenes representativas de Lionel Messi.
* **Clase Cristiano:** Se utilizaron 50 imágenes representativas de Cristiano Ronaldo.
* **Procesamiento:** El modelo fue entrenado directamente en el navegador, generando un archivo de pesos que la página web utiliza para realizar las predicciones.

## 🛠️ Tecnologías

* [Teachable Machine](https://teachablemachine.withgoogle.com/) - Entrenamiento del modelo.
* HTML5 / CSS3 - Interfaz de usuario.
* JavaScript - Lógica de carga y ejecución del modelo.

## 👥 Integrantes

El equipo de desarrollo está conformado por:

* **Adriano Aragon**
* **Sebastian Blanco**
* **Santiago Perez**
* **Ney Salazar**

---
*Este proyecto fue realizado con fines educativos para demostrar el uso de herramientas de Machine Learning accesible.*
