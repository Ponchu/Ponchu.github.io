# Sitio de Pixelizi

Página pública de Pixelizi en <https://ponchu.github.io>, publicada con GitHub
Pages desde este repositorio (`Ponchu/Ponchu.github.io`, rama `main`).

| Archivo | Qué es |
| --- | --- |
| `index.html` | Página principal, en español e inglés. Es el "Sitio web" de la ficha de Google Play. |
| `privacy/index.html` | Política de privacidad y aviso de privacidad para México: <https://ponchu.github.io/privacy/>. La app la abre desde Ajustes. Es una copia de `docs/privacy/index.html` del repositorio de la app: no la edites aquí. |
| `img/` | El gráfico de funciones y tres capturas de la ficha de Play en cada idioma (`store/play/images/` en la app) y el ícono (`web/icons/Icon-192.png`). |
| `.nojekyll` | GitHub Pages publica los archivos tal cual, sin procesarlos con Jekyll. |

## Actualizar la política

1. Edita `docs/privacy/index.html` en el repositorio de la app
   (`E:\MY PROJECTS\PIXELME`).
2. Cópiala aquí como `privacy/index.html`, guarda el cambio y súbelo.

## app-ads.txt

Cuando tengas tu cuenta de AdMob, copia `docs/app-ads.txt` de la app a la raíz
de este repositorio, cambia `pub-0000000000000000` por tu ID de editor y
súbelo. Debe abrir en <https://ponchu.github.io/app-ads.txt>: AdMob solo lo
busca en la raíz del sitio.

## Publicar

- **La primera vez:** crea en GitHub un repositorio público y vacío llamado
  exactamente `Ponchu.github.io` y sube este. Luego, en *Settings → Pages*,
  elige *Deploy from a branch*, la rama `main` y la carpeta `/ (root)`.
- **Después:** `git push origin main`. Los cambios tardan hasta 10 minutos en
  verse.
