# 🏆 Desafio Machine Learning - Previsão de Preço de Fórmulas Manipuladas  

Este repositório contém a solução do **Desafio de Machine Learning**, onde o objetivo é prever o preço correto (`correto`) de fórmulas manipuladas a partir de um conjunto de dados fornecido.  

---

## 📂 Estrutura do Repositório  

📁 **desafio-machine-learning/**  
├── 📜 `desafio_ml_solucao.ipynb` → **Notebook principal do projeto**  
├── 📜 `dashboard.pbix` → **Arquivo final do Power BI**  
├── 📜 `Relatorio_Tecnico.pdf` → **Relatório técnico do desafio**  
├── 📜 `README.md` → **Documentação principal do repositório**  
├── 📜 `requirements.txt` → **Lista de bibliotecas Python necessárias**  

---

## 🎯 Objetivo do Desafio  

Prever o valor da coluna `correto` com o **menor erro possível**, utilizando **modelos de Machine Learning** e analisando os resultados com um **dashboard no Power BI**.  

📌 **Detalhes do dataset:**  
- **Total de registros:** 7.121  
- **Treinamento:** **5.121** dados  
- **Teste:** **2.000** dados  
- **Ferramentas utilizadas:** Python (Jupyter Notebook) e Power BI  

---

## 🛠️ Tecnologias Utilizadas  

### 📌 **Linguagens e Bibliotecas**  
- **Python** → Manipulação de dados e treinamento de modelos  
- `pandas` | `numpy` | `scikit-learn` | `xgboost` | `matplotlib` | `seaborn`  

### 📊 **Ferramentas de Visualização**  
- **Power BI** → Análise e visualização dos resultados  

---

## 📊 Modelos de Machine Learning Utilizados  

Foram testados **três modelos de regressão supervisionada**, e o melhor desempenho foi:  

| Modelo                        | RMSE ↓  *(Quanto menor, melhor)* |  
|--------------------------------|-----------------|  
| 🏆 **Gradient Boosting Regressor** | 🚀 **9.6370**  (**Melhor Modelo**) |  
| XGBoost Regressor              | 9.6557 |  
| Random Forest Regressor        | 10.1629 |  

📌 **Métrica utilizada:** **Root Mean Squared Error (RMSE)** → Mede o erro médio da previsão do modelo.  

---

## 📈 Dashboard no Power BI  

O Power BI foi utilizado para análise dos dados e validação dos resultados do modelo.  

### **📊 Visões Criadas:**  
✅ **Relação entre preço pré-calculado e preço correto**  
✅ **Distribuição do erro absoluto**  
✅ **Média do erro absoluto por quantidade de insumos**  
✅ **Evolução do erro percentual ao longo do tempo**  
✅ **KPIs: RMSE e Erro Médio Absoluto**  

🖼️ **Imagem do Dashboard Final:**  
![Dashboard Power BI](dashboard_final.png) *(Substituir pelo link correto da imagem se necessário)*  

---

## 🚀 Como Executar o Projeto?  

### **1️⃣ Clonar o Repositório**  
```sh
git clone https://github.com/seu-usuario/desafio-machine-learning.git
cd desafio-machine-learning

### **2️⃣ Instalar Dependências**

```sh
pip install -r requirements.txt
```

### **3️⃣ Executar o Notebook no Jupyter**

```sh
jupyter notebook
```

- Abra **notebooks/desafio_ml_solucao.ipynb**
- Execute todas as células para gerar os resultados

---

## 📤 Como Abrir o Dashboard no Power BI?

1. Baixe o arquivo `pbix/dashboard.pbix`
2. Abra no Power BI Desktop
3. Explore os gráficos e métricas 📊

---

## 📬 Contato

📧 Caso tenha dúvidas ou sugestões, entre em contato pelo GitHub.

---

✅ **Projeto 100% reprodutível e documentado.**  
🚀 **Pronto para análise e melhorias!** 🔥


