# Cartuchos NFC

Página con emulador de Game Boy Advance (EmulatorJS) para abrir juegos acercando un llavero NFC al celular.

**Los juegos comerciales (como FireRed) no se suben a este repositorio.** Cada celular guarda su propia copia en el navegador la primera vez que se abre el juego. Al repo, en `roms/`, solo van juegos con licencia libre (ver más abajo): GitHub Pages es público.

## Publicarla en GitHub Pages

1. En GitHub, creá un repositorio nuevo (por ejemplo `cartuchos`).
2. Subí `index.html` y este `README.md` (botón **Add file → Upload files**).
3. Andá a **Settings → Pages**, en *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guardá.
4. En uno o dos minutos la página queda en `https://esangomez.github.io/cartuchos/`.

## Link para grabar en el NFC

`https://esangomez.github.io/cartuchos/?juego=firered`

La página también muestra el link con un botón para copiarlo.

## Juegos libres desde la carpeta `roms/`

Los juegos con licencia que permite redistribuirlos se pueden subir al repo y abren directo, sin pedir el archivo:

1. Subí el archivo a `roms/` (en GitHub: *Add file → Upload files* y escribí `roms/` delante del nombre). Acepta `.gba`, `.gb` y `.gbc`.
2. Usá un nombre simple, sin espacios ni tildes: por ejemplo `roms/mi-juego.gba`.
3. Subí también su licencia, por ejemplo `roms/mi-juego-LICENSE.txt`.
4. El link para el NFC es el nombre del archivo sin la extensión: `https://esangomez.github.io/cartuchos/?juego=mi-juego`

En la página de inicio aparece solo, con su botón para copiar el link. **No subas a `roms/` juegos comerciales**: todo lo que esté en el repo es público.

## Grabar el NFC

1. Instalá **NFC Tools** (Android o iPhone).
2. *Escribir → Agregar un registro → URL / URI* y pegá el link del juego.
3. *Escribir* y acercá el sticker (NTAG213/215, 25 mm).
4. Opcional: en *Otros → Bloquear etiqueta* para que no se pueda sobrescribir (es irreversible).

## Cómo funciona en el celular

- **Primera vez** que acercás un llavero en un celular: la página pide elegir el archivo del juego. Queda guardado.
- **Desde ahí**: acercás el llavero y arranca directo.
- **Partidas**: se guardan con el guardado normal del juego, en el navegador de ese celular.
- Si se borran los datos del navegador, hay que volver a cargar el archivo (las partidas también se pierden).
- En iPhone, guardá la página en la pantalla de inicio para que Safari no borre los datos por inactividad.
