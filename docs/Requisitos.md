# Sistema de Treinos Acadêmicos

# Requisitos do Sistema

## 1. Visão Geral

O sistema tem como objetivo auxiliar estudantes no gerenciamento,
organização e acompanhamento de suas atividades acadêmicas,
oferecendo ferramentas de produtividade, monitoramento de desempenho
e gamificação através de rankings e estatísticas.

---

## 2. Objetivo

Desenvolver uma plataforma capaz de oferecer ferramentas de
organização acadêmica, acompanhamento de progresso e incentivo
à constância nos estudos através de métricas, rankings de desempenho
e interação entre usuários.

---

## 3. Usuários do Sistema

- Administrador
- Usuário comum
- Moderador

---

## 4. Requisitos Funcionais

| Código | Descrição |
|---|---|
| RF01 | O sistema deve permitir cadastro e autenticação de usuários |
| RF02 | O sistema deve permitir gerenciamento do perfil do usuário |
| RF03 | O sistema deve permitir gerenciamento de disciplinas acadêmicas |
| RF04 | O sistema deve permitir gerenciamento de tarefas acadêmicas |
| RF05 | O sistema deve permitir registro e gerenciamento de sprints de estudo |
| RF06 | O sistema deve associar sprints às disciplinas cadastradas |
| RF07 | O sistema deve apresentar estatísticas de estudo do usuário |
| RF08 | O sistema deve exibir progresso acadêmico por disciplina |
| RF09 | O sistema deve calcular e exibir streaks de estudo consecutivos |
| RF10 | O sistema deve apresentar gráficos e indicadores de desempenho acadêmico |
| RF11 | O sistema deve calcular pontuações com base nas atividades registradas |
| RF12 | O sistema deve exibir rankings de desempenho entre usuários |
| RF13 | O sistema deve atualizar automaticamente rankings e estatísticas após registros de estudo |
| RF14 | O sistema deve permitir gerenciamento de amizades entre usuários |
| RF15 | O sistema deve exibir um feed com atividades de amigos |
| RF16 | O sistema deve permitir interações através de curtidas e comentários em postagens |
| RF17 | O sistema deve permitir criação e gerenciamento de comunidades |
| RF18 | O sistema deve permitir participação de usuários em comunidades |
| RF19 | O sistema deve exibir feeds de comunidades |
| RF20 | O sistema deve exibir rankings dentro das comunidades |
| RF21 | O sistema deve permitir busca de usuários e comunidades |
| RF22 | O sistema deve permitir navegação entre dashboard, perfil, feed e comunidades |
| RF23 | O sistema deve restringir funcionalidades privadas a usuários autenticados |
| RF24 | O sistema deve garantir que apenas autores possam editar ou remover seus conteúdos |

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
| RN02 | Apenas administradores podem remover usuários |
| RN03 | Rankings devem ser atualizados automaticamente após registros de estudo |
| RN04 | Cada sprint deve estar associado a uma disciplina |
| RN05 | O sistema deve contabilizar horas estudadas para cálculo de desempenho |
| RN06 | Streaks devem ser incrementados apenas quando houver atividade diária registrada |
| RN07 | Usuários só podem editar ou remover conteúdos de sua autoria |
| RN08 | Rankings das comunidades devem considerar apenas membros participantes |

---

## 7. Considerações Finais

Os requisitos apresentados poderão sofrer alterações
durante o desenvolvimento do projeto, conforme necessidades
identificadas pela equipe ou pelos usuários do sistema.