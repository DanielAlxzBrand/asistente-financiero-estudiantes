# Asistente Financiero para Estudiantes Universitarios

Asistente financiero interactivo dirigido a estudiantes universitarios colombianos que estudian y trabajan. Genera un diagnóstico y un plan de presupuesto personalizado a partir de datos reales del estudiante (ingreso neto, gastos esenciales, semestre, carrera y objetivo profesional).

**Proyecto final del curso Claude 101 (Anthropic Academy).**

🔗 **Demo en vivo:** _(se actualizará automáticamente con el link de GitHub Pages una vez publicado)_

---

## ¿Qué hace?

- Calcula la capacidad financiera real: `Ingreso neto − Gastos esenciales = Capacidad disponible`, en lugar de usar porcentajes fijos genéricos.
- Controles deslizantes interactivos para ajustar ocio (2%–15%) y ahorro (5%–30%), con recálculo automático en tiempo real.
- Diagnóstico de salud financiera en tres niveles: Saludable, Precaución o Riesgo financiero, con motivos explícitos.
- Separa tres tipos de ahorro: fondo de emergencia, ahorro general y metas financieras personales.
- Recomienda certificaciones y cursos de forma dinámica según carrera, semestre y objetivo profesional.
- Sugiere un perfil de inversión (Conservador / Moderado / Agresivo) condicionado a la estabilidad financiera real del estudiante, con instrumentos usados en Colombia (CDT, FIC, COLCAP, ETF), sin prometer rentabilidades.
- Incluye una sección de transparencia ("¿Cómo se calculó tu plan?") que muestra paso a paso cada cifra del presupuesto.

## Metodología

Todo el contenido financiero y pedagógico se fundamentó exclusivamente en diez documentos de educación financiera (BCRA, SBS, ICETEX, AMV, entre otros) cargados como base de conocimiento en Claude Projects (Project Knowledge), evitando el uso de fuentes externas no verificadas. El desarrollo se construyó en fases iterativas usando Claude (Anthropic) — Claude Projects, Project Knowledge y Artifacts.

## Stack técnico

HTML5 + CSS3 + JavaScript (vanilla), en un único archivo autocontenido, sin frameworks ni dependencias externas de ejecución.

## Autor

Daniel Alexander Brand García
