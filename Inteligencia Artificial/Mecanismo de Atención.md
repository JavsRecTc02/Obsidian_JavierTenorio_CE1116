---
Fecha de creación: 2026-03-14 13:45
Fecha de Modificación: 2026-03-14 13:45
tags: 
Tema:
---


## 📚 Idea/Concepto 

Esta es una técnica que permite a un modelo identificar la relevancia entre elementos de una secuencia. A partir de representaciones iniciales, se generan vectores Query, Key y Value mediante matrices de pesos aprendibles ($W_q, W_k, W_v$). La similitud entre Query y Key se calcula mediante un producto escalar escalado $\frac{QK^T}{\sqrt{d_k}}$ y se normaliza con la función softmax para obtener los pesos de atención. Estos pesos se utilizan para producir una suma ponderada de los vectores Value, generando representaciones contextualizadas que capturan dependencias entre los elementos de la secuencia.
## 📌 Puntos Claves (Opcional)
- Relevancia entre elementos
- Generación de vectores Query, Key y Value
- Función de softmax
- Representaciones contextualizadas

## 🔗 Connections
- [[Embeddings]]
- [[Ventana de Contexto]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 