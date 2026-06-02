# 🧠 Trabajo Final IA — Visión Artificial con ML5.js

Proyecto final del curso de Inteligencia Artificial y Machine Learning.  
Aplicación web con **5 módulos de visión artificial** integrados en un dashboard tipo iframe, desarrollada con **ML5.js**, **p5.js**.

---

## 📋 Módulos

| # | Módulo | Descripción |
|---|--------|-------------|
| 01 | **Detección de imagen** | Clasifica imágenes usando el modelo MobileNet de ML5 con barra de confianza |
| 02 | **Trazado de línea** | Detecta ambas manos en tiempo real y traza una línea entre los dedos índices con p5.js |
| 03 | **Detección facial** | Detecta partes del rostro (ojos, nariz, cejas, boca) con FaceMesh y color personalizable |
| 04 | **Teachable Machine** | Clasifica objetos en tiempo real con un modelo propio entrenado en Teachable Machine, con voz en español |
| 05 | **Alerta de persona** | Detecta personas con COCO-SSD y activa una alarma de audio si la persona permanece más de 5 segundos |

---

## 🚀 Demo rápida

```
Abrir index.html en el navegador → seleccionar un módulo desde el menú lateral
```

> ⚠️ Requiere acceso a la cámara web. Algunos módulos necesitan conexión a internet para cargar los modelos.

---

## 🛠️ Tecnologías

- [ML5.js](https://ml5js.org/) — MobileNet, HandPose, FaceMesh, ObjectDetector (COCO-SSD)
- [p5.js](https://p5js.org/) — canvas y captura de video
- [Teachable Machine](https://teachablemachine.withgoogle.com/) — modelo personalizado (Plumón, Control remoto, Billetera, Botella)
- HTML5 / CSS3 — interfaz y estilos
- Web Speech API — síntesis de voz en módulo 04

---

## 📁 Estructura del proyecto

```
TrabajoFinal/
├── index.html          # Dashboard principal (iframe)
├── modulo01.html       # Detección de imagen
├── modulo02.html       # Trazado de línea (HandPose)
├── modulo03.html       # Detección facial (FaceMesh)
├── modulo04.html       # Teachable Machine
├── modulo05.html       # Alerta de persona (COCO-SSD)
├── css/
│   ├── style.css
│   ├── modulo01.css
│   ├── modulo02.css
│   ├── modulo04.css
│   └── modulo05.css
├── image/              # Imágenes para módulo 01
│   └── perro.jpg, gato.jpg, leon.jpg ...
├── audio/
│   └── alarma.mp3      # Sonido de alerta módulo 05
└── model/              # Modelo Teachable Machine exportado
    ├── metadata.json
    ├── model.json
    └── weights.bin
```

---

## ▶️ Cómo ejecutar

1. Clona o descarga el repositorio
2. Abre `index.html` en un navegador moderno (Chrome recomendado)
3. Permite el acceso a la cámara cuando se solicite
4. Selecciona un módulo desde el panel lateral o las tarjetas de inicio

> Para el **módulo 04 (Teachable Machine)**, el modelo ya está incluido en la carpeta `model/` — no necesita conexión al servidor de Google.

---

## 👤 Autor

**Sandro Pachas Romani**  
Estudiante de Ingeniería de Software con Inteligencia Artificial  
Instituto SENATI — Perú  

GitHub: [@sandropr24](https://github.com/sandropr24)
