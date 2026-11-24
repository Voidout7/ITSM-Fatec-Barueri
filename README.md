# UTILIZAÇÃO DO GLPI PARA A GESTÃO DE CHAMADOS TÉCNICOS NA FATEC BARUERI

Proposta de implementação e configuração do sistema **GLPI** para a Secretaria Acadêmica Virtual (SAV) da FATEC Barueri, visando a triagem, categorização e priorização no atendimento aos alunos.

## O Problema

Atualmente, o contacto entre os estudantes e a secretaria ocorre através de um portal (baseado em osTicket) que funciona com uma fila estritamente sequencial (ordem de chegada). 
* Dúvidas recorrentes (limite de faltas, calendário, notas) disputam a mesma fila que solicitações complexas ou urgentes (trancamento de matrícula).
* Existe um prazo único de devolutiva de até 5 dias úteis para qualquer caso.
* Não há possibilidade de réplica no mesmo ticket, obrigando o aluno a abrir um novo chamado caso a dúvida persista.

## A Solução (GLPI)

Adoção do GLPI 11, um sistema de gestão de chamados de código aberto alinhado às boas práticas do ITIL, para organizar e triar o atendimento. A nova estrutura oferece:

* **Base de Conhecimento e Autoatendimento:** Respostas a dúvidas recorrentes disponíveis numa base pública, reduzindo a abertura de chamados repetitivos.
* **Matriz de Prioridade:** Cálculo automático da prioridade combinando a urgência informada pelo aluno e o impacto definido pelo atendente.
* **Acordos de Nível de Serviço (SLA):** Prazos de resposta e solução adequados a cada categoria, substituindo o prazo único atual.
* **Continuidade do Atendimento:** Possibilidade de acompanhamentos (réplicas) dentro do próprio chamado.

## Benefícios

* **Alunos:** Respostas imediatas para dúvidas simples via autoatendimento e resolução mais rápida para casos urgentes.
* **Equipa do SAV:** Redução de tarefas repetitivas e receção de chamados mais completos, classificados por formulários específicos e regras de negócio.
* **Instituição:** Ganho de eficiência sem necessidade de aumentar a equipa de atendimento, além da geração de indicadores e estatísticas nativas.

## Objetivos

**Geral:** Propor e configurar o GLPI como ferramenta de triagem, priorização e controle dos chamados da Secretaria Acadêmica Virtual da Fatec Barueri.

**Específicos:**
1. Caracterizar o funcionamento do sistema atual e identificar as principais dificuldades de alunos e funcionários.
2. Definir categorias, critérios de prioridade e prazos (SLAs) adequados à secretaria.
3. Estruturar uma base de conhecimento com as dúvidas mais frequentes.
4. Configurar um ambiente de demonstração funcional do GLPI (formulários, regras de negócio e SLAs).
5. Preparar a avaliação da solução com os utilizadores e a reprodução da interface da SAV para o TG II.

## Equipe

| Integrante | Frente principal | Papel no Scrum |
|---|---|---|
| David | Back-end e integração | Desenvolvedor |
| Gabriel | Inteligência / PLN | Desenvolvedor |
| Ian | Front-end e UX | Desenvolvedor |
| Indaiá | Requisitos, qualidade e documentação | Scrum Master |

## Links

- [Formulário de Avaliação - Funcionários](https://docs.google.com/forms/d/e/1FAIpQLSdplX-vxtJQnkJo8aCcxSn-VV-2HvkT6UrDKd3g3WWMSBYGYw/viewform)
- [Formulário de Avaliação - Alunos](https://docs.google.com/forms/d/e/1FAIpQLSd9Qv6oN9sl4DnQyCMVb3nRGv7ra48N-dSmToLwbfOd324Brg/viewform)
