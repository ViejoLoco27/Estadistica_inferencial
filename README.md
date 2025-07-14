# 📊 Curso de Estadística Aplicada - Bitácora y Scripts Técnicos

Este repositorio documenta los temas teóricos, ejercicios prácticos y scripts técnicos desarrollados durante el curso de **Estadística Aplicada**, enfocado en el análisis inferencial, muestreo, estimaciones y visualización de resultados en Python.

---

## 🧠 Objetivos del curso

- Comprender los fundamentos del muestreo y la inferencia estadística.
- Aplicar el Teorema del Límite Central y el cálculo de errores.
- Construir intervalos de confianza y evaluar hipótesis.
- Calcular tamaños óptimos de muestra según contexto.
- Visualizar simulaciones estadísticas en Python con herramientas como `Matplotlib` y `Pandas`.

---

## 🧾 Temas abordados

### 1. Fundamentos teóricos
- Población vs. muestra
- Muestreo aleatorio simple
- Representatividad muestral

### 2. Distribuciones y valores críticos
- Teorema del Límite Central (TLC)
- Distribución normal estándar
- Estimador Z vs. valor crítico Z
- Nivel de confianza vs. significancia

### 3. Inferencia y estimación
- Intervalos de confianza:
  - Para poblaciones con desviación estándar conocida
  - Para poblaciones sin desviación estándar conocida
- Error inferencial
- Visualización gráfica de dispersión muestral

### 4. Cálculo de tamaño muestral
- Para poblaciones infinitas:
  - \( n = \left(\frac{Z \cdot \sigma}{e}\right)^2 \)
- Para poblaciones finitas:
  - \( n = \frac{Z^2 \cdot \sigma^2 \cdot N}{Z^2 \cdot \sigma^2 + e^2 \cdot (N - 1)} \)

### 5. Aplicaciones prácticas
- Estudios de ingreso mensual
- Estimaciones de gasto promedio
- Simulación con múltiples muestras
- Validación visual con curvas de confianza

---

## 🧮 Scripts destacados

Los notebooks y archivos incluidos en este repositorio presentan:

- Muestreo aleatorio simple con `pandas.sample()`
- Simulaciones con `for` loops y `random_state`
- Cálculo y visualización de intervalos de confianza con `scipy.stats.norm`
- Gráficas de dispersión con `matplotlib.pyplot`
- Cálculo de tamaño de muestra optimizado para distintas poblaciones

---

## 📁 Estructura del repositorio


---

## 💡 Aprendizaje destacado

> “A través de la conexión entre estimador Z, valor crítico y error inferencial, comprendí cómo el Teorema del Límite Central fundamenta las técnicas modernas de estimación. Cada simulación refuerza la importancia de la representatividad muestral y la toma consciente de decisiones estadísticas.”

---

## 🚀 Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- SciPy
- Matplotlib
