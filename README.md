# Noir Barber Club — Informe de Publicidad y Campañas (Junio 2026)

Landing page de una sola página (scroll) que presenta el resumen de actividad
de **redes sociales y publicidad** de junio 2026, con el branding de
Noir Barber Club (negro profundo, dorado `#c7a46c`, logo monograma "N",
tipografías Montserrat + Cormorant Garamond).

## Contenido

```
noir-informe-junio/
├── index.html      ← landing autocontenida (sin build ni dependencias)
├── assets/
│   ├── logo-monograma.svg   ← logo solo monograma
│   └── logo-completo.svg    ← logo + "{ Barber Club }"
└── README.md
```

Datos: rendimiento de Instagram y anuncios, periodo 30 May – 28 Jun 2026.
Inversión del mes: 100 €.

## Desplegar

`index.html` es estático y funciona offline. Sirve desde cualquier hosting:

- **Vercel:** importar el repo o arrastrar la carpeta → publica sin configuración.
- **Local:** `python3 -m http.server` en esta carpeta.

No requiere build ni npm.
