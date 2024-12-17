![aabblogo](https://astecpmpa.com.br/wp-content/uploads/2018/01/Logo-AABB-600x416-600x330.jpg)
# Documento de Controle de Módulos e Funcionalidades

**Projeto:** MEU CLUBE

**Data de Criação:** 28/11/2024

# Índice
### <a href="#1-introdução">1. Introdução</a>
### <a href="#2-estrutura-do-documento">2. Estrutura do Documento</a>
### <a href="#3-lista-de-módulos-e-funcionalidades">3. Lista de Módulos e Funcionalidades</a>
- **<a href="#módulo-1-dashboard">1. Dashboard</a>**
- **<a href="#módulo-2-aposentados">2. Aposentados</a>**
   - <a href="#funcionalidade-21-almoço-de-quinta-feira">2.1 Almoço de Quinta Feira</a>
- **<a href="#módulo-3-biblioteca">3. Biblioteca</a>**
- **<a href="#módulo-4-eventos">4. Eventos</a>**
    - <a href="#funcionalidade-41-proximos-eventos">4.1 Proximos Eventos</a>
    - <a href="#funcionalidade-42-meus-ingressos">4.2 Meus Ingressos</a>
- **<a href="#módulo-5-locações">5. Locaçoes</a>**
    - <a href="#funcionalidade-51-espaços-para-locação">5.1 Espaços para Locações</a>
    - <a href="#funcionalidade-52-minhas-locações">5.2 Minhas Locaçoes</a>
- **<a href="#módulo-6-incrições-esportivas">6. Inscriçoes Esportivas (em contruçao)</a>**
- **<a href="#módulo-7-marque">7. Marque</a>**
    - <a href="#funcionalidade-71-quadra">7.1 Quadra</a>
    - <a href="#funcionalidade-72-raias">7.2 Raias</a>
    - <a href="#funcionalidade-73-espaços-para-locação">7.3 Espaços para Locaçao</a>
    - <a href="#funcionalidade-74-coworking">7.4 Coworking</a>
    - <a href="#funcionalidade-75-minhas-reservas">7.5 Minhas Reservas</a>
- **<a href="#módulo-8-meus-dados">8. Meus Dados</a>**
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

### Módulo 1: Dashboard

**Descrição:** Um resumo com dados pessoais do associado como cadastro, programa de fidelidade e minhas reservas.
- **Requisitos para conclusão:**  
  - [ ] Mostrar cadastro completo ou nao, porcentagem de preenchimento.
  - [ ] As reservas feitas.
  - [ ] Programa de Fidelidade.
- **Bugs/Erros:**  
  - Erro gramatical em "trocar seus ponto"
- **Status:** [Em progresso]

---

### Módulo 2: Aposentados

**Descrição:** Gerenciar o almoço de Quinta Feira dos associados.

#### Funcionalidade 2.1: Almoço de Quinta Feira
- **Descrição:** Listar os proximos almocos de quinta feira.
- **Requisitos para conclusão:**  
  - [ ] Listar os proximos almocos com suas datas e informações.
 - **Bugs/Erros:**  
   - nao foram encontrados erros.
- **Status:** [Em Validação] 

---

### Módulo 3: Biblioteca

**Descrição:** Exibição com exemplares no acervo da biblioteca.
- **Requisitos para conclusão:**  
  - [ ] Pesuisar exemplares. 
  - [ ] Obter detalhes de um exemplar especifico.
  - [ ] Favoritar algum exemplar especifico.
  - [ ] ver marc tags.
- **Bugs/Erros:**  
  - Carregar pre visualizacao das imagens dos exemplares.
  - mudar de "pesquisar por titulo" para "pesquisar"
- **Status:** [Em progresso]

---

### Módulo 4: Eventos

**Descrição:** Listar todos os eventos disponiveis do clube.

#### Funcionalidade 4.1: Proximos Eventos
**Descrição:** Mostrar os proximos eventos do clube.
- **Requisitos para conclusão:**  
  - [ ] Listar os proximos eventos.
  - [ ] possibildade de compra/inscrição no evento.
- **Bugs/Erros:**  
  - nenhum evento listado. 
- **Status:** [Em progresso]

#### Funcionalidade 4.2: Meus Ingressos
- **Descrição:** Lista dos ingressos que o associado possui.
- **Requisitos para conclusão:**  
  - [ ] Listar todos os ingressos disponiveis.
  - [ ] Exibir detalhes dos ingressos.
- **Bugs/Erros:**  
   - seçao inoperante, sem acesso.
- **Status:** [Em progresso]

---

### Módulo 5: Locações

**Descrição:** Locação de espaços, salões... inserir carrossel de fotos para fomentar o marketing e tornar mais "vendável". (talvez na opcão de abas deixar uma especifica para fotos em carrossel).

#### Funcionalidade 5.1: Espaços para Locação
- **Descrição:** Locação de espaços, salões, armários e materiais (com e sem custos), emissão de contrato, controle de prazos de pré-reservas e lista de interessados.
Regras para locação, moldes e limites com rotinas parametrizáveis: pré-reservas, lista de interessados e reservas com periodicidade.
- **Requisitos para conclusão:**  
  - [ ] Listar os espaços disponiveis para locação.
  - [ ] Exibir detalhes dos espaços como fotos e textos.
  - [ ] Carrossel de fotos para marketing.
- **Bugs/Erros:**  
  - Seção em funcionamento. Adicionar um carrossel de fotos para que atraia mais locações através do marketing.
- **Status:** [Em progresso]

#### Funcionalidade 5.2: Minhas Locações
- **Descrição:** É exibido os espaços locados pelo associado.
- **Requisitos para conclusão:**  
  - [ ] Listar os espaços que o associado locou.
  - [ ] Gerenciar locações.
  - [ ] Depois que for aprovado, bloquear a opção do usuario editar o que foi enviado na prosposta.
- **Bugs/Erros:**  
   - locações listadas corretamente esperando aprovação do setor responsável.
- **Status:** [Em progresso]

---

### Módulo 6: Incrições Esportivas

- **Descrição:** Módulo onde é possivel o associado se inscrever e gerenciar inscrições em atividades esportivas.
- **Requisitos para conclusão:**  
  - [ ] Listar as atividades esportivas disponiveis para inscrição.
  - [ ] Exibir detalhes das atividades.
  - [ ] Gerenciar Inscrições.
- **Bugs/Erros:**  
  - seçao indisponivel, sem acesso.
- **Status:** [Em progresso]

---

### Módulo 7: Marque

**Descrição:** Destinado a marcação de quadras e espaços.

#### Funcionalidade 7.1: Quadra
- **Descrição:** O associado consegue agendar quadras e espaços além gerenciar suas reservas. É mostrado os locais disponiveis para agendamento assim como disponibilidade de dias e horarios.
- **Requisitos para conclusão:**  
  - [ ] Listar as quadras disponiveis e suas regras.
  - [ ] Exibir detalhes das datas e horarios disponiveis.
  - [ ] Gerenciar os agendamentos.
- **Bugs/Erros:**  
  - nao foram encontrados erros.
- **Status:** [Em progresso]

#### Funcionalidade 7.2: Raias
- **Descrição:** O associado consegue agendar raias e gerenciar suas reservas. É mostrado os locais disponiveis para agendamento assim como disponibilidade de dias e horarios.
- **Requisitos para conclusão:**  
  - [ ] Listar as raias disponiveis e suas regras.
  - [ ] Exibir detalhes das datas e horarios disponiveis.
  - [ ] Gerenciar os agendamentos.
- **Bugs/Erros:**  
  - nao foram encontrados erros.
- **Status:** [Em progresso]

#### Funcionalidade 7.3: Espaços para Locação
- **Descrição:** O associado consegue locar espaços e gerenciar suas reservas. É mostrado os locais disponiveis para agendamento assim como disponibilidade de dias e horarios.
- **Requisitos para conclusão:**  
  - [ ] Listar os locais disponiveis e suas regras.
  - [ ] Exibir detalhes das datas e horarios disponiveis.
  - [ ] Gerenciar as locações.
- **Bugs/Erros:**  
  - nao foram encontrados erros.
- **Status:** [Em progresso]

#### Funcionalidade 7.4: Coworking
**Descrição:** Destinado a locação da sala de coworking.
- **Requisitos para conclusão:**  
  - [ ] Listar a sala disponivel e suas regras.
  - [ ] Exibir detalhes das datas e horarios disponiveis.
  - [ ] Gerenciar as locações.
- **Bugs/Erros:**  
   nao foram encontrados erros.
- **Status:** [Em progresso]

#### Funcionalidade 7.5: Minhas Reservas
**Descrição:** Lista com todas as locações e agendamentos do associado.
- **Requisitos para conclusão:**  
  - [ ] Listar a sala disponivel e suas regras.
  - [ ] Exibir detalhes das datas e horarios disponiveis.
  - [ ] Gerenciar as locações.
- **Bugs/Erros:**  
  - nao foram encontrados erros.
- **Status:** [Em progresso]

---

### Módulo 8: Meus Dados

**Descrição:** Destinado aos dados pessoais do associado. Informações do cadastro e foto de perfil.
- **Requisitos para conclusão:**  
  - [ ] Exibir todos os dados do associado.
  - [ ] Gerenciar suas informações pessoais e de cadastro.
- **Bugs/Erros:**  
  - nao foram encontrados erros.
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
