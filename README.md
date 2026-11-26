# Simulação de Projeto SCRUM — Vendas e Atendimento

Projeto colaborativo desenvolvido durante a simulação prática de **Scrum / Agile** da Generation, aplicando fluxo ágil no [GitHub Projects](https://github.com/users/sugarfreecat/projects/3), versionamento no [GitHub](https://github.com/) e análise de dados de vendas e atendimento com [Google Colab](https://accounts.google.com/SignOutOptions?hl=pt-BR&continue=https://colab.research.google.com/notebook&ec=GBRAqQM) e Google Sheets.

## 🎯 Objetivo do Projeto
Simular o ciclo de trabalho ágil de uma equipe de dados — desde a organização do backlog e o planejamento da Sprint até a coleta, limpeza, análise exploratória, análise diagnóstica, visualização e registro do processo — mantendo colaboração, visibilidade e flexibilidade nas funções e prioridades.

## 🛠️ Ferramentas Utilizadas
* **Gestão e versionamento:** [GitHub](https://github.com/) e [GitHub Projects](https://github.com/users/sugarfreecat/projects/3) (quadro com colunas *Backlog*, *Ready*, *In progress*, *In review* e *Done*)
* **Análise e código:** [Google Colab](https://accounts.google.com/SignOutOptions?hl=pt-BR&continue=https://colab.research.google.com/notebook&ec=GBRAqQM) (`analise_vendas.ipynb` em Python com `pandas` e `matplotlib`)
* **Base de dados:** Google Sheets (*Base Simulação Vendas e Atendimento - Com Erros para Limpeza*)

## 👥 Divisão de Tarefas no Quadro
* **scrum #1 — Coleta de dados:** `ClebersonBS`
* **scrum #2 — Limpeza de dados:** `danferas`
* **scrum #3 — Análise exploratória:** `viniciuspaulo99`
* **scrum #4 — Análise diagnóstica:** `Danlowst`
* **scrum #5 — Análise preditiva:** `meryllinoliveira`
* **scrum #6 — Dashboard de visualização:** `sugarfreecat`

> Observação: o grupo mantém flexibilidade para redistribuir tarefas, apoiar colegas e ajustar prioridades conforme o andamento da Sprint.

## 🔄 Fluxo da Simulação SCRUM
1. **Preparação e Registro de Produto:** definição de papéis/dinâmica ágil, conexão das ferramentas ao repositório e criação dos cartões no quadro.
2. **Planejamento de Sprint:** seleção de um subconjunto viável de tarefas para o ciclo e movimentação para a coluna de trabalho ativo.
3. **Execução e Dailies:** ciclos curtos de execução com alinhamentos rápidos sobre avanços, próximos passos e bloqueios.
4. **Registro e Aprendizados:** documentação do processo, das decisões tomadas e dos desafios que podem surgir em projetos reais.

## 📂 Arquivos e Referências do Projeto
* **Notebook inicial no Colab:** [`analise_vendas.ipynb`](https://colab.research.google.com/)
* **Planilha base no Google Sheets:** *Base Simulação Vendas e Atendimento - Com Erros para Limpeza* (contém registros de pedidos `101` a `112` com inconsistências propositais para limpeza, como duplicata, campos vazios, padronização de texto/status e valor negativo em pedido cancelado).

## ⚠️ Desafios Comuns em Projetos Reais
* **Qualidade e padronização dos dados:** dados duplicados, valores ausentes, formatações inconsistentes e regras de negócio ambíguas (como valores negativos ou cancelamentos).
* **Sincronização entre ferramentas:** manter alinhados os arquivos do repositório, notebooks/planilhas e o status real das tarefas no quadro.
* **Comunicação e escopo:** lidar com mudanças de prioridade, dependências entre etapas e bloqueios técnicos sem perder o ritmo da equipe.
