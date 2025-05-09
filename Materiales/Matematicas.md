# Guía de Estudio y Hoja de Trabajo

---

## 📘 Guía de Estudio

#### Aritmética

**Temas fundamentales**  
- **Operaciones con fracciones:**  
  - Suma/resta: $\frac{a}{b}\pm\frac{c}{d}=\frac{ad\pm bc}{bd}$.  
  - Multiplicación: $\frac{a}{b}\cdot\frac{c}{d}=\frac{ac}{bd}$.  
  - División: $\frac{a/b}{c/d}=\frac{a}{b}\cdot\frac{d}{c}$.  

- **Decimales y porcentajes:**  
  - Convertir porcentaje a decimal: $p\% = \tfrac p{100}$.  
  - Calcular porcentaje de un valor: $P = V\cdot\tfrac p{100}$.  

- **MCD y mcm:**  
  - Método de Euclides para MCD$(a,b)$.  
  - Relación: $a\cdot b = \mathrm{MCD}(a,b)\times \mathrm{mcm}(a,b)$.

- **Potencias y raíces:**  
  - $a^m\cdot a^n = a^{m+n}$, $(a^m)^n = a^{mn}$. 
  - $\frac{a^m}{a^n}=a^{m-n}$ 
  - $\sqrt[n]{a^m} = a^{m/n}$.

**Ejemplos de práctica**  
1. Reduce $\displaystyle \frac{3}{4} + \frac{5}{6} = ?$  
2. Encuentra el 15 % de 240.  
3. Calcula MCD(84, 30) y mcm(84, 30).  
4. Simplifica $(2^3)^2 \cdot 2^{-1}$.

---

### 1. Álgebra

**Conceptos clave**  
- Forma general de las ecuaciones de primer grado: $ax + by = c$.  
- Despeje de variables.  
- Factorización: trinomios, diferencia de cuadrados, por agrupación.  
- Funciones: dominio, rango, notación $f(x)$.

**Fórmulas esenciales**  

| Tema                      | Fórmula / Método                                            |
|---------------------------|-------------------------------------------------------------|
| Ecuación lineal           | $y = mx + b$                                               |
| Sistema de dos ecuaciones | Métodos: sustitución, igualación, reducción (suma/resta)    |
| Trinomio cuadrado perfecto| $a^2 + 2ab + b^2 = (a + b)^2$                              |
| Diferencia de cuadrados   | $a^2 - b^2 = (a - b)(a + b)$                               |

**Ejemplo resuelto**  
Resolver el sistema:  
$$
\begin{cases}
2x + y = 5\\
x - 2y = -4
\end{cases}
$$ 
1. De la primera: $y = 5 - 2x$  
2. Sustituir en la segunda:  
   \[
   x - 2(5 - 2x) = -4 
   \;\Longrightarrow\;
   x - 10 + 4x = -4
   \;\Longrightarrow\;
   5x = 6
   \;\Longrightarrow\;
   x = \tfrac{6}{5}
   \]  
3. Entonces  
   $$
   y = 5 - 2\cdot\tfrac{6}{5}
     = 5 - \tfrac{12}{5}
     = \tfrac{13}{5}
   $$

---

### 2. Geometría Analítica

**Conceptos clave**  
- Distancia entre puntos $(x_1,y_1)$ y $(x_2,y_2)$.  
- Punto medio.  
- Ecuación de la recta: punto-pendiente y forma general.  
- Circunferencia: centro $(h,k)$ y radio $r$.

**Fórmulas esenciales**  

| Tema                 | Fórmula                                                       |
|----------------------|---------------------------------------------------------------|
| Distancia            | $d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$                   |
| Punto medio          | $\bigl(\tfrac{x_1+x_2}{2},\,\tfrac{y_1+y_2}{2}\bigr)$        |
| Recta (p-pendiente)  | $y - y_1 = m\,(x - x_1)$                                    |
| Ecuación punto pendiente | $y-y_1 = m(x - x_1)$
| Ecuación general de la recta | $Ax + By + C = 0$ 
| Circunferencia       | $(x - h)^2 + (y - k)^2 = r^2$
| Ecuación general de la circunferencia | $x^2 + y^2 + Dx + Ey + F = 0$
|

**Ejemplo resuelto**  
Ecuación de la recta por $(1,2)$ con pendiente $m=-3$:  
$$
y - 2 = -3(x - 1)
\;\Longrightarrow\;
y = -3x + 5
$$

#### Secciones cónicas
- *Parábola*:
	- Elementos: vértice, foco, directriz, lado recto, eje de simetría.
	- Ecuaciones canónicas y ordinarias (horizontal y vertical).
		- Vertical con vértice en $(h,k)$: $(x−h)^2=4p(y−k)$.
		- Horizontal con vértice en $(h,k)$: $(y−k)^2=4p(x−h)$.
