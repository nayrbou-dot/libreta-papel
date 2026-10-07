# Libreta Papel — para Honor MagicPad 4

Bloc de notas y cuaderno de bocetos que funciona **sin internet**. Todo se guarda solo en la tablet.

## Instalación (una sola vez)

**Opción A — recomendada (app instalada, 100 % sin conexión después):**
1. Sube esta carpeta a cualquier alojamiento web gratuito con https (por ejemplo, arrastra la carpeta a Netlify Drop o usa GitHub Pages).
2. Abre la dirección en **Chrome** en la MagicPad 4 → menú ⋮ → **Instalar app** / **Añadir a pantalla de inicio**.
3. Desde ese momento se abre como una app normal, a pantalla completa y sin necesidad de internet.

**Opción B — rápida:** copia `index.html` a la tablet y ábrelo con Chrome.
Sirve para probar, pero según cómo lo abra el gestor de archivos, Android puede no dejar guardar notas ni usar el micrófono. Para el uso diario, usa la opción A.

## Privacidad y acceso (solo tú)
- **La primera vez que abras la app, crea tu contraseña.** Sin ella no se ve nada.
- Puedes activar **huella o rostro** (usa el sensor de la tablet). La contraseña sigue sirviendo siempre.
- **Todo se guarda cifrado** (AES-256): notas, dibujos, imágenes, vídeos y audios. Aunque alguien copie los datos del navegador, no puede leerlos sin tu contraseña o tu huella.
- **Nada sale de la tablet.** La app no tiene servidor ni cuenta y no envía datos a internet.
- **Se bloquea sola** tras unos minutos sin usarla, o al volver después de salir de la app. Se puede ajustar en Opciones ⋮ (de 1 a 30 minutos). El candado 🔒 de la barra la bloquea al instante.
- Tras varios intentos fallidos, hay que esperar cada vez más antes de volver a probar.
- **Si olvidas la contraseña, nadie puede recuperar las notas** (ni siquiera tú). Haz copias de seguridad.
- **Tus otros dispositivos:** instala la app en cada uno y crea tu contraseña. Para pasar las notas, usa Opciones → Copia de seguridad → Exportar en uno e Importar en el otro. La copia va **cifrada con una contraseña** que eliges al exportarla.
- La dirección web donde alojes la app solo contiene el programa vacío, nunca tus notas. Si además quieres que nadie más pueda ni abrir esa dirección, protégela con un acceso por correo (por ejemplo, Cloudflare Pages + Cloudflare Access, gratis, limitado a tu email).
- Recomendado: ten activado el bloqueo de pantalla de Android en la tablet.

## Para transcribir notas de voz sin internet
La transcripción se hace **en la propia tablet**. La primera vez, la app intenta descargar el idioma (eso sí necesita internet una sola vez). También puedes descargarlo tú: Ajustes de Android → Google → Voz → Reconocimiento sin conexión → **Español**.
Si tu tablet no puede transcribir sin conexión, la transcripción queda **desactivada** para que tu voz no salga del dispositivo. Puedes activar «Transcribir en la nube de Google» en Opciones, pero entonces el audio se envía a Google.
La lectura en voz alta usa el motor de voz del sistema (Ajustes → Accesibilidad → Texto a voz).

## Uso
- **Pluma, marcador, borrador, lazo, texto y mano** en la barra superior. Con el Magic-Pencil la presión cambia el grosor del trazo.
- Con «Solo el lápiz dibuja» activado (Opciones ⋮), el dedo mueve la hoja, hace zoom con dos dedos, reproduce vídeos y gira el 3D. La palma se ignora mientras escribes.
- **+** (abajo a la derecha): imagen, foto con cámara, vídeo, nota de voz y sitio en 3D.
- Toca un objeto con el dedo para ver su barra: mover (⠿), editar, leer en voz alta, borrar. El círculo azul de la esquina cambia el tamaño.
- **Editar imagen:** girar, espejo, recortar, brillo, contraste, saturación, sepia, desenfoque, B/N.
- **Notas de voz:** se graban y se transcriben a la vez. «Leer» las lee en voz alta, «Transcribir» vuelve a transcribirlas y «Pasar a texto» crea una nota de texto con la transcripción.
- **3D:** foto 360°/panorámica (mirar alrededor), modelos .glb/.obj/.stl (escaneos de habitaciones o edificios), o una maqueta de ejemplo. Botón de pantalla completa.
- **🔊 arriba:** lee en voz alta toda la nota (textos y transcripciones).
- **Opciones ⋮:** tipo de papel (blanco, rayado, cuadrícula, puntos), idioma de voz, exportar PNG y copia de seguridad.
