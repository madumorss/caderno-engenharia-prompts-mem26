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

As 15 fontes utilizadas no NotebookLM são:

1. **OpenAI Prompt Engineering Guide** (link com restrição de acesso, referenciado como base teórica).
2. **How to write better prompts for GitHub Copilot** – artigo do GitHub Blog sobre boas práticas para prompts de código.
3. **LangChain Quickstart** – documentação oficial da LangChain sobre criação de agentes com ferramentas e memória.
4. **Elaboração de Projetos_Apostila.pdf** – material da ENAP sobre conceitos de projeto, ciclo de vida e áreas de conhecimento.
5. **11._gestao_de_projetos_autor_luiz_fernando_rodrigues_campos.pdf** – livro didático do e-Tec Brasil sobre gestão de projetos.
6. **Ebook-gestao-de-projetos-v01a-19-04-2023-compressed.pdf** – guia básico de gestão de projetos da artia.
7. **guia-pratico-de-projetos.pdf** – guia prático do MGI/PNUD, com abordagem adaptada ao setor público.
8. **manual_CNMP.pdf** – manual do Conselho Nacional do Ministério Público sobre gestão de projetos no setor público.
9. **gestao-de-projetos_livro_alunos.pdf** – livro da KLS sobre gestão de projetos (escopo, tempo, custos, riscos, portfólio).
10. **Ruy_Guilherme_Ravazi_TCC.pdf** – trabalho de conclusão de curso da USP sobre tomada de decisão baseada em dados na Indústria 4.0.
11. **007ff380ee5ac49ffc34442f5c2a2b86.pdf** – artigo acadêmico sobre Big Data Analytics na qualidade da tomada de decisão (UFRGS).
12. **2302.11382v1.pdf** – catálogo de padrões de prompt (arXiv), com 16 padrões aplicáveis a LLMs.
13. **diego,+1684.pdf** – resenha do livro “Análise da informação para tomada de decisão”, abordando inteligência organizacional, Web 2.0 e Big Data.
14. **2. Webquest - Roberto Roggiero Junior.pdf** – artigo sobre Business Intelligence, ERP e tomada de decisão.
15. **A Tomada de Decisão Baseada em Dados na Indústria 4.0 (TCC USP)** – já listado no item 10, mas mantido como referência consolidada no conjunto de 15 fontes.

## 🧪 Engenharia de Prompts e “Cicatrizes”

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
Prompt para Identificar Riscos Invisíveis
markdown
Atue como um analista de riscos.  
Com base no projeto [descreva brevemente], faça-me perguntas para identificar:
- Premissas frágeis que podem se tornar riscos.
- Stakeholders ocultos (órgãos reguladores, comunidades afetadas, etc.).
- Possíveis fontes de scope creep e gold plating.
Após minhas respostas, elabore uma matriz de riscos com causas, consequências e estratégias de resposta.
Prompt para Criar Matriz RACI
markdown
Aja como um especialista em governança de projetos.  
Com base na EAP fornecida, crie uma matriz RACI (Responsável, Aprovador, Consultado, Informado) para cada pacote de trabalho.  
Considere os seguintes papéis: Gerente de Projetos, Patrocinador, Equipe Técnica, Usuários-chave.  
Apresente em formato de tabela.
Prompt para Documentar Lições Aprendidas
markdown
Crie um modelo de registro de lições aprendidas para o projeto [nome].  
Inclua campos para: fase do projeto, situação observada, impacto, causa raiz, ação tomada, recomendação para projetos futuros.  
Ao final de cada marco, preencherei este modelo com a equipe.
