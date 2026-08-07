# VeriFact

## Sistema inteligente para análisis de información digital

VeriFact es una plataforma web orientada al análisis automatizado de contenidos digitales para identificar indicadores asociados a posibles casos de desinformación.

El sistema permitirá introducir un texto o una URL y obtener un análisis acompañado de un nivel de riesgo y una explicación de los factores que contribuyeron al resultado.

## Problema

La circulación masiva de información en Internet dificulta que los usuarios puedan determinar rápidamente la confiabilidad de determinados contenidos.

Las publicaciones pueden presentar lenguaje sensacionalista, afirmaciones absolutas, ausencia de fuentes verificables u otros patrones asociados con información engañosa.

VeriFact busca proporcionar una herramienta que facilite el análisis inicial de estos contenidos y apoye la toma de decisiones informadas.

## Objetivo

Diseñar e implementar una plataforma web modular para el análisis automatizado de contenidos digitales, capaz de identificar indicadores asociados a posibles casos de desinformación y proporcionar un nivel de riesgo acompañado de una explicación de los factores detectados.

## Funcionalidades previstas

- Registro e inicio de sesión.
- Análisis de texto.
- Análisis mediante URL.
- Identificación de indicadores asociados a posibles casos de desinformación.
- Generación de una puntuación de riesgo.
- Clasificación del resultado.
- Explicación de los factores detectados.
- Historial de análisis.
- Dashboard de estadísticas.
- Gestión de usuarios.

## Arquitectura inicial

La solución se plantea como una arquitectura modular con separación de responsabilidades.

```text
Frontend
    |
    v
Backend
    |
    +---- Users
    |
    +---- Content
    |
    +---- Analysis
    |
    +---- Reports
    |
    v
Analysis Engine
    |
    v
Database
