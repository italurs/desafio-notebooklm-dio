# Caderno Temático: Como Avaliar Fundos de Investimentos

## 🎯 Contexto e Objetivos
- **Tema Escolhido:** Avaliação, Análise e Seleção de Fundos de Investimentos.
- **Objetivo de Estudo:** Compreender a metodologia prática para analisar e comparar fundos de investimentos, avaliando métricas de risco, retorno, lâminas de informações, histórico de gestão e adequação ao perfil de investidor.

---

## 📚 Curadoria de Fontes
Fontes abertas selecionadas para análise e carregadas no NotebookLM:
1. [BORA INVESTIR - COMO SELECIONAR FUNDOS](https://borainvestir.b3.com.br/tipos-de-investimentos/como-escolher-um-fundo-de-investimento/)
2. [BTG - GUIA COMPLETO SELEÇÃO DE FUNDOS](https://content.btgpactual.com/blog/fundos-de-investimentos/fundo-de-investimento)
3. [INFOMONEY - GUIA COMPLETO SELEÇÃO DE FUNDOS](https://www.infomoney.com.br/guias/fundos-de-investimento/)

---

## 🧪 Engenharia de Prompts e "Cicatrizes" 
### Testes de Prompts
- **Prompt Inicial (Versão 1):** *"Como avaliar se um fundo de investimento é bom?"*
  - **Resultado:** Resposta genérica focada apenas em rentabilidade passada.
- **Prompt Otimizado (Versão 2):** *"Com base nas fontes fornecidas, quais são as principais métricas de risco-retorno (como Índice Sharpe, Volatilidade e Drawdown) que devem ser analisadas antes de selecionar um fundo de investimento?"*
  - **Resultado:** Resposta precisa, estruturada em tópicos e conectada diretamente aos documentos normativos e técnicos.

### Dificuldades e Aprendizados:
- Para evitar respostas muito conceituais da IA, foi necessário explicitar nos prompts que a análise deveria focar em critérios práticos de tomada de decisão (como taxa de administração, liquidez, estratégia do gestor e métricas ajustadas ao risco).

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
- **Classificação e Estrutura:** Os fundos organizam-se por classes (Renda Fixa, Ações, Multimercado, Cambial) com diferentes níveis de exposição a risco.
- **Análise Qualitativa:** Avaliação do histórico do gestor, consistência da equipe técnica, filosofia de investimento e transparência do material informativo.
- **Análise Quantitativa:** Avaliação de métricas de desempenho ajustadas ao risco, como Índice Sharpe, Volatilidade anualizada, Alpha em relação ao benchmark e Drawdown máximo (maior queda histórica).

### 2. Glossário de Conceitos
- **Índice Sharpe:** Medida que avalia o retorno de um investimento em relação ao risco assumido.
- **Drawdown:** A queda percentual máxima em relação ao pico histórico do fundo, indicando o risco de perda no pior cenário temporal.
- **Benchmark:** Índice de referência usado para comparar a performance do fundo (ex: CDI, Ibovespa, IPCA).
- **Taxa de Performance:** Taxa cobrada quando o fundo supera o seu benchmark de referência (geralmente baseada na regra da "linha d'água").

### 3. Prompts Reutilizáveis para Revisão
- `Prompt 1:` *"Compare os riscos e indicadores essenciais de um fundo de Renda Fixa versus um fundo Multimercado segundo os documentos."*
- `Prompt 2:` *"Quais perguntas de due diligence um analista deve fazer ao ler a lâmina essencial e o regulamento de um fundo?"*
- `Prompt 3:` *"Gere 3 cenários práticos de simulação de análise de fundos com perguntas e gabarito explicativo."*
