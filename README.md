# ecologIA: Limpiar el Parque 🌳♻️

Un juego educativo donde ayudás a limpiar un parque lleno de basura. Desarrollado en **HTML, CSS y JavaScript** (HTML5 Canvas), sin librerías externas.

Recorré el parque, que está **sucio y descuidado**, y completá cada **misión** recogiendo la basura que se indica **antes de que el tiempo se agote (20 segundos por misión)**. Cada residuo guarda un dato real sobre el medio ambiente que el personaje te cuenta al terminar la ronda. Al final, los niños entran al parque y juegan en los premios que colocaste.

## 🎯 Misiones

Cada misión pide recoger **solo** un residuo concreto. La misión activa se muestra en la parte superior:

| Nivel | Qué recoger | Premio |
|---|---|---|
| 1 | 🧴 Botellas de plástico (azules) | ⚽ Pelota con arco |
| 2 | 📰 Diarios, 📦 cajas y 📄 papeles (arrugados/usados) | Columpio y sube y baja |
| 3 | 🍌 Cáscaras de plátano, 🍉 de sandía y 🍎 manzanas mordidas | 3 carritos para pasear niños |
| 4 | 💩 Residuos peligrosos | Pileta con tobogán |

## 🏆 Los premios y el tablero

Al completar cada misión, su premio aparece en el **tablero de premios** (abajo a la derecha). Cuando termines de limpiar el parque:

1. El personaje te muestra los **datos curiosos** de la ronda con tiempo para leerlos.
2. Después podés **colocar los premios**: elegí uno en el tablero y hacé clic donde quieras en el parque.
3. La **pelota** tiene 2 pasos: primero colocás el **arco** elegido y luego la pelota.

### Opciones de pelota ⚽🏀🏐
Al ganar la primera misión podés elegir el deporte del arco: **fútbol**, **básquet** o **vóley**.

## 🎪 La apertura del parque

Cuando colocás todos los premios y presionás **"Terminar"**, el parque se abre y entran:

- **Adultos** que pasean y **niños que corren por todos lados**.
- **Niños jugando en los juegos**: se columpian en el columpio (sincronizado con el asiento), suben y bajan en el sube y baja (sincronizado), nadan en la pileta con olas, **manejan los carritos dando vueltas** y **dos niños juegan con la pelota** (se la pasan y tiran al arco).

Al final aparece el botón **"🔄 Volver a jugar"** para reiniciar la partida.

## 🎮 Cómo Jugar

- **Mové** a tu personaje con las flechas (`← ↑ ↓ →`) o **WASD** (o el D-pad táctil en celular).
- **Caminá sobre la basura** que pide la misión para recogerla y avanzar en tu objetivo.
- Tenés **20 segundos** por misión; si se acaba el tiempo perdés una vida (3 corazones).
- Al completar cada ronda, el personaje te lee los **datos ambientales** de esa ronda con tiempo para leerlos.

## ✨ Características

- **Parque que se limpia solo:** con cada misión completada desaparecen el barro, las manchas y los papeles, y el parque vuelve a florecer.
- **Educativo:** datos ambientales reales leídos al final de cada ronda.
- **Residuos dibujados a mano:** botellas azules, papeles arrugados, cajas usadas, diarios doblados, cáscaras de plátano/sandía y manzanas mordidas (sin emojis).
- **Sistema de misiones:** cada misión pide recoger un residuo concreto; los de otras misiones se ven apagados.
- **Premios colocables:** pelota con arco (3 deportes), columpio y sube y baja, 3 carritos y pileta.
- **Animación de apertura:** adultos y niños pasean, corren y juegan en los juegos colocados.
- **Sistema de vidas:** 3 corazones; perdés uno cuando se agota el tiempo.
- **Música de fondo de parque:** ambiente natural (viento, arroyo y pájaros) + melodía alegre generada en vivo con *Web Audio API*. Botón **🔊** para silenciar.
- **Efectos de sonido** generados en tiempo real, sin archivos externos.
- **Gráficos en Canvas:** parque, árboles, personaje y personas dibujados con primitivas vectoriales.
- **Globo de diálogo con la cara del personaje** dibujada (niño/niña), sin emojis.
- **Responsive + D-pad táctil:** funciona en celulares, tablets y computadoras.

## 🛠️ Tecnologías

- **HTML5:** estructura y lienzo de dibujo (`<canvas>`).
- **CSS3:** interfaz, pantallas de inicio/derrota y diseño responsivo.
- **JavaScript (Vanilla):** bucle de juego, colisiones, sonido procedural (naturaleza + melodía), animaciones y estado del juego.

## 🚀 Instalación y Uso

No requiere instalación ni librerías externas.

1. Cloná el repositorio:
   ```
   git clone https://github.com/antonellaavalosc-ux/ecologIA.git
   ```
2. Abrí `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).

## 🏆 Objetivo

Completá las **4 misiones**, colocá los premios y mirá cómo el parque cobra vida con los niños jugando. ¡El planeta te necesita!
