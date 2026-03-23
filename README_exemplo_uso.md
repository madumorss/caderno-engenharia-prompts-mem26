Exemplo de Interação: Prompt Mestre para Gerência de Projetos
Este documento apresenta um exemplo prático de uso de um prompt estruturado (engenharia de prompt) com o modelo DeepSeek.
O objetivo é demonstrar como um prompt bem definido pode orientar a IA a assumir um papel específico e conduzir uma coleta de dados interativa antes de gerar artefatos complexos.

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

O orçamento de R$ 250.000 inclui honorários da artista, custos de ferramentas/moldes e custos de mídia e campanha?
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

<details> <summary>📁 Clique para expandir e ver os 10 artefatos completos (TAP, Escopo, EAP, RACI, Matriz de Riscos, Plano de Comunicação, KPIs, Reflexão, Lista de Verificação, Lições Aprendidas + análise de trade-off)</summary>
1. Termo de Abertura do Projeto (TAP)
Campo	Descrição
Nome do Projeto	VENTILACOR – Linha Especial Adriana Varejão
Justificativa	Parceria da Britania com a artista Adriana Varejão para criar uma linha de ventiladores com arte exclusiva, ampliando a visibilidade da marca em novos segmentos sociais (arte, design, colecionismo) e aumentando o ticket médio de vendas.
Objetivo SMART	Lançar até 20/05/2026 uma linha especial de ventiladores (mínimo de 2 modelos) com arte licenciada de Adriana Varejão, sem alteração estrutural dos produtos existentes, atingindo ticket médio 30% superior à linha convencional e gerando ROI positivo em 12 meses.
Benefícios Esperados	• Aumento do ticket médio das vendas
• Diferenciação da marca no mercado de eletrodomésticos
• Entrada em nichos de arte e design
• Fortalecimento da imagem institucional pela parceria cultural
Fonte de Recursos	Orçamento de Marketing e Inovação Britania: R$ 250.000 (inclui licenciamento, produção da linha especial, marketing e contingência)
Autoridade do Gerente	Aprovar despesas até R$ 25.000 sem escalonamento; realocar recursos entre fases dentro do orçamento total; decidir sobre adequações de escopo respeitando o “não escopo”; reporte direto ao Diretor de Marketing (patrocinador executivo).
2. Escopo Detalhado
Declaração de Escopo (O QUE SERÁ ENTREGUE)

Categoria	Entregáveis
Produto	• Linha de ventiladores (2 modelos – mesa/piso) com arte exclusiva de Adriana Varejão aplicada em sobreposição (adesivo, silk screen ou peça decorativa sem alteração estrutural)
• Embalagem especial com identidade visual da parceria
• Numeração limitada (opcional, se viável)
Serviços / Campanha	• Material de ponto de venda (display, adesivos, folhetos)
• Campanha digital (redes sociais, influenciadores de arte e design)
• Conteúdo making of com a artista (para uso em mídia)
• Ativação de lançamento (evento ou ação em showroom, dentro do orçamento)
Gestão	• Contrato de licenciamento de imagem e direitos autorais assinado
• Relatórios de desempenho de vendas (sell-in e sell-out)
Não Escopo (O QUE NÃO SERÁ FEITO)

Item	Justificativa
Desenvolvimento de novas peças estruturais (hélice, grade, base, motor)	Projeto baseia-se em licenciamento de imagem, sem investimento em ferramentas ou engenharia de produto estrutural.
Alteração de performance técnica (fluxo de ar, ruído, eficiência)	Mantém especificações dos modelos-base já existentes.
Produção em larga escala superior a 5.000 unidades	Restrição orçamentária e posicionamento de edição limitada.
Expansão da garantia ou pós-venda dedicado	Utiliza estrutura de garantia e SAC já existente da Britania.
Exportação para mercados externos	Projeto focado no mercado brasileiro.
3. Estrutura Analítica do Projeto (EAP)
Fase PRÉ (Desenvolvimento de Temática, Alinhamento e Diretrizes)

Contrato e Direitos
1.1. Negociação e assinatura do contrato de licenciamento com Adriana Varejão
1.2. Definição de direitos de uso de imagem e exclusividade

Diretrizes Criativas
2.1. Briefing de marca Britania para a artista
2.2. Criação e aprovação da arte final (2 variações)
2.3. Definição de aplicação técnica (sobreposição, cores, acabamento)

