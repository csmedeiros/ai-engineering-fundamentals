# Ep. 03 — Memoria de conversación, ventana de contexto y ventana deslizante

**Language:** es

## Tema

Por qué el modelo olvida entre calls, cómo armar historial, qué es context length exceeded y la mitigación mínima: **ventana deslizante**.

**Linear:** [CM-43](https://linear.app/caiomedeiros/issue/CM-43)

## Progresiones del notebook

1. Calls aisladas → olvida
2. Lista de historial → recuerda
3. Crecer hasta context length exceeded
4. Ventana deslizante → descarta lo antiguo, mantiene lo reciente

## Layout

- `notebooks/03-conversation-memory-sliding-window.ipynb`

