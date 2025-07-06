# Práctica “Estructuras No Lineales – Ejercicios Arboles"

## 📌 Información General

- **Título:** Estructuras No Lineales – Ejercicios Arboles
- **Asignatura:** Estructura de Datos
- **Carrera:** Computación
- **Estudiante:** Mathias Añazco
- **Fecha:** 06/07/2025
- **Profesor:** Ing. Pablo Torres

---

## 🛠️ Descripción

✅ Ejercicio 01: Inserción en un Árbol Binario de Búsqueda (BST)


- Clase: InsertBST
- Método principal: insert(Node root, int value)


- Descripción:
Este método construye un árbol binario de búsqueda (BST) insertando nodos de forma ordenada. Si el valor a insertar es menor que el nodo actual, se coloca en el subárbol izquierdo; si es mayor o igual, en el derecho.
Se utiliza recursión para recorrer el árbol hasta encontrar la posición correcta.
- Resultado:
Un árbol binario ordenado que permite búsquedas eficientes

🔄 Ejercicio 02: Inversión de un Árbol Binario

- Clase: InvertBST
- Método principal: invertTree(Node root)


- Descripción:
Este método invierte un árbol binario, reflejándolo horizontalmente. Para cada nodo, intercambia sus hijos izquierdo y derecho.
La inversión se realiza de forma recursiva, aplicando el mismo proceso a cada subárbol.
- Resultado:
Un árbol simétrico respecto a su raíz, útil para pruebas de simetría o visualización.


📋 Ejercicio 03: Listar Niveles en Listas Enlazadas

- Clase: ListLevelsBST
- Método principal: listLevels(Node root)


- Descripción:
Este método recorre el árbol por niveles (usando una cola) y agrupa los nodos de cada nivel en una lista enlazada.
Cada nivel del árbol se representa como una LinkedList<Integer>, y todas las listas se almacenan en una lista principal.
- Resultado:
Una estructura tipo List<LinkedList<Integer>> que representa el árbol nivel por nivel.

📏 Ejercicio 04: Calcular la Profundidad Máxima del Árbol

- Clase: MaxDepthBST
- Método principal: maxDepth(Node root)

  
- Descripción:
Este método calcula la profundidad máxima (altura) del árbol binario.
Compara la profundidad de los subárboles izquierdo y derecho de cada nodo y retorna el valor máximo más uno (por el nodo actual).
- Resultado:
Un número entero que indica cuántos niveles tiene el árbol desde la raíz hasta la hoja más profunda.


---

## 🚀 Ejecución

Para ejecutar el proyecto:

1. Compila el código:
    ```bash
    javac App.java
    ```
2. Ejecuta la aplicación:
    ```bash
    java App
    ```

---

## 🧑‍💻 Ejemplo de Salida
```plaintext
Ejercicio 01: Inserción en un Árbol Binario de Búsqueda (BST)

Árbol binario:
5 3 7 2 4 6 8
Recorrido en orden:
2 3 4 5 6 7 8

Ejercicio 02: Inversión de un Árbol Binario

Árbol binario original:
2 3 4 5 6 7 8
Árbol binario invertido:
8 7 6 5 4 3 2

Ejercicio 03: Listar Niveles en Listas Enlazadas

Nivel 0: 5 -> null
Nivel 1: 7 -> 3 -> null
Nivel 2: 8 -> 6 -> 4 -> 2 -> null

Ejercicio 04: Calcular la Profundidad Máxima del Árbol

Profundidad máxima del árbol: 3
```

---
## 🚀 Vista Previa
![Image](https://github.com/Mathias-Anazco/imagenEst/blob/main/Captura%20de%20pantalla%202025-07-06%20110958.png?raw=true)
