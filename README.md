# Marco Silva — Executive + Founder

Sitio personal bilingüe (inglés/español) listo para GitHub Pages, diseñado sin frameworks ni dependencias de compilación.

## Abrir localmente

Abre `index.html` en Chrome, Edge o Firefox. También puedes iniciar un servidor local:

```powershell
cd marco-silva-website
python -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Publicar en GitHub Pages

1. Crear un repositorio público llamado `TU_USUARIO.github.io` (sustituir `TU_USUARIO` por el usuario real de GitHub).
2. Copiar los archivos de esta carpeta a la raíz del repositorio, incluyendo `.nojekyll`, `assets/`, `styles.css`, `script.js` e `index.html`.
3. Hacer commit y push a la rama `main`.
4. En GitHub, ir a **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root)** y guardar.
5. Esperar a que GitHub publique el sitio. La URL será `https://TU_USUARIO.github.io/`.

No es necesario configurar GitHub Actions: al ser un sitio estático, GitHub Pages lo publica directamente.

## Personalizar

- **Retrato:** reemplazar `assets/marco-silva.webp` con una fotografía optimizada con el mismo nombre.
- **Contenido EN/ES:** editar el objeto `copy` dentro de `script.js`; el HTML contiene el texto inicial en inglés.
- **Colores y diseño:** editar variables CSS al principio de `styles.css`.
- **LinkedIn y contacto:** enlaces actuales apuntan a LinkedIn y correo proporcionados por Marco.
- **GitHub:** botón GitHub intencionalmente omitido hasta confirmar el usuario público.
- **IT Evolve:** el botón apunta a la sección interna Ventures hasta disponer de un sitio externo confirmado.
- **Insights:** enlace a la actividad de LinkedIn; sustituir por artículos internos cuando existan.
- **SEO:** si usas dominio propio, añadir URL canónica y URLs absolutas para Open Graph.

## Alcance

Este proyecto incluye Home y secciones About, Expertise, Ventures, Insights, Community y Contact en una misma página con navegación interna, interfaz responsive y persistencia del idioma en el navegador.

FRR Plus se presenta expresamente como plataforma en desarrollo y validación controlada, sin atribuirle capacidades productivas o clientes.
