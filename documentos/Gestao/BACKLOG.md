# Backlog da ABP

**106 atividades:** 91 tasks da planilha e 15 atividades complementares. Sprint 1 = 50, Sprint 2 = 31, Sprint 3 = 25.

Os identificadores T001 a T091 preservam as tasks da planilha. T092 a T106 completam lacunas do desafio. Responsáveis começam sem atribuição. Estimativas de referência normalizadas devem ser validadas pela equipe.

Correções: T002/T003/T004 vinculadas ao RF01 pela descrição original; RF21 mede temas da prova, não estudos visualizados; RNF04 depende da validação do servidor.

## Sprint 1 — 28/09/2026 a 22/10/2026

Protótipo completo e modelagem integral

| Task | Atividade | Área | Requisitos | Dependências |
|---|---|---|---|---|
| T002 | Prototipar a página inicial | figma | RF01 | — |
| T003 | Modelar em UML a navegação inicial | uml | RF01 | — |
| T004 | Documentar os dados e decisões de persistência da tela inicial | modelagem | RF01 | — |
| T006 | Prototipar início e retorno à certificação | figma | RF02 | — |
| T007 | Modelar em UML início e retorno à certificação | uml | RF02 | — |
| T008 | Modelar o estado da certificação e a retomada | modelagem | RF02 | — |
| T010 | Prototipar o cadastro e seus estados de validação | figma | RF03 | — |
| T011 | Modelar em UML o cadastro | uml | RF03 | — |
| T012 | Modelar candidatos e unicidade do CPF | modelagem | RF03 | — |
| T015 | Prototipar login com CPF e senha | figma | RF04 | — |
| T016 | Modelar em UML autenticação e sessão | uml | RF04 | — |
| T017 | Modelar os dados necessários à autenticação | modelagem | RF04 | — |
| T021 | Prototipar a avaliação por tema | figma | RF05 | — |
| T022 | Modelar em UML a execução da certificação | uml | RF05 | — |
| T023 | Modelar certificação e temas respondidos | modelagem | RF05 | — |
| T025 | Modelar em UML o sorteio das questões | uml | RF06 | — |
| T026 | Modelar temas e banco de questões | modelagem | RF06 | — |
| T029 | Prototipar a área de estudos | figma | RF07 | — |
| T030 | Modelar em UML a navegação nos estudos | uml | RF07 | — |
| T033 | Prototipar feedback e continuidade após uma resposta | figma | RF09 | — |
| T036 | Modelar em UML resposta feedback e continuidade | uml | RF09 | — |
| T037 | Modelar respostas e estados de resolução | modelagem | RF09 | — |
| T047 | Prototipar resultado final | figma | RF16 | — |
| T049 | Modelar em UML o cálculo do resultado | uml | RF16 | — |
| T050 | Modelar os dados do resultado final | modelagem | RF16 | — |
| T052 | Prototipar aprovação e reprovação | figma | RF17 | — |
| T053 | Modelar a elegibilidade do certificado | modelagem | RF17 | — |
| T054 | Modelar em UML a emissão condicionada à aprovação | uml | RF17 | — |
| T059 | Prototipar certificado eletrônico | figma | RF18 | — |
| T060 | Modelar certificado e identificador de validação | modelagem | RF18 | — |
| T061 | Modelar em UML a geração do certificado | uml | RF18 | — |
| T067 | Prototipar o acompanhamento de progresso | figma | RF21 | — |
| T070 | Modelar o progresso da certificação | modelagem | RF21 | — |
| T071 | Modelar em UML o acompanhamento de progresso | uml | RF21 | — |
| T072 | Prototipar estados responsivos para celular e computador | figma | RNF01 | — |
| T077 | Organizar Product Backlog e rastreabilidade dos requisitos | gestao | RNF05 | — |
| T078 | Formalizar as metas e o planejamento das três Sprints | gestao | RNF05 | — |
| T079 | Documentar branches commits e fluxo de Pull Requests | gestao | RNF05 | — |
| T080 | Definir critérios de pronto da equipe | gestao | RNF05 | — |
| T081 | Revisar estimativas com a equipe | gestao | RNF05 | — |
| T082 | Consolidar modelo conceitual lógico físico e DDL PostgreSQL | modelagem | RNF06 | — |
| T086 | Registrar Daily Scrum Review e Retrospective | gestao | RNF06 | — |
| T087 | Registrar dúvidas e alinhamentos com o cliente ou professor | gestao | RNF06 | — |
| T092 | Documentar arquitetura e escolher tecnologia do back-end | gestao | RP01, RP02, RP03, RP05 | — |
| T093 | Completar protótipo de validação pública e histórico | figma | RF19, RF20 | — |
| T094 | Completar modelo de estudos imagens e histórico | modelagem | RF07, RF20, RP04, RP07 | — |
| T095 | Modelar máquina de estados e contratos da certificação | uml | RF09, RF10, RF11, RF12, RF13, RF14, RF15 | — |
| T101 | Definir proteção dos dados no modelo e na arquitetura | modelagem | RNF03, RNF04, RF18, RF19 | — |
| T102 | Selecionar os 12 temas e esclarecer regras em aberto | gestao | RF05, RF06, RF07, RP06, RP07 | — |
| T106 | Revisar entrega integral do Figma UML e banco da Sprint 1 | testes | RNF06, RF01, RF02, RF03, RF04, RF05, RF06, RF07, RF08, RF09, RF10, RF11, RF12, RF13, RF14, RF15, RF16, RF17, RF18, RF19, RF20, RF21 | T082, T093, T094, T095, T101, T102 |

