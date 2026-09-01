# Guardián del planeta 🌳♻️

Un juego educativo donde ayudas a limpiar un parque lleno de basura. Desarrollado en **HTML, CSS y JavaScript** (HTML5 Canvas), **sin librerías ni dependencias externas**. Se utilizó **Opencode** para la creación de este juego.

Recorre el parque, que está **sucio y descuidado**, y completa cada **misión** recogiendo la basura que se indica **antes de que el tiempo se agote (30 segundos por misión)**. Cada residuo guarda un **dato real sobre el medio ambiente** que el personaje te cuenta al terminar la ronda. Al ganar cada misión recibes un **premio** que colocas en el parque; al final, los niños entran a jugar en los juegos que armaste.

## 🎯 Misiones

Cada misión pide recoger **solo** un residuo concreto. La misión activa se muestra en el **cartel inferior** del parque (con su barra de progreso). Los residuos que no corresponden a la misión actual se ven apagados y no se pueden recoger. Al inicio de cada misión, tienes 5 segundos para prepararte.

| Nivel | Qué recoger (Objetivo) | Premio al ganar |
|---|---|---|
| **1** | 🧴 **Botellas de plástico** (8 residuos) | ⚽ **Pelota amarilla** |
| **2** | 🛢️ **Galones de plástico** (7 residuos) | 🥅 **Pelota con arco** (Fútbol, básquet o vóley) |
| **3** | 🥛 **Vasos de plástico** (6 residuos) | 🛝 **Sube y baja** |
| **4** | 🫙 **Tapers de plástico** (4 residuos) | 🎠 **Columpio** |
| **5** | 🛍️ **Bolsas de plástico** (7 residuos) | 🏎️ **3 carritos para pasear niños** |
| **6** | 🪥 **Sorbetes de plástico** (6 residuos) | 🏊 **Piscina** (con agua animada) |
| **7** | 🍬 **Envoltorios de dulces** (5 residuos) | 🚲 **3 bicicletas** |
| **8** | 🛠️ **Taller de reciclaje:** Minijuego en primera persona | 🪴 **4 Macetas recicladas con plantas** grandes |

### 🛠️ Misión 8 al Detalle: El Taller de Reciclaje
La **Misión 8** es el clímax del juego. Una vez que el parque ha sido limpiado de toda la basura superficial, se te invita a realizar una actividad práctica de reciclaje a través de un **minijuego inmersivo en primera persona**.

En lugar de simplemente caminar y recoger, la pantalla cambia a una vista sobre una mesa de trabajo de madera, donde aplicarás las "3R" (Reducir, Reutilizar y Reciclar). Tu objetivo será fabricar macetas utilizando botellas de plástico que recolectaste en el Nivel 1. El taller se compone de 5 fases interactivas y secuenciales:

1. **Cortar:** Haz clic y arrastra las tijeras ✂️ sobre la botella de plástico a lo largo de la línea punteada para cortarla a la mitad.
2. **Lijar:** Usa un bloque de lija 🧽 para frotar los bordes cortados de la botella, suavizándolos para que no queden filosos (se ve el polvo de lijado).
3. **Pintar:** Elige uno de los 4 colores de pintura disponibles (Rojo 🔴, Azul 🔵, Amarillo 🟡 o Verde 🟢) y arrastra el pincel 🖌️ sobre el plástico hasta pintar toda la superficie exterior de tu maceta reciclada.
4. **Tierra:** Arrastra una bolsa de sustrato/tierra 🟤 y viértela con cuidado dentro de la maceta vacía hasta llenarla.
5. **Plantar:** Finalmente, selecciona una planta 🌱 y arrástrala sobre la tierra. Aparecerá una planta frondosa con hermosas flores, ¡indicando que has terminado la maceta!

Una vez que completes la primera maceta, podrás presionar **"Ir al Parque"**. Como premio por tu esfuerzo creativo, recibirás **4 réplicas de la maceta decorada que fabricaste**, para colocarlas libremente por todo el parque en el Modo Colocación y embellecer el lugar.

**Puntos:** cada residuo correcto suma puntos y avanza la barra de la misión. El progreso se muestra en el HUD.

**Hechos ambientales:** cada residuo tiene un dato educativo. Al terminar la ronda, el personaje te los lee uno por uno en su **globo de diálogo** (con su cara dibujada), sin repetir los que ya te contó.

## 🏆 Los premios y el tablero

Al completar cada misión, su premio aparece en el **tablero de premios** (abajo a la derecha). Cuando termines de limpiar el parque:

1. El personaje te muestra los **datos curiosos** de la ronda con tiempo para leerlos.
2. Después puedes **colocar los premios**: elige uno en el tablero y haz **clic** (o toca) donde quieras en el parque.
3. La **pelota** se coloca en 2 pasos: primero el **arco** elegido y luego la pelota.
4. Para la última misión, podrás colocar **4 macetas con flores grandes** para decorar el parque.
5. Cuando termines de colocar todo, presionas **"Terminar"** y el parque se abre.

### Opciones de pelota ⚽🏀🏐
Al ganar la primera misión puedes elegir el deporte del arco: **fútbol**, **básquet** o **vóley**. El arco cambia de forma y los niños juegan según ese deporte.

