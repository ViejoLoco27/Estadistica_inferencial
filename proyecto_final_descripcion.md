# 📘 Proyecto Final – Estadística Inferencial Aplicada

Este archivo documenta el desarrollo del proyecto final del curso de **Estadística Inferencial**, utilizando la Encuesta Nacional por Muestreo de Hogares (PNAD - Brasil, 2015) como fuente principal de datos. El proyecto sigue un guión metodológico que combina análisis probabilístico, cálculo inferencial, estimación y simulación de tamaños muestrales en un contexto real.

---

## 🧠 Objetivo del proyecto

Responder a una serie de ejercicios prácticos que integran conocimientos vistos en el curso:

- Aplicación de distribución binomial en muestreo de proporciones.
- Estimación de parámetros poblacionales y error inferencial.
- Cálculo del tamaño de muestra bajo diferentes niveles de confianza.
- Evaluación del costo estadístico de una encuesta según requerimientos del cliente.
- Simulación de intervalos de confianza y análisis de viabilidad presupuestaria.

---

## 🗂️ Dataset utilizado

- **Fuente**: Encuesta Nacional por Muestreo de Hogares – IBGE (PNAD 2015)
- **Variables seleccionadas**:
  - Ingreso mensual del trabajo principal
  - Edad
  - Altura (variable derivada)
  - Sexo
  - Unidad Federal (UF)
  - Color
  - Años de estudio

Se aplicaron filtros para depurar registros inválidos o incompletos.

---

## 🔍 Ejercicios abordados

### Problema A – Probabilidad de seleccionar grupos con 70% hombres
- Se aplicó la distribución binomial para calcular la probabilidad de seleccionar grupos de 10 individuos con 7 hombres y 3 mujeres.
- Resultado: \( P(k=7 \mid n=10, p=0.70) \approx 0.267 \)

### Problema B – Cantidad de grupos necesarios
- Se estimó cuántos grupos de 10 individuos deben seleccionarse aleatoriamente para obtener 100 grupos con proporción 7/3 hombres/mujeres.
- Resultado: 374 grupos

### Problema C – Diseño de encuesta y estimaciones inferenciales
- Se simuló una encuesta de ingresos bajo restricciones de tiempo, costo y error máximo.
- Muestra base: 200 elementos (random_state = 101)
- Cálculo de tamaño muestral para niveles de confianza de 90%, 95% y 99%.
- Evaluación del costo para cada nivel y análisis de viabilidad financiera.
- Cálculo del intervalo de confianza para la media con el nivel viable (95%)
- Estimación del margen de error real alcanzable con el presupuesto.
- Proyección del costo si se exige un margen de error del 5%.

---

## 🧮 Herramientas utilizadas

- `pandas` – Manipulación de datos
- `numpy` – Operaciones numéricas
- `scipy.stats.norm` – Distribución normal e intervalos de confianza
- `scipy.stats.binom` – Distribución binomial
- `matplotlib.pyplot` – Visualización de simulaciones
- Cálculos adicionales sobre media, desviación estándar, errores y costos

---

## 📊 Resultados destacados

- Se comprendió el vínculo entre error inferencial, desviación estándar, nivel de confianza y tamaño de muestra.
- Se aplicó el Teorema del Límite Central en la interpretación de simulaciones.
- Se evaluó el costo estadístico de la recolección de datos en función de precisión deseada.
- Se realizó la toma de decisiones informadas a partir de probabilidades, márgenes y presupuestos.

---

## 📁 Estructura del repositorio