## Sprint 2 — 23/10/2026 a 05/11/2026

Implementação do portal e motor da certificação

| Task | Atividade | Área | Requisitos | Dependências |
|---|---|---|---|---|
| T001 | Implementar página inicial e instruções da certificação | frontend | RF01 | — |
| T005 | Implementar as ações de iniciar e retornar à certificação | frontend | RF02 | T018, T019 |
| T009 | Implementar formulário de cadastro | frontend | RF03 | T010 |
| T013 | Implementar persistência e validação do cadastro | backend | RF03 | T012 |
| T014 | Implementar formulário de login com CPF e senha | frontend | RF04 | T015 |
| T018 | Implementar autenticação com CPF e senha | backend | RF04 | T017, T013 |
| T019 | Implementar consulta dos 12 temas da certificação | backend | RF05 | T026 |
| T020 | Implementar tela reutilizável de questão | frontend | RF05 | T021, T024 |
| T024 | Implementar sorteio de uma questão entre quatro por tema | backend | RF06 | T026 |
| T027 | Implementar listagem dos temas para estudo | frontend | RF07 | T029 |
| T028 | Implementar página de conteúdo didático por tema | frontend | RF07 | T027, T094 |
| T031 | Validar imagem e quatro alternativas com uma correta | backend | RF08 | T026 |
| T032 | Implementar feedback da resposta e ações de continuidade | frontend | RF09 | T020, T035 |
| T034 | Consultar a alternativa correta após encerrar a questão | backend | RF09 | T024 |
| T035 | Persistir respostas e estado da certificação | backend | RF09 | T037 |
| T038 | Implementar cronômetro regressivo de 150 segundos | backend | RF10 | T020, T095 |
| T039 | Encerrar questão não respondida ao esgotar o tempo | backend | RF11 | T038, T035 |
| T040 | Oferecer continuar ou encerrar a sessão após cada resposta | backend | RF12 | T032 |
| T041 | Persistir a retomada pelo próximo tema pendente | backend | RF13 | T035 |
| T042 | Implementar interface de interrupção e retomada | frontend | RF13 | T041, T043 |
| T043 | Encerrar a questão em perda de conexão ou fechamento | backend | RF14 | T095, T035 |
| T044 | Impedir nova resposta a um tema encerrado | backend | RF15 | T023, T035 |
| T045 | Bloquear repetição também na interface | frontend | RF15 | T044 |
| T064 | Registrar histórico completo de respostas da certificação | backend | RF20 | T035 |
| T075 | Implementar proteção e minimização de dados pessoais | backend | RNF03 | T012, T101 |
| T088 | Criar serviços de aplicação e PostgreSQL com Docker Compose | infra | RNF07 | T092, T082 |
| T091 | Produzir as 48 questões com imagens e alternativas | conteudo | RNF08 | T102 |
| T096 | Validar jornada inicial cadastro e login | testes | RF01, RF02, RF03, RF04 | T001, T005, T013, T018 |
| T097 | Validar prova tempo interrupção e retomada | testes | RF05, RF06, RF08, RF09, RF10, RF11, RF12, RF13, RF14, RF15, RF20 | T031, T039, T043, T044, T064 |
| T100 | Revisar tecnicamente questões imagens e material didático | conteudo | RNF08, RP06, RP07 | T091 |
| T105 | Integrar front-end e API com tratamento de erros | backend | RP03, RF03, RF04, RF05, RF06, RF07, RF09, RF13 | T092, T013, T018, T024, T035 |

