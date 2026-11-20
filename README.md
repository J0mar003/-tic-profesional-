# 💖 Corazón Valiente

Un juego estilo **Flappy Bird** donde en lugar de un pájaro controlas un **corazón**, y los obstáculos son **bloques con pensamientos negativos** ("No puedo", "Miedo", "Fracaso"…). Si chocas con uno, el juego te muestra un pensamiento positivo para reencuadrarlo.

Hecho con HTML + JavaScript + Canvas, **sin librerías ni archivos externos**: todo está en un único `index.html`.

## 🎮 Cómo jugar

| Acción | Control |
| --- | --- |
| Latir y subir | `Espacio`, `↑`, `W`, clic o toque en pantalla |
| Pausa | `P`, `Esc` o botón "Pausa" |
| Sonido on/off | `M` o botón "Sonido" |

Pasa por el hueco entre los bloques: cada par superado suma 1 punto. La velocidad aumenta poco a poco y el hueco se reduce un poco. Tu mejor puntuación se guarda en el navegador.

## ▶️ Ejecutarlo en tu computadora

Solo abre `index.html` con doble clic en cualquier navegador moderno.

## 🚀 Publicarlo en GitHub (con vista en vivo)

1. Crea un repositorio nuevo en GitHub (por ejemplo `corazon-valiente`).
2. Sube `index.html` y `README.md` (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y pulsa **Save**.
5. Espera 1–2 minutos: el juego quedará disponible en
   `https://TU_USUARIO.github.io/corazon-valiente/`

## 🛠️ Personalizar

Todo está al inicio del `<script>` de `index.html`:

- `THOUGHTS`: lista de pensamientos (`t`) y su frase positiva (`r`). Agrega o cambia los que quieras.
- `GRAVITY`, `FLAP_V`: qué tan rápido cae y sube el corazón.
- `BASE_SPEED`, `MAX_SPEED`: velocidad del juego.
- `GAP_START`, `GAP_MIN`: tamaño del hueco (más grande = más fácil).
- `PALETTE`: colores de los bloques.

## 📄 Licencia

Libre para usar y modificar.
