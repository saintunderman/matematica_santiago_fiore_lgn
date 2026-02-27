# Simulador de la Ley de los Grandes Números

Este proyecto es una herramienta educativa e interactiva diseñada para mostrar de manera empírica la **Ley de los Grandes Números** a través de la simulación de distintos experimentos aleatorios. Permite visualizar cómo, a medida que aumenta el número de experimentos, la frecuencia relativa de los eventos converge hacia la probabilidad teórica.

## Tecnologías Utilizadas

* **JavaScript (Vanilla ES6+):** Lógica para la generación de números aleatorios y el cálculo de promedios acumulados.
* **Chart.js:** Biblioteca utilizada para el renderizado de gráficos estadísticos dinámicos.
* **MathJax:** Integración de fórmulas matemáticas en LaTeX para explicar el fundamento teórico.
* **HTML5 & CSS3:** Estructura y estilos visuales con una experiencia de usuario optimizada.

## Fundamento Teórico

La aplicación explica matemáticamente la **Ley Débil de los Grandes Números**, la cual establece que para una secuencia de variables aleatorias independientes e idénticamente distribuidas (i.i.d.):

$$\lim_{n \to \infty} P\left( \left| \bar{X}_n - \mu \right| < \epsilon \right) = 1$$

Esto significa que el promedio de los resultados obtenidos de un gran número de ensayos debe estar cercano al valor esperado $\mu$, y tenderá a acercarse más a medida que se realicen más ensayos.

---
## Acceso al Simulador

https://saintunderman.github.io/matematica_santiago_fiore_lgn/

---

## Licencia y Créditos

Desarrollado por **Santiago Fiore**.

* **Sitio Web:** https://sites.google.com/view/santiago-fiore/portada
* **Licencia:** Creative Commons CC BY-NC-SA 4.0.
