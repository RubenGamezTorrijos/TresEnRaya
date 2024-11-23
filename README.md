# 🎮**Tres en Raya: Java**
¡Bienvenido al proyecto Tres en Raya! 🎯 Este proyecto está desarrollado en Java con el editor Netbeans con el que podrán jugar diferentes 2 jugadores en modo local (sin conexión a internet) en lateral aparecen los participantes y quién ha ganado.

![TresEnRaya_Java](https://user-images.githubusercontent.com/19588354/140736544-59df772c-18e2-4dde-be8b-3a423eac1478.jpg)
![TresEnRaya_Java_Imagen](https://user-images.githubusercontent.com/19588354/140736546-b424749a-093e-4cff-b220-5f7ce4e0562a.jpg)


![Status](https://img.shields.io/badge/Estado-Producción-green?style=flat-square)
![GitHub license](https://img.shields.io/github/license/RubenGamezTorrijos/TresEnRaya?style=flat-square)
![GitHub version](https://img.shields.io/github/v/tag/RubenGamezTorrijos/TresEnRaya?label=versión&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/RubenGamezTorrijos/TresEnRaya?style=flat-square)
![GitHub Repo stars](https://img.shields.io/github/stars/RubenGamezTorrijos/TresEnRaya?style=social)

![GitHub issues](https://img.shields.io/github/issues/RubenGamezTorrijos/TresEnRaya?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/RubenGamezTorrijos/TresEnRaya?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/RubenGamezTorrijos/TresEnRaya?style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/RubenGamezTorrijos/TresEnRaya/main.yml?style=flat-square)

> **Versión actual:** 1.0.0  
> **Plataforma:** Java
> **Compatibilidad:** Windows

---

## 📋 Índice
- [Características](#-características)
- [Estructura](#-estructura)
- [Guía de uso](#-guía-de-uso)
- [Desarrollo](#-desarrollo)
- [Capturas](#-capturas)
- [Contribuciones](#-contribuciones)
- [Próximas mejoras](#-próximas-mejoras)
- [Créditos](#-créditos)
- [Licencia](#-licencia)

---

## 🌟 Características
* ✅ **Frontend:** Interfaz de usuario en *.form
* ✅ **Lenguaje:** Está desarrollado en Java y con IDE NetBeans.
* ✅ **Jugadas:** Combinaciones posibles según la jugada que realice cada jugador hasta ganar y supar.
* ✅ **Diseño Responsivo:** Compatible con dispositivos de escritorio.
* ✅ **Pruebas:** Se realiza el juego con X o Y hasta completar las 3 en raya.

---

## 📂 Estructura

**Estructura del proyecto**
```
TresEnRaya/
├── TresEnRaya/
│   ├── src/
│   │   └── tresenraya/ 
│   │        ├── Juego.form       # Front-end diseño interfaz de usuario
│   │        ├── Juego.java       # Acciones del juego y botones 
│   │        ├── LogicaJuego.java # Lógica del juego en Java 
│   │        └── logo.png
│   ├── build.xml                 # manifest declaración de dependencias
│   └── manifest.mf               # Estructura Juego: Constructor
├── README.md                     # Documentación del proyecto
└── LICENSE                       # Licencia Apache 2.0

```

---

## 🚀 **Guía de Uso**
### 1. Instalación
🔹1. Clona este repositorio:
```
git clone https://github.com/tu-usuario/TresEnRaya.git
cd calculator
```

🔹2. Instala las dependencias:

```
Instalar dependencias del proyecto
```

### 2. Ejecución del Proyecto

#### 🖥️ Frontend (Interfaz JavaFX)
Para ejecutar la interfaz de usuario localmente, importar el proyecto en Netbeans.

#### 🛠️ Backend
Para iniciar el servidor backend, ejecuta el siguiente comando:
```
Iniciar Netbeans o Importar
```
Esto iniciará el editor NetBeans para su ejecución.

---

## 🧑‍💻 Desarrollo
**Scripts útiles**

- Iniciar el servidor backend:
```
node backend/app.js
```
- Ejecutar el frontend (solo abrir en navegador).

> **NOTAS:** Requisitos de Desarrollo Asegúrate de tener instalado Node.js y npm para poder ejecutar el proyecto.

---

## 🧮 Ejemplos de Consultas
|Jugadores	| Descripción	Ejemplo |
|:----------|:-------------------|
| ``X``  |  Jugador 1 |
| ``o``	|  Jugador 2 |

---

## 🗂️ Contribuciones
**🤝 ¿Quieres colaborar? ¡Eres bienvenido! Sigue estos pasos:**
🔹1. Haz un fork de este repositorio.
🔹2. Crea un branch para tu funcionalidad:
```
git checkout -b mi-funcionalidad
```
🔹3. Haz un commit con tus cambios:
```
git commit -m "Añadir mi funcionalidad"
```
🔹4. Sube tus cambios:
```
git push origin mi-funcionalidad
```
🔹5. Abre un pull request en este repositorio.

---

## 🔮 Próximas Mejoras
- Añadir bbdd para guardar historial y usuario.
- Mejorar la interfaz de usuario con temas oscuros y claros.

---

## ✨ Créditos
Este proyecto no sería posible sin la colaboración de todos los desarrolladores que han contribuido:

### 🧑‍💻Rubén Gámez Torrijos
🖥️ - Desarrollo del frontend y la interfaz de usuario.
🔢 - Implementación de la lógica del juego.


Agradecemos también a todas las personas que probaron y sugirieron mejoras. 🙌

---

## 📝 Licencia
Este proyecto está bajo la licencia Apache 2.0. ¡Siéntete libre de usarlo, modificarlo y compartirlo!