- *Elipse*:
	- Elementos: centro, focos, vértices, covértices, ejes (mayor y menor), lado recto, excentricidad. 
	- Ecuaciones canónicas y ordinarias (horizontal y vertical). 
		- Horizontal con centro en $(h,k)$: $\frac{(x-h)^2}{a^2} + \frac{(y-k)^2}{b^2}=1$ 
		- Vertical con centro en $(h,k)$: $\frac{(x-h)^2}{b^2} + \frac{(y-k)^2}{a^2}=1$
- *Hipérbola*:
	- Elementos: centro, focos, vértices, asíntotas, ejes (transverso y conjugado), lado recto, excentricidad.
	- Ecuaciones canónicas y ordinarias (horizontal y vertical).
		- Horizontal con centro en $(h,k)$: $\frac{(x-h)^2}{a^2} -\frac{(y-k)^2}{b^2}=1$
		- Vertical con centro en $(h,k)$: $\frac{(y-k)^2}{a^2} -\frac{(x-h)^2}{b^2}=1$

---

### 3. Probabilidad y Estadística

**Conceptos clave**  
-  Población, muestra, variable (cualitativa, cuantitativa discreta, cuantitativa continua).
-  Tablas de frecuencias: absoluta, relativa, acumulada.
-  Representaciones gráficas: histograma, polígono de frecuencias, gráfica de barras, gráfica circular, ojiva.
- Espacio muestral y eventos.  
- Probabilidad clásica:  
  $$
    P(A)=\frac{\text{casos favorables}}{\text{casos totales}}
  $$  
- Medidas de tendencia central: media, mediana, moda.  
- Varianza y desviación estándar.  
- Representación gráfica: histograma, diagrama de cajas.

**Fórmulas esenciales**  

| Tema                   | Fórmula                                                       |
|------------------------|---------------------------------------------------------------|
| Media aritmética       | $\bar x = \tfrac{1}{n}\sum_{i=1}^n x_i$                      |
| Varianza               | $\sigma^2 = \tfrac{1}{n}\sum_{i=1}^n (x_i - \bar x)^2$        |
| Desviación estándar    | $\sigma = \sqrt{\sigma^2}$                                  |
| Unión de eventos       | $P(A\cup B) = P(A) + P(B) - P(A\cap B)$                     |

**Ejemplo resuelto**  
Datos: 2, 4, 4, 6, 8  
- Media:  
  $$
  \bar x = \frac{2+4+4+6+8}{5} = 4.8
  $$  
- Varianza:  
  $$
  \sigma^2 = \frac{(2-4.8)^2 + (4-4.8)^2 + \dots + (8-4.8)^2}{5}
           = 4.56
  $$  
- Desviación estándar:  
  $$
  \sigma \approx 2.135
  $$

---

#### Probabilidad
- Conceptos básicos:
	- Conceptos básicos: experimento aleatorio, espacio muestral, evento.
	- Enfoques de la probabilidad: clásico, frecuencial, subjetivo.
	- Técnicas de conteo:
		- Principio fundamental del conteo (multiplicativo y aditivo).
		- Permutaciones (con y sin repetición).
		- Combinaciones.
- Definición axiomática de probabilidad.
- Reglas de probabilidad:
	- Regla de la suma: $P(A \cup B) = P(A) + P(B) - P(A\cap B)$
	- Eventos mutuamente excluyentes $P(A \cup B) = P(A) + P(B)$
	- Probabilidad condicional: $P(A|B)=\frac{P(A\cap B)}{P(B)}$
	- Regla de la multiplicación: $P(A\cap B) = P(B) \cdot P(A|B)$ o $P(A\cap B) = P(A) \cdot P(B|A)$.
	- Eventos independientes: $P(A\cap B) = P(A) \cdot P(B)$  

---
#### Regla de Bayes

**Fórmula**  
$$
P(B \mid A) \;=\; \frac{P(A \mid B)\,P(B)}{P(A)}\quad\text{donde}\quad
P(A)=\sum_i P(A\mid B_i)\,P(B_i).
$$

**Interpretación**  
- $P(B)$: probabilidad a priori de $B$.  
- $P(A\mid B)$: probabilidad de observar $A$ si $B$ ocurre.  
- $P(B\mid A)$: probabilidad a posteriori de $B$ dado que ocurrió $A$.

**Ejemplo resuelto**  
En una prueba de detección:  
- $P(\text{enfermo})=0.02$,  
- sensibilidad $P(\text{+}\mid\text{enfermo})=0.95$,  
- falsos positivos $P(\text{+}\mid\neg\text{enfermo})=0.10$.  

¿Cuál es $P(\text{enfermo}\mid\text{+})$?  

$$
P(\text{enfermo}\mid +)
=\frac{0.95\cdot0.02}{0.95\cdot0.02 + 0.10\cdot0.98}
=\frac{0.019}{0.019 + 0.098}
\approx 0.162.
$$

---

### 4. Análisis de Datos

