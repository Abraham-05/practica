# Actividad: Propuesta de Práctica Temática Documentada en Entorno de Terminal

## 1) Título de la práctica
**Diseño de Mini Proyecto en Terminal: de la Idea a la Documentación**

> Puedes ajustar el título final de tu propuesta a algo como:
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general
En esta actividad vas a **diseñar una propuesta de proyecto pequeño** que pueda desarrollarse en un repositorio de GitHub Classroom, priorizando la **documentación, planeación y justificación técnica** antes de escribir código en gran cantidad.

Tu propuesta deberá elegir **un lenguaje principal**:
- **ARM64 Assembly**
- **C**
- **Python**
- **Bash**

> **Nota importante sobre ARM64 Assembly:** úsalo solo para programas **muy pequeños**, con alcance acotado y objetivos claros (por ejemplo, utilerías mínimas o demostraciones de conceptos puntuales).

La meta es que tu proyecto sea **factible en tiempo corto**, compatible con herramientas de IA de uso gratuito y sin depender de infraestructura compleja.

---

## 3) Objetivo académico
Al finalizar, deberás demostrar que sabes:
- Delimitar el alcance de una práctica técnica realista.
- Justificar un caso de uso concreto.
- Diseñar la estructura base de un repositorio.
- Definir un plan de pruebas inicial.
- Comunicar decisiones técnicas de forma clara y ordenada.

---

## 4) Restricciones del proyecto
Tu propuesta **debe** cumplir estas restricciones:
- Proyecto pequeño y temático.
- Enfoque principal en documentación y planeación.
- Sin frameworks pesados.
- Sin APIs de paga.
- Sin bases de datos.
- Sin servicios en la nube.
- Sin contenedores.
- Sin dependencias complejas o difíciles de instalar.
- Debe poder ejecutarse localmente en terminal (al menos una parte del flujo).

---

## 5) Entregables del estudiante
Tu repositorio debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Carpetas opcionales (si ya tienes avance de implementación):
- `src/`
- `scripts/`
- `tests/`

---

## 6) Estructura recomendada del repositorio
Usa como base la siguiente estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende de tu lenguaje elegido (`s`, `c`, `py`, `sh`, etc.).

---

## 7) Contenido mínimo esperado por archivo

### `README.md`
Incluye:
- Nombre del proyecto.
- Lenguaje principal elegido.
- Resumen de 5 a 8 líneas del problema que resolverás.
- Instrucciones básicas de uso (aunque sea prototipo).
- Alcance: qué sí incluye y qué no incluye.

### `docs/propuesta.md`
Incluye:
- Descripción detallada de la idea.
- Objetivo general.
- 3 objetivos específicos.
- Perfil de usuario al que va dirigido.
- Justificación técnica del lenguaje seleccionado.
- Alcance técnico (MVP pequeño y realista).

### `docs/caso_de_uso.md`
Incluye:
- Situación real o simulada donde el proyecto aporta valor.
- Actor principal.
- Entradas esperadas.
- Flujo básico de uso en pasos.
- Salida esperada.
- Limitaciones conocidas.

### `docs/estructura_repositorio.md`
Incluye:
- Árbol de carpetas final planeado.
- Propósito de cada carpeta/archivo.
- Convenciones de nombres (archivos, scripts y pruebas).
- Estrategia para separar lógica, scripts y documentación.

### `docs/plan_de_pruebas.md`
Incluye:
- Lista de pruebas mínimas (al menos 5).
- Qué valida cada prueba.
- Datos de entrada por prueba.
- Resultado esperado.
- Criterios de aceptación básicos.

---

## 8) Guía para Codex (obligatoria)
Sigue esta secuencia al construir tu entrega:

1. Planifica primero la estructura completa del repositorio.  
2. Genera cada archivo de forma independiente.  
3. Asegúrate de incluir TODOS los archivos.  
4. Verifica:  
   - ¿Hay múltiples archivos?  
   - ¿Cada archivo tiene contenido?  
   - ¿Se respetó el formato de delimitadores?  
5. Mantén la salida debajo de 500 líneas.

---

## 9) Criterios de evaluación sugeridos (100%)
- **Claridad de la propuesta y delimitación del alcance** – 25%
- **Calidad del caso de uso y coherencia funcional** – 20%
- **Estructura del repositorio y organización técnica** – 20%
- **Plan de pruebas (calidad y viabilidad)** – 20%
- **Redacción técnica, formato y completitud de entregables** – 15%

---

## 10) Recomendaciones finales para estudiantes
- Piensa en una práctica que puedas explicar, probar y defender.
- Evita ambigüedades: define entradas, salidas y límites.
- Si eliges ARM64, reduce al mínimo el alcance funcional.
- Documenta primero, programa después.
- Prioriza una solución simple, entendible y demostrable.

---

## Setup Script
No se requiere configuración adicional.
