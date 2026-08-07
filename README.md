# ecologIA: Limpiar el Parque 🌳♻️

Un juego educativo donde ayudás a limpiar un parque lleno de basura. Desarrollado en **HTML, CSS y JavaScript** (HTML5 Canvas).

Recorré el parque, que está **sucio y descuidado**, y completá cada **misión** recogiendo la basura que se indica **antes de que el tiempo se agote**. ¡Completá tu primera misión para ganar una pelota amarilla 🎾 que podrás colocar donde quieras! Cada residuo te enseña un dato sobre el medio ambiente. ¡Sé el guardian que el planeta necesita!

## 🎯 Misiones

Cada misión pide recoger **solo** un residuo concreto. La misión activa se muestra en la parte superior:

| Nivel | Qué recoger | Premio |
|---|---|---|
| 1 | 🧴 Solo botellas de plástico | 🎾 Pelota amarilla |
| 2 | 📰 Solo papel y cartón | Columpio y sube y baja |
| 3 | 🍉 Cáscaras de plátano, de sandía y corazones de manzana | Carrito de paseo con luces |
| 4 | 💩 Solo popo de perro *(recoger los residuos peligrosos)* | Pileta con tobogán |

## 🏆 Los premios y el tablero

Al completar cada misión, su premio aparece en el **tablero de premios** (abajo a la derecha). Cuando termines de limpiar el parque:
1. Presioná **"Colocar premios"**.
2. Hacé clic en un casillero del tablero para elegir el premio.
3. Hacé clic donde quieras del parque para colocarlo (o parate ahí y presioná **Espacio**).

## 🎮 Cómo Jugar

- **Mové** a tu personaje por el parque con las flechas (`← ↑ ↓ →`) o **WASD**.
- **Caminá sobre la basura** que pide la misión para recogerla y avanzar en tu objetivo.
- Los residuos de otras categorías también se pueden juntar por puntos.
- Aprendé un dato curioso real sobre el medio ambiente con cada residuo recogido.

## ✨ Características

- **Parque que se limpia solo:** con cada misión completada el parque se ve más limpio: desaparecen el barro, las manchas, los papeles y la basura, y los árboles y flores vuelven a florecer.
- **Educativo:** dato ambiental real con cada residuo recogido.
- **Sistema de misiones:** cada misión pide recoger un residuo concreto.
- **Premios colocables:** pelota, columpio, carrito con luces y pileta con tobogán.
- **5 misiones** progresivas con más basura y menos tiempo.
- **Sistema de vidas:** 3 corazones; perdés uno cada vez que se agota el tiempo.
- **Efectos de sonido:** Generados en tiempo real con *Web Audio API*, sin archivos externos.
- **Gráficos en Canvas:** Parque, árboles y personaje dibujados con primitivas vectoriales.
- **Responsive + D-pad táctil:** Funciona en celulares, tablets y computadoras.

## 🛠️ Tecnologías

- **HTML5:** Estructura y lienzo de dibujo (`<canvas>`).
- **CSS3:** Interfaz, pantallas de inicio/derrota/victoria y diseño responsivo.
- **JavaScript (Vanilla):** Bucle de juego, detección de colisiones, sonido procedural y estado del juego.

## 🚀 Instalación y Uso

No requiere instalación ni librerías externas.

1. Cloná el repositorio:
   ```
   git clone https://github.com/antonellaavalosc-ux/ecologIA.git
   ```
2. Abrí `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).

## 🏆 Objetivo

Completá las **4 misiones** limpiando el parque y coleccioná todos los premios. ¡Cuanto más rápido recicles, más puntos!
