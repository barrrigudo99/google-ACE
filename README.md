# Google ACE Quiz App

App web sencilla para practicar preguntas tipo test de la certificación **Google Cloud Associate Cloud Engineer**.

## Ejecutar en local

```bash
python -m http.server 8000
```

Abre después:

```txt
http://localhost:8000
```

## Estructura

```txt
.
├── index.html
├── styles.css
├── app.js
└── data/
    └── preguntas.json
```

## Uso

Sustituye `data/preguntas.json` por tu banco completo de preguntas. La app espera un objeto con `metadata` y un array `preguntas`.

Funcionalidades incluidas:

- Carga de preguntas desde JSON.
- Filtro por dominio y tema.
- Modo aleatorio.
- Navegación anterior/siguiente.
- Corrección inmediata.
- Explicación de la respuesta.
- Resumen de aciertos y precisión.
- Diseño responsive.
