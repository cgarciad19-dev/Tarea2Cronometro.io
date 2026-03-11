# ⏱ ChronoRace — Cronómetro de Competidores

Sistema de cronometraje en tiempo real para competencias, construido con HTML, CSS y JavaScript puro.

## 🚀 Demo en vivo
**[Ver aplicación →](https://TU-USUARIO.github.io/chronorace/)**  
**[Ver diagramas UML →](https://TU-USUARIO.github.io/chronorace/uml-diagrams.html)**

---

## ✅ Funcionalidades

- **Cronómetro maestro** con precisión de milisegundos
- **Agregar / eliminar competidores** en cualquier momento
- **Captura de tiempos** individuales por competidor con un clic
- **Clasificación en tiempo real** ordenada automáticamente
- **Diferencia vs. líder** calculada instantáneamente para cada posición
- **Panel de estadísticas** (líder, total, finalizados, en carrera)
- **Atajos de teclado**: `Espacio` = Iniciar/Detener, `Shift+R` = Reset

---

## 📐 Diagramas UML

| # | Diagrama | Descripción |
|---|----------|-------------|
| 1 | Casos de Uso | Actores e interacciones con el sistema |
| 2 | Clases | Estructura estática: atributos, métodos y relaciones |
| 3 | Secuencia | Flujo temporal de mensajes entre componentes |
| 4 | Objetos | Instancia concreta del sistema durante una carrera |
| 5 | Componentes | Arquitectura en capas y módulos |
| 6 | Actividad | Flujo completo de actividades del sistema |

---

## 🌐 Despliegue en GitHub Pages

```bash
# 1. Crea un repositorio en GitHub (ej: chronorace)
# 2. Clona el repositorio
git clone https://github.com/TU-USUARIO/chronorace.git

# 3. Copia los archivos index.html y uml-diagrams.html
# 4. Commit y push
git add .
git commit -m "ChronoRace app + UML diagrams"
git push origin main

# 5. Ve a Settings → Pages → Branch: main → Save
# Tu app estará en: https://TU-USUARIO.github.io/chronorace/
```

---

## 🛠 Tecnologías

- HTML5 / CSS3 / JavaScript ES6+ (sin dependencias externas)
- Google Fonts (Orbitron + Rajdhani)
- Mermaid.js (solo para diagramas UML)

---

## 📁 Estructura

```
chronorace/
├── index.html         ← Aplicación principal
├── uml-diagrams.html  ← 6 Diagramas UML interactivos
└── README.md
```
