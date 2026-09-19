# LR Media / Medios LR

Shared media library for Los Recomendados developers. / Biblioteca compartida de medios para los desarrolladores de Los Recomendados.

Use this repository to store and reuse approved images, videos, audio, documents, and other static assets across LR projects. / Usa este repositorio para guardar y reutilizar imágenes, videos, audio, documentos y otros recursos estáticos aprobados en los proyectos de LR.

## Upload from GitHub Mobile / Subir desde GitHub Mobile

1. Open this repository in the GitHub mobile app. / Abre este repositorio en la aplicación móvil de GitHub.
2. Open the folder that matches the asset type. / Abre la carpeta que corresponda al tipo de recurso.
3. Tap **Add file** → **Upload files**. / Toca **Add file** → **Upload files**.
4. Select the media from your device. / Selecciona el archivo desde tu dispositivo.
5. Use a clear commit message, such as `Add summer campaign hero image` or `Agregar imagen principal de campaña de verano`. / Usa un mensaje de commit claro.
6. Commit directly to `main` for routine uploads, or create a branch/pull request when review is needed. / Haz commit directamente a `main` para cargas rutinarias, o crea una rama/solicitud de cambios cuando se necesite revisión.

Keep uploads organized using the folder layout below. GitHub Mobile preserves the folder structure when you upload files. / Mantén las cargas organizadas usando la estructura siguiente. GitHub Mobile conserva la estructura de carpetas al subir archivos.

## Folder layout / Estructura de carpetas

```text
images/       Imágenes
  brand/      Marca, logotipos y elementos de identidad
  social/     Redes sociales y campañas
  web/        Sitios web y productos
  misc/       Imágenes varias
videos/       Videos
  social/     Videos para redes sociales
  promos/     Promociones y campañas
  misc/       Videos varios
audio/        Audio, música y voz
documents/    Documentos, guías y referencias
other/        Otros recursos
```

## Naming files / Nombrar archivos

Use lowercase names with hyphens and include useful context. / Usa nombres en minúsculas, separados por guiones, e incluye contexto útil:

```text
<project>-<purpose>-<date-or-version>.<extension>

website-home-hero-2026-09.jpg
campaign-fall-reel-v2.mp4
brand-logo-white.svg
```

Avoid spaces, special characters, vague names such as `final-final.png`, and filenames that contain private information. / Evita espacios, caracteres especiales, nombres vagos como `final-final.png` y nombres que contengan información privada.

## Media guidelines / Reglas para medios

- Upload only assets that the organization is allowed to use. / Sube solo recursos que la organización tenga permiso para usar.
- Do not commit passwords, API keys, personal data, or confidential material. / No hagas commit de contraseñas, claves API, datos personales ni material confidencial.
- Prefer web-friendly formats: WebP/JPEG/PNG for images and MP4 (H.264/AAC) for video. / Prefiere formatos adecuados para la web: WebP/JPEG/PNG para imágenes y MP4 (H.264/AAC) para video.
- Compress media before uploading when practical. / Comprime los medios antes de subirlos cuando sea posible.
- Keep individual files below GitHub's 100 MB hard limit. Large files should use an approved external asset store instead of Git history. / Mantén cada archivo por debajo del límite estricto de 100 MB de GitHub. Los archivos grandes deben usar un almacenamiento externo aprobado.
- Do not replace or delete an asset that another project may use without checking its references. / No reemplaces ni elimines un recurso que otro proyecto pueda usar sin revisar sus referencias.
- Add a short description in the commit message; use a pull request when an asset needs approval. / Añade una descripción breve en el mensaje de commit y usa una solicitud de cambios cuando el recurso necesite aprobación.

## Using an asset / Usar un recurso

Each file has a stable GitHub URL. Open the file on GitHub and use **Copy permalink** when you need a version-pinned link. / Cada archivo tiene una URL estable de GitHub. Abre el archivo en GitHub y usa **Copy permalink** cuando necesites un enlace fijado a una versión.

For public assets, the raw URL can be used by applications that are allowed to fetch GitHub-hosted files. / Para recursos públicos, las aplicaciones autorizadas pueden usar la URL raw para obtener archivos alojados en GitHub.

## Contributions / Contribuciones

See [CONTRIBUTING.md](CONTRIBUTING.md) for the upload checklist and review guidance. / Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para ver la lista de comprobación y las reglas de revisión.
