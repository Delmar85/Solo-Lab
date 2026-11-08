# 🎸 Solo Lab

**Tu gimnasio musical para guitarra y bajo, en el navegador.** Escoges qué entrenar, le das play y sigues lo que se ilumina. Hecho para principiantes: cada palabra técnica tiene un botón **?** que la explica en sencillo.

## Las 4 rutinas

| Rutina | Nivel | Qué entrenas |
|---|---|---|
| 🥁 **Ritmo** | Básico | Tocar parejo y a tiempo. Patrones de rasgueo con flechas (↓ ↑) que se iluminan, o patrones de bajo (raíz, quinta, octava). |
| 🎸 **Acompañar** | Básico | Tocar los acordes de una canción con la banda. Diagrama grande del acorde actual, el que sigue y cuántos tiempos faltan para cambiar. |
| 🔥 **Solo** | Intermedio | Improvisar. El mástil ilumina la escala que combina, la raíz y las notas del acorde que suena. Incluye **Ritmo del solo**: rejilla de corcheas y semicorcheas, generador de ritmos con 5 niveles y guía con la raíz o con las notas, en los 12 tonos. |
| 🎛️ **Crear bases** | Libre | Chord Pad: una tecla = un acorde que ya combina con el tono. Graba tu progresión y úsala como pista. |

### Teoría y oído

| Sección | Qué entrenas |
|---|---|
| 👂 **Oído** | Quiz de mayor o menor, intervalos (con canciones de referencia) y cambios de acorde (IV, V, vi, ii, iii). 3 niveles, aciertos y racha. |
| 🗺️ **Notas del mástil** | Juego de “encuentra la nota” en la cuerda E, la A, ambas o todas. Mide tu velocidad. Modo estudio para ver todas las notas. |
| 🖐️ **CAGED** | Las 5 formas (C, A, G, E, D) de cualquier acorde mayor por todo el mástil, con la pentatónica encima para solear. |
| 🎡 **Círculo de quintas** | Círculo interactivo: toca un tono y ve su familia de acordes (I, ii, iii, IV, V, vi, vii°), escucha I–IV–V–I y mándalo a la pista. |
| 🎚️ **Afinador** | Afinador con micrófono para guitarra y bajo, más tonos de referencia para afinar de oído. |

En el inicio hay una **rutina diaria de 25 minutos** con atajos a cada sección y tips de técnica limpia para guitarra y bajo.

Cada rutina trae una guía de 3 pasos.

## Funciones

- **Guitarra o bajo:** cambia el mástil, los patrones y las guías.
- **Tu pista:** tono, mayor o menor, progresiones clásicas (pop, rock, años 50, jazz, blues de 12, andaluza…), estilo (rock, balada, funk, shuffle, psicodélico) y qué instrumentos suenan.
- **Velocidad:** botones − / +, atajos Lento · Medio · Rápido.
- **Cuenta de entrada** 1-2-3-4 antes de arrancar.
- **💪 Subir velocidad solo:** +4 BPM cada 4 compases, como en el gym.
- **Cronómetro** de práctica.
- **Diagramas de acordes** reales (abiertos y con cejilla), con la raíz marcada en naranja.
- **Esquema en números romanos** (I–V–vi–IV) debajo de cada acorde: el mismo patrón sirve en cualquier tono.
- **Ritmo del solo:** entrena dónde caen tus notas. Rejilla para contar (“1 y 2 y”, “1 e y a”), generador de ritmos de 1 o 2 compases que terminan en silencio, complejidad de Simple a Reto, guía que suena solo el ritmo, la raíz o las notas (que brillan en el mástil), modo grande para ver de lejos y volúmenes separados.
- **Todos los tonos:** tono al azar o recorrido automático por el círculo de quintas cada 4 compases.
- **Formas de acordes optimizadas:** elige 🟢 Fáciles (abiertos), 🌊 Fluidas (triadas en 3 cuerdas), Cejillas (misma zona) o Clásicas. La app calcula la combinación en la que la mano se mueve menos durante toda la vuelta, marca en **verde los dedos que se quedan fijos** y te dice cómo hacer cada cambio.
- **Escala sugerida automática** (ej. en Do mayor → pentatónica menor de La).
- **Glosario** integrado con botones **?**.
- Nombres en **C D E** o **Do Re Mi**.
- Atajos en compu: **barra espaciadora** = play/stop; en Crear bases, teclas **A W S E D F T G Y H U J K**.

## Cómo usarlo

Abre `index.html` en el navegador (Chrome, Safari o Edge). Necesita internet para cargar el motor de audio (Tone.js) y las fuentes.

> En iPhone, quita el modo silencio para escuchar el audio.

## Publicarlo gratis con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `solo-lab`), en **Public**.
2. Sube `index.html` y este `README.md` (**uploading an existing file**).
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/solo-lab/`.

Para actualizar: **Add file → Upload files** y sube el nuevo `index.html`.

## Ruta

- [x] Escalas, pista y metrónomo
- [x] Chord Pad y grabar progresiones
- [x] Rutinas de gimnasio (Ritmo, Acompañar, Solo, Crear)
- [x] Diagramas de acordes y modo bajo
- [ ] Guardar tus progresiones y licks favoritos
- [x] Afinador, oído, notas del mástil, CAGED y círculo de quintas
- [ ] Afinaciones alternativas (Drop D, medio tono abajo)
- [ ] Retos diarios y registro de progreso

## Tecnología

HTML + CSS + JavaScript en un solo archivo. Audio con [Tone.js](https://tonejs.github.io/). Tipografía Permanent Marker y DM Sans (Google Fonts).
