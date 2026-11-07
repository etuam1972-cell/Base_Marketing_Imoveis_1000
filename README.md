# 🏠 ANÁLISE DE DADOS PARA COMPRA DE UM IMÓVEL
### 📊 Marketing Analytics | Data Analytics | Information Value (IV) | Excel | Power BI

**Projeto acadêmico | Base sintética criada com auxílio de IA generativa | 1.000 clientes**

---

## 🎯 1. Objetivo do Projeto

Investigar os fatores associados à decisão de compra de um imóvel, utilizando uma base de dados sintética com informações de 1.000 clientes.

O objetivo foi identificar quais características pessoais, financeiras, comportamentais e relacionadas às campanhas de marketing apresentam maior associação com a aquisição ou não de um imóvel.

A proposta foi transformar dados de clientes e interações comerciais em informações capazes de apoiar a compreensão do comportamento de compra e a identificação de potenciais oportunidades de melhoria nas estratégias de marketing e vendas.

### 📌 Indicador geral da base

<text>**1.000 clientes analisados**</text>

<text>**135 imóveis adquiridos**</text>

<text>**13,5% de conversão observada na base**</text>

---

## 🗄️ 2. Variáveis analisadas

A base contempla informações demográficas, socioeconômicas, financeiras, comportamentais e comerciais.

### 👤 Perfil demográfico e familiar

- Idade.
- Profissão.
- Escolaridade.
- Estado civil.
- Possuir filhos.
- Quantidade de filhos.
- Região do país onde reside.

### 💰 Perfil financeiro

- Salário mensal.
- Existência de dívidas.
- Percentual de endividamento.
- Score de crédito.
- Tempo de emprego em anos.
- Possuir imóvel atualmente.
- Valor disponível para entrada.
- Interesse em financiamento.

### 📣 Marketing e comportamento do cliente

- Canal de marketing utilizado no contato.
- Número de impressões em anúncios.
- Número de cliques em anúncios.
- Número de visitas ao site.
- Número de downloads de materiais.
- Número de contatos com o corretor.
- Número de visitas aos imóveis.
- Satisfação com o atendimento.

### 🏡 Características da intenção de compra

- Urgência da compra.
- Tipo de imóvel de interesse.
- Faixa de preço desejada.
- Distância entre o imóvel e o local de trabalho.
- Decisão final: compra ou não compra.

---

## 📊 3. Preparação e Classificação das Variáveis

📌 **Objetivo:** identificar a natureza de cada variável para selecionar técnicas estatísticas adequadas.

Foi realizada uma classificação das variáveis considerando seus tipos e características.

### 🔢 Tipos de variáveis avaliadas

- **Quantitativas contínuas:** salário, percentual de endividamento, valor de entrada e distância.
- **Quantitativas discretas:** idade, quantidade de filhos, cliques, visitas e contatos.
- **Qualitativas nominais:** profissão, região, canal de marketing e tipo de imóvel.
- **Qualitativas ordinais:** escolaridade, satisfação e urgência da compra.
- **Variável dependente:** aquisição ou não do imóvel.

Essa etapa foi importante para orientar a escolha das análises e evitar a aplicação indiscriminada de técnicas estatísticas em variáveis com naturezas diferentes.

---

## 🔍 4. Análise Exploratória – Compra x Não Compra

📌 **Objetivo:** investigar individualmente o comportamento de cada variável em relação à decisão de compra.

Foi criada uma aba de resumo com a quantidade de clientes que adquiriram ou não o imóvel.

Posteriormente, cada variável foi analisada individualmente, buscando identificar diferenças de comportamento entre os dois grupos.

### 📈 Abordagens utilizadas

- Distribuição dos clientes por categoria.
- Comparação entre compradores e não compradores.
- Análise de médias, medianas e percentis.
- Distribuição de variáveis financeiras.
- Avaliação de comportamento de marketing.
- Identificação de possíveis padrões de compra.

A análise exploratória permitiu compreender melhor o perfil dos clientes e identificar variáveis que mereciam uma investigação estatística mais aprofundada.

