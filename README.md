
# 📊 Avaliação de Modelos de Classificação

Este projeto demonstra como calcular métricas de avaliação de desempenho de modelos de classificação
utilizando a **matriz de confusão**.

As métricas implementadas são:
- **Acurácia**
- **Precisão**
- **Sensibilidade (Recall)**
- **Especificidade**
- **F1-Score**

---

## 🔎 Matriz de Confusão

A matriz de confusão compara os **valores reais** com as **previsões** do modelo.

|                | Previsto Positivo | Previsto Negativo |
|----------------|------------------|------------------|
| **Real Positivo** | VP (Verdadeiro Positivo) ✅ | FN (Falso Negativo) ❌ |
| **Real Negativo** | FP (Falso Positivo) ❌ | VN (Verdadeiro Negativo) ✅ |

- **VP (True Positive)** → O modelo disse "positivo" e era positivo.  
- **VN (True Negative)** → O modelo disse "negativo" e era negativo.  
- **FP (False Positive)** → O modelo disse "positivo" mas era negativo.  
- **FN (False Negative)** → O modelo disse "negativo" mas era positivo.  

---

## 📐 Fórmulas das Métricas

- **Acurácia** = (VP + VN) / (VP + VN + FP + FN)  
- **Precisão** = VP / (VP + FP)  
- **Recall (Sensibilidade)** = VP / (VP + FN)  
- **Especificidade** = VN / (VN + FP)  
- **F1-Score** = 2 × (Precisão × Recall) / (Precisão + Recall)  

---

## 📂 Estrutura do Repositório

- `Metrics_Code.ipynb` → Notebook com o código organizado.  
- `README.md` → Arquivo explicativo com teoria e instruções.  

---

## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   cd seu-repo
   ```

2. Abra o Jupyter Notebook ou Google Colab.

3. Execute o arquivo:
   ```bash
   jupyter notebook Metrics_Code.ipynb
   ```

---

## ✅ Exemplo de Saída

O código gera:
- A matriz de confusão plotada com **Seaborn**.  
- As métricas calculadas no console.

Exemplo de saída esperada:

```
Acurácia: 0.87
Precisão: 0.86
Recall (Sensibilidade): 0.85
Especificidade (média): 0.90
F1-Score: 0.85
```

---

✍️ Autor: *KARMA*
