# Análise de NPS e Satisfação do Cliente

## Objetivo

Este projeto tem como objetivo traduzir análises técnicas e dados brutos de NPS em insights acionáveis para o negócio.
A partir da análise da variabilidade do NPS, buscamos entender como a experiência do cliente impacta os resultados e, com isso, propor recomendações claras que apoiem tanto a área logística quanto iniciativas de melhoria contínua da experiência do cliente.

A análise busca principlamente responder às seguintes perguntas de negócio:

* Quais fatores são mais críticos para a satisfação?
* O que mais gera detratores?
* Existe um ponto de ruptura na experiência do cliente?
* Que tipo de cliente tende a ter NPS mais alto ou mais baixo?

---

## Contexto

Um e-commerce nacional recentemente passou por um crescimento acelerado de vendas, o que por um lado foi benéfico para o negócio, já que trouxe ganhos importantes de escala, entretanto proporcionalmente elevou os desafios relevantes na experiência do cliente, o que acabou refletindo diretamente na alta variabilidade do Net Promoter Score (NPS) entre diferentes perfis de consumidores.

---

## Estrutura dos dados

O dataset contém informações sobre:

* Perfil do cliente (idade, região, tempo de relacionamento)
* Pedidos (valor, quantidade de itens, parcelas)
* Logística (tempo de entrega, atrasos, tentativas)
* Atendimento (contatos com suporte, tempo de resolução)
* Experiência (reclamações, CSAT)
* NPS (pontuação de satisfação)

---

## Metodologia

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

## Tecnologias utilizadas

* Python
* Pandas
* Matplotlib / Seaborn
* Scikit-learn (opcional, para análise de importância de variáveis)

---

## Como executar

```bash
# Clone o repositório
git clone <seu-repo>

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook/script
```

---

## Dados

O dataset utilizado neste projeto está disponível na pasta data/.

---
## Resumo da conclusão

Melhorar o NPS não depende apenas de encantar o cliente, mas de eliminar consistentemente as fricções ao longo da jornada.

---

## Autores

   * Maria Clara Ferreira de Souza Bova RM: 371497
   * Luiz Eduardo Teixeira Alves de Oliveira RM: 374244
     
Alunos da Postech de AI Scientist
