# Skill Agents · Google Antigravity

Bienvenido a la guía interactiva sobre cómo crear y usar **Skill Agents** en **Google Antigravity**.

🔗 **Demo en vivo**: [Ver la aplicación](https://huanrasan.github.io/skill-agents-guide/) (si está desplegada en GitHub Pages)

## ¿Qué son los Skill Agents?

Los **Skills** son comportamientos inteligentes que le inyectas permanentemente a tu Agente Antigravity. No son recetas de pasos, sino un nuevo modo de pensar y actuar ante un tipo de problema.

* **Comportamiento Cognitivo**: Define cómo razona el agente y qué herramientas prioriza.
* **Activación Automática**: El agente detecta cuándo aplicar el skill orgánicamente.
* **Personalizables**: Crea skills a medida (ej: experto en React, auditor de seguridad).
* **Siempre Disponibles**: Residen en `.agents/skills/[nombre]/SKILL.md` dentro de tu proyecto.

## Workflows vs Skills

* **Workflows (`.agents/workflows/`)**: Recetas procedurales y lineales. Responden al "qué" y "cuándo".
* **Skills (`.agents/skills/`)**: Talentos cognitivos orgánicos. Responden al "cómo".

Un workflow puede invocar skills en un mismo flujo (ej: `/secure-deploy` llama automáticamenhte a la skill `security-auditor`).

## Ejemplo Multi-AI

El ejemplo **Multi-AI Pipeline** demuestra cómo se puede usar un workflow para permitir a Antigravity adoptar automáticamente el perfil cognitivo óptimo para cada fase del proyecto (Arquitecto, QA, Desarrollador Senior o Experto en Seguridad), haciendo posible el desarrollo autónomo.

```bash
# Ejemplo de uso interactivo:
/multi-ai-pipeline crea un módulo de autenticación
```

---
*Construido con Google Antigravity · Multi-AI Pipeline Skill*