---

## 🧮 5. Information Value (IV) – Poder de Separação das Variáveis

📌 **Objetivo:** avaliar o poder de separação das variáveis em relação à decisão de compra ou não compra do imóvel.

Foi utilizada a técnica **Information Value (IV)**, frequentemente aplicada em análises de risco de crédito e modelagem de comportamento para avaliar a capacidade de uma variável distinguir dois grupos.

O IV permite identificar quais variáveis apresentam maior poder de separação entre clientes que compraram e clientes que não compraram.

### 📊 Classificação utilizada

| Information Value | Interpretação |
|---|---|
| Abaixo de 0,02 | Muito fraco |
| 0,02 a 0,10 | Fraco |
| 0,10 a 0,30 | Médio |
| 0,30 a 0,50 | Forte |
| Acima de 0,50 | Suspeito ou potencialmente excessivo |

A classificação é uma referência prática e deve ser interpretada considerando o contexto, a qualidade dos dados e a forma de agrupamento das variáveis.

### 🏆 Principais resultados

<text weight="semibold" color="secondary" size="sm">VARIÁVEIS COM IV MÉDIO</text>

| Variável | IV | Classificação |
|---|---:|---|
| 💰 Salário mensal | 0,20 | Médio |
| 💳 Score de crédito | 0,20 | Médio |
| 🏦 Valor de entrada | 0,22 | Médio |

<text weight="semibold" color="secondary" size="sm">VARIÁVEIS COM IV FORTE</text>

| Variável | IV | Classificação |
|---|---:|---|
| 📉 Percentual de endividamento | 0,35 | Forte |
| ⭐ Satisfação com atendimento | 0,30 | Forte |

Esses resultados destacaram cinco variáveis relevantes para investigar a separação entre os grupos de compradores e não compradores.

---

## 💰 6. Análise Financeira – Salário, Crédito e Valor de Entrada

📌 **Objetivo:** investigar como a capacidade financeira dos clientes pode estar associada à decisão de compra.

### Salário mensal

- 75% dos clientes possuíam salário mensal de até **R$ 7.706,21**.
- 50% possuíam salário mensal de até **R$ 5.407,04**.
- IV: **0,20 – Médio**.

A distribuição salarial demonstra a importância de considerar a capacidade financeira dos clientes em relação às faixas de preço dos imóveis ofertados.

### Score de crédito

- 75% dos clientes apresentavam score de até **695 pontos**.
- 50% apresentavam score de até **645 pontos**.
- IV: **0,20 – Médio**.

O score foi investigado como uma variável associada ao perfil de crédito e à possível capacidade de obtenção de financiamento.

### Valor de entrada

- Valor médio disponível: **R$ 42.125,48**.
- 73,7% possuíam no máximo **R$ 54.096,63**.
- IV: **0,22 – Médio**.

A elevada variabilidade dos valores disponíveis para entrada demonstra a importância de analisar a capacidade financeira individual em conjunto com a faixa de preço do imóvel desejado.

**📌 Interpretação:** salário, score de crédito e valor de entrada apresentaram poder de separação médio. Em conjunto, ajudam a investigar possíveis limitações financeiras associadas à não aquisição do imóvel.

---

## 📉 7. Análise de Endividamento e Satisfação com Atendimento

📌 **Objetivo:** investigar duas variáveis que apresentaram maior poder de separação na análise de IV.

### Percentual de endividamento

<badge color="success">IV 0,35 – Forte</badge>

- Média de endividamento: **10,34%**.
- 75% dos clientes apresentavam endividamento de até **18,1%**.
- Foram identificados clientes com níveis de endividamento superiores a **45,2%**.

O resultado indica que o percentual de endividamento foi uma das variáveis com maior capacidade de separar os grupos de compra e não compra.

A análise sugere investigar a relação entre comprometimento financeiro, capacidade de pagamento e intenção de aquisição de imóveis.

### Satisfação com atendimento

<badge color="success">IV 0,30 – Forte</badge>

Um resultado interessante foi observado entre os clientes que não compraram:

