# 🎸 Solo Lab

Gimnasio de improvisación para guitarra y bajo, en el navegador. Eliges tono y progresión, le das play a la pista y el diapasón te ilumina las notas de la escala para que saques tus solos y licks.

## Qué hace (v2)

- **Tono y progresión:** 12 tonos, modo mayor o menor, progresiones clásicas (pop, rock, jazz, blues de 12 compases, andaluza…).
- **Escala sugerida automática:** por ejemplo, en Do mayor te pone la pentatónica menor de La (su relativa).
- **Pista de acompañamiento:** batería, acordes y bajo generados en vivo. Estilos: rock, balada, funk y shuffle. Tempo de 50 a 170 BPM.
- **Metrónomo** independiente.
- **Diapasón interactivo (15 trastes):** escalas pentatónica menor/mayor, blues, mayor, menor natural, dórica y mixolidia. Vista por notas o por grados, y por posiciones (1 a 5).
- **Notas del acorde que suena** resaltadas en amarillo mientras corre la pista.
- **Mi camino:** marca las notas de tu lick, esconde lo demás y tócalo.
- **Chord Pad (v2):** una tecla = un acorde completo, inspirado en los sintes de acordes.
  - *Modo Tono:* cada tecla da el acorde correcto del tono (en Do mayor: C, Dm, Em, F, G, Am, Bdim), como triada, séptima, novena, add9, sus2 o sus4, con su número romano.
  - *Modo Libre:* eliges el tipo (mayor, menor, 7, maj7, m7, sus, add9, m9, 6, dim, aug) y tocas cualquier nota.
  - Toque de acorde, rasgueo o arpegio; inversiones; octava; bajo opcional; 3 sonidos (pad psicodélico, piano eléctrico, pluck).
  - **Grabar progresión** y usarla como pista de fondo.
  - Diapasón que muestra dónde están las notas del acorde.
  - En compu: teclas A W S E D F T G Y H U J K.

## Cómo usarlo

Abre `index.html` en el navegador (Chrome, Safari o Edge). Necesita internet para cargar el motor de audio (Tone.js) y las fuentes.

> En iPhone, quita el modo silencio para escuchar el audio.

Atajo: **barra espaciadora** = play / stop.

## Publicarlo gratis con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `solo-lab`).
2. Sube `index.html` y este `README.md`.
3. Ve a **Settings → Pages**, en *Source* elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/solo-lab/`.

## Ruta (siguientes versiones)

- [ ] Biblioteca de acordes con diagramas y variaciones (abiertos, cejilla, triadas)
- [x] Constructor de progresiones propias (Chord Pad)
- [ ] Modo bajo (diapasón de 4 cuerdas + líneas de bajo)
- [ ] Afinaciones alternativas (Drop D, medio tono abajo)
- [ ] Guardar tus caminos/licks favoritos

## Tecnología

HTML + CSS + JavaScript en un solo archivo. Audio con [Tone.js](https://tonejs.github.io/).
