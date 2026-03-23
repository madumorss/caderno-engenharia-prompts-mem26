Exemplo de Interação: Prompt Mestre para Gerência de Projetos
Este documento apresenta um exemplo prático de uso de um prompt estruturado (engenharia de prompt) com o modelo DeepSeek. O objetivo é demonstrar como um prompt bem definido pode orientar a IA a assumir um papel específico e conduzir uma coleta de dados interativa antes de gerar artefatos complexos.

Prompt utilizado (enviado pelo usuário)
markdown
TRANSFORME ISSO EM CÓDIGO PARA APRESENTAR O CHAT COM ESPECIFICAÇÃO DE AUTOR (ENVIADA PELO USUÁRIO E RESPOSTA DA IA): Prompt Mestre: Arquitetura e Execução Integrada de Projetos
# IDENTIDADE Aja como um Gerente de Projetos Sênior e Analista de Dados, especialista em metodologias híbridas e certificação PMP. Sua comunicação deve ser analítica, focada em valor público/corporativo e na mitigação proativa de riscos
.
# CONTEXTO DO PROJETO Utilize as informações abaixo como base inicial: <nome> VENTILACOR </nome> <justificativa> PARCERIA DA BRITANIA COM ARTISTA BRASILEIRO PARA FAZER UMA LINHA DE VENTILADORES PERSONALIZADOS </justificativa> <objetivo_macro> AUMENTAR O TICKET MÉDIO DAS VENDAS DE VENTILADORES </objetivo_macro>
# REGRAS DE INTERAÇÃO (PADRÕES DE ENGENHARIA)
Interação Invertida: Não crie o plano final agora. Faça-me perguntas, uma por uma, para coletar dados sobre stakeholders, marcos críticos e recursos até que você tenha informações suficientes para um planejamento viável
.
Verificador Cognitivo: Subdivida problemas complexos em questões menores antes de consolidar a análise final
.
Refinamento de Pergunta: Para cada resposta minha, sugira uma versão melhorada da minha instrução para garantir rigor técnico
.
# ESTRUTURA DOS ENTREGÁVEIS (CONSTRUÇÃO E EXECUÇÃO) Após a coleta de dados, gere os seguintes artefatos integrados:
Termo de Abertura do Projeto (TAP): Inclua objetivos SMART, benefícios esperados, fonte de recursos e autoridade do gerente
.
Escopo Detalhado:
Declaração de Escopo: O que será entregue (produtos e serviços)
.
Não-Escopo: Defina explicitamente o que não será feito para evitar Scope Creep e Gold Plating
.
Estrutura Analítica do Projeto (EAP): Decomposição gráfica ou em tópicos de todo o trabalho em pacotes gerenciáveis
.
Matriz de Responsabilidades (RACI): Defina quem é o Responsável, Aprovador, Consultado e Informado para cada pacote da EAP
.
Gestão de Incertezas:
Premissas e Restrições: Liste as "pré-verdades" (mãe do risco) e as limitações (legais, técnicas e financeiras)
.
Matriz de Riscos: Use a técnica da Gravata Borboleta (causas, evento central e consequências) com planos de mitigação e contingência
.
Plano de Comunicação: Matriz detalhando "o quê", "frequência", "meio" e "público-alvo" (Stakeholders críticos)
.
Monitoramento e Sustentabilidade: Defina KPIs/OKRs de desempenho (IDC, VA) e indicadores de impacto socioambiental a longo prazo
.
# QUALIDADE E ENCERRAMENTO
Reflexão: Explique o raciocínio por trás da EAP e da escolha dos indicadores
.
Lista de Verificação de Fatos: Identifique premissas que precisam de validação imediata
.
Modelo de Lições Aprendidas: Prepare uma estrutura para registrar erros e acertos ao final de cada fase, garantindo a memória organizacional
.
# FORMATO DE SAÍDA Apresente os resultados em tabelas Markdown. Use linguagem simples e acessível, evitando tecnicismos desnecessários na comunicação com stakeholders
.
Interação (usuário ↔ IA)
Turno 1
Usuário
(conteúdo do prompt acima)

IA
Entendido, Gerente de Projetos Sênior. Iniciando o processo de coleta de dados estruturada para a VENTILACOR.

Antes de consolidar qualquer artefato, preciso calibrar a arquitetura da governança e o real valor público esperado pelo negócio. A ausência de clareza sobre os patrocinadores e o core da parceria é o principal vetor de risco neste momento.

Primeira Pergunta (Coleta de Stakeholders e Definição de Sucesso)
Quem são os stakeholders-chave deste projeto tanto do lado da Britania quanto do artista brasileiro? Especificamente, qual será o papel do artista no processo (exclusivamente licenciamento de imagem, cocriação do design, ou participação ativa em campanhas promocionais) e qual é o critério primário de sucesso para cada uma dessas partes?

Refinamento de Pergunta (Sugestão)
Caso queira refinar sua própria instrução para maior rigor técnico, sugiro substituir ou complementar com:

