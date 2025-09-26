# 📊 Projeto MVP 2025/2 - Machine Learning & Analytics (PUC-Rio)

Este repositório contém o projeto desenvolvido como **MVP (Mínimo Produto Viável)** da Sprint de *Machine Learning & Analytics* da Pós Graduação pela PUC-Rio.  

O objetivo do trabalho é aplicar técnicas de **Ciência de Dados e Aprendizado de Máquina** para analisar e prever o fenômeno de **Attrition (rotatividade de colaboradores)** em uma base de dados corporativa.

O projeto desenvolvido na Sprint anterior foi utilizado como base para desenvolvimento desse MVP. <a href="https://github.com/vitortmoraes/vitormoraes_mvp_2025-1.git">Clique aqui para visualizar o projeto anterior.</a>

---

## 🎯 Objetivo do Projeto
- Definir um problema de **classificação supervisionada**.  
- Preparar e explorar um dataset real, obtido de fonte pública.  
- Construir **modelos de Machine Learning** capazes de prever o risco de desligamento de funcionários.  
- Comparar modelos, avaliar métricas e discutir resultados.  

---

## 📂 Estrutura do Repositório
- `Vitor Moraes | Machine Learning & Analytics (40530010056_20250_01).ipynb` → Notebook principal do projeto.  
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` → Dataset utilizado (em formato `.csv`, carregado via **GitHub RAW**).  
- `README.md` → Este arquivo de apresentação.  

---

## 🛠️ Tecnologias e Bibliotecas
O projeto foi desenvolvido em **Python 3.10+** utilizando o ambiente Google Colab.  

Principais bibliotecas:
- `pandas`, `numpy` → manipulação e análise de dados  
- `matplotlib`, `seaborn` → visualização de dados  
- `scikit-learn` → pré-processamento, modelagem, avaliação de modelos  
- `joblib` → salvamento do modelo final  

---

## 🔍 Metodologia
1. **Coleta e preparação dos dados**  
   - Dataset carregado via URL pública (GitHub RAW).  
   - Limpeza, tratamento de valores ausentes, codificação categórica e normalização.  

2. **Exploração de Dados (EDA)**  
   - Estatísticas descritivas.  
   - Visualizações de distribuição e correlações.  

3. **Modelagem**  
   - Baseline com `DummyClassifier`.  
   - Modelos testados:  
     - Regressão Logística  
     - Random Forest  
     - Gradient Boosting  
   - Uso de **Pipeline + ColumnTransformer** para pré-processamento.  
   - **GridSearchCV** para busca de hiperparâmetros.  

4. **Avaliação**  
   - Métricas: Accuracy, F1-score, ROC AUC.  
   - Visualizações: Matriz de Confusão, Curva ROC.  
   - Discussão sobre overfitting/underfitting e limitações do modelo.  

5. **Conclusão**  
   - Melhor modelo escolhido com base em F1 e AUC.  
   - Insights sobre rotatividade de colaboradores.  
   - Sugestões de próximos passos (uso de SMOTE, ensembles mais robustos, coleta de mais dados).  

---

## 📈 Resultados
- O baseline (`DummyClassifier`) serviu como referência inicial.  
- Modelos baseados em **Random Forest** com ajuste de hiperparâmetros apresentaram melhor desempenho.  
- O modelo final alcançou **boa performance em F1 e ROC AUC**, mostrando capacidade de prever corretamente casos de desligamento.  

---

## ✅ Checklist de Requisitos (PUC-Rio)
- [x] Dataset público via URL  
- [x] Problema de ML definido  
- [x] Exploração e tratamento de dados  
- [x] Baseline implementado  
- [x] Múltiplos modelos comparados  
- [x] Pipeline com ColumnTransformer  
- [x] GridSearchCV aplicado  
- [x] Avaliação com métricas e gráficos  
- [x] Conclusão e análise crítica  
- [x] Checklist final preenchido  

---

## 📌 Como Executar
1. Clone este repositório em sua máquina local:
    ```bash
    git clone https://github.com/vitortmoraes/vitormoraes_mvp_2025-1.git
    ```

2. Abra o **notebook_mvp.ipynb** no **Google Colab** ou em um ambiente local com suporte a Jupyter Notebooks.

3. Execute as células do notebook para reproduzir o trabalho de análise e pré-processamento.

---

## 👨‍💻 Autor
- **Vitor Moraes**  
  <img src="https://i.pinimg.com/1200x/1e/2a/03/1e2a033d11daf6346c6ce1df6f8b2dbb.jpg" alt="Foto de Vitor" width="150" height="150">

- **LinkedIn**: [https://www.linkedin.com/in/vitor-moraes-2801ba340/](https://www.linkedin.com/in/vitor-moraes-2801ba340/)
- **E-mail**: [vitor.tm@gmail.com](mailto:vitor.tm@gmail.com)

## 💡 Agradecimentos

Agradeço ao curso de **Pós Graduação em Ciência de Dados e Analytics** da **PUC-RIO** e aos recursos disponíveis que tornaram este trabalho possível.

---

<img src="https://reari.uff.br/wp-content/uploads/sites/171/2023/09/pucrio.png" alt="Foto de Vitor" width="150" height="150">
