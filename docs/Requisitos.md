# Sistema de Treinos Acadêmicos

# Requisitos do Sistema

## 1. Visão Geral

O sistema tem como objetivo auxiliar estudantes no gerenciamento,
organização e acompanhamento de suas atividades acadêmicas,
oferecendo ferramentas de produtividade e monitoramento de desempenho e estatísticas.

---

## 2. Objetivo

Desenvolver uma plataforma capaz de oferecer ferramentas de
organização acadêmica, acompanhamento de progresso e incentivo
à constância nos estudos através de estatísticas de estudo.

---

## 3. Usuários do Sistema

- Usuário comum

---

## 4. Requisitos Funcionais

| Código | Descrição |
|---|---|
| RF01 | O sistema deve permitir cadastro de usuários |
| RF02 | O sistema deve permitir a autenticação de usuários
| RF03 | O sistema deve permitir gerenciamento de disciplinas acadêmicas |
| RF04 | O sistema deve permitir gerenciamento de tarefas acadêmicas |
| RF05 | O sistema deve permitir registro e gerenciamento de sprints de estudo |
| RF06 | O sistema deve associar sprints às disciplinas cadastradas |
| RF07 | O sistema deve apresentar estatísticas de estudo do usuário |
| RF08 | O sistema deve exibir estatísticas por disciplina |
| RF09 | O sistema deve permitir que o usuário configure sua meta diária e semanal de estudo
| RF10 | O sistema deve calcular e exibir streaks de metas de estudo cumpridas consecutivas |
| RF11 | O sistema deve apresentar gráficos e indicadores de desempenho acadêmico |

---

## 5. Requisitos Não Funcionais

| Código | Descrição |
|---|---|
| RNF01 | O sistema deve responder ações do usuário em até 2 segundos |
| RNF02 | O sistema deve possuir autenticação segura |
| RNF03 | O sistema deve possuir interface intuitiva e responsiva |
| RNF04 | O sistema deve manter disponibilidade contínua durante seu funcionamento |
| RNF05 | O sistema deve armazenar os dados de forma segura |
| RNF06 | O sistema deve garantir integridade das informações cadastradas |
| RNF07 | O sistema deve possuir boa usabilidade para estudantes |

---

## 6. Regras de Negócio

| Código | Regra |
|---|---|
| RN01 | Cada usuário deve possuir um email único |
| RN02 | O total de horas estudadas é calculado somando a duração de todos os sprints concluídos pelo usuário |
| RN03 | O streak é incrementado quando o total de minutos estudados no dia atinge ou supera a meta diária configurada pelo usuário |
| RN04 | Enquanto o usuário não configurar sua meta, o streak não é calculado e exibe o estado 'meta não definida

---

## 7. Considerações Finais

Os requisitos apresentados poderão sofrer alterações
durante o desenvolvimento do projeto, conforme necessidades
identificadas pela equipe ou pelos usuários do sistema.
