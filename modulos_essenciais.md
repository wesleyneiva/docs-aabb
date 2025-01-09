# Documento de Módulos Essenciais 

**Projeto:** Intranet 

**Data de Criação:** 10/12/2024  

## Índice
#### <a href="#1-objetivo"> Objetivo </a>
#### <a href="#2-estrutura-do-documento"> Estrutura do Documento </a>
#### <a href="#3-lista-de-módulos-essenciais"> Lista de Módulos Essenciais </a>
- ##### <a href="#módulo-1-gerenciamento-de-quadro-social"> 1. Gerencialmento de Quadro Social </a>
- ##### <a href="#módulo-2-atividades-esportivas"> 2. Atividades Esportivas</a>
- ##### <a href="#módulo-3-academia"> 3. Academia </a>
- ##### <a href="#módulo-4-locação"> 4. Locaçao </a>
- ##### <a href="#módulo-5-eventos"> 5. Eventos </a>
- ##### <a href="#módulo-6-acesso"> 6. Acesso </a>
- ##### <a href="#módulo-7-atendimento"> 7. Atendimento </a>
- ##### <a href="#módulo-8-portaria"> 8. Portaria </a>
- ##### <a href="#módulo-9-fidelidade"> 9. Fidelidade </a>
- ##### <a href="#módulo-10-biblioteca"> 10. Biblioteca </a>
#### <a href="#funcionalidades"> Funcionalidade </a>
#### <a href="#conclusão"> Conclusao </a>

---

## 1. Objetivo
Este documento tem como objetivo listar e descrever os módulos essencias para operação na virada. \
✔️ indicará concluido \
❗ indicará nao concluido

---

## 2. Estrutura do Documento

1. Nome do módulo  
2. Descrição geral do módulo
3. Objetivo final
4. Status

---

## 3. Lista de Módulos Essenciais

### Módulo 1: Gerenciamento de Quadro Social 
****Alterar nome para "Quadro Social"**** ❗ 

**Descrição Geral:** Responsável por fomentar toda relação entre o associado/não associado e o clube, no que se refere a parte cadastral.

**Objetivo Final:** \
Ter os parâmetros do clube ❗ \
****Ter regras de consideração inadimplência.****
****Regras de licenciamento.****
****Regra para solicitar atualização de foto.****
****Regras de tempo para processo de proposta associativa.****
****Regras de convites.****

Disponibilizar categorias ❗ \
****Falta alguns parâmetros, sugestão: \
  Permite dependentes, cobra taxa por dependente, categoria de não-sócio, retira titular responsável, nao acessa portal, categoria invativa (sim/nao).****

Tipo de dependentes ❗\
****Limites de idades e os processos ao chegar no limite.****

Valores correspondentes ✔️ \
Criação de tipos de cadastros ✔️

Cadastros de documentos necessários para vinculo ❗\
****Vinculação com as categorias.****

Eventos financeiros e suas vinculações, com tipo e cadastro ❗\
****Sugiro ter um modulo do financeiro que deve contemplar as configurações necessárias 
para integração com ERP e parametrização de valores, onde seria possível programar valores 
futuros. Realizamos uma call, no dia 08/01, onde tratamos a respeito a demonstração do que 
temos no sistema e pode ajudar na exemplificação. parametrização de valores, valores futuros, conforme categoria.****

Gerenciamento dos contratos de associação para emissão ❗\
****Vincular estilo o contrato de locação, mas tratando a respeito da associação com seus 
respectivos documentos necessários de assinatura.****

**Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

---

### Módulo 2: Atividades Esportivas

**Descrição Geral:** Responsável pela gereciamento dos cadastros da atividaes esportivas e  matriculas em escolas esportivas.

**Objetivo Final:** \
Criação de cursos ou atividades com seus parâmetros e controles. ✔️ \
Tipo de atividades, turmas, horários, idades, pacotes (de uma ou mais atividades, por matrícula). ✔️

Lista de espera (controle com registros e prazos). ❗\
****Não encontrado.****

Automatização de encerramento de inscrição e chamado de lista de espera. ❗\
****Não encontrado.****

Controle de lista de chamada on-line para professores. ✔️

Controle de locais das aulas vinculado ao sistema de locação de espaços. ❗\
****Não desenvolvido a vinculação.****

Gerenciamentodo cadastro de professores/prestadores para exibição das informações dos memso na parte web, em atividades prestadas por terceirizados como forma de parceria. ❗\
****Desenvolvimento BIO?****      

Controle dos recebimentos, conforme contrato firmado. ❗\
****Depende do financeiro para testes e relatório.****     

Gerenciamento dos contratos relativo as matriculas e prestadores. ❗\
****Tela ok, mas sem função.****   

- **Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

---

### Módulo 3: Academia
****(Seria uma cópia de INSCRIÇÕES ESPORTIVAS)**** ❗

**Descrição Geral:** Responsável pela gerecimento dos cadastros da atividaes da academia e das matriculas dos alunos.

