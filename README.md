Tabla con tipos de negocio (Datos Estructurados)
================================================

Volcado de datos SQL con estructura y datos (algo mas de 2200 tipos)
de tipos de negocio posibles. Es necesario para el marcado de datos
que utiliza Google y otros buscadores...

Es la lista completa de @TYPES, que se utilizan en el marcado LD+JSON como por ejemplo este:

```javascript
<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Restaurant",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Sunnyvale",
    "addressRegion": "CA",
    "postalCode": "94086",
    "streetAddress": "1901 Lemur Ave"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4",
    "reviewCount": "250"
  },
  "name": "GreatFood",
  "openingHours": [
    "Mo-Sa 11:00-14:30",
    "Mo-Th 17:00-21:30",
    "Fr-Sa 17:00-22:00"
  ],
  "priceRange": "$$",
  "servesCuisine": [
    "Middle Eastern",
    "Mediterranean"
  ],
  "telephone": "(408) 714-1489",
  "url": "http://www.dishdash.com"
}
</script>
```