Planejamento e Governança
3.1. Kick-off com patrocinadores e principais stakeholders
3.2. Plano de comunicação interna e externa

Fase TRANS (Desenvolvimento das Peças, Logística e Marketing)

Desenvolvimento da Aplicação
4.1. Viabilidade técnica de aplicação da arte nos modelos existentes
4.2. Protótipos visuais para aprovação da artista e da engenharia
4.3. Aprovação de qualidade da arte aplicada

Produção e Logística
5.1. Definição do volume de produção (edição limitada)
5.2. Aquisição de insumos especiais (adesivos, embalagem, etc.)
5.3. Produção do lote piloto e validação
5.4. Produção em escala (dentro da linha existente)
5.5. Armazenagem e distribuição para canais selecionados

Marketing e Comunicação
6.1. Desenvolvimento de campanha digital (conteúdo, anúncios)
6.2. Produção de material de ponto de venda
6.3. Planejamento de ativação de lançamento
6.4. Relações com imprensa e influenciadores

Fase PÓS (Vendas e Pós-Venda)

Vendas e Monitoramento
7.1. Ativação de canais (briefing de vendas, materiais)
7.2. Acompanhamento de sell-in e sell-out
7.3. Pesquisa de satisfação e percepção de marca

Encerramento e Lições Aprendidas
8.1. Análise de resultados (ticket médio, ROI)
8.2. Sessão de lições aprendidas com equipe e artistas
8.3. Relatório final e recomendações para futuras parcerias

4. Matriz de Responsabilidades (RACI)
Pacote da EAP	Sponsor (Dir. Mkt)	Artista (Adriana)	Gerente Projeto	Engenharia	Marketing	Supply Chain	Jurídico	Qualidade	Vendas
1. Contrato e Direitos	A	C	R	I	I	I	R	I	I
2. Diretrizes Criativas	A	R	C	C	R	I	I	I	I
3. Planejamento e Governança	A	I	R	C	C	C	I	I	I
4. Desenvolvimento da Aplicação	A	C	R	R	C	I	I	C	I
5. Produção e Logística	I	I	C	R	I	R	I	C	I
6. Marketing e Comunicação	A	C	C	I	R	I	I	I	C
7. Vendas e Monitoramento	A	I	C	I	C	I	I	I	R
8. Encerramento	A	C	R	C	C	C	I	C	I
Legenda: R = Responsável (executa) | A = Aprovador (approves) | C = Consultado (consulted) | I = Informado (informed)

5. Gestão de Incertezas
Premissas e Restrições

Tipo	Descrição
Premissas	• Artista disponível para aprovações nos prazos definidos.
• Contrato de licenciamento assinado em até 45 dias.
• Modelos-base escolhidos têm capacidade produtiva disponível.
• Canais de venda aceitam condições de edição limitada (sem desconto agressivo).
Restrições	• Orçamento fixo de R$ 250.000 – qualquer estouro exige cortes em outras frentes.
• Prazo de lançamento 20/05/2026 inegociável (campanha de inverno).
• Sem alteração estrutural nos produtos (limitação técnica).
Matriz de Riscos (Técnica Gravata Borboleta)

