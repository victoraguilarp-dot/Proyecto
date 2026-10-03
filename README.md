# Proyecto
# SCAR — Self-Correcting Adaptive Scientific Computing

## Descripción

SCAR es un proyecto de investigación que estudia el uso de aprendizaje automático para adaptar dinámicamente el nivel de fidelidad de una simulación científica.

El objetivo es investigar si una simulación puede reducir su costo computacional utilizando diferentes niveles de fidelidad, manteniendo al mismo tiempo el error dentro de un límite establecido.

## Problema de investigación

Las simulaciones científicas de alta fidelidad pueden requerir una cantidad considerable de recursos computacionales.

SCAR busca estudiar una estrategia en la que el nivel de fidelidad de la simulación se adapte según el estado del sistema, el error estimado y el presupuesto computacional disponible.

## Pregunta de investigación

¿Puede un controlador basado en aprendizaje automático seleccionar dinámicamente el nivel de fidelidad de una simulación científica y reducir su costo computacional manteniendo el error dentro de un límite establecido?

## Hipótesis

Un controlador basado en aprendizaje automático puede seleccionar dinámicamente el nivel de fidelidad de una simulación física, reduciendo el costo computacional respecto a una simulación de alta fidelidad, mientras mantiene el error numérico dentro de un límite previamente establecido.

## Caso de estudio inicial

El primer caso de estudio será la simulación numérica de transferencia de calor en dos dimensiones.

Se utilizarán diferentes niveles de fidelidad para estudiar la relación entre:

* Precisión
* Tiempo de ejecución
* Memoria utilizada
* Costo computacional

## Metodología

El proyecto se desarrollará progresivamente:

1. Implementación del solver numérico.
2. Construcción de una solución de referencia de alta fidelidad.
3. Implementación de diferentes niveles de fidelidad.
4. Generación de datos experimentales.
5. Desarrollo del controlador basado en aprendizaje automático.
6. Estimación del error y confiabilidad.
7. Adaptación dinámica de la fidelidad.
8. Incorporación de un presupuesto computacional.
9. Comparación con métodos de resolución fija.
10. Evaluación de resultados y limitaciones.

## Tecnologías

* Python
* NumPy
* SciPy
* scikit-learn
* PyTorch
* Matplotlib

## Estado del proyecto

🟡 Investigación en etapa inicial.

Actualmente se está definiendo el problema, la metodología y el diseño experimental.

## Resultados

Los resultados serán incorporados progresivamente a medida que se realicen los experimentos.

## Investigación

Este repositorio documentará el desarrollo del proyecto, incluyendo:

* Código fuente
* Experimentos
* Datos
* Resultados
* Gráficos
* Documentación
* Decisiones metodológicas

## Autor

Proyecto de investigación en desarrollo.
