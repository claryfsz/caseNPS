# 📊 Análise de NPS e Satisfação do Cliente

## 🎯 Objetivo

Este projeto tem como objetivo analisar os principais fatores que impactam a satisfação dos clientes, utilizando o NPS (Net Promoter Score) como métrica central.

A análise busca responder às seguintes perguntas de negócio:

* Quais fatores são mais críticos para a satisfação?
* O que mais gera detratores?
* Existe um ponto de ruptura na experiência do cliente?
* Que tipo de cliente tende a ter NPS mais alto ou mais baixo?

---

## 🧠 Contexto

A satisfação do cliente é um dos principais indicadores de sucesso para empresas orientadas à experiência.
Entender os drivers de NPS permite identificar falhas operacionais e oportunidades de melhoria na jornada do cliente.

---

## 📂 Estrutura dos dados

O dataset contém informações sobre:

* 👤 Perfil do cliente (idade, região, tempo de relacionamento)
* 🛒 Pedidos (valor, quantidade de itens, parcelas)
* 🚚 Logística (tempo de entrega, atrasos, tentativas)
* 📞 Atendimento (contatos com suporte, tempo de resolução)
* 😡 Experiência (reclamações, CSAT)
* ⭐ NPS (pontuação de satisfação)

---

## ⚙️ Metodologia

A análise foi conduzida em etapas:

1. Classificação dos clientes em:

   * Promotores (NPS 9–10)
   * Neutros (NPS 7–8)
   * Detratores (NPS 0–6)

2. Análise exploratória dos dados (EDA)

3. Comparação entre grupos de clientes

4. Identificação de:

   * Drivers de satisfação
   * Fatores geradores de detratores
   * Pontos de ruptura na jornada

5. Segmentação de perfis de clientes

---

## 📊 Principais Insights

### 🔑 Drivers de satisfação

A satisfação do cliente está fortemente associada a fatores operacionais:

* Atraso na entrega
* Número de contatos com suporte
* Tempo de resolução
* Quantidade de reclamações

👉 Quanto maior a fricção na jornada, menor o NPS.

---

### 😡 O que gera detratores

Clientes detratores apresentam:

* Mais interações com suporte
* Maior número de reclamações
* Maior tempo de resolução
* Atrasos mais elevados

👉 Detratores surgem do acúmulo de problemas, e não de um único evento.

---

### ⚠️ Ponto de ruptura

Foi identificado um limite crítico na experiência:

* Atrasos acima de 2 dias → queda acentuada no NPS
* Mais de 3 contatos com suporte → aumento significativo de detratores

👉 A experiência deixa de ser recuperável após esse ponto.

---

### 👥 Perfis de clientes

**Clientes com alto NPS:**

* Baixa fricção operacional
* Pouco contato com suporte
* Maior taxa de recompra

**Clientes com baixo NPS:**

* Alta exposição a problemas
* Múltiplas interações com suporte
* Mais reclamações

---

## 📈 Recomendações

Com base na análise:

* 🚚 Reduzir atrasos logísticos (principal driver)
* 📞 Melhorar eficiência do atendimento (resolver no primeiro contato)
* ⚙️ Monitorar clientes com alto risco de churn/detrator
* 📊 Implementar acompanhamento contínuo de NPS

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* Matplotlib / Seaborn
* Scikit-learn (opcional, para análise de importância de variáveis)

---

## 🚀 Como executar

```bash
# Clone o repositório
git clone <seu-repo>

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook/script
```

---

## 💡 Conclusão

Melhorar o NPS não depende apenas de encantar o cliente, mas de eliminar consistentemente as fricções ao longo da jornada.

---

## 👩‍💻 Autores

Maria Clara Ferreira  
Alunos da Postech de IA Scientist
