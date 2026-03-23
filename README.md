# caderno-engenharia-prompts-mem26
Caderno temático sobre engenharia de prompts aplicada a projetos, desenvolvido no NotebookLM com 15 fontes. Inclui registro de cicatrizes, miniguia com resumos, glossário e prompts reutilizáveis, destacando Prompt Mestre para gestão integrada de projetos (TAP, EAP, RACI, riscos, comunicação).

# Caderno Temático: Engenharia de Prompts na Criação e Desenvolvimento de Projetos

> Projeto para o desafio da DIO – NotebookLM e Engenharia de Prompts

## 📌 Contexto e Objetivos

**Contexto:**  
Este caderno temático foi desenvolvido a partir da exploração de 15 fontes no NotebookLM, que incluem desde padrões de engenharia de prompts até guias práticos de gestão de projetos. O foco central foi investigar como a engenharia de prompts pode ser aplicada de forma estratégica em todas as fases de um projeto – desde a concepção e planejamento até a execução, monitoramento e encerramento.

**Objetivos:**  
- Mapear padrões de prompt aplicáveis a cada etapa do ciclo de vida do projeto.  
- Documentar o processo de refinamento das perguntas (as “cicatrizes”) para extrair o máximo das IAs generativas.  
- Consolidar um guia prático com resumos estruturados, glossário e prompts reutilizáveis.

## 📚 Curadoria de Fontes

As fontes utilizadas no NotebookLM combinam conhecimentos de engenharia de prompts, gestão de projetos e análise de dados:

1. **OpenAI Prompt Engineering Guide** (link com restrição, mas referenciado como base teórica).
2. **How to write better prompts for GitHub Copilot** (GitHub Blog) – boas práticas para prompts de código.
3. **LangChain Quickstart** (docs.langchain.com) – demonstra criação de agentes com ferramentas e memória.
4. **Elaboração de Projetos – Apostila (ENAP)** – material didático sobre conceitos de projeto, ciclo de vida, áreas de conhecimento.
5. **Guia Básico de Gestão de Projetos (artia)** – introdução a gestão de projetos, papéis, ciclo de vida e ferramentas.
6. **Guia Prático de Projetos (MGI/PNUD)** – abordagem adaptada ao setor público, com domínios e artefatos.
7. **Gestão de Projetos (e-Tec Brasil)** – texto didático sobre conceitos, áreas de conhecimento e metodologias.
8. **Manual do CNMP** – gestão de projetos no setor público, com modelos de TAP, cronograma, matriz de riscos.
9. **Gestão de Projetos (KLS)** – abordagem acadêmica sobre escopo, tempo, custos, riscos e portfólio.
10. **A Tomada de Decisão Baseada em Dados na Indústria 4.0 (TCC USP)** – revisão sobre como dados influenciam a decisão.
11. **Big Data Analytics na Qualidade da Tomada de Decisão (UFRGS)** – revisão sobre fatores que influenciam a qualidade da decisão.
12. **A Prompt Pattern Catalog (arXiv)** – catálogo de 16 padrões de prompt aplicáveis a LLMs.
13. **Resenha: Análise da informação para tomada de decisão** – discussão sobre inteligência organizacional, Web 2.0 e Big Data.
14. **Webquest – Tomada de Decisão** – artigo sobre Business Intelligence, ERP e a importância de dados estruturados.
15. **Outros PDFs e materiais** sobre gestão de projetos, riscos, sustentabilidade e portfólio.

## 🧪 Engenharia de Prompts e “Cicatrizes”

As perguntas a seguir foram feitas ao NotebookLM durante a investigação. A coluna “Resposta da IA” transcreve os trechos mais relevantes obtidos, e a coluna “Aprendizado / Ajuste” documenta as cicatrizes.