**Objetivo Final:** 
- [ ] Criação de cursos ou atividades com seus parâmetros e controles
- [ ] tipo de atividades, turmas, horários, idades, pacotes (de uma ou mais atividades, por matrícula)
- [ ] lista de espera (controle com registros e prazos)
- [ ] automatização de encerramento de inscrição e chamado de lista de espera
- [ ] Controle de lista de chamada on-line para professores
- [ ] controle de locais das aulas vinculado ao sistema de locação de espaços
- [ ] Gerenciamentodo cadastro de professores/prestadores para exibição das infromações dos mesmos na parte web
- [ ] em atividades prestadas por terceirizados como forma de parceria, controle dos recebimentos, conforme contrato firmado
- [ ] Gerenciamento dos contratos relativo as matriculas e prestadores

- **Status:**
- [x] nao iniciado
- [ ] em progresso
- [ ] concluido

---

### Módulo 4: Locação

**Descrição Geral:** Responsável pelo gerencimento do serviço de locação.

**Objetivo Final:** 

Locação de espaços, salões, armários e materiais (com e sem custos). ❗\
****Faltam armários, locação recorrente e materiais.****

Emissão de contrato, controle de prazos de pré-reservas e lista de interessados.❗\
****Não é possível testar fila de espera.****

Regras para locação, moldes e limites com rotinas parametrizáveis: pré-reservas, lista de interessados e reservas com periodicidade.❗\
****Parametros nao encontrados.**** 

Incorporação do Marque: espaços esportivos, churrasqueiras, raias e quadras (Aluguel com e sem custos).❗

Gerenciamento dos contratos e documentos relativos.❗\
****Falta uma inserção de solicitação de reserva por parte do atendimento para uma 
pessoa.****


- **Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

---

### Módulo 5: Eventos

**Descrição Geral:** Responsável pelo gerenciamento dos eventos.

**Objetivo Final:** \
Criação de eventos, com venda ou não de ingressos, e parametrização de tipos e formatos. ❗\
****Falta parametrização de valores.****

Inscrições em torneios e eventos esportivos.❗\
****Teste deu erro ao fazer inscrição.****

Submódulo de gestão de lugares: Será implementado um layout padrão com formas geométricas a serem posicionadas montando o layout das mesas ou cadeiras a serem disponibilizadas no evento em particular. ✔️

Realização de check-in dos ingressos do evento.❗\
****Não foi desenvolvimento.****

Acompanhamento on-line de vendas, registros e relatórios com base nas opções existentes.✔️

- **Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

---

### Módulo 6: Acesso

**Descrição Geral:** Responsável pelo gerenciamento do acesso.

**Objetivo Final:** \
Criação de locais de acesso com regras de categorias e atividades esportivas, com parametrizações de catracas.❗\
****Desenvolver parametrização de regras vinculação com espaços.****

Gerenciamento dos parâmentros do estacionamento.❗\
****Não desenvolvido.****

- **Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

---

### Módulo 7: Atendimento

**Descrição Geral:** Módulo que destina-se ao atendimento dos associados e usuários.

**Objetivo Final:** 
- [ ] CRM para atendimento, classificando por tipo de atendimento: presencial, telefônico, mídias sociais, consulta
- [ ] Criação de tela que localiza e efetua o cadastro
- [ ] Ter a frente de caixa para cobrança de valores: integração com TEF (pagamento cartão, pix), emissão de boleto via integração BB e dinheiro
- [ ] Acesso a todas os registros das pessoas da matrícula e estes movimentos, tais como: tentativas e acessos, locações, inscrições em atividades, eventos, mudança de situação, categoria e fidelidade, etc...

- **Status:**
- [x] nao iniciado
- [ ] em progresso
- [ ] concluido

--- 

### Módulo 8: Portaria

**Descrição Geral:** Módulo que destina-se ao gerenciamento dos rotinas de portaria.

**Objetivo Final:** 
Visualização dos acessos e suas ocorrências.❗\
Registro de visitantes e fornecedores com liberação temporária de acesso e emissão de crachás temporários.✔️\
Visualização de eventos, atividade e locações agendadas com detalhes.❗\
Registro de ocorrências, cobrança de estacionamento (caixa de cobrança registro de valores e cobrança) e liberação dos tickets.❗\
Registros de encomendas.✔️

- **Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

--- 

### Módulo 9: Fidelidade

**Descrição Geral:** Módulo que destina-se a gerenciamento do programa fidelidade.

**Objetivo Final:** 
- [ ] Gerenciamento do programa com suas regras de geração de pontos, produtos (controle de estoque), procesos de retiradas de produtos e relatórios
- [ ] Ver a estratégia para vincular com gameficação tais como cadastros e demais possibilidades.

- **Status:**
- [x] nao iniciado
- [ ] em progresso
- [ ] concluido

---

### Módulo 10: Biblioteca

**Descrição Geral:** Gerenciamento da biblioteca\
****Terá que passar por uma análise pela responsável da área pela necessidade de conhecimento especifico.**** ❗


**Objetivo Final:** 
- [ ] Gerenciamento do acervo, processo de controle de emprestimos de material e suas regras.

- **Status:**
- [ ] nao iniciado
- [x] em progresso
- [ ] concluido

---

## Funcionalidades
Processo de contratação, associação, locação e etc, totalmente digitizados, incluído assinatura e validação de documentos e troca de documentos.✔️\
Sistema de atendimento digital integrado com chatbot com IA e FAQ. ✔️

## Conclusão
Este documento será atualizado de acordo com os testes e validações para confirmar as funcionalidades e o desempenho dos módulos. Com foco em criar uma experiência positiva, intuitiva e satisfatória entre o sistema e o usuário.
