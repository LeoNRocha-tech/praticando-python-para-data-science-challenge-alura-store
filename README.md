# Análise de Dados - Alura Store

**Objetivo:** Recomendar qual loja deve ser vendida com base em dados estratégicos de faturamento, categorias, avaliações e custos operacionais.

---

## 🎯 Propósito da Análise
Esta análise avalia o desempenho de **4 lojas** da rede Alura Store para identificar qual delas oferece o melhor custo-benefício para venda. Foram considerados:

1. **Faturamento total** por loja.
2. **Desempenho por categoria** de produtos.
3. **Avaliação média** dos clientes.
4. **Produtos mais/menos vendidos**.
5. **Custo de frete médio**.

---

## 📊 Dados Analisados

### 1. Faturamento por Loja (R$)
| Loja   | Valor            |
|--------|------------------|
| Loja 1 | 1.534.509,12     |
| Loja 2 | 1.488.459,06     |
| Loja 3 | 1.464.025,03     |
| Loja 4 | 1.384.497,58     |

**Insight:**  
- Loja 1 tem o **maior faturamento**, mas a diferença para a Loja 2 é de apenas 3%.

---

### 2. Categorias Mais Vendidas
| Categoria           | Loja 1 | Loja 2 | Loja 3 | Loja 4 |
|----------------------|--------|--------|--------|--------|
| Móveis               | 465    | 442    | 499    | 480    |
| Eletrônicos          | 448    | 422    | 451    | 451    |
| Brinquedos           | 324    | 313    | 315    | 338    |

**Padrões:**  
- **Móveis** e **Eletrônicos** são as categorias líderes em todas as lojas.
- Loja 4 tem baixo desempenho em **Eletrodomésticos** (254 unidades).

---

### 3. Avaliação Média dos Clientes
| Loja   | Nota (0-5) |
|--------|------------|
| Loja 1 | 3.98       |
| Loja 2 | 4.04       |
| Loja 3 | 4.05       |
| Loja 4 | 4.00       |

**Insight:**  
- Loja 3 tem a **melhor avaliação**, enquanto a Loja 1 tem a pior, apesar de liderar em faturamento.

---

### 4. Frete Médio (R$)
| Loja   | Custo       |
|--------|-------------|
| Loja 1 | 34,69       |
| Loja 2 | 33,62       |
| Loja 3 | 33,07       |
| Loja 4 | 31,28       |

**Correlação:**  
- Lojas com **fretes mais altos** tendem a ter **avaliações mais baixas** (ex: Loja 1).

---
## 🚀 Como Reproduzir a Análise

   **Passos**:
- Clone o repositório.
- Execute o Jupyter Notebook `analise_lojas.ipynb`.
- Siga as células sequencialmente para gerar gráficos e tabelas.

## 📌Conclusões
A **Loja 1** é a recomendada para venda devido ao seu **alto faturamento**, mas apresenta riscos como **baixa avaliação** e **custos de frete elevados**. Detalhes completos estão no projeto.
