# AI System — Framework Personal de Agentes y Skills

Este repositorio contiene un sistema modular de **agentes** y **skills** diseñado para automatizar tareas de desarrollo, aprendizaje guiado y documentación técnica.  
El objetivo es disponer de un entorno reutilizable para cualquier proyecto (Java, Spring, Python, Node, etc.) basado en tres componentes:

## 🧠 1. Agente Principal
Define el comportamiento general del asistente:
- orquesta los distintos skills
- interpreta las órdenes del usuario
- mantiene coherencia entre sesiones
- gestiona el flujo de trabajo (contexto → desarrollo → documentación)

## 🧩 2. Skills
Módulos independientes que realizan tareas específicas:
- **skill_global_context** → genera `contexto_global.md` a partir de documentos técnicos
- **skill_pasos_logicos** → tutor paso a paso para crear funcionalidades sin generar código directamente
- **skill_journal** → genera la bitácora técnica de cada sesión (`journal.md`)

Cada skill está diseñado para ser reutilizable en cualquier proyecto o tecnología.

## 📁 3. Artefactos
Archivos generados automáticamente por los skills:
- `contexto_global.md`
- `journal.md`
- `backlog.md` (opcional)
- otros documentos derivados del flujo de trabajo

## 📦 Estructura del repositorio
```
/agents
   agente_principal.md
/skills
   skill_global_context.md
   skill_pasos_logicos.md
   skill_journal.md
/artifacts
/docs
```

## 🎯 Objetivo del proyecto
Crear un sistema profesional de agentes IA que:
- automatice la comprensión de requisitos
- guíe el desarrollo paso a paso
- documente el progreso de forma automática
- sea portable entre proyectos y tecnologías
- sirva como portfolio técnico para procesos de selección

## 📌 Estado
En construcción. Se irán añadiendo agentes, skills y ejemplos de uso.

