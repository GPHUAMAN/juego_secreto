# 🎮 JS Game — Adivina el Número

Juego web donde el usuario adivina un número secreto (1–30) usando pistas de "mayor/menor". HTML + CSS + JavaScript vanilla.

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Características
- Número secreto generado sin repetirse en la sesión
- Contador de intentos y retroalimentación por jugada
- Botón "Nuevo juego" habilitado solo al ganar

## 📂 Estructura
```
├── index.html
├── style.css
├── app.js
└── img/
```

## 🚀 Ejecutar
Abrir `index.html` en el navegador (sin dependencias).

## ⚠️ Pendiente
Los botones no están conectados a `verificarIntento()` / `reiniciarJuego()` (faltan `id="valorUsuario"` y listeners)
