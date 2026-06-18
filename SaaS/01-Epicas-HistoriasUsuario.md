# Backlog Scrum

# EPIC-001 - Motor de generación de contenido

## HU-001 Investigación automática

Como creador de contenido, quiero obtener información relevante
automáticamente, para reducir tiempo de investigación.

Criterios: - Identificar temas relevantes. - Resumir información. -
Clasificar prioridad.

---

## HU-002 Generador de guiones IA

Como productor, quiero generar guiones estructurados, para mantener un
formato consistente.

Criterios: - Introducción atractiva. - Contexto. - Datos. -
Explicación. - Cierre.

---

# EPIC-002 - Producción Multimedia

## HU-003 Generación visual

Crear: - Miniaturas - Imágenes - Presentaciones

---

## HU-004 Avatar IA

Convertir guiones en videos usando presentadores virtuales.

---

# EPIC-003 - Publicación YouTube

Automatizar: - Títulos - Descripción - Tags - Categorías - Publicación

---

# EPIC-004 - Analytics Engine

Analizar: - Vistas - CTR - Retención - Suscriptores

---

# EPIC-005 - Optimización basada en Analytics

Objetivo:
Mejorar continuamente el rendimiento del contenido usando métricas reales de YouTube Analytics.

---

## ISSUE-006 / HU-006 - Optimizar CTR YouTube

### Contexto

Después de publicar el MVP (MH5M-001) se detecta una oportunidad de mejora en la conversión de impresiones a vistas.

### Métrica inicial

Video:
MH5M-260616-001-SEGURIDAD

Datos iniciales:

- Impresiones: 229
- CTR: 1.3%
- Duración promedio: 1:49
- Retención aproximada: 48%

### Problema

CTR inicial por debajo del objetivo.

La audiencia que entra consume el contenido, pero pocas personas hacen clic desde las recomendaciones.

### Hipótesis

La miniatura actual comunica seriedad y confianza, pero puede percibirse demasiado institucional.

Puede faltar:
- Curiosidad
- Pregunta detonadora
- Beneficio inmediato para el usuario

### Cambio propuesto

Optimizar:

- Miniatura
- Título
- Primer impacto visual

Agregar elementos como:

- Pregunta clave
- Dato relevante
- Contraste

Sin perder identidad:

"Contexto • Datos • Explicación"

### Criterios de aceptación

- Crear nueva plantilla de miniatura v0.2
- Generar títulos alternativos
- Comparar rendimiento

### Métrica objetivo

CTR objetivo:

> Mayor a 3%

### Estado

BACKLOG

---

## ISSUE-007 / HU-007 - Mejorar posicionamiento en búsqueda YouTube

### Tipo

Optimización / Growth Analytics

### Contexto

Durante el análisis inicial del MVP del canal México Hoy en 5 Minutos, se detecta que YouTube comenzó a recomendar el contenido, pero aún existe poca presencia en resultados de búsqueda.

Video analizado:
MH5M-260616-001-SEGURIDAD

### Métricas iniciales

Periodo:
Primeras horas posteriores a publicación.

Fuentes de tráfico:

- Other YouTube Features: 50%
- Suggested Videos: 21.4%
- Direct or Unknown: 7.1%
- Channel Pages: 7.1%
- External: 7.1%
- YouTube Search: sin tráfico significativo

### Análisis

Resultado positivo:
YouTube está clasificando correctamente el contenido y comenzó a probarlo mediante recomendaciones.

El tráfico inicial depende principalmente de:
- recomendaciones internas
- sugerencias automáticas

### Problema detectado

El contenido depende principalmente de recomendación automática.
Existe baja captación mediante usuarios que buscan activamente información.
Se requiere aumentar descubrimiento orgánico.

### Hipótesis

Los metadatos actuales son correctos para clasificación inicial, pero requieren mayor alineación con intención de búsqueda del usuario.

### Cambios propuestos

Optimizar:

- títulos orientados a preguntas
- descripción con términos clave
- capítulos del video
- palabras clave mencionadas dentro del guion
- miniatura alineada al interés del usuario

### Criterios de aceptación

