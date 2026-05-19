# Diagrama de Ishikawa · Banco Confianza

**Herramienta interactiva de análisis de calidad con caso de estudio real**

---

## 🎯 Demo en vivo

| Herramienta | Enlace |
|---|---|
| 🐟 Diagrama interactivo | [tomaspro56.github.io/Diagrama-de-Ishikawa/](https://tomaspro56.github.io/Diagrama-de-Ishikawa/) |
| 🎮 Juego de clasificación | [tomaspro56.github.io/Diagrama-de-Ishikawa/juego.html](https://tomaspro56.github.io/Diagrama-de-Ishikawa/juego.html) |

---

## Acerca del proyecto

El **Diagrama de Ishikawa** (o diagrama de espina de pescado) es una herramienta de análisis de causa raíz ampliamente utilizada en gestión de calidad. Permite identificar de forma estructurada las causas que originan un problema, agrupándolas en categorías para facilitar el diagnóstico y la toma de decisiones.

Este proyecto fue desarrollado como apoyo visual a una exposición en la materia **Fundamentos de Calidad** del [Instituto Tecnológico Metropolitano (ITM)](https://www.itm.edu.co), Medellín, Colombia. En lugar de una presentación estática, se construyeron dos páginas web interactivas que permiten explorar la metodología y aplicarla sobre un caso de estudio real.

---

## Características

### 🐟 Diagrama Interactivo

Visualización SVG navegable del diagrama de Ishikawa aplicado al caso Banco Confianza, con tres vistas disponibles:

- **Vista del diagrama** — espina de pescado con 5 categorías de causa (Personas, Tecnología, Procesos, Datos, Entorno), cada una con sus causas específicas conectadas al nodo central *"Errores en estados de cuenta"*
- **Vista del caso de estudio** — panel con los datos del Banco Confianza: tipos de error, nivel de criticidad por categoría y evolución mensual de reclamos
- **Vista educativa** — explicación del método Ishikawa, para qué sirve cada categoría y cómo interpretar el diagrama

### 🎮 Juego de Clasificación

Actividad interactiva por equipos pensada para dinamizar la clase:

- **4 equipos** compiten simultáneamente
- Una **ruleta** asigna aleatoriamente uno de los 4 casos de problemas reales a cada equipo
- **2 minutos por turno** para clasificar las causas
- Mecánica **drag-and-drop**: arrastrar causas a la categoría correcta
- **Sistema de puntos por equipo** y ranking final entre los 4 equipos

---

## Caso de estudio: Banco Confianza

| Indicador | Valor |
|---|---|
| Reclamos mensuales | 120 |
| Costo estimado mensual | ~$12,000 USD |
| Problema central | Errores en estados de cuenta |

El Banco Confianza registraba **120 reclamos mensuales** relacionados con inconsistencias en los estados de cuenta entregados a sus clientes, lo que generaba un costo operativo de aproximadamente **$12,000 USD al mes** entre atención al cliente, correcciones manuales y pérdida de confianza.

Este caso ilustra bien el uso del Diagrama de Ishikawa porque el problema tiene causas distribuidas en múltiples frentes: errores humanos en la captura de datos, fallas en los sistemas de generación de reportes, procesos de validación ausentes o mal definidos, y factores de entorno como cambios regulatorios no incorporados a tiempo. Ninguna causa aislada explica el fenómeno completo — exactamente el escenario donde Ishikawa es más útil.

---

## Cómo usarlo localmente

### Opción 1 — Live Server (recomendado)

```bash
git clone https://github.com/tomaspro56/Diagrama-de-Ishikawa.git
cd Diagrama-de-Ishikawa
```

Abrir la carpeta en VS Code y lanzar **Live Server** (extensión de Ritwick Dey) sobre `index.html`. El juego en `juego.html` funciona desde el mismo servidor.

### Opción 2 — Abrir directo en el navegador

```bash
git clone https://github.com/tomaspro56/Diagrama-de-Ishikawa.git
```

Navegar a la carpeta descargada y abrir `index.html` o `juego.html` directamente con el navegador. No requiere servidor — todo es client-side.

---

## Stack técnico

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de las páginas |
| CSS3 (vanilla) | Estilos y animaciones |
| JavaScript (vanilla) | Lógica interactiva y mecánicas del juego |
| SVG | Diagrama de espina de pescado |

Sin frameworks, sin dependencias externas, sin proceso de build.

---

## Contexto académico

- **Materia:** Fundamentos de Calidad
- **Institución:** Instituto Tecnológico Metropolitano (ITM)
- **Ciudad:** Medellín, Colombia
- **Propósito:** Exposición sobre herramientas de análisis de calidad

El objetivo de la exposición era presentar el Diagrama de Ishikawa no solo como un concepto teórico, sino como una herramienta aplicable a situaciones reales. Las páginas interactivas permiten que el público explore el diagrama a su ritmo y refuerce el aprendizaje a través del juego.

---

Desarrollado por **Tomás Pérez** · ITM 2026
