# Cronómetro de Competidores

Sistema de cronometraje en tiempo real para competencias, construido con HTML, CSS y JavaScript.

## Demostración
**[Ver aplicación →](https://cgarciad19-dev.github.io/Tarea2Cronometro.io/)**  
**[Ver diagramas UML →](https://cgarciad19-dev.github.io/Tarea2Cronometro.io/uml-diagrams.html)**

---

## Funcionalidades

- **Cronómetro maestro** con precisión de milisegundos
- **Agregar / eliminar competidores** en cualquier momento
- **Captura de tiempos** individuales por competidor con un clic
- **Clasificación en tiempo real** ordenada automáticamente
- **Diferencia vs. líder** calculada instantáneamente para cada posición
- **Panel de estadísticas** (líder, total, finalizados, en carrera)
- **Atajos de teclado**: `Espacio` = Iniciar/Detener, `Shift+R` = Reset

---

## Diagramas UML

| # | Diagrama | Descripción |
|---|----------|-------------|
| 1 | Casos de Uso | Actores e interacciones con el sistema |
| 2 | Clases | Estructura estática: atributos, métodos y relaciones |
| 3 | Secuencia | Flujo temporal de mensajes entre componentes |
| 4 | Objetos | Instancia concreta del sistema durante una carrera |
| 5 | Componentes | Arquitectura en capas y módulos |
| 6 | Actividad | Flujo completo de actividades del sistema |

---

## Tecnologías

- HTML5 / CSS3 / JavaScript ES6+ (sin dependencias externas)
- Google Fonts (Orbitron + Rajdhani)
- Mermaid.js (solo para diagramas UML)

---

## Estructura

```
chronorace/
├── index.html         ← Aplicación principal
├── uml-diagrams.html  ← 6 Diagramas UML interactivos
└── README.md
```
