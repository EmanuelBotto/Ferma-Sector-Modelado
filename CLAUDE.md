# Bóveda de referencia: modelado, detallado y planos de montaje (Tekla Structures 2025)

Esta carpeta es una bóveda de Obsidian y es la fuente de verdad del sector para
parámetros y procedimientos. Respondé siempre en español.

## Regla principal
Antes de responder cualquier consulta sobre modelado, detallado, plano de montaje,
acotado, parámetros, macros o plantillas de Tekla:

1. Leé `INDICE.md` y `00 Inicio.md`.
2. Abrí el nodo de la etapa que corresponde (`Modelado`, `Detallado` o `Plano de montaje`).
3. Abrí la nota de la pieza (`Pieza - etapa`) y seguí exactamente lo que dice.
4. Si la consulta abarca más de una etapa, seguí el bloque **Flujo** al final de la nota.
5. Los valores fijos están en `04 Parametros`. No los copies de memoria: leelos de ahí.
6. Citá siempre la nota de origen, por ejemplo `[[Columna - detallado]]`.
7. Si no hay nota sobre el tema, decilo de forma explícita. No inventes parámetros,
   valores ni pasos.
8. Si dos notas se contradicen, avisame y mostrame ambas.

## Estructura
- `00 Inicio.md`: mapa general y flujo (modelar → detallar → plano de montaje).
- `01 Modelado/`: nodo `Modelado.md` + una nota por pieza (`Pieza - modelado.md`).
- `02 Detallado/`: nodo `Detallado.md` + una nota por pieza (`Pieza - detallado.md`).
- `03 Plano de montaje/`: nodo `Plano de montaje.md` + una nota por pieza (`Pieza - montaje.md`).
- `04 Parametros/`: valores fijos compartidos por las tres etapas (un valor, un solo lugar).
- `05 Macros/`: notas sobre las macros en C# (Tekla Open API).
- `05 Ejemplos/`: PDFs y capturas de planos de referencia (fuente principal).
- `06 Instructivos/`: instructivos internos en PDF (pueden estar desactualizados; fuente secundaria).
- `99 Plantillas/`: plantillas para notas nuevas.

## Cómo crear notas a partir de planos de ejemplo
- Leé los PDF de `05 Ejemplos/` indicados en el pedido (de a 2 o 3 del mismo tipo).
- Los ejemplos mandan sobre los instructivos de `06 Instructivos/`: usá los instructivos solo
  para lo que los ejemplos no muestran, marcalo `[Inst.]` y avisame si se contradicen.
- Creá una nota por tema usando `99 Plantillas/Plantilla de pieza.md`.
- Cada regla extraída debe citar el plano de origen.
- Marcá como `(a confirmar)` todo lo que no esté claro o que pueda ser una excepción.
- Al final de la nota, listá las dudas que te quedaron.
- Agregá la nota nueva al nodo de su etapa y a `INDICE.md`.

## Convenciones
- Nombre de nota: `Pieza - etapa` (por ejemplo `Viga - detallado.md`).
- Cada nota empieza con una línea de resumen y trae `revisado:` en el encabezado.
- Parámetros en tablas o listas, siempre con unidad.
- Enlazá notas relacionadas con `[[Nombre de la nota]]`.

## Al editar la bóveda
- No borres ni reescribas notas existentes sin que yo lo pida. Proponé el cambio primero.
- Las notas creadas por Claude llevan `estado: borrador` hasta que yo las revise.
- No modifiques la carpeta `.obsidian/`.
