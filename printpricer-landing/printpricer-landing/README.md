# PrintPricer — Landing Page

Sitio web estático listo para GitHub Pages.

## Estructura

```
printpricer-landing/
└── index.html    ← Página principal (logo embebido en base64)
```

## Cómo publicar en GitHub Pages

1. Crea un repositorio en GitHub (ej. `printpricer-landing`).
2. Sube esta carpeta como contenido del repositorio.
3. Ve a **Settings → Pages → Source → Deploy from branch → main / root**.
4. Tu sitio estará disponible en: `https://TU-USUARIO.github.io/printpricer-landing/`

## Actualizar el enlace de descarga

En `index.html`, busca las dos líneas con:

```
https://github.com/TU-USUARIO/TU-REPO/releases/latest/download/PrintPricer_Setup.exe
```

Reemplaza `TU-USUARIO` y `TU-REPO` con tu usuario y repositorio de GitHub Releases
donde alojes el instalador.

## Alojar el instalador

1. En el repositorio del instalador, ve a **Releases → Create a new release**.
2. Sube `PrintPricer_Setup.exe` como asset.
3. El enlace de descarga directa será:
   `https://github.com/TU-USUARIO/TU-REPO/releases/latest/download/PrintPricer_Setup.exe`

---

Sheeds Studios · spprtshds@gmail.com