### Física de la pelota ⚽
Una vez que los niños están jugando con la pelota, el personaje puede interactuar con ella:

- **Espacio / Enter**: patear la pelota en la dirección en que miras. Sale rodando con rebotes en los bordes y frena por fricción.
- **R** (cerca de la pelota): **agarrarla**; la pelota queda en tu mano y te sigue mientras caminas.
- **R** de nuevo mientras la tienes: **tirarla por arriba** — sale con un arco parabólico, cae por gravedad y sigue rodando hasta detenerse.

## 🎡 La apertura del parque

Cuando colocas todos los premios y presionas **"Terminar"**, aparece la pantalla de "¡Felicidades eres un guardian del planeta!", y luego el parque se abre y entran **adultos** que pasean y **niños que corren por todos lados**. Los niños solo van a jugar a los juegos que **realmente colocaste**:

- **Columpio y sube y baja**: un niño se columpia (movimiento sincronizado con el asiento) y otros suben y bajan en el sube y baja.
- **Pileta**: dos niños nadan y chapotean, con el agua con ondas cuando hay niños adentro.
- **Carritos**: tres niños **manejan los carritos** dando vueltas en círculo; el conductor asoma cabeza y hombros adentro del auto.
- **Pelota**: dos niños juegan al deporte elegido (fútbol/básquet/vóley), se pasan la pelota y la tiran al arco.
- Si no colocaste algún juego, **no aparecen niños jugando en la nada**: simplemente corren por el parque.

Al final aparece el botón **"🔄 Volver a jugar"** para reiniciar la partida completa.

## 🎮 Cómo Jugar

- **Mueve** a tu personaje con las flechas (`↑ ↓ ← →`) o **WASD** (o el **D-pad táctil** en celulares).
- **Camina sobre la basura** que pide la misión para recogerla y avanzar en tu objetivo.
- Tienes **30 segundos** por misión; si se acaba el tiempo pierdes una **vida** (3 corazones en total).
- Al completar cada ronda, el personaje te lee los **datos ambientales** de esa ronda con tiempo para leerlos.
- En el modo colocación, **clic** coloca el premio seleccionado; **Espacio/Enter** también lo coloca en la posición del personaje.

## ✨ Características

- **Parque que se limpia solo:** con cada misión completada desaparecen el barro, las manchas y los papeles, y el parque vuelve a florecer.
- **Minijuego Taller de Reciclaje:** Una vista en primera persona donde interactúas con herramientas (tijeras, lija, pinceles de colores, tierra) para transformar botellas de plástico en macetas reales paso a paso, arrastrando el mouse para simular el trabajo manual.
- **Educativo:** datos ambientales reales leídos al final de cada ronda, con una frase de transición entre el nivel 7 y el 8.
- **Múltiples Macetas:** El jugador ahora puede crear su propia maceta decorada y plantar hasta 4 de ellas en el parque final.
- **Estética Pulida:** Interfaz opaca (fondos oscurecidos) que resalta los elementos del HUD, mejorando el contraste visual.
- **Residuos dibujados a mano:** botellas azules, papeles arrugados, cajas usadas, diarios doblados, cáscaras de plátano/sandía y manzanas mordidas (sin emojis).
- **Sistema de misiones:** cada misión pide recoger un residuo concreto; los de otras misiones se ven apagados.
- **Premios colocables:** pelota con arco (3 deportes), columpio y sube y baja, 3 carritos y pileta.
- **Animación de apertura:** adultos y niños pasean, corren y juegan en los juegos colocados (solo en los que existen).
- **Pelota interactiva:** patear (Espacio), agarrar y tirar por arriba (R).
- **Sistema de vidas:** 3 corazones; pierdes uno cuando se agota el tiempo.
- **Música de fondo de parque:** ambiente natural (**viento, arroyo y pájaros**) + **melodía alegre** generada en vivo con *Web Audio API*. Botón flotante para silenciar/activar.
- **Efectos de sonido** generados en tiempo real, sin archivos externos.
- **Gráficos en Canvas:** parque, árboles, personaje y personas dibujados con primitivas vectoriales.
- **Globo de diálogo con la cara del personaje** dibujada (niño/niña), sin emojis.
- **Tablero de premios** con slots de colocación semitransparentes.
- **Responsive + D-pad táctil:** funciona en celulares, tablets y computadoras.

## 🛠️ Tecnologías

- **HTML5:** estructura, HUD y lienzo de dibujo (`<canvas>`).
- **CSS3:** interfaz, pantallas de inicio/derrota, transparencias y diseño responsivo.
- **JavaScript (Vanilla):** bucle de juego, colisiones, física de la pelota, sonido procedural (naturaleza + melodía), animaciones y estado del juego.

> 📦 Todo el juego está empaquetado en un **único archivo**: `ecologIA-juego.html` (HTML + CSS + JS).

## 🚀 Instalación y Uso

No requiere instalación ni librerías externas.

1. Clona el repositorio:
   ```
   git clone https://github.com/antonellaavalosc-ux/ecologIA.git
   ```
2. Abre `ecologIA-juego.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. Si no ves los últimos cambios, fuerza la recarga con **Ctrl+F5**.

## 🌍 Objetivo

Completa las **8 misiones**, coloca los premios y mira cómo el parque cobra vida con los niños jugando. ¡El planeta te necesita!
