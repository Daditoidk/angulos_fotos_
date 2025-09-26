# Catálogo de Ángulos de Cámara

> Plantilla de README para documentar ángulos de cámara en foto/video. Rellena los *placeholders* (`TODO`) y agrega/edita filas en la tabla.

## 🎯 Objetivo

Crear una referencia visual rápida de ángulos de cámara, con nombre, mini descripción y su imagen de ejemplo.

## 🗂️ Estructura sugerida del repo

```
/
├─ README.md
├─ images/
│  ├─ thumbs/           # miniaturas (600–900px lado largo)
│  └─ full/             # imagen en alta resolución
└─ prompts/             # si generas imágenes con IA, guarda aquí los prompts
```

> **Convención de nombres:** `images/thumbs/<slug>.jpg` y `images/full/<slug>.jpg` (ej: `angulo-picada-34.jpg`).

## ✅ Criterios por fila

* **Título**: cómo quieres listar el ejemplo (puede incluir el sujeto o el contexto).
* **Nombre del ángulo**: término técnico (ej. *picada 3/4*, *nadir*, *contrapicado*, *overhead 45°*, *plano holandés*).
* **Imagen**: miniatura que enlace a la versión en alta.

## 📷 Tabla de ángulos (edita y agrega filas)

> Reemplaza `TODO` y las rutas de imagen cuando tengas tus renders/fotos. Duplica filas para agregar más.

| Título                 | Nombre del ángulo            | Imagen                                                                           |
| ---------------------- | ---------------------------- | -------------------------------------------------------------------------------- |
| TODO: Retrato serio    | TODO: Picada 3/4 izquierda   | [![thumb](images/thumbs/angulo-picada-34.jpg)](images/full/angulo-picada-34.jpg) |
| TODO: Acción con bate  | TODO: Overhead 3/4 derecha   | [![thumb](images/thumbs/overhead-34.jpg)](images/full/overhead-34.jpg)           |
| TODO: Escena urbana    | TODO: Contrapicado           | [![thumb](images/thumbs/contrapicado.jpg)](images/full/contrapicado.jpg)         |
| TODO: Producto en mesa | TODO: Cenital (overhead 90°) | [![thumb](images/thumbs/cenital.jpg)](images/full/cenital.jpg)                   |

> Sugerencia: mantén todas las miniaturas con la **misma relación de aspecto** (p.ej., 3:2 o 1:1) para una tabla uniforme.

## 🧾 Glosario rápido (opcional)

*(Mantén esto corto. Úsalo sólo si te sirve)*

* **Picada**: cámara por encima del sujeto, inclinada hacia abajo (≈ 15–60°).
* **Cenital / Overhead 90°**: cámara totalmente desde arriba.
* **Contrapicado**: cámara por debajo del sujeto, apuntando hacia arriba.
* **Nadir**: cámara exactamente por debajo, apuntando 90° hacia arriba.
* **3/4**: desplazamiento lateral o rotación de cámara ±45° respecto al frente del sujeto.
* **Plano holandés (Dutch tilt)**: horizonte inclinado.

## 🧰 Campos extra (si quieres ampliarlo)

Si más adelante necesitas más detalle, puedes cambiar la tabla a esta variante:

| Título | Nombre del ángulo | Focal / FOV       | Altura de cámara       | Eje (yaw/pitch/roll)                | Imagen                                                   |
| ------ | ----------------- | ----------------- | ---------------------- | ----------------------------------- | -------------------------------------------------------- |
| TODO   | TODO              | TODO: 35 mm / 70° | TODO: ojo/pecho/arriba | TODO: yaw ±45°, pitch -30°, roll 0° | [![thumb](images/thumbs/TODO.jpg)](images/full/TODO.jpg) |

> **Nota**: Los campos técnicos son opcionales. Úsalos si te sirven para reproducibilidad.

## 📝 Cómo agregar un nuevo ángulo

1. Exporta la **miniatura** (`images/thumbs/<slug>.jpg`) y la **versión full** (`images/full/<slug>.jpg`).
2. Añade una fila a la tabla con: `Título`, `Nombre del ángulo`, y el Markdown de imagen/enlace.
3. (Opcional) Guarda el *prompt* o notas en `prompts/<slug>.md`.

### Snippet listo para pegar (nueva fila)

```
| TODO: Título | TODO: Nombre del ángulo | [![thumb](images/thumbs/TODO.jpg)](images/full/TODO.jpg) |
```

## 🔍 Buenas prácticas rápidas

* Mantén coherencia en **iluminación** y **fondos** si comparas ángulos.
* Documenta variaciones: *3/4 izquierda* vs *3/4 derecha*; *picada suave* (≈15–25°) vs *picada fuerte* (≈45–60°).
* Incluye **metadatos** en el nombre del archivo si te es útil (ej.: `picada-34-f35mm-roll0.jpg`).

## 🧩 Ejemplo de prompt (opcional)

```
Ángulo: picada 3/4 izquierda
Instrucciones: cámara por encima del sujeto, inclinación ~35°, yaw 45° a la izquierda, roll 0°. Sujeto mirando al frente.
Estilo: fotografía realista, luz suave lateral, fondo neutro.
```

---

> Hecho con ❤️ para iterar rápidamente. Cuando estés listo, borra esta sección y deja solo la tabla y lo esencial.
