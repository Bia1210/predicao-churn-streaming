# 📈 Relatório Técnico de Ciência de Dados com Foco em Negócio (Data-Driven Business Report)

**Projeto:** Sistema Inteligente de Predição de Cancelamento de Assinaturas (Churn)  
**Equipe:** Beatriz C. Melo, Flávia R. B. Melo, Renan Cunha  
**Orientação:** Profª. Joelma Benicio de Lima Printes  
**Contexto:** Curso Técnico de Nível Médio em Inteligência Artificial — Disciplina de Python para Ciência de Dados  

---

## 1. Sumário Executivo
Este relatório apresenta a análise preditiva e os insights estratégicos extraídos da base de clientes da plataforma de streaming. O objetivo central é identificar antecipadamente o risco de cancelamento de assinaturas (*churn*) para permitir intervenções direcionadas de retenção, reduzindo o custo de aquisição de novos clientes (CAC) e aumentando o valor do tempo de vida do cliente (LTV).

---

## 2. O Problema de Negócio
- **Desafio:** A perda contínua de assinantes impacta diretamente a receita recorrente da plataforma.
- **Objetivo Estratégico:** Construir um modelo preditivo capaz de sinalizar clientes com alta probabilidade de cancelamento antes que a assinatura expire.
- **Métrica Chave de Negócio:** Redução da taxa de *churn* mensal e otimização do ROI em campanhas de retenção.

---

## 3. Análise Exploratória e Insights de Negócio
Com base no processamento e cruzamento das variáveis do dataset, identificamos os seguintes padrões comportamentais e demográficos:

* **Perfil Demográfico:** *(Insira aqui o perfil predominante identificado, ex: faixa etária, renda ou estado civil com maior índice de cancelamento)*.
* **Comportamento de Consumo:** *(Insira aqui descobertas sobre o uso, ex: preferência de legenda/dublagem, controle parental ou tipo de plano)*.
* **Gargalos Identificados:** *(Ex: clientes em determinada faixa de renda ou com determinados perfis apresentam maior volatilidade)*.

---

## 4. Metodologia Científica e Modelagem
1. **Tratamento de Dados:** Limpeza, codificação de variáveis categóricas e normalização de atributos contínuos.
2. **Algoritmos Avaliados:** *(Ex: Regressão Logística, Árvore de Decisão, Random Forest)*.
3. **Métricas de Avaliação do Modelo:**
   * **Acurácia:** *(Insira a acurácia %)*
   * **Recall (Sensibilidade):** *(Métrica crucial para garantir que o máximo de clientes prestes a cancelar sejam identificados)*
   * **Precisão / F1-Score:** *(Métrica de equilíbrio entre falsos positivos e falsos negativos)*

---

## 5. Recomendações Estratégicas para o Negócio
Com base nos resultados obtidos, recomendamos as seguintes ações para a equipe de Marketing e Produto:

1. **Campanhas Preventivas Segmentadas:** Enviar ofertas de renovação personalizada para o segmento de clientes sinalizado como alto risco pelo modelo.
2. **Melhoria da Experiência da Plataforma:** Ajustar o catálogo ou recursos (como legenda/dublagem e perfis de renda) de acordo com as preferências dos grupos com maior tendência ao cancelamento.
3. **Monitoramento Contínuo:** Integrar o modelo preditivo ao sistema da empresa para gerar alertas automáticos mensais.

---

## 6. Próximos Passos
- Implementação de técnicas de *Feature Engineering* para capturar hábitos de uso em tempo real.
- Teste de novos algoritmos de *Ensemble* ou Redes Neurais para maximizar a métrica de *Recall*.
