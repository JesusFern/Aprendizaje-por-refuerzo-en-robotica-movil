# Aprendizaje por Refuerzo en Robótica Móvil

## 📌 Descripción  
Proyecto que implementa **Q-Learning**, **Monte Carlo** y **SARSA** para entrenar un robot móvil en entornos con obstáculos. El objetivo es navegar desde un punto inicial hasta un destino optimizando políticas de movimiento.

## 👥 Autores  
- **Jesús Fernández Rodríguez**  
  `jesferrod1, jesferrod1@gmail.com`  
- **Enrique Pérez Milla**  
  `enrpermil, enrique.perez.milla@gmail.com`  
_Universidad de Sevilla, España_  

## ⚙️ Métodos  
| Algoritmo      | Implementación | Parámetros clave |  
|----------------|----------------|------------------|  
| **Q-Learning** | `mdptoolbox`   | Iteraciones (10k-100M), γ=0.9 |  
| **Monte Carlo**| Custom (Python)| Primera/cada visita, γ=0.9, 1k iter |  
| **SARSA**      | Custom (Python)| ε-voraz, α=0.5, γ=0.9 |  

## 📊 Resultados  
- **Q-Learning**: Políticas más precisas con iteraciones altas (ej. 100M).  
- **Monte Carlo**: Diferencias mínimas entre variantes por limitación computacional.  
- **SARSA**: Sensible a α, pero requiere más iteraciones para converger.  

## 🔍 Conclusiones  
- ✅ Algoritmos aplicables a problemas reales.  
- ⚠️ **Alto costo computacional**: Necesidad de optimización o hardware avanzado.  

## 📚 Referencias  
- [`mdptoolbox`](https://pymdptoolbox.readthedocs.io)  
- Sutton & Barto, *Reinforcement Learning: An Introduction* (MIT Press, 2018).  
