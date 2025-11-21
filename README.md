# Dynamic-TRADES

**Autores**:
* Jorge Villarreal
* Ademir Muñoz

## Contexto
En este seminario se aborda el problema de <em>trade-off</em> en redes neuronales convolucionales bajo ataques adversariales. Este fenómeno ocurre cuando los métodos de defensa incrementan la robustez del modelo, pero a su vez generan una disminución en la precisión bajo condiciones estándar, limitando la aplicabilidad práctica de estos modelos.

## Propuesta
Se presenta un enfoque basado en el método <strong>TRADES</strong>, donde el parámetro de regularización λ se redefine como una función dinámica dependiente de la entrada. Esto permite que el modelo ajuste de manera adaptativa el peso entre muestras adversariales y estándar, buscando un balance más eficiente entre robustez y precisión.A través de un estudio comparativo de distintos métodos de defensa, se analizan los efectos de este <em>trade-off</em> sobre el rendimiento general del modelo. El objetivo de la propuesta es optimizar el equilibrio entre robustez y precisión, manteniendo competitividad frente a ataques adversariales y considerando métricas de evaluación actuales.
