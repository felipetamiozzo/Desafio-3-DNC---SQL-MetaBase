# Desafio-3-DNC---SQL-MetaBase
Análise de dados de uma Edtech utlizando o MetaBase e SQL .

---

# Desafio: Gerando Planos de Ação a partir de Análises com SQL

## Descrição

Este projeto foi desenvolvido como parte de um desafio proposto para gerar planos de ação a partir de análises de dados, utilizando consultas SQL dentro da ferramenta Metabase. O objetivo é apoiar uma Edtech no crescimento do número de usuários cadastrados, oferecendo insights estratégicos a partir da análise dos dados disponíveis.

## Contexto

Você atua como um analista de dados em uma Edtech, e o foco da empresa é acelerar o crescimento de novos usuários. A partir das análises de diferentes aspectos da aquisição de clientes, são fornecidas informações que ajudarão a determinar os próximos passos estratégicos da empresa.

## Objetivo

- Construir um dashboard interativo usando SQL no Metabase.

- Fornecer insights baseados em gráficos e tabelas, destacando aspectos como:
  - Distribuição por gênero.
  - Média de idade dos leads.
  - Percentagem de sessões assistidas.
  - Estágios de conversão e status das interações com os leads.
  - Principais motivos de rejeição dos leads.
  
## Tabelas Utilizadas

1. **leads_basic_details**: Contém detalhes básicos dos leads (idade, gênero, cidade, etc.).
2. **sales_managers_assigned_leads_details**: Informações sobre a atribuição de leads aos gerentes de vendas.
3. **leads_interaction_details**: Detalhes das interações dos leads com os gerentes.
4. **leads_demo_watched_details**: Informações sobre as sessões de demonstração assistidas pelos leads.
5. **leads_reasons_for_no_interest**: Razões pelas quais os leads perderam o interesse.

## Desenvolvimento

As etapas abaixo detalham os gráficos e tabelas criados durante o desafio:

1. **Gráfico de Pizza**  
   Exibe a quantidade de leads masculinos e femininos.  
   **Funções usadas**: Operação matemática e agrupamento.
   
2. **Gráfico de Cartão**  
   Exibe a média de idade dos leads.  
   **Funções usadas**: Operação matemática.

3. **Gráfico de Barras**  
   Exibe a quantidade de leads por tipo de educação atual.  
   **Funções usadas**: Operação matemática, agrupamento e ordenação.

4. **Tabela de Médias**  
   Mostra a média da percentagem de sessões assistidas (maiores que 50%), agrupadas por idioma.  
   **Funções usadas**: Operação matemática, agrupamento, cláusula WHERE.

5. **Gráfico de Linhas**  
   Mostra a quantidade de ligações atendidas por plataforma ao longo do tempo.  
   **Funções usadas**: Operação matemática, agrupamento, união de tabelas, cláusula WHERE.

**Entrega**
A entrega foi feita como uma apresentação contendo as consultas SQL e capturas de tela do dashboard.