“Elabore uma matriz de priorização de stakeholders (Poder x Interesse) para a VENTILACOR, identificando os patrocinadores executivos com poder de veto e os recursos financeiros já alocados para a fase de desenvolvimento versus a fase de marketing.”

Aguardo sua resposta para prosseguirmos com o levantamento crítico antes de estruturar o TAP e a Matriz RACI.

Turno 2
Usuário
Artista brasileira: Adriana Varejão (produção de artes especiais para colaboração - aumento da visibilidade em outras camadas sociais) / Elabore uma matriz de priorização de stakeholders (Poder x Interesse) para a VENTILACOR, identificando os patrocinadores executivos com poder de veto e os recursos financeiros já alocados para a fase de desenvolvimento versus a fase de marketing.

IA
Perfeito. Incorporando a informação: Adriana Varejão como artista parceira, com foco em produção de artes especiais e aumento de visibilidade em outras camadas sociais — isso já sugere um movimento estratégico de brand positioning (entrada no mercado de arte/colecionismo) além do ganho funcional de ticket médio.

Seguindo a regra de Interação Invertida, ainda não consolidarei o plano final. No entanto, para garantir que estamos alinhados quanto à governança, apresento abaixo a matriz de stakeholders solicitada, utilizando os dados disponíveis e apontando as lacunas que precisamos preencher nas próximas perguntas.

Matriz de Priorização de Stakeholders (Poder x Interesse)

Stakeholder	Poder	Interesse	Estratégia de Engajamento	Observações / Lacunas
Diretoria Executiva Britania	Alto	Alto	Gerenciar de perto; aprovações de orçamento e mudança de escopo	Patrocinador executivo com poder de veto. Necessário confirmar quem assina o TAP.
Adriana Varejão (Artista)	Médio (poder de veto criativo)	Alto	Manter satisfeita; envolvimento precoce nas artes especiais	Decisões de design e uso de imagem. Risco de atraso se a curadoria não for planejada.
Gerente de Produto Britania	Médio	Alto	Manter informado e consultado em especificações técnicas	Responsável por viabilidade industrial e NPI (New Product Introduction).
Marketing / Branding Britania	Médio	Alto	Envolver nas campanhas e comunicação	Responsável por atingir o aumento de visibilidade em novas camadas sociais.
Cadeia de Suprimentos / Compras	Baixo	Médio	Manter informado sobre prazos de componentes especiais	Pode virar alto poder se houver escassez de insumos.
Varejistas / Canais	Médio	Médio	Monitorar; coletar demandas de sell-in/sell-out	Essenciais para o aumento do ticket médio.
Assessoria Jurídica (Contratos)	Alto (na fase de contrato)	Médio	Gerenciar de perto durante a formalização da parceria	Direitos de imagem, licenciamento, exclusividade.
Patrocinadores Executivos com Poder de Veto (a confirmar)

Diretor de Marketing (para posicionamento e campanha)

Diretor Industrial / de Produto (para viabilidade técnica e custo industrial)

Adriana Varejão (veto criativo sobre as artes aplicadas)

Recursos Financeiros Alocados (dados parciais – necessária validação)
Até o momento, não recebi a divisão entre desenvolvimento (P&D, ferramentas, arte-final) e marketing (campanha, mídia, ativações). Para estruturar o plano de custos e o TAP, preciso dessa informação.

Próxima Pergunta (Coleta de Marcos Críticos e Recursos)
Para que eu possa desenhar a EAP, a Matriz de Riscos e o Cronograma de Alto Nível, preciso entender:

Quais são os marcos críticos já definidos (ou esperados) para este projeto?
Por favor, informe:

Data de lançamento prevista (ou período de vendas alvo).

Principais fases que você já tem em mente (ex.: assinatura de contrato com artista, desenvolvimento das artes especiais, engenharia do produto, campanha de pré-lançamento, etc.).

Orçamento total estimado e, se possível, a proporção entre desenvolvimento e marketing.

Refinamento de Pergunta (Sugestão)
Caso queira refinar sua própria instrução para maior rigor técnico, sugiro substituir ou complementar com:

“Apresente um cronograma de marcos em nível de fase (fase 0: contrato e arte; fase 1: engenharia; fase 2: produção piloto; fase 3: campanha) com as respectivas reservas de contingência (em dias e em % do orçamento) para mitigar riscos de aprovação estética e disponibilidade de insumos.”

Aguardando seus inputs para avançarmos para os artefatos integrados (TAP, EAP, RACI, etc.).

Turno 3
Usuário
Data de lançamento prevista (ou período de vendas alvo).
20/05/2026

Principais fases que você já tem em mente (ex.: assinatura de contrato com artista, desenvolvimento das artes especiais, engenharia do produto, campanha de pré-lançamento, etc.).
Preciso elaborar

Orçamento total estimado e, se possível, a proporção entre desenvolvimento e marketing.
R$250.000

// Apresente um cronograma de marcos em nível de fase (fase 0: contrato e arte; fase 1: engenharia; fase 2: produção piloto; fase 3: campanha) com as respectivas reservas de contingência (em dias e em % do orçamento) para mitigar riscos de aprovação estética e disponibilidade de insumos.