Evento Central	Causas (ameaças)	Consequências (impactos)	Mitigação (antes)	Contingência (depois)
Atraso na aprovação estética pela artista	• Artista com agenda sobrecarregada
• Divergência de direção criativa
• Processo de aprovação sem prazo definido no contrato	• Atraso em toda a cadeia (produção, marketing)
• Lançamento comprometido
• Custos extras com produção expressa	• Incluir cronograma detalhado de aprovações no contrato
• Reuniões de alinhamento semanais na fase criativa
• Reserva de contingência de 15 dias	• Acionar cláusula de aprovação por representante autorizado caso artista não responda em 5 dias úteis
• Remanejar marketing para ações de pré-reserva enquanto aguarda aprovação
Custo de produção inviabiliza margem esperada	• Aumento no preço de insumos especiais (embalagem, adesivos)
• Volume de produção menor que o planejado diluindo custos fixos
• Subestimativa de royalties	• Margem reduzida ou ticket médio insuficiente para atingir ROI
• Necessidade de cortes em marketing	• Definir volume mínimo econômico junto à engenharia e supply chain
• Negociar royalties fixos + variáveis com limite
• Orçar com base em cotações reais de insumos	• Reduzir investimento em ativação de lançamento e realocar para cobrir custos de produção
• Aumentar lote de produção para diluir custo fixo (se houver demanda)
Baixa aceitação pelos canais de venda	• Varejistas relutantes em reservar espaço para edição limitada
• Condições comerciais (preço) acima do usual	• Sell-in abaixo do esperado
• Estoques parados e impacto na imagem da linha	• Apresentar campanha e materiais de ponto de venda com antecedência
• Criar exclusividade para canais selecionados
• Oferecer condições especiais de consignação para primeiros pedidos	• Acionar plano de vendas diretas (e-commerce próprio) para escoar estoque
• Transformar excedente em brindes promocionais para linha regular
6. Plano de Comunicação
Público-Alvo (Stakeholders)	O quê (conteúdo)	Frequência	Meio
Patrocinador (Diretor de Marketing)	Status do projeto, decisões críticas, indicadores de prazo e orçamento	Semanal (30 min)	Reunião presencial / call + relatório resumo
Artista (Adriana Varejão)	Aprovações de arte, alinhamento criativo, agendamento de conteúdo	Sob demanda (conforme fases)	E-mail + reuniões específicas
Comitê Executivo Britania	Apresentação de marcos, resultados de vendas, ROI	Mensal	Relatório executivo + reunião trimestral
Equipe do Projeto (Engenharia, Marketing, Supply Chain)	Acompanhamento de tarefas, riscos, pendências	Quinzenal (1h)	Reunião de status (online)
Canais de Venda (varejistas)	Informações do produto, campanha, condições comerciais	Antes do lançamento (2x)	Kit digital + call de alinhamento
Comunicação Externa (imprensa, consumidores)	Lançamento, making of, disponibilidade	Conforme cronograma de campanha	Release, redes sociais, influenciadores
7. Monitoramento e Sustentabilidade
KPIs / OKRs de Desempenho

Indicador	Métrica	Fórmula / Fonte	Meta	Frequência
Cronograma (IDC)	Índice de Desempenho de Prazo	SPI = VA / VP	≥ 0,95	Quinzenal
Custo (IDC)	Índice de Desempenho de Custo	CPI = VA / CR	≥ 0,95	Quinzenal
Ticket Médio	Valor médio da venda da linha especial vs. linha convencional	Sistema de vendas	+30%	Pós-lançamento (30, 60, 90 dias)
Sell-out	Unidades vendidas ao consumidor final	Sell-out report dos varejistas	≥ 80% do produzido em 3 meses	Mensal
Visibilidade de Marca	Menções em mídia / alcance de campanha	Relatório de mídia, métricas redes sociais	+50% sobre campanha anterior	Ao final da campanha
Indicadores de Impacto Socioambiental (Longo Prazo)

Dimensão	Indicador	Justificativa
Social	Percepção de aproximação com o universo da arte e cultura	Fortalece a imagem da Britania como marca que valoriza a cultura brasileira, ampliando relevância em camadas sociais que consomem arte.
Ambiental	Uso de embalagens com conteúdo reciclado ou certificado	Projeto optará por embalagens de papelão certificado (FSC) e redução de plástico na embalagem, alinhado à política de sustentabilidade.
Econômico	ROI positivo em até 12 meses	Garante que a parceria gera valor financeiro e justifica futuros investimentos em projetos similares.
8. Reflexão (Racional por Trás da EAP e dos Indicadores)
Estrutura Analítica do Projeto (EAP)
A divisão em pré, trans e pós atende à necessidade do cliente de visualizar o fluxo completo:

Pré concentra os elementos críticos de contrato, alinhamento criativo e governança – fase onde o risco de descasamento entre marca e artista é maior.

Trans reúne o ciclo de execução industrial e de marketing, que neste modelo são interdependentes (a arte aprovada precisa ser viabilizada tecnicamente antes da campanha).

Pós garante que o aprendizado e a mensuração de resultados sejam institucionalizados, criando um fechamento adequado e base para futuras parcerias.

Essa estrutura também facilita a alocação de reservas de contingência: maior reserva na fase pré (devido à subjetividade criativa) e trans (risco de insumos), e menor reserva na fase pós (já com execução consolidada).

