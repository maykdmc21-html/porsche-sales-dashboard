# 🏎️ Porsche Sales Performance Dashboard

Dashboard interativa desenvolvida em HTML/JS com Chart.js para análise de desempenho de vendas sanitizadas da Porsche.

🔗 **Link da Dashboard no GitHub Pages:** [https://seu-usuario.github.io/seu-repositorio/](https://seu-usuario.github.io/seu-repositorio/)

---

## 📌 Perguntas de Negócio Respondidas

1. **Qual modelo gera a maior receita total?**
   - *Objetivo:* Identificar os modelos de maior impacto financeiro no portfólio de vendas.
2. **Quais são os métodos de pagamento predominantemente utilizados?**
   - *Objetivo:* Mapear o comportamento e preferência financeira dos clientes de alto padrão.
3. **Como a receita de vendas está distribuída por Estado (UF)?**
   - *Objetivo:* Avaliar a penetração regional da marca e orientar estratégias de marketing.

---

## 🛠️ Tratamento de Dados Realizado

- **Limpeza:** Remoção de colunas redundantes e não sanitizadas.
- **Filtragem:** Exclusão/Tratamento de registros corrompidos/inválidos na data e valores de venda.
- **Padronização:** Formatação de valores numéricos para preço (`SalesPriceSanitized`) e modelo (`PorscheModelSanitized`).

---

## 🤖 Engenharia de Prompt e Ferramentas

- **Ferramentas utilizadas:** ChatGPT com Canvas para prototipação do código Front-end.
- **Evolução do Prompt:** A primeira versão do prompt gerava gráficos estáticos. Adicionei a instrução explícita de escutadores de eventos (`change` event listeners) no JS para recalcular os dados do array filtrado em tempo real e re-renderizar os gráficos do Chart.js.