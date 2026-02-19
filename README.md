# Projeto 1: Análise de Churn - Relacionamento com o Cliente

## 🌐 Dashboard Interativ
Criei uma visualização dinâmica para facilitar a identificação dos grupos de risco.
👉 **[[Clique aqui para ver o Gráfico Interativo](https://marcostheuss.github.io/projeto1-analise-de-churn/)**



### 🔎 **Insights Extraídos do Gráfico**

* **Zona de Estabilidade (0-2 contatos):** Clientes que entram em contato poucas vezes possuem a menor taxa de cancelamento.
* **Ponto de Atenção (3 contatos):** É o limite da satisfação. A partir daqui, o índice de cancelamento começa a ganhar corpo.
* **Zona de Risco Crítico (4 ou mais contatos):** Clientes com 4 ou mais contatos apresentam propensão altíssima ao Churn.
* **Taxa de 100% de Cancelamento:** Clientes com **6 contatos** atingem o ápice da insatisfação.


### 💡 **Recomendações Estratégicas**

1.  **Ação Proativa:** Implementar um alerta para o time de retenção assim que um cliente realizar o **3º contato** no ano.
2.  **Melhoria no Suporte:** Analisar o motivo dos contatos repetidos para resolver a **causa raiz** e evitar que o cliente precise ligar novamente.
3.  **Fidelização:** Oferecer benefícios ou revisão de taxas para clientes na **"Zona de Risco"** antes que o 4º contato ocorra.
4.  **Treinamento de Equipe:** Focar em **resolução no primeiro contato (FCR)** para diminuir o atrito do cliente com a marca.

---

### 🛠️ **Tecnologias Utilizadas**

* **Python:** Linguagem principal para o processamento e limpeza de dados.
* **Pandas:** Biblioteca essencial para a manipulação e tratamento da base de dados.
* **Plotly Express:** Ferramenta utilizada para a criação de gráficos interativos e visuais.
* **GitHub Pages:** Plataforma de hospedagem para disponibilizar o dashboard em formato **HTML** de forma pública e acessível.
* **Google Colab:** Ambiente de desenvolvimento em nuvem utilizado para escrever e executar o código.

