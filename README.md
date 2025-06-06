# PRIMER EXAMEN PARCIAL  
## ASIGNATURA: Motores y Tractores Agrícolas

**Nombre:**  
**Grupo:** Sexto Año  
**Fecha:** 7 de Junio 2025  

---

## Enunciado

> **Calcular la presión y temperatura máxima del ciclo de trabajo de un motor diésel no sobrealimentado que posee los siguientes parámetros:**
>
> - Relación de compresión: **ε = 16.5**
> - Exceso de aire: **α = 1.4**
> - Poder calorífico inferior: **Hu = 42,500 kJ/kg**
> - Presión fin de compresión: **Pc = 5.0 MPa**
> - Temperatura fin de compresión: **Tc = 940 K**
> - Gases residuales: **γT = 0.033**
> - Moles antes de combustión: **M₁ = 0.699 kmol**
> - Moles después de combustión: **M₂ = 0.727 kmol**
> - Moles CO₂: **Mco₂ = 0.0725 kmol**
> - Moles H₂O: **Mazo = 0.063 kmol**
> - Moles NO: **N₀ = 0.0416 kmol**
> - Moles O₂: **M₀ = 0.55 kmol**
> - Relación de combustión: **λ = 1.8**
> - Eficiencia de combustión: **ξ = 0.82**
> - Exponente politrópico: **n₂ = 1.24**
> - Rendimiento mecánico: **η = 0.92**
>
> **Además, determine la presión y temperatura al final de la expansión, considerando n₂ = 1.24, así como la presión media indicada del motor.**

---

## 1. Presión y Temperatura Máxima del Ciclo

### **Fórmulas utilizadas**

- **Presión máxima (ciclo Diesel, método simplificado):**
  \[
  p_z = P_c
  \]
- **Temperatura máxima:**
  \[
  T_z = \frac{\lambda \cdot M_1 \cdot T_c}{M_2}
  \]

### **Cálculos**

- \(\lambda \cdot M_1 = 1.8 \times 0.699 = 1.2582\)
- \(1.2582 \times 940 = 1,183.708\)
- \(T_z = \frac{1,183.708}{0.727} = 1,627.8\) K

**Resultados:**
- **Presión máxima del ciclo:**  
  \[
  \boxed{p_z = 5.00\ \text{MPa}}
  \]
- **Temperatura máxima del ciclo:**  
  \[
  \boxed{T_z = 1,628\ \text{K}}
  \]

---

## 2. Presión y Temperatura al Final de la Expansión

### **Fórmulas utilizadas**

- \(\delta = \frac{\varepsilon}{\lambda}\)
- \(T_b = \frac{T_z}{\delta^{(n_2-1)}}\)
- \(p_b = \frac{p_z}{\delta^{n_2}}\)

### **Cálculos**

- \(\delta = \frac{16.5}{1.8} = 9.1667\)
- \(\delta^{n_2-1} = 9.1667^{0.24} = 1.701\)
- \(T_b = \frac{1,627.8}{1.701} = 957.4\) K
- \(\delta^{n_2} = 9.1667^{1.24} = 15.59\)
- \(p_b = \frac{5.0}{15.59} = 0.32\) MPa

**Resultados:**
- **Temperatura al final de la expansión:**  
  \[
  \boxed{T_b = 957\ \text{K}}
  \]
- **Presión al final de la expansión:**  
  \[
  \boxed{p_b = 0.32\ \text{MPa}}
  \]

---

## 3. Presión Media Indicada del Motor (\(p_{mi}\))

### **Fórmula utilizada**

\[
p_{mi} = \frac{p_z - p_b}{n_2 - 1} \cdot \eta
\]

- \(p_z = 5.0\) MPa
- \(p_b = 0.32\) MPa
- \(n_2 = 1.24\)
- \(\eta = 0.92\)

### **Cálculo**

- \(p_z - p_b = 5.0 - 0.32 = 4.68\)
- \(n_2 - 1 = 0.24\)
- \(\frac{4.68}{0.24} = 19.5\)
- \(p_{mi} = 19.5 \times 0.92 = 17.98\) MPa

**Resultado:**
- **Presión media indicada del motor:**  
  \[
  \boxed{p_{mi} = 18.0\ \text{MPa}}
  \]
  (redondeado a un decimal)

---

## **Resumen de Resultados**

| Magnitud / Variable                  | Valor   | Unidad |
|--------------------------------------|---------|--------|
| Presión máxima ciclo (\(p_z\))       | 5.00    | MPa    |
| Temperatura máxima ciclo (\(T_z\))   | 1,628   | K      |
| Temp. fin expansión (\(T_b\))        | 957     | K      |
| Presión fin expansión (\(p_b\))      | 0.32    | MPa    |
| Presión media indicada (\(p_{mi}\))  | 18.0    | MPa    |

---

**Notas:**  
- Se utilizaron únicamente las fórmulas simplificadas que solicita el profesor.
- Todos los cálculos intermedios están explicados y los resultados están redondeados según criterio académico.
- ![image1](image1) corresponde al enunciado original del examen.