| Fase | Prompt / Pergunta | Resposta da IA | Aprendizado / Ajuste |
|------|-------------------|----------------|----------------------|
| **Exploração inicial** | *“Explique os diferentes tipos de padrões de prompt para o ChatGPT.”* | A IA listou alguns padrões de forma genérica. | A resposta foi muito ampla. Percebi que precisava direcionar para **gestão de projetos** para obter aplicação prática. |
| **Foco em gestão de projetos** | *“Como a engenharia de prompts pode facilitar a criação, desenvolvimento e manutenção em projetos com e sem fins lucrativos?”* | Resposta detalhada dividida por fases (criação, desenvolvimento, manutenção) e diferenciando contextos lucrativos e sociais. | Aprendi que definir uma **persona** (ex.: “analista de negócios”) e estruturar por **fases** melhora drasticamente a relevância. |
| **Aprofundamento em análise de dados** | *“Como desenvolver prompts efetivos na análise de dados e elaboração de projetos?”* | A IA apresentou os quatro pilares do prompt (identidade, instruções, contexto, exemplos) e padrões como Verificador Cognitivo e Reflexão. | Refinei o prompt para incluir **exemplos (few-shot)** e **template de saída**, tornando as respostas mais acionáveis. |
| **Inclusão de elementos negligenciados** | *“Poderia identificar dados essenciais na construção e execução de projeto que podem ter ‘passado despercebidos’?”* | A IA listou itens como **não-escopo**, **premissas**, **iceberg de custos**, **fatores comportamentais**, **lições aprendidas**. | Passei a pedir explicitamente esses elementos em todos os prompts de planejamento. |
| **Prompt final consolidado** | *“Como esse prompt completo (cobrindo cada mínimo detalhe essencial de um projeto) é?”* | A IA gerou o **Prompt Mestre** completo (reproduzido na íntegra na seção de Prompts Reutilizáveis). | O resultado final é um prompt que pode ser reutilizado para iniciar qualquer projeto com alto nível de detalhamento. |

**Cicatrizes (troubleshooting):**  
- **Respostas genéricas**: solução foi definir uma **persona específica** e exigir **formatos estruturados** (tabelas, templates).  
- **Escopo mal delimitado**: sem pedir explicitamente o **não-escopo**, a IA sugeria entregas excessivas. Adicionei essa instrução para evitar *gold plating*.  
- **Informações faltantes**: a técnica de **Interação Invertida** (o modelo pergunta antes de responder) foi fundamental para coletar dados não considerados inicialmente.  

## 📘 Miniguia de Estudo

### Resumos Estruturados

**1. Padrões de Prompt Essenciais para Projetos**  
- **Interação Invertida (Flipped Interaction)**: o modelo faz perguntas para levantar requisitos antes de propor soluções.  
- **Verificador Cognitivo**: divide problemas complexos em subquestões, aumentando a precisão.  
- **Reflexão**: pede que o modelo explique o raciocínio por trás de uma decisão, permitindo auditoria.  
- **Template (Modelo)**: força a saída a seguir uma estrutura pré-definida (ex.: Termo de Abertura).  

**2. Artefatos Obrigatórios em um Projeto Bem Estruturado**  
- **Termo de Abertura (TAP)**: objetivos SMART, justificativa, stakeholders, autoridade do gerente.  
- **Escopo**: declaração do que será e do que **não** será entregue.  
- **EAP (Estrutura Analítica do Projeto)**: decomposição do trabalho em pacotes gerenciáveis.  
- **Matriz RACI**: responsabilidades (Responsável, Aprovador, Consultado, Informado).  
- **Matriz de Riscos**: causas, consequências, planos de mitigação e contingência.  
- **Plano de Comunicação**: o quê, quem, frequência, canal.  
- **Indicadores (KPIs/OKRs)**: métricas de desempenho e impacto.  

**3. Dados Frequentemente Negligenciados**  
- **Não‑escopo**: evita expectativas irreais.  
- **Premissas**: consideradas a “mãe do risco”.  
- **Iceberg de custos**: custos indiretos (manutenção, treinamento, legal).  
- **Fatores comportamentais**: moral da equipe, satisfação do cliente.  
- **Lições aprendidas**: documentação contínua para evitar repetição de erros.

### Glossário

