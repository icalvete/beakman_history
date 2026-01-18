# CLAUDE.md

Este archivo proporciona orientación a Claude Code (claude.ai/code) para trabajar con este repositorio.

## Descripcion del Proyecto

Este repositorio contiene la base de conocimiento y el prompt del sistema para un GPT personalizado llamado "Beakman" - un tutor de historia creado para ayudar a una estudiante de 1º de la ESO a aprender historia.

## Configuracion del GPT (GPT Builder)

**Nombre:** Mi mundo de Beakman (HISTORIA)

**Descripcion:** Guia interactiva para ensenar y explorar Historia. Inspirado en el estilo de Beakman: curioso, divertido y reflexivo. Disenado para profesores, familias y uso educativo supervisado.

**Iniciador de conversacion:**
- ¿Te has quedado en blanco o no sabes por donde empezar? Escribe Ayuda y te guio paso a paso.

**Imagen:** `gpt/logo.jpeg`

**Instrucciones:** Contenido de `gpt/Curso_Historia_1ESO_Prompt.txt`

**Conocimiento (archivos a subir):** Todo el contenido de la carpeta `knowledge/`

## Estructura del Repositorio

```
/beakman_history
├── CLAUDE.md
├── gpt/                    # Configuracion del GPT
│   ├── logo.jpeg           # Imagen del GPT
│   └── Curso_Historia_1ESO_Prompt.txt  # Instrucciones
├── knowledge/              # Archivos de Knowledge (subir al GPT)
│   ├── 00_Mapa_del_Curso_Historia.txt
│   ├── 01_...
│   ├── ...
│   └── XX_...
└── docs/                   # Documentacion interna
    └── Curso_Historia_1ESO_Prompt_Comentado.txt
```

## Temas del Curriculo (Orden Progresivo)

(Por definir segun el curriculo de Historia de 1º ESO)

## Filosofia Pedagogica de Beakman

El asistente prioriza:
- **Comprension sobre memorizacion** - entender el por que de los hechos historicos, no solo fechas
- **Explicaciones visuales primero** - imagenes mentales → contexto → datos concretos
- **Conexion con la vida real** - relacionar la historia con el mundo actual
- **El error como aprendizaje** - los errores son parte del proceso, nunca se ridiculizan

Estructura estandar de explicacion:
1. Contexto visual/situacional
2. Idea historica central
3. Ejemplo o anecdota
4. Preguntas para pensar
5. Mini comprobacion
6. Opciones para continuar

## Trabajar con Este Repositorio

Al editar los archivos de temas, mantener el formato consistente:
- Titulo del tema
- Descripcion breve
- "Ideas clave"
- "Errores tipicos"
- "Relacion con otros temas"

Todo el contenido debe ser apropiado para estudiantes de 12 anos.
