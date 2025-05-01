# 📊 Desenrola Brasil — Análise Estatística

Este repositório contém uma análise exploratória e descritiva sobre o programa **Desenrola Brasil**, utilizando exclusivamente fundamentos de **estatística** como parte de um projeto de **Ciência de Dados**.

## 🧠 Objetivo

O objetivo deste projeto é aplicar **conceitos estatísticos básicos** para compreender melhor o impacto e a distribuição dos dados relacionados ao programa Desenrola Brasil, que visa a **renegociação de dívidas de milhões de brasileiros**. A proposta é desenvolver uma análise acessível e robusta, sem o uso de técnicas avançadas de machine learning, focando em:

- Estatísticas descritivas  
- Distribuição de frequências  
- Medidas de tendência central  
- Medidas de dispersão  
- Visualização de dados  

## 🔍 Sobre o Desenrola Brasil

O **Desenrola Brasil** é um programa criado pelo **Governo Federal** com o objetivo de **ajudar milhões de brasileiros a saírem da inadimplência**, oferecendo a oportunidade de **negociar dívidas com condições especiais**, como descontos significativos e prazos mais flexíveis de pagamento.

Lançado em 2023, o programa foi pensado para **movimentar a economia, reduzir a inadimplência** e promover o **reingresso das pessoas no mercado de crédito**. Ele envolve uma parceria entre o governo, instituições financeiras e empresas credoras, funcionando como uma ponte para facilitar acordos de forma acessível.

### 🧾 Como funciona?

O Desenrola Brasil é dividido principalmente em **duas faixas de atendimento**, com critérios específicos:

- **Faixa 1**: Destinada a pessoas com **renda mensal de até 2 salários mínimos** ou inscritas no **CadÚnico** (Cadastro Único para Programas Sociais). Nesta faixa, as dívidas bancárias e não bancárias (como contas de água, luz, varejo e telefonia) podem ser negociadas com **descontos de até 96%** e parcelamento em até **60 vezes**.
  
- **Faixa 2**: Foca em pessoas com **renda de até R$ 20 mil por mês**, para negociações diretas com os bancos, que oferecem condições especiais para regularização de débitos.

Além disso, o programa também possibilita a **limpeza do nome nos birôs de crédito**, o que pode abrir portas para novos financiamentos, cartões ou financiamentos habitacionais, por exemplo.

### 📈 Impacto

Desde seu lançamento, o Desenrola Brasil já impactou **milhões de brasileiros**, tendo registrado altos volumes de negociação nas primeiras semanas de funcionamento. O programa tem sido considerado uma das maiores iniciativas públicas de renegociação de dívidas da história do país.


## 🧰 Tecnologias e Ferramentas

- Python  
- Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook 

## Visão Geral

Este relatório apresenta estatísticas descritivas para os três tipos de operações classificadas como `TIPO_DESENROLA` (1, 2 e 3). Foram analisadas duas métricas principais:  
- **`NUMERO_OPERACOES`**: quantidade de operações realizadas  
- **`VOLUME_OPERACOES`**: valor financeiro total movimentado nas operações  

---

### Resumo Estatístico por Tipo

### TIPO_DESENROLA 1 – Perfil com Alto Volume e Baixo Ticket Médio

- **Número de Operações:**
  - **Média:** 399,24  
  - **Mediana:** 22,00  
  - **Desvio padrão:** 1.354,78  
  - **Mínimo:** 1  
  - **Máximo:** 29.380

- **Volume de Operações:**
  - **Média:** R$ 414.948,71  
  - **Mediana:** R$ 14.939,22  
  - **Desvio padrão:** R$ 1.438.309,60  
  - **Mínimo:** R$ 0,03  
  - **Máximo:** R$ 31.656.400,47

> **Análise:**  
> Este grupo possui grande dispersão no número de operações, com poucos casos muito acima da média (indicado pelo desvio alto e mediana baixa). O volume financeiro segue o mesmo padrão. Indica muitas operações de pequeno valor, com alguns casos extremos.

---

### TIPO_DESENROLA 2 – Perfil com Mais Operações e Volume Elevado

- **Número de Operações:**
  - **Média:** 237,41  
  - **Mediana:** 14,50  
  - **Desvio padrão:** 1.587,46  
  - **Mínimo:** 1  
  - **Máximo:** 46.456

- **Volume de Operações:**
  - **Média:** R$ 987.306,09  
  - **Mediana:** R$ 63.730,52  
  - **Desvio padrão:** R$ 6.137.275,14  
  - **Mínimo:** R$ 0,05  
  - **Máximo:** R$ 214.653.115,30

> **Análise:**  
> Apesar da média ser menor que o Tipo 1, este grupo apresenta o maior número absoluto de operações e volume financeiro. A diferença entre média e mediana indica concentração de valores em poucas operações muito grandes.

---

### TIPO_DESENROLA 3 – Baixo Número de Operações com Alto Valor Médio

- **Número de Operações:**
  - **Média:** 72,84  
  - **Mediana:** 16,00  
  - **Desvio padrão:** 225,78  
  - **Mínimo:** 1  
  - **Máximo:** 3.175

- **Volume de Operações:**
  - **Média:** R$ 2.745.341,48  
  - **Mediana:** R$ 484.222,69  
  - **Desvio padrão:** R$ 11.368.921,69  
  - **Mínimo:** R$ 77,60  
  - **Máximo:** R$ 214.562.582,21

> **Análise:**  
> Grupo com poucas operações e valores médios bastante altos. O alto desvio padrão sugere forte influência de outliers, mas a mediana já aponta valores elevados. Pode representar renegociações de grandes dívidas.

---

## Considerações Finais
Os três tipos analisados apresentam perfis distintos:
- **Tipo 1:** grande quantidade de operações pequenas.
- **Tipo 2:** mistura de muitas operações e grandes volumes.
- **Tipo 3:** poucas operações de altíssimo valor.

Essas diferenças podem orientar políticas específicas para cada segmento do programa Desenrola Brasil.


### Dashboard no PowerBi

[<img src="/imagens/dash.jpg">](https://app.powerbi.com/view?r=eyJrIjoiYWZhYTdiZjUtYWEyMy00NmU0LTk3ZWUtNzJlMzljZmVkZjg5IiwidCI6IjZjY2E5MGExLTkzYTAtNDNlYS05YTA0LTZjZDU3MmFiZjlmMCJ9)




