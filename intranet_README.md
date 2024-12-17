![aabblogo](https://astecpmpa.com.br/wp-content/uploads/2018/01/Logo-AABB-600x416-600x330.jpg)
# Documento de Controle de Módulos e Funcionalidades

**Projeto:** INTRANET
**Data de Criação:** 28/11/2024

# Índice
### <a href="#1-introdução">1. Introdução</a>
### <a href="#2-estrutura-do-documento">2. Estrutura do Documento</a>
### <a href="#3-lista-de-módulos-e-funcionalidades">3. Lista de Módulos e Funcionalidades</a>
- **<a href="#módulo-1-estacionamento">1. Estacionamento</a>**
    - <a href="#funcionalidade-11-vouchers">1.1 Vouchers</a>
    - <a href="#funcionalidade-12-convênios">1.2 Convenios</a>
    - <a href="#funcionalidade-13-motivos-isenção">1.3 Motivos Isenção</a>
- **<a href="#módulo-2-associados">2. Associados</a>**
    - <a href="#funcionalidade-21-listar">2.1 Listar</a>
    - <a href="#funcionalidade-22-perfiscategorias">2.2 Perfis/Categoria</a>
    - <a href="#funcionalidade-23-entidades">2.3 Entidades</a>
    - <a href="#funcionalidade-24-configurações">2.4 Configurações</a>
- **<a href="#módulo-3-eventos">3. Eventos</a>**
    - <a href="#funcionalidade-31-listar">3.1 Listar</a>
    - <a href="#funcionalidade-32-categorias">3.2 Categorias</a>
    - <a href="#funcionalidade-33-almoço-5feira">3.3 Almoço 5Feira</a>
- **<a href="#módulo-4-marque">4. Marque</a>**
- **<a href="#módulo-5-inscrição-esportiva">5. Inscrição Esportiva</a>**
    - <a href="#funcionalidade-51-esportes">5.1 Esportes</a>
    - <a href="#funcionalidade-52-área-do-instrutor">5.2 Área do instrutor</a>
    - <a href="#funcionalidade-53-gerenciar-instrutores">5.3 Gerenciar Instrutores</a>
- **<a href="#módulo-6-locação">6. Locação</a>**
    - <a href="#funcionalidade-61-reservas">6.1 Reservas</a>
    - <a href="#funcionalidade-62-relatórios">6.2 Relatorios</a>
- **<a href="#módulo-7-recepção">7. Recepção</a>**
    - <a href="#funcionalidade-71-ambientes">7.1 Ambientes</a>
    - <a href="#funcionalidade-72-agendar-encomendas">7.2 Agendar Encomendas</a>
    - <a href="#funcionalidade-73-catracas">7.3 Catracas</a>
    - <a href="#funcionalidade-74-restrição-de-usuários">7.4 Restrição de Usuário</a>
    - <a href="#funcionalidade-75-credenciais-temporárias">7.5 Credenciais Temporarias</a>
    - <a href="#funcionalidade-76-validar-acesso">7.6 Validar Acesso</a>
    - <a href="#funcionalidade-77-visitantes">7.7 Visitantes</a>
- **<a href="#módulo-8-biblioteca">8. Biblioteca (em construção)</a>**
    - <a href="#funcionalidade-81-criar">8.1 Criar</a>
- **<a href="#módulo-9-contatos">9. Contatos</a>**
    - <a href="#funcionalidade-91-todos-os-contatos">9.1 Todos os Contatos</a>
    - <a href="#funcionalidade-92-tipos-de-contatos">9.2 Tipos de Contatos</a>
- **<a href="#módulo-10-solicitações">10. Solicitações</a>**
    - <a href="#funcionalidades-101-kanban">10.1 Kanban</a>
    - <a href="#funcionalidade-102-minhas-solicitações">10.2 Minhas Solicitações</a>
- **<a href="#módulo-11-tickets">11. Tickets</a>**
    - <a href="#funcionalidades-111-dashboard">11.1 Dashboard</a>
    - <a href="#funcionalidades-112-lista">11.2 Lista</a>
    - <a href="#funcionalidades-113-categorias">11.3 Categorias</a>
    - <a href="#funcionalidades-114-status">11.4 Status</a>
    - <a href="#funcionalidades-115-prioridades">11.5 Prioridades</a>
- **<a href="#módulo-12-staff">12. Staff</a>**
    - <a href="#funcionalidades-121-usuários">12.1 Usuários</a>
    - <a href="#funcionalidades-122-departamentos">12.2 Departamentos</a>
- **<a href="#módulo-13-configurações">13. Configurações</a>**
    - <a href="#funcionalidades-131-pagamentos">13.1 Pagamentos</a>
    - <a href="#funcionalidades-132-permissões">13.2 Permissões</a>
    - <a href="#funcionalidades-133-todas-as-permissões">13.3 Todas as permissões</a>
- **<a href="#módulo-14-meus-dados">14. Meus Dados</a>**
### <a href="#4-resumo-do-status-geral">4. Resumo Status Geral</a>
### <a href="#5-considerações-finais">5. Consideraçoes Finais</a>

---

## 1. Introdução  
Este documento tem como objetivo listar os módulos e funcionalidades do projeto, bem como os critérios e requisitos necessários para que sejam considerados finalizados e funcionais.  

---

## 2. Estrutura do Documento  

Cada módulo será descrito em uma seção específica, com a seguinte estrutura:  

1. Nome do módulo  
2. Funcionalidades do módulo  
3. Requisitos para cada funcionalidade  
4. Status atual  

---

## 3. Lista de Módulos e Funcionalidades  

### Módulo 1: Estacionamento

**Descrição:** Informações relativas ao estacionamento.

#### Funcionalidade 1.1: Vouchers
- **Descrição:** Administrar os vouchers.
- **Requisitos para conclusão:**  
  - [ ] Adicionar vouchers com opção de vincular a um evento e/ou atividade financeira especifica. Com opção de parametros de % ou valor de desconto.
  - [ ] Editar ou excluir vouchers.
- **Bugs/Erros:**  
  - Caixa de seleção sem funcionalidade.
  - Ao selecionar um item é exibida mensagem "ação realizada com sucesso".
  - Só é possível pesquisar pelo nome do voucher, não pelo código do mesmo.
- **Status:** [Em progresso]

#### Funcionalidade 1.2: Convênios 
- **Descrição:** Administrar informações relativas aos convênios. 
- **Requisitos para conclusão:**  
  - [ ] Adicionar convênios com opção de parametros de %, valor de desconto, ou definição de valor a ser cobrado.
  - [ ] Editar ou excluir convênios.
- **Bugs/Erros:**  
  - Caixa de seleção sem funcionalidade.
- **Status:** [Em progresso] 

#### Funcionalidade 1.3: Motivos Isenção 
- **Descrição:** Administrar informações relativas aos motivos de isenções.
- **Requisitos para conclusão:**  
  - [ ] Adicionar motivos de isenção de estacionamento. 
  - [ ] Editar ou excluir isenções.
- **Bugs/Erros:**  
  - Caixa de seleção sem funcionalidade.
  - Palavra escrita de forma errada gramaticalmente "Execeção".
- **Status:** [Em progresso] 

### Funcionalidade 1.4: Relatórios ---inlcluir no indice ----
- **Descrição:** Relatóris relativos ao estacionamento.
- **Requisitos para conclusão:**  
  - [ ] Relatórios refente a validações, uso de vouches, status de ticket´s
- **Bugs/Erros:**  
 - Não desenvolvido.
- **Status:** [Em progresso] 

---

### Módulo 2: Associados - Mudar o nome para Gerenciamento de quadro social.

**Descrição:** Gerenciar os cadastros junto ao clube.

#### Funcionalidade 2.1: Listar
- **Descrição:** Listar os cadastro dos associados ao clube.
- **Requisitos para conclusão:**  
  - [ ] Listar o cadastro do associado assim como obter as informações pessoais dos membros da matrícula.
  - [ ] Editar informações gerais relativo aos cadastros.
 - **Bugs/Erros:**  
   - Caixa de pesquisa e botão filtros sem funcionalidade.
   - Caixa de seleção sem funcionalidade.
- **Status:** [Em progresso] 

#### Funcionalidade 2.2: Perfis/Categorias 
- **Descrição:** Gerenciar os perfis cadastrados no clube.
- **Requisitos para conclusão:**  
  - [ ] Adicionar perfil
  - [ ] Numero total de associados de acordo com perfil (comunitário, convenio...).
 - **Bugs/Erros:**  
   - Caixa de pesquisa e botão filtros sem funcionalidade.
   - Caixa de seleção sem funcionalidade.
- **Status:** [Em progresso] 

#### Funcionalidade 2.3: Entidades
- **Descrição:** Gerenciar as entidades conveniadas.
- **Requisitos para conclusão:**  
  - [requisito 1]  
  - [requisito 2]
 - **Bugs/Erros:**  
   - [bug1]
   - [bug2]
- **Status:** [Não iniciado / Em progresso / Finalizado / Em validação]

#### Funcionalidade 2.4: Configurações
- **Descrição:** Gerenciar as numerações dos sócios.
- **Requisitos para conclusão:**  
  - [ ] [requisito 1]  
  - [ ] [requisito 2]
 - **Bugs/Erros:**  
   - [bug 1]
   - [bug 2]
- **Status:** [Não iniciado / Em progresso / Finalizado / Em validação]

---

### Módulo 3: Eventos

**Descrição:** Gerenciar os proximos eventos do clube.

#### Funcionalidade 3.1: Listar  
- **Descrição:** Gerenciar a lista de eventos.
- **Requisitos para conclusão:**  
  - [ ] Adicionar os eventos. 
  - [ ] Listar os eventos.
  - [ ] Detalhes, editar e/ou excluir eventos da lista.
- **Bugs/Erros:**  
  - não é possível adicionar um novo evento, botão inativo após preencher formulario.
  - Caixa de pesquisa não retorna resultados.
- **Status:** [Em progresso]

#### Funcionalidade 3.2: Categorias 
- **Descrição:** Gerenciar as categorias dos eventos.
- **Requisitos para conclusão:**  
  - [ ] Adicionar categorias eventos. 
  - [ ] Listar categorias cadastradas.
  - [ ] Editar e/ou excluir categorias da lista de categorias cadastradas.
 - **Bugs/Erros:**  
   - Editar categoria sem funcionalidade.
   - Botão para adicionar categoria com nomenclatura "editar".
- **Status:** [Em progresso]

#### Funcionalidade 3.3: Almoço 5Feira
- **Descrição:** Gerenciar o almoço de 5Feira.
- **Requisitos para conclusão:**  
  - [ ] Adicionar um novo menu e data do almoço.
  - [ ] Listar os almoços e suas datas além de filtrar por data.
  - [ ] Editar e/ou excluir almoços cadastrados.
 - **Bugs/Erros:**  
   - Caixa de seleção sem funcionalidade.
- **Status:** [Em progresso]

---

### Módulo 4: Marque

**Descrição:** Gerenciar a marcação de espaços no clube assim como todo relatório, restrições, configurações e edições de horário.
- **Requisitos para conclusão:**  
  - [ ] Adicionar um novo espaço para locação.
  - [ ] Listar e cadastrar reservas.
  - [ ] Listar e cadastrar restrições.
  - [ ] motivos de restrições.
  - [ ] relatórios do dia e quantidade de reservas por espaço.
 - **Bugs/Erros:**  
   - Visualizar ambiente não disponível.
   - cursor para seleção de menus.
- **Status:** [Em progresso]

---

### Módulo 5: Inscrição Esportiva (mudar nomenclatura "escolas esportivas" ou "atividades esportivas")

**Descrição:** Gerenciar atividades esportivas e suas inscrições.

#### Funcionalidade 5.1: Esportes
- **Descrição:** Adicionar novo esporte, editar e ver turmas disponíveis.
- **Requisitos para conclusão:**  
  - [ ] Listar as atividades esportivas disponíveis.
  - [ ] Editar, ver e criar turmas.
  - [ ] Criar novo esporte.
  - [ ] Aula experimental condicionada a limite de vagas disponiveis na turma.
  - [ ] Natação tem regras especificas (3 perguntas - se a crianca tem vivencia na modalidade...).
  - [ ] Transferencia de matricula de uma atividade para outro usuario dentro da mesma matricula.
- **Bugs/Erros:**
   - Após criar turma ao editar nao atualiza na tela de turma inserida.
   - nao salva a edição de turma "InvalidRequestException"
- **Status:** [Em progresso]

#### Funcionalidade 5.2: Área do Instrutor
- **Descrição:** Área do professor, lista de acordo com a modalidade esportiva, turmas e chamada.
- **Requisitos para conclusão:**  
  - Ver as suas turmas e realizar chamadas.
- **Bugs/Erros:**  
   - [Bug1]
   - [Bug2]
- **Status:** [Em progresso]

#### Funcionalidade 5.3: Gerenciar Instrutores
- **Descrição:** Gerenciamento de instrutores.
- **Requisitos para conclusão:**  
  - [ ] adicionar ou remover instrutor.
  - [ ] pesquisar por nome ou email.
- **Bugs/Erros:**  
   - Não foram identificados erros.
- **Status:** [Em validação]

---

### Módulo 6: Locação

**Descrição:** Gerenciar locações de espaços, salões, coworking...

#### Funcionalidade 6.1: Reservas
- **Descrição:** Locação de espaços, salões, armários e materiais (com e sem custos), emissão de contrato, controle de prazos de pré-reservas e lista de interessados.
Regras para locação, moldes e limites com rotinas parametrizáveis: pré-reservas, lista de interessados e reservas com periodicidade.
- **Requisitos para conclusão:**  
  - [ ] Listar as reservas com um relatório sobre status.
  - [ ] Listar os usuários, matr., ambiente, evento, data.
  - [ ] pesquisar por nome, data e filtrar por status.
  - [ ] informações, editar, convidados e doc para assinar.
- **Bugs/Erros:**  
   - Erro ao editar e/ou mudar status com a seguinte mensagem "InvalidRequestException".
- **Status:** [Em progresso]

#### Funcionalidade 6.2: Relatórios
- **Descrição:** Dashboard com relatório de acordo com status da solicitação de reserva.
- **Requisitos para conclusão:**  
  - [ ] Listar as reservas com um relatório sobre status.
  - [ ] Lista com usuários e o status de sua solicitação de locação.
- **Bugs/Erros:**  
   - Erro ao editar e/ou mudar status com a seguinte mensagem "InvalidRequestException".
- **Status:** [Em progresso]

---

### Módulo 7: Recepção

**Descrição:** Gerenciar atividades esportivas e suas inscrições.

#### Funcionalidade 7.1: Ambientes
- **Descrição:** Lista de ambientes disponíveis com nome e capacidade.
- **Requisitos para conclusão:**  
  - [ ] Listar ambientes disponíveis.
  - [ ] Adicionar ambientes, editar e excluir.
- **Bugs/Erros:**  
   - Botão de atualizar fora da margem da pagina.
   - Erro ao cadastrar bloqueio com a seguinte mensagem "SQLSTATE[HY000]: General error: 1364 Field 'description' doesn't have a default value (Connection: default, SQL: insert into `event_environment_blocks` (`env_id`, `start_date`, `end_date`) values (39, 2024-12-02, 2024-12-03))".
- **Status:** [Em progresso]

#### Funcionalidade 7.2: Agendar Encomendas
- **Descrição:** Lista do agendamento do recebimento de pedidos.
- **Requisitos para conclusão:**  
  - [ ] Listar os usuários com agendamento de pedidos a receber.
  - [ ] nome, previsão de entrega, entregadora e detalhes.
  - [ ] Editar ou excluir alguma previsão de entrega.
- **Bugs/Erros:**  
   - Ao deletar uma algum item da lista, a relação some deixando a mensagem "Usuário(s) não encontrado(s)".
- **Status:** [Em progresso]

#### Funcionalidade 7.3: Catracas
- **Descrição:** [Lista das catracas assim como código, nome, status e manutenção]
- **Requisitos para conclusão:**  
  - [ ] Lista de todas as catracas do clube.
  - [ ] Tabela com nome, status, ultima manutenção, código e ações.
- **Bugs/Erros:**  
   - Após atualizar catraca o botão "voltar" não retorna a pagina da lista de catracas.
- **Status:** [Em progresso]

#### Funcionalidade 7.4: Restrição de usuários
- **Descrição:** Relação de usuários com restrição de acesso ao clube.
- **Requisitos para conclusão:**  
  - [ ] Lista de restrições com nome, motivo, cpf e data do fim da restrição.
  - [ ] Atualizar ou excluir restrição.
- **Bugs/Erros:**  
   - Ao adicionar uma nova restrição na lista o campo "nome" na próxima pagina muda para "motivo da restrição".
- **Status:** [Em progresso]

#### Funcionalidade 7.5: Credenciais Temporárias
- **Descrição:** Adiciona uma credencial temporária para visitante ou associado.
- **Requisitos para conclusão:**  
  - [ ] Lista com nome, tipo, cpf e data de validade da credencial.
  - [ ] Atualizar ou excluir credencial temporária.
- **Bugs/Erros:**  
   - Ao adicionar uma nova credencial visitante erro "Houve um error!O arquivo não foi transferido. Impossível continuar".
   - Ao adicionar uma nova credencial associado erro "Houve um error!UserNotFoundException".
- **Status:** [Em progresso]

#### Funcionalidade 7.6: Validar Acesso
- **Descrição:** Validar acesso do associado.
- **Requisitos para conclusão:**  
  - [ ] Validar acesso do usuário.
  - [ ] Pesquisar por ID, nome, matricula e CPF.
- **Bugs/Erros:**  
   - Não é possivel realizar a pesquisa do usuário retornando o seguinte erro "TemporaryCredentialsNotExistException"
   - não é possível criar a credencial temporaria como relatado no erro acima, logo a mesma não é encontrada. 
- **Status:** [Em progresso]

#### Funcionalidade 7.7: Visitantes
- **Descrição:** Listar os visitantes do clube.
- **Requisitos para conclusão:**  
  - [ ] Adicionar visitante temporário agendada.
  - [ ] Listar visitantes com respectivas datas.
- **Bugs/Erros:**  
   - não é possível adicionar visitante retornando erro "Houve um error!
SQLSTATE[42S02]: Base table or view not found: 1146 Table 'aabbpoa-dev.user_guest_notifications' doesn't exist (Connection: default, SQL: delete from `user_guest_notifications` where `guest_user` = 54)"
   - botão adicionar visitante com erro gramatical "visitanta".
   - erro gramatical ao informar nenhum visitante cadastrado "Nunha credencial temporária encontrada".
- **Status:** [Em progresso]

---

### Módulo 8: Biblioteca

**Descrição:** Gerenciar a biblioteca assim como seus exemplares.

- **Requisitos para conclusão:**  
  - Ver documento externo criado por especialista.
- **Bugs/Erros:**  
   - [Bug 1]
- **Status:** [Em progresso]

---

### Módulo 9: Contatos

**Descrição:** é possível visualizar a lista de contatos públicos e privados sendo possível adicionar, visualizar, editar e excluir contatos. Além de pesquisar e filtrar por públicos ou privados.

#### Funcionalidade 9.1: Todos os Contatos
- **Descrição:** listar todos os contatos publicos e privados.
- **Requisitos para conclusão:**  
  - [ ] vizualizar a lista com todos os contatos.
  - [ ] filtrar por pulblico e/ou privado.
  - [ ] adicionar novos contatos.
  - [ ] visualizar, editar e excluir contatos.
- **Bugs/Erros:**  
   - ao atualizar a lista de todos os contatos o contato que é privado some da lista.
- **Status:** [Em Validação]

#### Funcionalidade 9.2: Tipos de Contatos
- **Descrição:** lista de tipos de contatos.
- **Requisitos para conclusão:**  
  - [ ] vizualizar os tipos de contatos.
  - [ ] adicionar tipos de contatos.
  - [ ] listar de acordo com nome e descrição.
  - [ ] vizualizar, editar e excluir os tipos de contatos.
- **Bugs/Erros:**  
   - em ações ao selecionar para visualizar detalhes do tipo de contato o subtitulo da pagina está "AABB Kids - Configurações" e "valor do evento".
- **Status:** [Em progresso]

---

### Módulo 10: Solicitações

**Descrição:** Módulo onde é possível abrir novas solicitações como antigo sistema de demandas.

#### Funcionalidades 10.1: Kanban
- **Descrição:** Sistema visual para organizar as etapas do processo da solicitação
- **Requisitos para conclusão:**
  - [ ] mostrar a evolução das solicitações abertas
  - [ ] identificar a fase da solicitação assim como modifica-la
- **Bugs/Erros:**
  - kanban sem funcionalidade retornando o erro "error Ocorreu um erro ao processar sua solicitação. Tente novamente mais tarde."
- **Status:** [Em processo]  

#### Funcionalidade 10.2: Minhas solicitações
- **Descrição:** listar todas as solicitações além de adicionar novas.
- **Requisitos para conclusão:**  
  - [ ] vizualizar as solicitações.
  - [ ] mostrar nome, departamento destino, prioridade, status, data de criação e prazo de vencimento.
  - [ ] adicionar novas solicitações.
  - [ ] acessar a solicitação especifica e seus detalhes.
  - [ ] enviar mensagens e anexar arquivos.
- **Bugs/Erros:**  
   - nao foram encontrados erros.
- **Status:** [Em validação]

---

### Módulo 11: Tickets

**Descrição:** Dashboard de tickets mostrar número de tickets total, abertos, atrasados e resolvidos hoje.

#### Funcionalidades 11.1: Dashboard
- **Descrição:** Pesquisar tickets, filtragem por status e por prioridades. Listar por total, abertos, atrasdos e resolvidos hoje.
- **Requisitos para conclusão:**
  - [ ] Evoluir para ouvidoria categoria necessário pré-existência ticket
  - [ ] Classificação, tags para poder filtrar e gerar relatórios
  - [ ] Criar solicitação interna oriunda de ticket externo - tarefa
- **Bugs/Erros:**
  - relatorio com numero do ticket nao esta sendo gerado permanecendo todos com numero zero. mesmo tendo ticket aberto e listado.
- **Status:** [Em processo]

#### Funcionalidades 11.2: Lista
- **Descrição:** Lista de tickets
- **Requisitos para conclusão:**
  - [ ] Listar todos os tickets abertos.
  - [ ] filtrar e pesquisar tickets.
  - [ ] acessar os detalhes e historico, atualizar status.
- **Bugs/Erros:**
  - nao foram encontrados erros.
- **Status:** [Em validação]

#### Funcionalidades 11.3: Categorias
- **Descrição:** Categorias de tickets
- **Requisitos para conclusão:**
  - [ ] Listar as categorias dos tickets.
  - [ ] Adicionar nova categoria. Além de editar e exlcluir.
- **Bugs/Erros:**
  - é possivel criar uma categoria com 2 caracteres, porem nao é possivel editar nem exclui-la.
- **Status:** [Em processo]

#### Funcionalidades 11.4: Status
- **Descrição:** Status de tickets
- **Requisitos para conclusão:**
  - [ ] Listar as cores de acordo com status do ticket.
- **Bugs/Erros:**
  - botao para excluir "novo/padrao" inoperante.
- **Status:** [Em processo]

#### Funcionalidades 11.5: Prioridades
- **Descrição:** Prioridade de tickets
- **Requisitos para conclusão:**
  - [ ] Listar e editar cores de acordo com prioridade do ticket.
  - [ ] Adicionar nova prioridade ou excluir algum existente.
- **Bugs/Erros:**
  - erro ao adicionar nova prioridade com a seguinte mensagem "Ocorreu um erro ao processar sua solicitação. Tente novamente mais tarde."
- **Status:** [Em processo]

---

### Módulo 12: Staff

**Descrição:** Cadastro de departamentos internos da AABB. Aos quais os usuários serão vinculados.

#### Funcionalidades 12.1: Usuários
- **Descrição:** Lista de usuários internos com acesso ao sistema.
- **Requisitos para conclusão:**
  - [ ] mostrar lista de usuarios, sua permissão, situação e departamento.
  - [ ] adicionar e gerenciar usuarios.
  - [ ] Sugestão de vincularmos os integrantes no seu nível hierárquico para o humanograma.
  - [ ] ter campos que posso detalhar os dados de contato, localização do departamento... 
- **Bugs/Erros:**
  - erro ao adicionar novo usuário mensagem "Houve um error!InvalidColumnEnumException"
  - erro ao editar usuario existente "Erro ao buscar informações"
- **Status:** [Em processo]

#### Funcionalidades 12.2: Departamentos
- **Descrição:** Lista de departamentos.
- **Requisitos para conclusão:**
  - [ ] listar todos os departamentos.
  - [ ] adicionar e gerenciar departamentos.
- **Bugs/Erros:**
  - nao foram encontrados erros.
- **Status:** [Em validação]

---

### Módulo 13: Configurações

**Descrição:** Configurações relativo a pagamentos, permissões e tradução de legenda de permissões.
#### Funcionalidades 13.1: Pagamentos
- **Descrição:** Lista de formas de pagamento disponiveis.
- **Requisitos para conclusão:**
  - [Requisito 1] 
  - [Requisito 2]
  - [Requisito 3]  
- **Bugs/Erros:**
  - [Bug 1]
  - [Bug 2]
  - [Bug 3]
- **Status:** [Não iniciado / Em progresso / Finalizado / Em validação]

#### Funcionalidades 13.2: Permissões
- **Descrição:** Grupos de permissões.
- **Requisitos para conclusão:**
  - [ ] listar todas as permissões de uso.
  - [ ] editar e/ou excluir permissões.
  - [ ] criar novo grupo de permissões.
- **Bugs/Erros:**
  - erro ao deletar grupo de permissão mensagem "Error Erro ao deletar regra"
- **Status:** [Em processo]

#### Funcionalidades 13.3: Todas as Permissões
- **Descrição:** Lista de todas as permissões disponiveis e sua respectiva tradução.
- **Requisitos para conclusão:**
  - [ ] listar todos as permissões de uso. assim como sua tradução.
  - [ ] editar traducão da permissao.
- **Bugs/Erros:**
  - erro ao deletar grupo de permissão mensagem "Error Erro ao deletar regra"
- **Status:** [Em processo]

---

### Módulo 14: Meus Dados

- **Descrição:** Formulario com todos os dados pessoais dos usuários. Além da foto do mesmo.
- **Requisitos para conclusão:**
  - [ ] Informações como tipo do privilegio, nome, email, cpf, numero do cracha, departamento do cracha
  - [ ] data nascimento, data de contratação, email corporativo
  - [ ] situação ativo, férias, inativo
- **Bugs/Erros:**
  - erro ao editar e/ou atualizar informações mensagem "Houve error! InvalidColumnEnumException"
- **Status:** [Em progresso]

---

## 4. Resumo do Status Geral  

| Módulo          | Funcionalidade         | Status           | Observações                   |
|------------------|------------------------|------------------|-------------------------------|
| [Nome do Módulo] | [Nome da Funcionalidade] | [Status Atual]   | [Notas relevantes, se houver.] |
| [Nome do Módulo] | [Nome da Funcionalidade] | [Status Atual]   | [Notas relevantes, se houver.] |

---

## 5. Considerações Finais  

Este documento será atualizado regularmente para refletir o progresso das funcionalidades e garantir a transparência e organização no desenvolvimento do projeto.  
