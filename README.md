# RITUAL — demo de portfolio

Sitio ficticio de cuidado personal con estética cálida. Incluye ingredientes revelados por el scroll y selector de rutinas. La marca, las actividades, productos y horarios son ejemplos conceptuales; no representan a una empresa real.

## Subir a GitHub y conectar con Vercel

1. Descomprime el ZIP y crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `style.css`, `motion.js` y este `README.md` a la raíz del repositorio con **Add file → Upload files → Commit changes**.
3. En [Vercel](https://vercel.com/new), elige **Import Git Repository**, conecta GitHub e importa ese repositorio.
4. Deja el directorio raíz en `./` y pulsa **Deploy**. No requiere instalación ni comando de compilación.

## Adaptación y contenido

Las imágenes se cargan desde Unsplash. Antes de reutilizar el diseño para un cliente real, sustitúyelas por material autorizado y cambia la marca, los textos y los datos de ejemplo. Los selectores y controles funcionan dentro de la demostración, sin pagos, reservas ni datos persistentes. El menú móvil se puede cerrar con Escape y las animaciones respetan `prefers-reduced-motion`. No se usan asteriscos ni flechas decorativas.

## Vista local

Desde esta carpeta, ejecuta `python3 -m http.server 8000` y abre `http://localhost:8000`.