Escolha dos Indicadores
Os KPIs combinam indicadores de gestão de projetos (SPI, CPI) com indicadores de negócio (ticket médio, sell-out). Isso permite ao patrocinador acompanhar tanto a saúde da execução quanto a efetividade comercial.
A inclusão de indicadores socioambientais reflete o objetivo implícito de “aumentar visibilidade em outras camadas sociais” – mensurar não apenas venda, mas também o valor de marca gerado pela parceria com uma artista de renome. O ROI de 12 meses assegura a disciplina financeira sem sacrificar o posicionamento de longo prazo.

9. Lista de Verificação de Fatos (Premissas a Validar Imediatamente)
Premissa	Status	Ação Necessária	Responsável	Prazo
Contrato de licenciamento assinado até 15/01/2026	Pendente	Iniciar negociação com assessoria da artista; definir cláusulas de prazo de aprovação.	Jurídico / PM	7 dias
Disponibilidade de Adriana Varejão para aprovações no cronograma	Pendente	Alinhar agenda de reuniões e aprovações antes da assinatura do contrato.	PM / Marketing	15 dias
Volume mínimo econômico de produção (ex.: 2.000 unidades) viável dentro do orçamento	Pendente	Engenharia e Supply Chain devem emitir nota técnica com custo unitário para diferentes volumes.	Engenharia / SC	30 dias
Canais de venda aceitam condições comerciais de edição limitada (preço sugerido +30%)	Pendente	Realizar pesquisa qualitativa com 3 principais varejistas.	Vendas / Marketing	30 dias
Disponibilidade de insumos especiais (embalagem diferenciada, adesivos de alto padrão) em até 60 dias	Pendente	Mapear fornecedores e lead times.	Supply Chain	20 dias
10. Modelo de Lições Aprendidas (Estrutura por Fase)
Fase	O que deu certo? (Acertos)	O que deu errado? (Desvios)	Recomendações para próximos projetos	Responsável pelo registro
Pré	(a preencher ao final da fase)	(a preencher ao final da fase)	(a preencher ao final da fase)	Gerente de Projetos
Trans	(a preencher ao final da fase)	(a preencher ao final da fase)	(a preencher ao final da fase)	Gerente de Projetos
Pós	(a preencher ao final da fase)	(a preencher ao final da fase)	(a preencher ao final da fase)	Gerente de Projetos
Instruções de uso: Ao término de cada fase, reunir a equipe principal e preencher as linhas correspondentes. Consolidar em um repositório acessível (ex.: SharePoint) para consulta em futuros projetos de parceria artística.

Análise de Trade-Off (Complemento Solicitado)
Cenário: Orçamento R$ 250.000, lançamento em 20/05/2026, licenciamento de imagem sem alteração estrutural.
As variáveis críticas são: volume de produção, complexidade das artes especiais e investimento em marketing.

Trade-Off	Efeito no Projeto	Decisão Recomendada
Aumentar volume de produção	Dilui custo fixo (royalties, ferramentas de embalagem), mas exige mais capital de giro em estoque; se o sell-out não acompanhar, compromete ROI.	Adotar volume conservador (entre 1.500 e 2.500 unidades) – suficiente para gerir estoque e testar mercado.
Aumentar complexidade das artes	Eleva custo unitário e risco de atraso na aprovação; porém fortalece o atributo de exclusividade e justifica ticket mais alto.	Priorizar uma arte icônica por modelo, com acabamento diferenciado (ex.: silk screen ou adesivo de alta durabilidade), mas evitar múltiplas cores ou acabamentos especiais que exijam novo processo produtivo.
Aumentar investimento em marketing	Amplia alcance e aumenta probabilidade de sell-out rápido; mas reduz margem líquida se não houver retorno imediato.	Alocar entre 35% e 40% do orçamento para marketing (cerca de R$ 90 mil–R$ 100 mil), suficiente para campanha digital consistente e ativação de lançamento sem comprometer a produção.
Variável a ser sacrificada em caso de estouro de custo ou prazo

Caso haja estouro de custo: Reduzir o investimento em complexidade das artes especiais (ex.: embalagem menos elaborada, redução de cores) antes de cortar marketing, pois o marketing é o vetor principal para garantir a rápida rotação do estoque e a percepção de valor da parceria.

Caso haja estouro de prazo: Sacrificar volume de produção (reduzir o lote) para manter a data de lançamento, pois o prazo de 20/05/2026 é estratégico para a campanha de inverno e a janela de oportunidade comercial.

</details>
