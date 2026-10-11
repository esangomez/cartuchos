# Cartuchos NFC

Página con emulador de Game Boy / Game Boy Color (EmulatorJS) para abrir juegos acercando un llavero NFC al celular.

**Las ROMs no se suben a este repositorio.** Cada celular guarda su propia copia en el navegador la primera vez que se abre cada juego. No agregues archivos `.gb` o `.gbc` al repo: GitHub Pages es público.

## Publicarla en GitHub Pages

1. En GitHub, creá un repositorio nuevo (por ejemplo `cartuchos`).
2. Subí `index.html` y este `README.md` (botón **Add file → Upload files**).
3. Andá a **Settings → Pages**, en *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guardá.
4. En uno o dos minutos la página queda en `https://esangomez.github.io/cartuchos/`.

## Links para grabar en los NFC

| Juego  | Link |
|--------|------|
| Red    | `https://esangomez.github.io/cartuchos/?juego=red` |
| Blue   | `https://esangomez.github.io/cartuchos/?juego=blue` |
| Green  | `https://esangomez.github.io/cartuchos/?juego=green` |
| Yellow | `https://esangomez.github.io/cartuchos/?juego=yellow` |

(Si usás otro nombre de repo, cambiá `cartuchos` por ese nombre. La página también muestra cada link con un botón para copiarlo.)

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
