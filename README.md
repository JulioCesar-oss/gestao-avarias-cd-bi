# 📦 Gestão de Avarias e Inteligência de Dados em Centro de Distribuição (CD)

## 📌 Contexto e Problema de Negócio
Ao assumir a frente de Planejamento, Controle e Execução (PCE) em um Centro de Distribuição de grande porte, identificou-se um duplo gargalo — operacional e de visibilidade gerencial:
- **Inexistência de BI e Visão Reativa:** Não havia nenhum painel ou indicador estruturado para a área de avarias. A operação atuava apenas sob cobrança da diretoria quando algum problema estourava, sem conseguir demonstrar o volume de mercadorias que a equipe efetivamente salvava e devolvia ao estoque vendável.
- **Acúmulo nas ruas de armazenagem:** Produtos danificados eram descartados diretamente nas pontas ("cabeças") das ruas, gerando obstrução operacional e contaminação de produtos íntegros (avaria secundária).
- **Falha no fluxo anterior:** Tentativas prévias delegavam o tratamento ao próprio separador ao final do pedido, gerando atrasos na expedição e baixa adesão devido à pressão por produtividade.

---

## 🛠️ Solução Implementada (Processo + Dados)

A solução foi dividida em três etapas sequenciais para garantir que o dado coletado fosse confiável antes da construção do primeiro painel da área:

### 1. Saneamento Operacional (Mutirão de Base Zero)
- Utilização de janelas de baixa movimentação (sábados) com equipe dedicada para higienização completa das ruas, segregação física dos itens acumulados e destinação correta para a área dedicada de avarias.

### 2. Redesenho do Fluxo e Governança (SOP)
- **Rondas Programadas:** Estabelecimento de horários fixos para varredura e recolhimento nas ruas e cabeças de rua, desonerando o time de separação.
- **Triagem Focada em Recuperação:** Criação de rotina dedicada de atendimento e recondicionamento na área de avarias, separando formalmente o que é perda total do que retorna ao estoque vendável.

### 3. Criação do Primeiro BI de Avarias (Mudança de Paradigma)
- Estruturação da coleta de dados da triagem e desenvolvimento inédito do painel de **Business Intelligence** da área, mudando o foco da gestão de "apenas cobrar falhas" para **mensurar proativamente o retorno financeiro da recuperação**.

---

## 📊 Principais Indicadores (KPIs) Monitorados no BI

O painel foi desenhado para dar visão tática (supervisão) e financeira (gerência/diretoria):
- **Valor Recuperado (R$) vs. Perda Efetiva (R$):** Medição direta da receita salva pela equipe de triagem e recondicionamento, dando visibilidade positiva da eficiência operacional à diretoria.
- **Visão por Setor / Rua:** Mapeamento de calor para identificar quais corredores ou departamentos geram maior incidência de avarias (causa raiz).
- **Volume Físico (Unidades/Caixas) e Valor Financeiro:** Acompanhamento duplo para evitar distorções entre itens de baixo giro/alto valor e itens de alto giro/baixo valor.
- **Status de Conformidade das Ruas:** Monitoramento contínuo para garantir ruas limpas e sem obstruções nas cabeças de rua.

---

## 🚀 Resultados e Impacto
- **Inversão da narrativa gerencial:** A área deixou de ser apenas alvo de cobranças pontuais da diretoria e passou a apresentar resultados tangíveis em reais (R$) recuperados.
- **Eliminação de gargalos físicos:** Fim do acúmulo de mercadorias nas ruas de separação e redução drástica de avarias secundárias (esmagamento/contaminação de itens bons).
- **Sustentabilidade do processo:** O fluxo desenhado e o BI criado permanecem ativos e padronizados na rotina diária do CD.

---

## 🧩 Competências Aplicadas
`Análise de Negócios` • `Mapeamento de Processos (AS-IS / TO-BE)` • `Logística & Supply Chain` • `Modelagem de KPIs` • `Business Intelligence` • `Governança Operacional`
