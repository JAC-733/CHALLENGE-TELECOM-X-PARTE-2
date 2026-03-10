# CHALLENGE-TELECOM-X-PARTE-2
Challenge Telecom X Parte 2
# Predicción de Cancelación de Clientes (Churn)

## Descripción
Este proyecto tiene como objetivo desarrollar modelos de **Machine Learning** para predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones.  
El análisis permite identificar los factores que influyen en la cancelación y proponer estrategias de retención para mejorar la satisfacción y fidelidad del cliente.

---

## Objetivos
- Predecir qué clientes tienen mayor riesgo de cancelar el servicio.
- Identificar los factores más importantes que afectan la cancelación.
- Proponer estrategias basadas en los resultados para reducir la pérdida de clientes.

---

## Modelos Utilizados
Se implementaron dos modelos de clasificación supervisada:

1. **KNN (K-Nearest Neighbors)**
2. **Random Forest**

Se utilizó **GridSearchCV** para optimizar hiperparámetros y las métricas de evaluación fueron:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de Confusión

---

## Resultados
- **Random Forest** presentó mejor desempeño que KNN, capturando relaciones más complejas entre las variables.
- Factores clave de cancelación identificados:
  - Baja antigüedad del cliente.
  - Contratos de corta duración.
  - Cargos mensuales elevados.
  - Falta de servicios adicionales.

---

## Estrategias de Retención
Basadas en los resultados del análisis:

- Implementar programas de fidelización para clientes nuevos.
- Ofrecer incentivos a contratos a largo plazo.
- Optimizar planes con cargos elevados para mejorar el valor percibido.
- Utilizar modelos predictivos para ofrecer promociones a clientes en riesgo.

---

## Conclusión
La predicción de cancelación mediante modelos de ML permite a la empresa anticipar la pérdida de clientes y tomar decisiones proactivas.  
Random Forest fue el modelo más efectivo y los factores contractuales y económicos resultaron ser los principales determinantes del churn.

---

## Estructura del Proyecto
