# ecologIA: Limpiar el Parque 🌳♻️

Un juego educativo donde ayudás a limpiar un parque lleno de basura. Desarrollado en **HTML, CSS y JavaScript** (HTML5 Canvas), **sin librerías ni dependencias externas**.

Recorré el parque, que está **sucio y descuidado**, y completá cada **misión** recogiendo la basura que se indica **antes de que el tiempo se agote (30 segundos por misión)**. Cada residuo guarda un **dato real sobre el medio ambiente** que el personaje te cuenta al terminar la ronda. Al ganar cada misión recibís un **premio** que colocás en el parque; al final, los niños entran a jugar en los juegos que armaste.

## 🎯 Misiones

Cada misión pide recoger **solo** un residuo concreto. La misión activa se muestra en el **cartel inferior** del parque (con su barra de progreso). Los residuos que no corresponden a la misión actual se ven apagados y no se pueden recoger.

| Nivel | Qué recoger | Premio |
|---|---|---|
| 1 | 🧴 Botellas de plástico | ⚽ Pelota con arco |
| 2 | 📰 Diarios, 📦 cajas y 📄 papeles | Columpio y sube y baja |
| 3 | 🍌 Cáscaras de plátano, 🍉 de sandía y 🍎 manzanas mordidas | 3 carritos para pasear niños |
| 4 | 💩 Residuos sanitarios | Pileta con tobogán |

**Puntos:** cada residuo correcto suma **15 puntos** y avanza la barra de la misión. El contador de puntos y el progreso se muestran en el HUD.

**Hechos ambientales:** cada residuo tiene un dato educativo. Al terminar la ronda, el personaje te los lee uno por uno en su **globo de diálogo** (con su cara dibujada), sin repetir los que ya te contó.

## 🏆 Los premios y el tablero

Al completar cada misión, su premio aparece en el **tablero de premios** (abajo a la derecha). Cuando termines de limpiar el parque:

1. El personaje te muestra los **datos curiosos** de la ronda con tiempo para leerlos.
2. Después podés **colocar los premios**: elegí uno en el tablero y hacé **clic** (o tocá) donde quieras en el parque.
3. La **pelota** se coloca en 2 pasos: primero el **arco** elegido y luego la pelota.
4. Cuando terminás de colocar, presionás **"Terminar"** y el parque se abre.

### Opciones de pelota ⚽🏀🏐
Al ganar la primera misión podés elegir el deporte del arco: **fútbol**, **básquet** o **vóley**. El arco cambia de forma y los niños juegan según ese deporte.

### Física de la pelota 🎮
Una vez que los niños están jugando con la pelota, el personaje puede interactuar con ella:

- **Espacio / Enter**: patear la pelota en la dirección en que mirás. Sale rodando con rebotes en los bordes y frena por fricción.
- **R** (cerca de la pelota): **agarrarla**; la pelota queda en tu mano y te sigue mientras caminás.
- **R** de nuevo mientras la tenés: **tirarla por arriba** — sale con un arco parabólico, cae por gravedad y sigue rodando hasta detenerse.

## 🎪 La apertura del parque

Cuando colocás todos los premios y presionás **"Terminar"**, el parque se abre y entran **adultos** que pasean y **niños que corren por todos lados**. Los niños solo van a jugar a los juegos que **realmente colocaste**:

- **Columpio y sube y baja**: un niño se columpia (movimiento sincronizado con el asiento) y otros suben y bajan en el sube y baja.
- **Pileta**: dos niños nadan y chapotean, con el agua con ondas cuando hay niños adentro.
- **Carritos**: tres niños **manejan los carritos** dando vueltas en círculo; el conductor asoma cabeza y hombros adentro del auto.
- **Pelota**: dos niños juegan al deporte elegido (fútbol/básquet/vóley), se pasan la pelota y la tiran al arco.
- Si no colocaste algún juego, **no aparecen niños jugando en la nada**: simplemente corren por el parque.

Al final aparece el botón **"🔄 Volver a jugar"** para reiniciar la partida completa.

## 🎮 Cómo Jugar

- **Mové** a tu personaje con las flechas (`← ↑ ↓ →`) o **WASD** (o el **D-pad táctil** en celulares).
- **Caminá sobre la basura** que pide la misión para recogerla y avanzar en tu objetivo.
- Tenés **30 segundos** por misión; si se acaba el tiempo perdés una **vida** (3 corazones en total).
- Al completar cada ronda, el personaje te lee los **datos ambientales** de esa ronda con tiempo para leerlos.
- En el modo colocación, **clic** coloca el premio seleccionado; **Espacio/Enter** también lo coloca en la posición del personaje.

## ✨ Características

- **Parque que se limpia solo:** con cada misión completada desaparecen el barro, las manchas y los papeles, y el parque vuelve a florecer.
- **Educativo:** datos ambientales reales leídos al final de cada ronda.
- **Residuos dibujados a mano:** botellas azules, papeles arrugados, cajas usadas, diarios doblados, cáscaras de plátano/sandía y manzanas mordidas (sin emojis).
- **Sistema de misiones:** cada misión pide recoger un residuo concreto; los de otras misiones se ven apagados.
- **Premios colocables:** pelota con arco (3 deportes), columpio y sube y baja, 3 carritos y pileta.
- **Animación de apertura:** adultos y niños pasean, corren y juegan en los juegos colocados (solo en los que existen).
- **Pelota interactiva:** patear (Espacio), agarrar y tirar por arriba (R).
- **Sistema de vidas:** 3 corazones; perdés uno cuando se agota el tiempo.
- **Música de fondo de parque:** ambiente natural (**viento, arroyo y pájaros**) + **melodía alegre** generada en vivo con *Web Audio API*. Botón **🔊 / 🔇** para silenciar/activar.
- **Efectos de sonido** generados en tiempo real, sin archivos externos.
- **Gráficos en Canvas:** parque, árboles, personaje y personas dibujados con primitivas vectoriales.
- **Globo de diálogo con la cara del personaje** dibujada (niño/niña), sin emojis.
- **Tablero de premios** con slots de colocación semitransparentes.
- **Responsive + D-pad táctil:** funciona en celulares, tablets y computadoras.

## 🛠️ Tecnologías

- **HTML5:** estructura, HUD y lienzo de dibujo (`<canvas>`).
- **CSS3:** interfaz, pantallas de inicio/derrota, transparencias y diseño responsivo.
- **JavaScript (Vanilla):** bucle de juego, colisiones, física de la pelota, sonido procedural (naturaleza + melodía), animaciones y estado del juego.

> 📄 Todo el juego está empaquetado en un **único archivo**: `ecologIA-juego.html` (HTML + CSS + JS).

## 🚀 Instalación y Uso

No requiere instalación ni librerías externas.

1. Cloná el repositorio:
   ```
   git clone https://github.com/antonellaavalosc-ux/ecologIA.git
   ```
2. Abrí `ecologIA-juego.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. Si no ves los últimos cambios, forzá la recarga con **Ctrl+F5**.

## 🏆 Objetivo

Completá las **4 misiones**, colocá los premios y mirá cómo el parque cobra vida con los niños jugando. ¡El planeta te necesita!