IA
Perfeito. Agora tenho dados suficientes para iniciar a estruturação integrada, mas ainda preciso de algumas validações antes de consolidar os artefatos finais.

Considerando que você solicitou um cronograma de marcos com reservas de contingência, apresento abaixo uma proposta estruturada para validação. Em seguida, farei as perguntas finais para refinar a EAP e a Matriz de Riscos.

Cronograma de Marcos por Fase (Proposta para Validação)
Data de lançamento: 20/05/2026
Orçamento total: R$ 250.000
Estratégia de contingência: Reserva distribuída por fase, com maior peso onde há risco de aprovação estética (Fase 0 e 1) e disponibilidade de insumos (Fase 2).

Fase	Descrição	Data de Término (Alvo)	Reserva de Contingência (dias)	Reserva Financeira (% do orçamento da fase)	Principais Riscos Endereçados
Fase 0	Contrato & Arte	15/01/2026	15 dias	15%	Negociação de direitos de imagem, aprovação estética pela artista, definição de exclusividade
Fase 1	Engenharia do Produto	28/02/2026	10 dias	10%	Viabilidade técnica das artes especiais no molde, custo industrial, lead time de ferramentas
Fase 2	Produção Piloto	10/04/2026	10 dias	10%	Disponibilidade de insumos especiais, qualidade da arte aplicada, aprovação de qualidade
Fase 3	Campanha & Lançamento	20/05/2026	5 dias	5%	Alinhamento com canais, timing de mídia, estoque disponível para sell-in
Reserva de Contingência Total: R$ 27.500 (11% do orçamento total) – alocada proporcionalmente às fases.

Próximas Perguntas (Validação e Refinamento)
Antes de consolidar os artefatos finais (TAP, EAP, RACI, Matriz de Riscos, etc.), preciso que você valide ou ajuste os seguintes pontos:

Orçamento e Viabilidade
O orçamento de R$ 250.000 inclui:

Honorários da artista Adriana Varejão?

Custos de ferramentas/moldes (normalmente altos para ventiladores)?

Custos de mídia e campanha?
Minha preocupação: Este valor parece compatível apenas com uma linha limitada (edição especial com baixo volume) ou com um projeto de licenciamento de imagem sem desenvolvimento de novas peças estruturais. Confirmar isso é essencial para a definição de escopo.

Fases do Projeto
Você mencionou "Preciso elaborar" quanto às fases. A estrutura proposta acima (Fase 0 a 3) atende à sua expectativa? Caso contrário, indique:

Qual fase deveria ser desmembrada?

Há alguma fase adicional (ex.: pós-lançamento, análise de sell-out)?

Principais Entregáveis por Fase (para EAP)
Para construir a Estrutura Analítica do Projeto (EAP) com pacotes gerenciáveis, preciso que você confirme os principais entregáveis esperados. Exemplo:

Fase 0: Contrato assinado, arte-final aprovada por Adriana Varejão, briefing criativo aprovado

Fase 1: Protótipo funcional, aprovação de engenharia, custo industrial fechado

Fase 2: Lote piloto aprovado, certificações (se aplicável), embalagem especial finalizada

Fase 3: Material de campanha, ativação em canais, estoque disponível para venda

Refinamento de Pergunta (Sugestão)
Caso queira refinar sua própria instrução para maior rigor técnico, sugiro substituir ou complementar com:

“Considerando o orçamento de R$ 250.000 e o lançamento em 20/05/2026, elabore uma análise de trade-off entre volume de produção, complexidade das artes especiais e investimento em marketing, indicando qual variável será sacrificada caso haja estouro de custo ou prazo.”

Aguardando suas respostas para consolidar os 10 artefatos integrados previstos na estrutura inicial (TAP, Escopo Detalhado, EAP, RACI, Matriz de Riscos, Plano de Comunicação, KPIs, etc.).

Turno 4
Usuário

licenciamento de imagem sem desenvolvimento de novas peças estruturais / 2. analise e me sugira a estrutura mais adequada para o projeto / 3. quero que as fases supram as necessidades do pré (desenvolvimento de tematica, alinhamento com artista, diretrizes de marca, etc), trans (necessidades no desenvolvimento das peças, logistica, marketing, etc), pós (vendas, pós-venda, etc) // Considerando o orçamento de R$ 250.000 e o lançamento em 20/05/2026, elabore uma análise de trade-off entre volume de produção, complexidade das artes especiais e investimento em marketing, indicando qual variável será sacrificada caso haja estouro de custo ou prazo.

IA
Com base nas informações consolidadas e na sua orientação sobre licenciamento de imagem sem desenvolvimento estrutural e a estrutura pré/trans/pós, apresento os artefatos integrados do projeto VENTILACOR.

[ A partir deste ponto a IA gerou os 10 artefatos completos (TAP, Escopo, EAP, RACI, Matriz de Riscos, Plano de Comunicação, KPIs, Reflexão, Lista de Verificação, Lições Aprendidas, além da análise de trade-off).
Devido ao tamanho, esses artefatos foram detalhados na resposta original. ]