**91,45% apresentaram notas acima de 5,8**, em uma escala de satisfação de 0 a 10.

Esse resultado demonstra que a não aquisição não esteve necessariamente associada a uma avaliação ruim do atendimento.

É possível que fatores financeiros, condições de financiamento, preço ou características do imóvel tenham maior relevância na decisão final.

**📌 Interpretação:** satisfação com atendimento apresentou forte poder de separação, mas isso não significa que a insatisfação tenha sido o motivo da não compra. A distribuição das notas precisa ser analisada em conjunto com o resultado de aquisição.

---

## 📊 8. Power BI – Marketing Analytics

📌 **Objetivo:** transformar os dados analisados em visualizações interativas para facilitar a exploração dos resultados.

Foi desenvolvido um dashboard em Power BI com algumas das principais informações da base.

### Recursos utilizados

- 📈 Indicadores gerais de clientes e conversão.
- 🏠 Comparação entre compra e não compra.
- 💰 Análise de variáveis financeiras.
- 📣 Exploração de canais de marketing.
- 🔍 Filtros e segmentações dinâmicas.
- 📊 Visualizações para comparação de perfis e comportamento.

O Power BI complementa as análises realizadas no Excel, permitindo explorar os dados por diferentes perspectivas e facilitar a interpretação dos resultados.

---

## 🧠 9. Competências demonstradas

| Área | Técnicas e conhecimentos |
|---|---|
| 📊 Data Analytics | Análise exploratória e interpretação de dados |
| 📣 Marketing Analytics | Análise de campanhas e comportamento de clientes |
| 🧮 Estatística | Distribuições, médias, medianas e percentis |
| 🎯 Information Value | Avaliação do poder de separação das variáveis |
| 👤 Customer Analytics | Segmentação e análise do perfil de clientes |
| 💰 Financial Analytics | Avaliação de variáveis financeiras |
| 📋 Excel | Tabelas, gráficos e análises estatísticas |
| 📊 Business Intelligence | Dashboards e filtros interativos |
| 🤖 IA Generativa | Apoio à criação de dados sintéticos |

---

## 💡 10. Conclusão

O projeto permitiu investigar diferentes fatores associados à decisão de compra de imóveis, integrando informações demográficas, financeiras e comportamentais com dados de marketing e atendimento.

A aplicação do Information Value destacou o percentual de endividamento e a satisfação com atendimento como variáveis com maior poder de separação entre compradores e não compradores, seguidos por salário mensal, score de crédito e valor de entrada.

Um dos principais aprendizados foi compreender que a decisão de compra é resultado de múltiplos fatores e que uma boa experiência de atendimento, isoladamente, não garante a conversão comercial.

A análise também demonstra como técnicas estatísticas podem apoiar a identificação de padrões, a segmentação de clientes e a investigação de oportunidades para aprimorar estratégias de marketing e vendas.

**Transformar dados de clientes em conhecimento sobre comportamento de compra é um passo importante para desenvolver estratégias comerciais mais orientadas por dados.**

---

## ⚠️ 11. Observação sobre os dados e limitações

Este projeto utiliza uma base sintética de 1.000 clientes, criada com auxílio de IA generativa, exclusivamente para fins acadêmicos e demonstração técnica.

Os resultados representam padrões presentes na base simulada e não devem ser interpretados como evidência de causalidade ou como conclusões generalizáveis para o mercado imobiliário real.

O Information Value avalia poder de separação, não comprova que uma variável causa a compra ou a não compra. Além disso, os resultados dependem da qualidade dos agrupamentos, da distribuição das variáveis e da representatividade dos dados.

---

## 🛠️ Ferramentas utilizadas

- 🟩 Microsoft Excel.
- 📊 Tabelas e gráficos dinâmicos.
- 🧮 Information Value (IV).
- 🟨 Microsoft Power BI.
- 🤖 IA generativa para apoio à criação da base sintética.

**Projeto acadêmico | Data Analytics | Marketing Analytics | Customer Analytics | Business Intelligence**
