# Reproductor

Reproductor de música y vídeo para Windows, gratuito y sin anuncios.
Creado por **[Julián Andrés Muñoz Armero](https://github.com/julianmunozarmero)**: diseño,
interfaz y desarrollo.

- Biblioteca de música y vídeos con portadas, listas de reproducción y cola.
- Reproduce prácticamente cualquier formato gracias a VLC.
- Interfaz con efecto «liquid glass», modo claro y oscuro, y color de acento.
- Controles multimedia de Windows (teclas de volumen y reproducción, y panel de
  medios).
- Subtítulos y pistas de audio, mini reproductor, y continuar donde lo dejaste.
- Se actualiza solo desde este repositorio.

## Descargar

**[Descarga la última versión](../../releases/latest)**: archivo `Reproductor-Setup-X.Y.Z.exe`.

Requisitos: Windows 10 (versión 1809 o posterior) u 11, de 64 bits.

Windows puede mostrar «Windows protegió su PC» porque el instalador todavía no
tiene firma de editor. Pulsa **Más información › Ejecutar de todas formas**.

Para comprobar que tu descarga es la original, compara su huella con el archivo
`.sha256` de la versión:

```powershell
Get-FileHash .\Reproductor-Setup-X.Y.Z.exe
```

## Actualizaciones

El programa busca una versión nueva una vez al día. Cuando hay una, muestra
«Versión X disponible · Actualizar»:

1. Descarga el instalador.
2. Comprueba su huella SHA-256.
3. Se instala y se vuelve a abrir solo.

También puedes buscarla a mano en **Ajustes › Actualizaciones**.

## Licencias de terceros

Usa VLC (LGPL/GPL), Qt (LGPL) y otros componentes de código abierto. Sus
licencias se instalan con el programa: **Ajustes › Acerca de › Licencias de
terceros**.

---

© 2026 Julián Andrés Muñoz Armero. Se puede descargar, usar y compartir gratis; por favor
enlaza a este repositorio en lugar de subir el instalador a otros sitios, así
todos reciben las actualizaciones.
