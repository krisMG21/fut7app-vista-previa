# Vista previa del sistema de diseño

Copia publicable de `docs/ux/tokens-preview.html` del repositorio del producto, renombrada a
`index.html` para que Cloudflare Pages la sirva en la raíz.

**Esto es un espejo, no la fuente.** La versión buena vive en el repositorio del producto, junto a
`tokens.json` y al documento del sistema de diseño. Si los tokens cambian, se vuelve a copiar
aquí. No se edita este fichero directamente.

Existe por dos razones:

1. Los tokens hay que mirarlos en un móvil, en la calle, con sol. En un monitor no demuestran nada.
2. No puede publicarse en `usuario.github.io` mientras corra el spike A: el desalojo de
   almacenamiento se cuenta por sitio, no por ruta, así que cada visita reiniciaría el reloj de
   inactividad del canario.

Repositorio desechable. Se borra cuando el sistema de diseño esté validado.

## Publicar

Cloudflare Pages → Create a project → Connect to Git → este repositorio.
Framework preset: None. Sin comando de compilación. Directorio de salida: la raíz.
