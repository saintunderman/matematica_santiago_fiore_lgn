# Simulador de la Ley de los Grandes Números

Este proyecto es una herramienta educativa e interactiva diseñada para mostrar de manera empírica la **Ley de los Grandes Números** a través de la simulación de lanzamientos de dados. Permite visualizar cómo, a medida que aumenta el número de experimentos, la frecuencia relativa de los eventos converge hacia la probabilidad teórica.

## Características Principales

* **Simulación Estocástica:** Generación de lanzamientos de dados virtuales (1 a 6 caras) con resultados aleatorios procesados en tiempo real.
* **Visualización Dinámica:** Incluye dos tipos de gráficos interactivos potenciados por **Chart.js**:
    * **Frecuencias Absolutas:** Gráfico de barras que muestra cuántas veces ha salido cada cara del dado.
    * **Convergencia de la Media:** Gráfico de líneas que ilustra cómo el promedio observado se estabiliza en el valor teórico ($3.5$) a medida que crecen los lanzamientos.
* **Control de Parámetros:** El usuario puede definir la cantidad de lanzamientos por iteración (desde 1 hasta 10,000) y la velocidad de la animación.
* **Panel de Estadísticas:** Resumen detallado que incluye el total de lanzamientos, el promedio actual y el error relativo respecto al valor esperado.
* **Interfaz Responsiva:** Diseño moderno y funcional que se adapta a cualquier tamaño de pantalla.

## Tecnologías Utilizadas

* **JavaScript (Vanilla ES6+):** Lógica para la generación de números aleatorios y el cálculo de promedios acumulados.
* **Chart.js:** Biblioteca utilizada para el renderizado de gráficos estadísticos dinámicos.
* **MathJax:** Integración de fórmulas matemáticas en LaTeX para explicar el fundamento teórico.
* **HTML5 & CSS3:** Estructura y estilos visuales con una experiencia de usuario optimizada.

## Cómo Funciona

1.  **Configuración:** Selecciona cuántos lanzamientos quieres realizar en cada paso.
2.  **Ejecución:** Haz clic en "Lanzar Dados" para iniciar la simulación o usa el modo automático para ver la progresión continua.
3.  **Análisis:** Observa cómo la línea de la media se acerca a la línea punteada roja ($3.5$), validando el teorema estadístico.

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
