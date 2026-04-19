# 🎥 Deja Que Entre el Sol — Proyecto Finalizado ✅

[![GitHub License](https://img.shields.io/github/license/Neymors/deja-que-entre-el-sol)](https://github.com/Neymors/deja-que-entre-el-sol/blob/main/LICENSE)
[![Netlify Status](https://api.netlify.com/api/v1/badges/46f5b606-d379-48d9-99ff-0e828adb1c45/deploy-status)](https://app.netlify.com/projects/deja-que-entre-el-sol/deploys)
[![Demo](https://img.shields.io/badge/🌐-Live%20Demo-brightgreen)](https://deja-que-entre-el-sol-vorterix.netlify.app/)

**Sitio NO oficial del equipo de streaming y contenido multimedia.** Un espacio donde la creatividad y el humor de Vorterix se encuentran con una arquitectura web sólida y moderna.

---

## 🧠 El Proyecto

Este sitio fue desarrollado como una plataforma integral para la comunidad de **Deja Que Entre el Sol**. El objetivo principal fue centralizar el contenido multimedia y las dinámicas del programa (como el NecroProde) en una interfaz rápida, estética y funcional.

### 🛠️ Tecnologías Core
- **Frontend:** HTML5, CSS3 (Glassmorphism & Dark Mode) y JavaScript Vanilla.
- **Backend (Serverless):** Netlify Functions (Node.js) para consumo seguro de APIs.
- **APIs:** YouTube Data API v3.
- **Despliegue:** Netlify con Continuous Integration desde GitHub.

---

## 🚀 Características Principales

- **🔄 Sistema de Proxy Seguro:** Implementación de una *Serverless Function* para gestionar las peticiones a la API de YouTube, protegiendo las credenciales en el lado del servidor.
- **📊 NecroProde dinámico:** Tabla de posiciones automatizada con lógica de ordenamiento por puntos.
- **🎬 Galería Auto-actualizable:** Consumo de contenido en tiempo real del canal oficial.
- **🌓 UI Adaptativa:** Modo oscuro integrado con persistencia en `localStorage`.
- **⏱️ Countdown Real-time:** Sistema de cuenta regresiva para el próximo programa en vivo.

---

## 👥 El Team

| [<img src="img/Team/Pergolini.jpeg" width=100><br>Mario Pergolini](https://instagram.com/mpergoliniok) | [<img src="img/Team/goncho.jpg" width=100><br>Goncho Banzas](https://instagram.com/gonchobanzas) | [<img src="img/Team/Fortunato.jpeg" width=100><br>Cami Fortunato](https://instagram.com/camilafortunatoph) |
|:---:|:---:|:---:|
| *Conductor Estrella* | *Experto en gaming* | *Reina De Tiktok* |

| [<img src="img/Team/Tropeanoo.jpeg" width=100><br>Juan Tropeano](https://instagram.com/juantropeano) | [<img src="img/Team/Rober.jpeg" width=100><br>Rober Galati](https://instagram.com/robergalati) | [<img src="img/Team/El Momo.jpg" width=100><br>Gerónimo Benabides](https://instagram.com/gero.momo) |
|:---:|:---:|:---:|
| *Gurú de redes* | *Especialista en humor* | *Boxeador, Sabe todo* |

---

## 🛡️ Arquitectura y Seguridad

A diferencia de un sitio estático convencional, este proyecto aplica conceptos de **Backend for Frontend (BFF)**:

1. **Ocultamiento de API Keys:** La clave de YouTube nunca llega al navegador del cliente; reside en las variables de entorno de Netlify.
2. **CORS Control:** El proxy está configurado para aceptar peticiones solo desde dominios autorizados.
3. **Optimización de Carga:** Se utiliza el método `rebase` en Git para mantener un historial de commits limpio y profesional.

---

## ⚙️ Instalación Local

Si querés testear el proyecto en tu máquina:

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/Neymors/deja-que-entre-el-sol.git](https://github.com/Neymors/deja-que-entre-el-sol.git)
