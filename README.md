# Utilização do GLPI para a Gestão de Chamados Técnicos na Fatec Barueri

Projeto de pesquisa (TG I) que analisa ferramentas de gerenciamento de serviços de TI (ITSM) e seleciona o **GLPI** para estruturar o atendimento técnico e o controle de ativos da área de TI da Fatec Barueri.

## O Problema
Atualmente, a equipe de TI da Fatec Barueri (composta por três profissionais) atende entre 1.500 e 2.000 usuários (alunos, professores e funcionários) e mantém de cinco a seis laboratórios, cerca de 400 computadores, oito impressoras, switches e mais de 20 pontos de acesso sem fio, operando sem um sistema centralizado:
- **Canais dispersos e registros voláteis:** As solicitações chegam pessoalmente, por e-mail ou são anotadas por professores em um caderno no balcão de atendimento, trocado a cada semestre.
- **Falta de indicadores:** Não há contabilização do volume mensal de chamados nem medição do tempo de atendimento.
- **Ausência de histórico dos equipamentos:** O controle patrimonial é feito em planilha de Excel sem registro de manutenções anteriores, dificultando identificar falhas recorrentes (como fonte ou memória) e justificar pedidos de peças ou recursos.

## A Solução (GLPI)
Após uma análise comparativa entre quatro ferramentas de ITSM (ServiceNow, Jira Service Management, GLPI e OTRS/Znuny), o **GLPI** foi selecionado (atingindo 90 de 100 pontos na matriz de decisão) por ser um software livre (licença GNU GPL), sem custo de licenciamento, sem limite de técnicos e compatível com a infraestrutura local da unidade. Alinhado às boas práticas do ITIL, o sistema oferece:
- **Central de Serviços (Ponto Único de Contato):** Registro, triagem e acompanhamento padronizado de incidentes e requisições via portal com formulários específicos.
- **Matriz de Prioridade e SLAs:** Cálculo automático de prioridade combinando urgência e impacto (considerando criticidade e número de usuários afetados, como laboratórios completos), além de prazos definidos de atendimento e solução.
- **Gestão de Ativos e CMDB Integrados:** Inventário automatizado (via GLPI Agent) com vínculo direto entre cada chamado e o equipamento atendido, formando um histórico técnico completo.
- **Base de Conhecimento e Autoatendimento:** Repositório de soluções para dúvidas e demandas frequentes, como instalação e atualização de softwares.

## Benefícios
- **Usuários (Alunos, Professores e Funcionários):** Canal único para abertura de chamados, acompanhamento transparente do status e acesso rápido a orientações de autoatendimento.
- **Equipe de TI:** Fim das anotações manuais em caderno, rastreabilidade de defeitos repetitivos por máquina e geração de métricas reais para dimensionar a equipe e solicitar componentes.
- **Instituição:** Implantação sem custo de licença, leveza para operar em servidor próprio de pequena capacidade e governança alinhada ao ITIL.

## Objetivos
**Geral:** Analisar ferramentas de ITSM, pagas e gratuitas, e selecionar a mais adequada para a gestão dos chamados técnicos e dos ativos de TI da Fatec Barueri, considerando funcionalidades, custo e licenciamento.

**Específicos:**
1. Identificar ferramentas de ITSM pagas e gratuitas disponíveis no mercado.
2. Comparar as ferramentas quanto a funcionalidades, gestão de ativos, custo e licenciamento.
3. Levantar, com a área de TI da Fatec Barueri, a forma atual de recebimento dos chamados técnicos e de controle dos equipamentos, bem como as necessidades da equipe.
4. Selecionar a ferramenta mais adequada e apresentar os recursos que atendem às necessidades levantadas.
5. Definir as etapas de implantação da ferramenta a serem realizadas no TG II (instalação em ambiente de homologação, cadastro de ativos, definição de categorias/SLAs, formulários e testes).

## Equipe

| Integrante | Frente principal | Papel no Scrum |
|---|---|---|
| David | Back-end e integração | Desenvolvedor |
| Gabriel | Inteligência / PLN | Desenvolvedor |
| Ian | Front-end e UX | Desenvolvedor |
| Indaiá | Requisitos, qualidade e documentação | Scrum Master |

## Orientação

| Prof. Vander Ribeiro Elme | Fatec Barueri (2026) |
