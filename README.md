# 📊 Análisis de Bienestar Mental mediante Modelos de Regresión

[cite_start]Este repositorio contiene un estudio estadístico y computacional sobre el impacto del estilo de vida en el bienestar mental, basado en el dataset **"Screen Time vs Mental Wellness Survey - 2025"**. [cite_start]El proyecto utiliza modelos de **regresión lineal simple y múltiple** para predecir niveles de estrés a partir de variables como productividad y calidad de sueño.

## 🚀 Acceso al Análisis Técnico
[cite_start]El procesamiento de datos y la generación de modelos se realizaron íntegramente en Python utilizando Google Colab. 

🔗 **[Google Colab: Metodos de regresion lineal.ipynb](https://colab.research.google.com/drive/1OmtBegmyRG1JWAFazHsCuhBC6pwvft?usp=sharing)**

## 📝 Resumen del Proyecto
[cite_start]La investigación analiza una muestra de 400 participantes para comprender el vínculo entre la tecnología, el descanso y la salud mental.

### Variables Analizadas
* [cite_start]**Variable de Respuesta (Y):** Nivel de estrés (Escala 1-10).
* [cite_start]**Variables Predictoras (X):** * Productividad percibida ($x_1$).
    * [cite_start]Calidad de sueño ($x_2$).
    * [cite_start]Horas de sueño diarias ($x_3$).

## 🧪 Metodología y Algoritmos
[cite_start]Para la obtención de coeficientes, se compararon dos enfoques fundamentales de la ciencia de datos:

1.  [cite_start]**Mínimos Cuadrados:** Solución directa mediante la ecuación normal para obtener coeficientes exactos.
2.  [cite_start]**Descenso de Gradiente:** Aproximación iterativa para minimizar la función de costo, ajustada mediante `learning_rate` y tolerancia.

## 📈 Conclusiones Clave
* [cite_start]**Correlación Fuerte:** Se identificó una correlación lineal negativa muy fuerte ($r = -0.876$) entre la productividad y el estrés.
* [cite_start]**Poder Predictivo:** El modelo de regresión simple basado en la **productividad** explica el **77.4%** de la variabilidad del estrés ($R^2 = 0.774$).
* [cite_start]**Eficiencia del Modelo:** Tras analizar el $R^2$ ajustado, se determinó que la adición de variables de sueño no mejora significativamente la predicción del modelo inicial, siendo la productividad la variable predictora más robusta.

## 🛠️ Tecnologías Utilizadas
* [cite_start]**Lenguaje:** Python.
* [cite_start]**Entorno:** Google Colab.
* [cite_start]**Matemática Aplicada:** Regresión Lineal Múltiple, Coeficiente de Determinación ($R^2$), Intervalos de Confianza y Descenso de Gradiente.

---
[cite_start]**Autores:** Gentile Valentino, Roa Elías, Rodriguez Ricon Mauricio.