- Crear plantilla SEO v0.2 ✔
- Definir formato estándar de títulos ✔
- Crear checklist previo a publicación ✔
- Medir fuentes de tráfico después del cambio ⏳

### Métrica objetivo

YouTube Search >= 15%
Retención promedio >= 40%

### Implementado en

MH5M-002

### Cambios aplicados

✔ Título orientado a pregunta detonadora
✔ Capítulos manuales agregados
✔ Mejor experiencia de usuario
✔ Mayor contexto para el algoritmo de YouTube

### Aprendizaje generado

"El primer cuello de botella detectado no está en la producción
del contenido, sino en la optimización de entrada:
CTR, búsqueda y empaque."

### Siguiente acción

Revisar Analytics de MH5M-002 para validar incremento
en tráfico por búsqueda vs MH5M-001 (baseline: 0%)

### Estado

DONE ✔

---

## ISSUE-008 - Optimización de segundo experimento de contenido

### Contexto

El MVP demostró retención aceptable pero CTR bajo.

### Hipótesis

Incrementar curiosidad inicial aumentará conversión.

### Cambios del experimento

- Nuevo formato de miniatura
- Hook inicial <10 segundos
- Títulos con pregunta

### Métrica comparativa

Video 001:
CTR 1.3%
Retención 48%

Objetivo Video 002:
CTR >= 3%
Retención >= 45%

### Estado

READY FOR SPRINT 1

---

## ISSUE-009 / HU-009 - Integrar tendencias de YouTube Inspiration

### Tipo

Content Intelligence / Growth Analytics

### Contexto

YouTube Studio proporciona señales internas sobre temas, búsquedas e intereses de usuarios.

Estas señales pueden utilizarse como entrada para mejorar la selección de temas del canal México Hoy en 5 Minutos.

### Problema

Actualmente los temas se seleccionan principalmente por análisis editorial.
Falta incorporar señales reales de demanda de audiencia.

### Hipótesis

Combinar:

- relevancia editorial
- tendencias actuales
- búsquedas frecuentes
- comportamiento de usuarios

incrementará:

- impresiones
- CTR
- descubrimiento orgánico

### Cambios propuestos

Agregar una etapa previa al guion:

```
Tema candidato
↓
Validación tendencias YouTube
↓
Análisis de demanda
↓
Priorización
↓
Producción
```

### Fuentes de información

- YouTube Inspiration
- YouTube Search
- Google Trends
- Noticias oficiales
- Fuentes periodísticas
- Analytics histórico del canal

### Criterios de aceptación

- Registrar tendencias encontradas antes de producir video
- Guardar palabras clave objetivo
- Documentar intención de búsqueda
- Comparar desempeño contra videos anteriores

### Métrica objetivo

YouTube Search >= 15%
CTR >= 3%

### Estado

BACKLOG

---

## ISSUE-010 - Diferenciación contra contenido IA masivo

### Contexto

Existe saturación de contenido generado automáticamente.
El canal puede percibirse como genérico.

### Riesgo

Pérdida de identidad editorial frente a competencia IA.

### Hipótesis

Agregar criterio editorial humano aumenta confianza y retención.

### Diferenciadores propuestos

Elementos exclusivos por episodio:

- Por qué importa este tema hoy
- Contexto histórico relevante
- Datos comparativos vs periodos anteriores

Nota:
Impacto ciudadano y neutralidad ya definidos
en 06-ContentStrategy.md

### Métrica objetivo

Mantener: Retención >= 45%
Incrementar: Suscriptores por vista

### Estado

BACKLOG

---

## EXPERIMENTO-002

### Hipótesis

Título con pregunta + miniatura con elemento de curiosidad
incrementa CTR vs episodio anterior.

### Variables modificadas

✔ Título con pregunta detonadora
✔ Miniatura con texto de curiosidad
✔ Capítulos manuales agregados
✔ Primer comentario fijado con CTA

### Comparativa

| Métrica | MH5M-001 | Objetivo MH5M-002 |
|---------|----------|-------------------|
| CTR | 1.3% | >= 3% |
| Retención | 48% | >= 45% |
| YouTube Search | ~0% | >= 15% |

### Estado

EN MEDICIÓN ⏳

### Resultado

Pendiente de Analytics

