# 🧠 Visualización y Comparación de Algoritmos de Ordenamiento en Python

Este proyecto implementa y visualiza cinco algoritmos clásicos de ordenamiento mediante animaciones paso a paso.

## 🔍 Algoritmos incluidos

- 🧼 Bubble Sort
- 🟡 Selection Sort
- 🟢 Insertion Sort
- 🔀 Merge Sort
- ⚡ Quick Sort

Las visualizaciones están diseñadas para fines educativos, facilitando la comprensión del comportamiento de cada algoritmo.

---

## 📊 Comparación de Rendimiento

A continuación se muestra una gráfica comparativa del **tiempo de ejecución** de cada algoritmo al ordenar:

- Una lista de **25 elementos** (misma usada para animaciones).
- Una lista de **1000 elementos** (sin animaciones).

### ⏱️ Tiempos de ejecución (ejemplo)

| 25 elementos | 1000 elementos |
|--------------------------|------------------------------------------|
| ![image](https://github.com/user-attachments/assets/708d97f4-c20b-481a-8e56-c10f1fe6de16) | ![image](https://github.com/user-attachments/assets/4ef4a3a0-feea-42ed-ba6a-75ff413ec034) |
|--------------------------|------------------------------------------|
| ![image](https://github.com/user-attachments/assets/fc4f558c-cc5a-47fc-9b88-b6222a3f6a36) | ![image](https://github.com/user-attachments/assets/3c84451a-ca2a-4132-a2cf-1b622496ad80) |
|--------------------------|------------------------------------------|

> Puedes generar esta gráfica usando `matplotlib` y midiendo el tiempo con `time.perf_counter()`.

---

## 🔢 Algoritmos y Visualizaciones

### 🧼 Bubble Sort

Compara cada par de elementos adyacentes y los intercambia si están en el orden incorrecto. Repite el proceso hasta que la lista esté ordenada.

![image](https://github.com/user-attachments/assets/bb5e93a8-59d7-49d5-8963-6aee30a0da7b)

---

### 🟡 Selection Sort

Encuentra el valor mínimo en cada iteración y lo coloca al principio de la sublista desordenada.



---

### 🟢 Insertion Sort

Toma un elemento de la lista y lo inserta en su posición correcta con respecto a los elementos ya ordenados.

![insertion](https://github.com/tuusuario/tu-repo/blob/main/insertion.png)

---

### 🔀 Merge Sort

Divide la lista en mitades recursivamente, ordena cada mitad, y luego las fusiona ordenadamente.

![merge](https://github.com/tuusuario/tu-repo/blob/main/merge.png)

---

### ⚡ Quick Sort

Elige un pivote, reordena la lista colocando menores a la izquierda y mayores a la derecha, y repite recursivamente en sublistas.

![quick](https://github.com/tuusuario/tu-repo/blob/main/quick.png)

---

## 📦 Requisitos

- Python 3.7+
- `matplotlib`
- `IPython.display` (para animaciones en Jupyter o Google Colab)

Instalación rápida:
```bash
pip install matplotlib
