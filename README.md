# Hoja de vida web · J. Daniel Tapias García

Sitio personal con mi hoja de vida en estilo ATS (sobrio y fácil de leer), mis proyectos y mis datos de contacto. Está construido con HTML y CSS, con diseño Mobile First y CSS Grid.

**Sitio publicado:** https://judatasgar.github.io/ATS_CV_JDTG/

## Páginas
- `index.html`: hoja de vida (perfil, experiencia, formación y habilidades)
- `proyectos.html`: proyectos en tarjetas
- `contacto.html`: correo, GitHub y LinkedIn

## Mockups
### Hoja de vida
![Inicio en celular](mockups/inicio-celular.png)
![Inicio en computador](mockups/inicio-computador.png)

### Proyectos
![Proyectos en celular](mockups/proyectos-celular.png)
![Proyectos en computador](mockups/proyectos-computador.png)

### Contacto
![Contacto en celular](mockups/contacto-celular.png)
![Contacto en computador](mockups/contacto-computador.png)

## Capturas del sitio publicado
![Celular](capturas/celular.png)
![Computador](capturas/computador.png)

## Breakpoints
- **Base (celular):** todo va en una sola columna, en el orden en que quiero que se lea la hoja de vida. El menú queda debajo de la cabecera, con un enlace por línea.
- **Desde 600px:** el menú pasa a una fila horizontal y el nombre se ve más grande. Las tarjetas se acomodan de a 2 cuando hay espacio.
- **Desde 1024px:** en la hoja de vida aparece una columna lateral a la izquierda con contacto y habilidades, y el contenido principal queda a la derecha. Las tarjetas se acomodan de a 3.

## Cómo lo publiqué
1. Creé un repositorio público en GitHub y lo conecté con mi carpeta local usando `git remote add origin`.
2. Fui subiendo el avance por etapas con `git add`, `git commit` y `git push`.
3. En el repositorio entré a **Settings → Pages**.
4. En *Build and deployment* elegí **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`, y guardé.
5. Esperé un par de minutos hasta que apareció el enlace del sitio y lo probé en el computador y en el celular.

## Fuentes consultadas
- Documentación de GitHub Pages: https://docs.github.com/es/pages/getting-started-with-github-pages
- Material de clase de Campuslands sobre CSS Grid, media queries y diseño responsive.
