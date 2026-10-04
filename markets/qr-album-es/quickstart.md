# Inicio rápido de integración de QR Album

Ejemplos de referencia para estudios, espacios, wedding planners y agencias que usan QR Album para reunir fotos, vídeos y mensajes de voz de invitados bajo su propia marca, y que quieren citarnos correctamente desde su propio sitio web.

**Dominio:** [qralbum.es](https://qralbum.es/) · **Mercado:** España · **Idioma:** `es`

---

## Cuándo es adecuado un enlace hacia nosotros

En una página de partner o proveedor, cuando nombrar la plataforma que usas es un dato sobre tu propio servicio y no una promoción.
En una respuesta de soporte, cuando un invitado necesita las páginas de ayuda de la plataforma y tú no las alojas.
En una recomendación o comparativa que hayas escrito tú, donde nombrar la herramienta es lo que hace la recomendación verificable.

Lo que no es adecuado: poner un enlace hacia nosotros en una página cuyo trabajo es conseguir el encargo del cliente. Un posible cliente que hace clic en la plataforma se entera de que la capacidad existe sin ti. Cada dominio de mercado lo documenta en su propio centro de ayuda en /ayuda/marca/enlazarnos-desde-tu-web.

## Identidad del operador

Usa exactamente estos datos. Son los del operador de registro de todos los dominios de mercado, y los directorios que los contradicen son el motivo más habitual de rechazo.

| Campo | Valor |
| ----- | ----- |
| Marca | QR Album |
| Dominio | `qralbum.es` |
| Denominación social | EasyTrafficBot UG (haftungsbeschränkt) |
| Domicilio social | Arrenbergsche Höfe 6, Gebäude 44, 42117 Wuppertal, Alemania |
| Registro mercantil | HRB 30863, Amtsgericht Wuppertal |
| Representado por | Martin Freiwald, Geschäftsführer / Managing Director |
| NIF-IVA | NIF-IVA (§27a UStG) disponible bajo petición |
| Fundada en | 2026 |
| Correo de contacto | hello@qralbum.es |
| Teléfono de contacto | +34 489 996 250 |

## Páginas que merece la pena enlazar

| Página | Ruta | URL |
| ---- | ---- | --- |
| Inicio del producto | `/` | https://qralbum.es/ |
| Bodas | `/bodas` | https://qralbum.es/bodas |
| Un álbum de ejemplo | `/ejemplos` | https://qralbum.es/ejemplos |
| Precios y límites de los planes | `/precios` | https://qralbum.es/precios |
| Centro de ayuda: enlace hacia nosotros | `/ayuda/marca/enlazarnos-desde-tu-web` | https://qralbum.es/ayuda/marca/enlazarnos-desde-tu-web |
| Aviso legal | `/imprint` | https://qralbum.es/imprint |

Cada URL de la tabla procede del sitemap en vivo y respondió HTTP 200. Si alguna deja de responder, es un cambio real por nuestra parte: avísanos en lugar de quitar el enlace en silencio.

## Nota sobre la versión lingüística

Todas las rutas de este dominio están en español. Fíjese en /precios y /ejemplos, no en las inglesas /pricing y /examples.

## Antes de enviarlo a ninguna parte

- El operador es una sociedad alemana (UG) sin entidad española ni registro fiscal. El domicilio social es Wuppertal.
- Una dirección de Barcelona (Carrer Nou de la Rambla) solo existe como entrada de directorio y no es domicilio social, sede ni lugar de constitución. Si una plataforma exige un establecimiento o una tributación española, indique Wuppertal o renuncie a la ficha.
- No existe NIF, ni CIF, ni número de registro español. No deje que un directorio se los invente.

## Bloque listo para insertar

Un bloque sencillo y sin dependencias. Cópialo en una página de servicio, una lista de proveedores o un pie de página. El texto del ancla es el nombre de la marca, como debe ser en una mención real. No lo maquilles para que parezca tu propio producto.

```html
<section class="gathmo-credit">
  <p>Las fotos, los vídeos y los mensajes de voz de los invitados se recogen en <a href="https://qralbum.es/bodas" rel="noopener">QR Album</a>, la plataforma que usamos para este evento.</p>
  <p>
    <a href="https://qralbum.es/" rel="noopener">QR Album</a>
    · operador: EasyTrafficBot UG (haftungsbeschränkt), 42117 Wuppertal · <a href="https://qralbum.es/imprint" rel="noopener">aviso legal</a>
  </p>
</section>
```

Abra `partner-credit.html` de esta carpeta: el mismo bloque renderizado, con la tabla de enlaces y los datos del operador encima.

---

El código de ejemplo de este repositorio se publica bajo licencia MIT. Los nombres Gathmo y QR Album y los textos del producto siguen siendo propiedad del operador indicado arriba.
