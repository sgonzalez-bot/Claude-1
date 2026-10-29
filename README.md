# Agente ACIS · PIEC · LOMLOE Primaria (Comunidad de Madrid)

Agente de Claude Code que junta el **currículo LOMLOE de Primaria de la Comunidad de Madrid** (Decreto 61/2022 y normativa de evaluación y atención a las diferencias individuales) con las **plantillas del centro** para ACIS, PIEC y adaptaciones no significativas.

## Contenido

| Ruta | Qué es |
| --- | --- |
| `.claude/agents/acis-piec-lomloe.md` | Definición del agente: flujo de trabajo, reglas y lista de comprobación |
| `referencia/normativa-madrid-primaria.md` | LOMLOE, RD 157/2022, Decreto 61/2022, Orden 130/2023, Decreto 23/2023: lo que afecta a ACIS y PIEC |
| `referencia/curriculo-decreto-61-2022.md` | Ciclos, competencias clave, áreas y códigos de competencias específicas y criterios (Lengua y Matemáticas) |
| `plantillas/01-adaptaciones-no-significativas.md` | Ficha DUA / adaptaciones metodológicas |
| `plantillas/02-acis.md` | ACIS por área |
| `plantillas/03-previo-piec.md` | Plan previo de inicio de curso (medidas provisionales AACC) |
| `plantillas/04-piec.md` | PIEC definitivo |
| `alumnos/` | Documentos generados con datos del alumnado. **Excluida de git.** |

## Cómo usarlo

Abre Claude Code en esta carpeta y pídelo directamente, por ejemplo:

- «Usa el agente acis-piec-lomloe para hacer la ACIS de Lengua de un alumno de 4.º con NCC de 2.º: lee palabras sencillas, no escribe frases…»
- «Con el agente acis-piec-lomloe, pasa el previo PIEC de Alejandro (en Drive) a PIEC definitivo.»
- «Revisa con el agente acis-piec-lomloe esta ACIS de Matemáticas y dime qué falta según la normativa.»

El agente puede leer los documentos del Drive del centro si el conector de Google Drive está activo, y crear el resultado como Google Doc si se le pide.

## Avisos

- Los resúmenes normativos no sustituyen al BOCM. Los puntos marcados con ⚠️ en `referencia/` están pendientes de comprobar con el texto oficial.
- Los documentos contienen datos de salud y NEE de menores: no subir nada de `alumnos/` ni documentos `.docx`/`.pdf` al repositorio.
