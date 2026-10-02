# Masajes Gros Quirolan · demo comercial

Sitio estático de demostración, no oficial. Está marcado con `noindex, nofollow`. Repositorio: [Urtxe/quirolan-demo](https://github.com/Urtxe/quirolan-demo). Demo publicada en [GitHub Pages](https://urtxe.github.io/quirolan-demo/).

## Qué se verificó

Consulta de la [ficha pública de Google Maps](https://www.google.es/maps/place/Masajes+gros+Quirolan/@43.3241187,-1.9730025,878m/data=!3m2!1e3!4b1!4m6!3m5!1s0xd51a50040d07bfd:0xe1ffbba61dc4993a!8m2!3d43.3241187!4d-1.9704222!16s%2Fg%2F11zkgf4skm?entry=ttu) el 2 de octubre de 2026:

- Nombre publicado: «Masajes gros Quirolan»; categoría: «Masajista».
- Dirección: Segundo Izpizua Kalea 26, 20001 Donostia / San Sebastián, Gipuzkoa.
- Teléfono: 611 83 47 40.
- La ficha muestra una valoración pública y fotografías, que se enlazan en su fuente sin reproducirlas.
- La vista consultada mostraba el horario de ese día, pero no permitió verificar el horario semanal completo. Se omite.
- La ficha ofrece «Añadir sitio web» y no muestra enlace web ni sistema de reservas.

Las búsquedas por nombre, dirección y teléfono no permitieron verificar una web propia, redes sociales, modalidades concretas de masaje, precios, identidad profesional ni WhatsApp. La demo no atribuye ninguno de esos datos al negocio. Su sección de masajes invita a preguntar directamente por ellos.

## Imágenes y contenido provisional

`assets/ambiente-conceptual.webp` y `assets/detalle-conceptual.webp` se generaron con la herramienta de imágenes integrada de OpenAI para esta demo. No muestran el establecimiento real. Prompts: (1) «Empty welcoming massage room, cream cotton, sunlit terracotta wall, oak stool, architectural editorial photography; no people, spa clichés, logos or text»; (2) «Folded cream towels on oak bench, terracotta plaster wall, warm daylight; no people, plants, candles, logos or text». La identidad visual y los textos de propuesta también requieren aprobación del negocio.

Antes de convertir la demo en web oficial, confirmar con Quirolan sus servicios, profesional, fotos, horarios, tarifas, política de citas y uso de WhatsApp. Sustituir las imágenes conceptuales por fotografías autorizadas y quitar `noindex` solo cuando proceda.

## Ejecutar en local

```powershell
python -m http.server 8000
```

Abrir `http://localhost:8000`. No hay compilación ni dependencias de producción.

## Despliegue en GitHub Pages

El remoto `origin` apunta a `https://github.com/Urtxe/quirolan-demo.git`. GitHub Pages usa **GitHub Actions**. El flujo `.github/workflows/deploy.yml` publica la raíz del proyecto en cada push a `main`; también se puede lanzar manualmente desde **Actions**.

Mantener `noindex, nofollow` mientras siga siendo una demo.