| Termo | Definição |
|-------|-----------|
| **Prompt** | Instrução fornecida a um modelo de linguagem para gerar uma resposta. |
| **Persona** | Definição de um papel para o modelo (ex.: “analista de dados sênior”) para alinhar tom e profundidade. |
| **Interação Invertida** | Padrão onde o modelo faz perguntas ao usuário para coletar informações antes de entregar a resposta final. |
| **Gold Plating** | Entrega de funcionalidades ou trabalhos extras não solicitados, gerando desperdício. |
| **Scope Creep** | Aumento não controlado do escopo do projeto. |
| **EAP** | Estrutura Analítica do Projeto – decomposição hierárquica do trabalho. |
| **RACI** | Matriz de responsabilidades: Responsável, Aprovador, Consultado, Informado. |
| **Tailoring** | Adaptação dos processos de gestão à complexidade e maturidade do projeto. |

### Prompts Reutilizáveis

#### Prompt Mestre: Arquitetura e Execução Integrada de Projetos
```markdown
# IDENTIDADE
Aja como um Gerente de Projetos Sênior e Analista de Dados, especialista em metodologias híbridas e certificação PMP. Sua comunicação deve ser analítica, focada em valor público/corporativo e na mitigação proativa de riscos.

# CONTEXTO DO PROJETO
Utilize as informações abaixo como base inicial:
<nome> [NOME DO PROJETO] </nome>
<justificativa> [DESCREVA O CENÁRIO E A NECESSIDADE ATUAL] </justificativa>
<objetivo_macro> [O QUE SE PRETENDE ALCANÇAR] </objetivo_macro>

# REGRAS DE INTERAÇÃO (PADRÕES DE ENGENHARIA)
- Interação Invertida: Não crie o plano final agora. Faça-me perguntas, uma por uma, para coletar dados sobre stakeholders, marcos críticos e recursos até que você tenha informações suficientes para um planejamento viável.
- Verificador Cognitivo: Subdivida problemas complexos em questões menores antes de consolidar a análise final.
- Refinamento de Pergunta: Para cada resposta minha, sugira uma versão melhorada da minha instrução para garantir rigor técnico.

# ESTRUTURA DOS ENTREGÁVEIS (CONSTRUÇÃO E EXECUÇÃO)
Após a coleta de dados, gere os seguintes artefatos integrados:

1. **Termo de Abertura do Projeto (TAP)**: Inclua objetivos SMART, benefícios esperados, fonte de recursos e autoridade do gerente.
2. **Escopo Detalhado**:
   - Declaração de Escopo: O que será entregue (produtos e serviços).
   - Não-Escopo: Defina explicitamente o que não será feito para evitar Scope Creep e Gold Plating.
3. **Estrutura Analítica do Projeto (EAP)**: Decomposição gráfica ou em tópicos de todo o trabalho em pacotes gerenciáveis.
4. **Matriz de Responsabilidades (RACI)**: Defina quem é o Responsável, Aprovador, Consultado e Informado para cada pacote da EAP.
5. **Gestão de Incertezas**:
   - Premissas e Restrições: Liste as "pré-verdades" (mãe do risco) e as limitações (legais, técnicas e financeiras).
   - Matriz de Riscos: Use a técnica da Gravata Borboleta (causas, evento central e consequências) com planos de mitigação e contingência.
6. **Plano de Comunicação**: Matriz detalhando "o quê", "frequência", "meio" e "público-alvo" (stakeholders críticos).
7. **Monitoramento e Sustentabilidade**: Defina KPIs/OKRs de desempenho (IDC, VA) e indicadores de impacto socioambiental a longo prazo.

# QUALIDADE E ENCERRAMENTO
- **Reflexão**: Explique o raciocínio por trás da EAP e da escolha dos indicadores.
- **Lista de Verificação de Fatos**: Identifique premissas que precisam de validação imediata.
- **Modelo de Lições Aprendidas**: Prepare uma estrutura para registrar erros e acertos ao final de cada fase, garantindo a memória organizacional.

# FORMATO DE SAÍDA
Apresente os resultados em tabelas Markdown. Use linguagem simples e acessível, evitando tecnicismos desnecessários na comunicação com stakeholders.
