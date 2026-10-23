# Gestão do Projeto Integrador: Catraca com Reconhecimento Facial

Este documento descreve o processo de planejamento e gestão de tarefas para o desenvolvimento do sistema de Catraca com Reconhecimento Facial, aplicando os conceitos ágeis vistos em aula.

## 1. Planejamento de Gerenciamento de Tarefas
Para o gerenciamento do projeto, adotamos metodologias ágeis (Scrum/Kanban) utilizando um quadro virtual. O objetivo é garantir visibilidade do progresso, divisão clara de responsabilidades e entregas contínuas.


---

## 2. Product Backlog e Prioridades
O levantamento de requisitos resultou na criação do nosso Product Backlog. As funcionalidades foram priorizadas com base no valor de negócio e dependências técnicas.

**Principais Épicos/Histórias:**
*   **Alta Prioridade:** Captura de imagem da câmera, Treinamento do modelo de reconhecimento facial, Integração.
*   **Média Prioridade:** Cadastro de novos usuários via sistema web, Registro de logs de acesso.
*   **Baixa Prioridade:** Dashboard de relatórios de acesso.

---

## 3. Sprint, Tarefas e Estimativas
O trabalho foi dividido em Sprints. Para a Sprint atual, selecionamos os itens de maior prioridade e os quebramos em tarefas menores (Tasks), atribuindo estimativas de esforço (ex: Story Points ou horas).

---

## 4. Quadro Kanban
Para o acompanhamento diário, estamos utilizando um board Kanban. O fluxo de trabalho está dividido nas seguintes colunas principais:
*   **To Do (A Fazer):** Tarefas da Sprint prontas para serem iniciadas.
*   **In Progress (Em Andamento):** Tarefas atualmente em desenvolvimento.
*   **Review/Test (Revisão/Teste):** Código em revisão ou hardware sendo testado.
*   **Done (Concluído):** Tarefas que atenderam aos critérios de conclusão.

---

## 5. Estratégia de Branches
Para manter a organização do código-fonte e evitar conflitos na integração do sistema de visão computacional com o controle da catraca, adotamos o seguinte fluxo de branches:
*   `main`: Código estável e pronto para produção/apresentação.
*   `develop`: Código em integração contínua (versão de testes).
*   `feature/nome-da-tarefa`: Branches temporárias para o desenvolvimento de cada nova funcionalidade (ex: `feature/modelo-facial`, `feature/api-catraca`).


---

## 6. Critérios de Conclusão (Definition of Done)
Para que uma tarefa seja movida para a coluna "Done", ela deve obrigatoriamente cumprir os seguintes critérios:
1.  Código implementado, limpo e comentado.
2.  Funcionalidade testada individualmente e integrada sem quebrar o sistema existente.
3.  Revisão de código (Pull Request) aprovada por pelo menos um membro da equipe.
4.  No caso de hardware (catraca), o protótipo físico deve responder corretamente ao comando de software.
---