**Conceptos clave**  
- Recolección y organización de datos.  
- Tablas de frecuencia.  
- Interpretación de gráficas.  
- Correlación y regresión lineal simple.

**Fórmulas esenciales**  

| Tema                       | Fórmula                                                         |
|----------------------------|-----------------------------------------------------------------|
| Coeficiente de correlación | $r = \displaystyle\frac{\sum (x_i-\bar x)(y_i-\bar y)}{\sqrt{\sum (x_i-\bar x)^2\;\sum (y_i-\bar y)^2}}$ |
| Recta de regresión         | $\hat y = a + b\,x$,  
  $$
    b = \frac{\sum(x_i-\bar x)(y_i-\bar y)}{\sum(x_i-\bar x)^2},
    \quad
    a = \bar y - b\,\bar x
  $$

---


### 5. Precálculo

**Conceptos clave**  
- Funciones polinómicas, racionales, exponenciales y logarítmicas.  
- Límites básicos y continuidad.  
- Identidades trigonométricas.  
- Transformaciones de gráficas.

**Fórmulas esenciales**  

| Tema                          | Fórmula / Identidad                                        |
|-------------------------------|-------------------------------------------------------------|
| Exponencial y logaritmo      | $a^x = e^{x\ln a},\;\log_a x = \tfrac{\ln x}{\ln a}$                          |
| Identidades trig.             | $\sin^2\theta + \cos^2\theta = 1$                        |
| Límites conocidos             | $\lim_{x\to0}\tfrac{\sin x}{x}=1, \;\lim_{x\to\infty}(1+\tfrac{1}{x})^x=e$                   |

---

## 📝 Hoja de Trabajo

Resuelve los siguientes ejercicios de práctica.

### Álgebra

1. Factoriza:  
   $$
   x^2 - 5x + 6
   $$
2. Resuelve:  
   $$
   3(x-2) + 4 = 2x + 1
   $$
3. Sistema:  
   $$
   \begin{cases}
   x + 2y = 7\\
   4x - y = 5
   \end{cases}
   $$

### Geometría Analítica

4. Calcula la distancia entre $(-1,3)$ y $(4,-2)$.  
5. Halla la ecuación de la circunferencia con centro $(2,-1)$ y radio $3$.

### Probabilidad y Estadística

6. Se lanza un dado justo. ¿Cuál es la probabilidad de obtener un número par o un múltiplo de 3?  
7. Para los datos 5, 7, 7, 10, 12: calcula media, mediana y moda.

### Análisis de Datos

8. Datos de horas de estudio y calificaciones:  

   | Horas | Calificación |
   |-------|--------------|
   | 2     | 65           |
   | 4     | 78           |
   | 6     | 85           |
   | 8     | 92           |
   | 10    | 96           |

   a) Calcula el coeficiente de correlación $r$.  
   b) Determina la recta de regresión.

### Precálculo

9. Simplifica:  
   $$
   \ln\bigl(e^{3x}\bigr)
   $$
10. Verifica la identidad:  
    $$
    \tan^2\theta + 1 = \sec^2\theta
    $$

---

## 🔑 Clave de Respuestas

1. $(x-2)(x-3)$  
2. $x = 3$  
3.  
   $$
   x = 7 - 2y;\quad
   4(7-2y) - y = 5
   \;\Longrightarrow\;
   9y = 23
   \;\Longrightarrow\;
   y = \tfrac{23}{9},\;
   x = \tfrac{17}{9}
   $$  
4.  
   $$
   d = \sqrt{(4 - (-1))^2 + (-2 - 3)^2}
     = \sqrt{25 + 25}
     = 5\sqrt{2}
   $$  
5.  
   $$
   (x-2)^2 + (y+1)^2 = 9
   $$  
6.  
   - Números pares: $\{2,4,6\}$ → 3 casos  
   - Múltiplos de 3: $\{3,6\}$ → 2 casos  
   - Intersección: $\{6\}$ → 1 caso  
   $$
   P = \frac{3 + 2 - 1}{6} = \frac{4}{6} = \frac{2}{3}
   $$  
7. Datos: 5, 7, 7, 10, 12  
   - Media: $\tfrac{5+7+7+10+12}{5}=8.2$  
   - Mediana: 7  
   - Moda: 7  
8.  
   - $\bar x = 6,\; \bar y = 83.2$  
   -  
     $$
     r \approx 0.992
     $$  
   -  
     $$
     b \approx 4.1,\quad
     a = 83.2 - 4.1\cdot6 \approx 58.6
     $$  
     $\hat y = 58.6 + 4.1x$  
9.  
   $$
   \ln(e^{3x}) = 3x
   $$  
10.  
    $$
    \tan^2\theta + 1
    = \frac{\sin^2\theta}{\cos^2\theta} + \frac{\cos^2\theta}{\cos^2\theta}
    = \frac{1}{\cos^2\theta}
    = \sec^2\theta
    $$




> Written with [StackEdit](https://stackedit.io/).
