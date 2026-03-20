# 🎯 Juego del Número Secreto

Un pequeño proyecto web interactivo desarrollado con **HTML, CSS y JavaScript**, donde el usuario debe adivinar un número secreto generado aleatoriamente.

## 📝 Descripción

Este proyecto consiste en un juego simple en el que el usuario intenta descubrir un número secreto entre **1 y 10**.  
Cuenta con un límite de **3 intentos**, mensajes de ayuda para orientar si el número es mayor o menor, y la opción de reiniciar la partida al terminar.

Es ideal como práctica para reforzar conceptos básicos de:

- Manipulación del DOM
- Funciones en JavaScript
- Eventos con botones
- Condicionales
- Variables y arrays
- Lógica básica de juegos

---

## 📥 Funcionalidades

- Generación de número secreto aleatorio
- Validación del número ingresado por el usuario
- Pistas indicando si el número secreto es **mayor** o **menor**
- Límite máximo de intentos
- Botón para iniciar una nueva partida
- Interfaz visual atractiva con estilos personalizados

---

## 💾 Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**

---

## 🔤 Estructura del proyecto

```bash
juego-numero-secreto/
│
├── index.html
├── style.css
├── app.js
└── img/
    ├── ia.png
    ├── code.png
    └── Ruido.png
```
## Cómo ejecutar el proyecto

1. Clona este repositorio:
```
git clone https://github.com/scarrascoore/Juego_NumeroSecreto.git
```

2. Abre el archivo index.html en tu navegador

> [!NOTE]
> También puedes usar la extensión Live Server en Visual Studio Code para ejecutarlo fácilmente.

## Lógica del juego

- Al iniciar, el sistema genera un número secreto aleatorio del 1 al 10.
- El jugador escribe un número en el campo de entrada.
- Si acierta, el sistema muestra un mensaje indicando en cuántos intentos lo logró.
- Si falla, recibe una pista:
  - “El número secreto es mayor”
  - “El número secreto es menor”
- Si supera el máximo de intentos, el juego termina.
- Luego puede presionar el botón “Nuevo juego” para reiniciar.

## Vista del proyecto

<img src="./img/image.png" alt="Vista previa del proyecto" width="800">

## 👨‍💻 Autor

Proyecto desarrollado por Shelvy Carrasco Oré como práctica de lógica de programación con JavaScript.

## 📄 Licencia

Este proyecto puede usarse con fines educativos y de práctica personal.
