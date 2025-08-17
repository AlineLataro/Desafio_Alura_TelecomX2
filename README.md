# 📊 Challenge TelecomX_2  
## Análise Preditiva de Evasão de Clientes  

Este repositório apresenta a solução do desafio **Telecom X**, cujo objetivo é aplicar técnicas de Machine Learning para prever a evasão de clientes e identificar os principais fatores que levam ao cancelamento dos serviços.  

---

## 🎯 Objetivo  

A Telecom X enfrenta elevados índices de cancelamento e busca:  

- **Coletar, tratar e preparar** os dados dos clientes.  
- **Analisar e explorar** os dados para compreender o comportamento dos usuários.  
- **Construir modelos preditivos** capazes de identificar clientes com maior risco de evasão.  
- Fornecer **insights estratégicos** que auxiliem na redução da evasão e no aumento da retenção.  

---

## 🧹 Limpeza e Tratamento de Dados  

As principais etapas executadas foram:  

- ✅ Importação e tratamento de dados, com transformação de variáveis categóricas e numéricas.  
- ✅ Remoção de valores ausentes e padronização.  
- ✅ Análise de correlação para seleção e exclusão de variáveis redundantes.  
- ✅ Preparação final dos dados para modelagem preditiva.  

---

## 🔍 Análise Exploratória e Modelagem Preditiva  

- **Proporção de evasão:** ~25,8% dos clientes cancelaram os serviços.  
- **Modelos testados:** Regressão Logística e Random Forest
- **Melhor desempenho:** Regressão Logística, com métricas:  
  - Acurácia: **75%**  
  - Precisão: **91%**  
  - Recall: **73%**  
  - F1-Score: **81%**  

- **Variáveis mais relevantes:**  
  - **Tempo de Contrato** → clientes com contratos curtos apresentam maior risco.  
  - **Valor Mensal** → valores mais altos estão associados à evasão.  
  - **Serviços adicionais** como segurança online e backup também mostraram impacto.  

---

## ✅ Recomendações Estratégicas  

- Implementar **ações de retenção personalizadas** para clientes com contratos curtos e valores mensais elevados.  
- Oferecer **pacotes promocionais e descontos progressivos** para aumentar a fidelização.  
- Utilizar o modelo de **Regressão Logística em monitoramento contínuo**, permitindo identificar e intervir proativamente em clientes com alto risco de cancelamento.  

---

## 🔧 Tecnologias e Ferramentas  

- Python 3.10+  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab

---

## ✍️ Autor  

Projeto desenvolvido por **Aline Lataro** como parte de um desafio de análise de dados no setor de telecomunicações.  

---

## 📝 Licença  

Projeto desenvolvido para fins **educacionais**.  
