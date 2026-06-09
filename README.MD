# 🐄 SocialMilk — API Documentation

> Documentación interactiva del backend de **SocialMilk**, una red social para productores lecheros con gestión ganadera integrada.

[![REST API](https://img.shields.io/badge/API-REST-38bdf8?style=flat-square)]()
[![Auth](https://img.shields.io/badge/Auth-JWT%20Bearer-fbbf24?style=flat-square)]()
[![Endpoints](https://img.shields.io/badge/Endpoints-67+-4ade80?style=flat-square)]()

---

## 📖 Descripción

**SocialMilk** es una plataforma que combina funcionalidades de red social con herramientas especializadas de gestión para productores lecheros. Permite llevar control del hato ganadero, registrar producción de leche, gestionar ventas e insumos, y conectar con otros productores a través de un feed social.

Este repositorio contiene la **documentación interactiva** del backend, generada a partir de la colección de Postman y desplegada con GitHub Pages.

---

## 🧩 Módulos del API

| Módulo | Descripción | Endpoints |
|---|---|:---:|
| 👤 **Auth & Perfiles** | Registro, login, sesión y gestión de perfiles | 7 |
| 🐄 **Animales** | Gestión del hato ganadero | 5 |
| 🏥 **Salud Animal** | Historiales clínicos y eventos sanitarios | 11 |
| 🥛 **Producción** | Registro de ordeño y análisis de producción | 6 |
| 📦 **Inventario de Leche** | Balance y movimientos de stock | 3 |
| 💰 **Ventas** | Registro de ventas a compradores | 4 |
| ✅ **Tareas** | Planificación de actividades ganaderas | 4 |
| 📝 **Publicaciones** | Feed social de la plataforma | 6 |
| 💬 **Interacciones** | Comentarios y likes en publicaciones | 7 |
| 🧪 **Insumos** | Suministros, inventario y movimientos | 10 |
| 🔍 **Auditoría** | Trazabilidad de acciones del sistema | 2 |
| 🤖 **AI Assistant** | Asistente de conocimiento conversacional | 3 |
| 🩺 **Health Check** | Diagnóstico de backend y base de datos | 2 |

---

## 🔐 Autenticación

La mayoría de endpoints requieren un token JWT enviado como Bearer token:

```
POST /auth/register  →  recibe { token, profileId }
POST /auth/login     →  recibe { token, profileId }

Authorization: Bearer <token>
```

---

## 🛠️ Despliegue local

Clona el repositorio y abre el archivo directamente en el navegador:

```bash
git clone https://github.com/tu-usuario/socialmilk-docs.git
cd socialmilk-docs
open index.html   # macOS
# o simplemente arrastra el archivo a tu navegador
```

---

## 📦 Estructura del repositorio

```
socialmilk-docs/
└── index.html      # Documentación interactiva completa
└── README.md       # Este archivo
```

---

## ⚙️ Activar GitHub Pages

1. Ve a **Settings → Pages** en tu repositorio
2. En *Source*, selecciona la rama `main` y la carpeta `/ (root)`
3. Guarda — en unos segundos estará disponible en `https://tu-usuario.github.io/socialmilk-docs`

> **Tip:** Renombra `SocialMilk_API_Docs.html` a `index.html` antes de subir para que GitHub Pages lo sirva automáticamente.

---

## 👨‍💻 Autor

**Juan Manuel Franco Osorio**  
Manizales, Colombia

---

<p align="center">
  Construido con 🐄 para la comunidad de productores lecheros
</p># SocialMilk-API-Documentation
