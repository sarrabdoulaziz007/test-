# TP1 - MNIST

## Objectif
Comparer différentes fonctions d'activation.

## Input
- Images MNIST 28x28
- 10 classes (0-9)

## Output
- Classe prédite
- Accuracy du modèle

## Code

```python
model.compile(
    optimizer='adam',
    loss='categorical_crossentropy',
    metrics=['accuracy']
)