## Sprint 3 — 06/11/2026 a 25/11/2026

Resultados certificados e entrega final

| Task | Atividade | Área | Requisitos | Dependências |
|---|---|---|---|---|
| T046 | Implementar página de resultado final | frontend | RF16 | T048 |
| T048 | Calcular a nota final no back-end após 12 temas | backend | RF16 | T035, T044 |
| T051 | Emitir certificado somente com aproveitamento mínimo de 65% | frontend | RF17 | T048, T053 |
| T055 | Gerar QR Code e dados de emissão do certificado | frontend | RF18 | T051, T060 |
| T056 | Implementar apresentação e exportação do certificado | frontend | RF18 | T055, T058 |
| T057 | Consultar resultado para compor o certificado | backend | RF18 | T048 |
| T058 | Consultar os dados do candidato para o certificado | backend | RF18 | T013 |
| T062 | Consultar autenticidade do certificado pelo identificador | backend | RF19 | T051, T060 |
| T063 | Implementar página pública de validação do certificado | frontend | RF19 | T062 |
| T065 | Exibir temas concluídos e pendentes na certificação | frontend | RF21 | T069 |
| T066 | Implementar painel de progresso da certificação | frontend | RF21 | T069 |
| T068 | Persistir temas concluídos na certificação | backend | RF21 | T035 |
| T069 | Consultar progresso do candidato | backend | RF21 | T068 |
| T073 | Validar responsividade das telas implementadas | frontend | RNF01 | — |
| T074 | Medir e melhorar o carregamento de páginas e questões | frontend | RNF02 | — |
| T076 | Impedir manipulação da nota no back-end | frontend | RNF04 | T048 |
| T083 | Documentar instalação e execução do projeto | gestao | RNF06 | — |
| T084 | Documentar a API do portal | gestao | RNF06 | — |
| T085 | Documentar funcionalidades implementadas e limitações | gestao | RNF06 | — |
| T089 | Integrar aplicação e banco no ambiente de containers | infra | RNF07 | T088 |
| T090 | Validar dependências e configuração dos containers | infra | RNF07 | T089 |
| T098 | Validar resultado certificado e proteção da nota | testes | RF16, RF17, RF18, RF19, RNF04 | T048, T051, T056, T063, T076 |
| T099 | Executar validação integral do MVP | testes | RNF01, RNF02, RP09 | T096, T097, T098, T073 |
| T103 | Validar execução do projeto em ambiente limpo | infra | RNF07, RP05 | T083, T089, T090 |
| T104 | Preparar entrega apresentação Review e Retrospective finais | gestao | RNF05, RNF06, RP09 | T099, T103, T085 |

