# ToDoList - Sistema de Gerenciamento de Tarefas

### 👤 Identificação do Projeto
* *Integrantes:* Ana Julia Bernardino Klenk, André Felipe Lima de Almdeida, João Pedro Galdino e Silva.
* *Curso:* Análise e Desenvolvimento de Sistemas
* *Turma:* 402
* *Disciplina:* Tópicos Especiais de Sistemas

---

### 📝 Resumo
O *ToDoList* é uma aplicação desenvolvida em C# voltada para a organização de produtividade pessoal e corporativa. O sistema permite que usuários gerenciem suas demandas diárias por meio de uma interface estruturada, garantindo que tarefas sejam registradas, priorizadas e monitoradas de forma eficiente. Utilizando uma arquitetura baseada em modelos de dados e persistência em banco de dados, a ferramenta oferece uma solução robusta para o controle de fluxos de trabalho, auxiliando tanto indivíduos quanto pequenas equipes na otimização de tempo e organização de metas.

---

### 🚀 Funcionalidades
* *Gestão de Tarefas (CRUD):* Criação, edição, exclusão e visualização de itens.
* *Categorização de Demandas:* Organização de tarefas por projetos ou áreas específicas.
* *Atribuição de Status:* Controle de progresso (Pendente, Em Andamento, Concluído).
* *Definição de Prioridades:* Classificação de urgência para melhor tomada de decisão.
* *Persistência de Dados:* Armazenamento seguro de todas as informações em banco de dados.

---

### 🔍 Descrição das Funcionalidades

#### 1. Gerenciamento Completo de Entidades (CRUD)
O núcleo do sistema é fundamentado no conceito de CRUD (Create, Read, Update, Delete). Isso permite que o usuário tenha controle total sobre as tabelas do banco de dados, podendo inserir novas tarefas ou categorias, consultar a lista existente em tempo real, atualizar informações conforme a necessidade e remover registros obsoletos, mantendo a integridade dos dados.

#### 2. Estrutura Multicamadas (Modelos e Classes)
Seguindo os requisitos acadêmicos, o projeto utiliza entre 2 a 4 entidades principais (como Tarefa, Categoria e Usuario), que representam as tabelas no banco de dados. Essa estrutura permite relacionamentos entre os dados, como vincular uma tarefa específica a uma categoria de "Trabalho" ou "Estudos".

#### 3. Controle de Status e Priorização
Cada tarefa possui atributos específicos que definem seu estado atual e sua relevância. A funcionalidade de alteração permite que o usuário mova uma tarefa de "Pendente" para "Concluída" de forma intuitiva, enquanto o sistema de prioridades ajuda a destacar o que deve ser feito primeiro, aumentando a eficácia da ferramenta no ambiente empresarial.

#### 4. Listagem Dinâmica
O sistema oferece uma visualização clara de todos os registros armazenados. A funcionalidade de listagem recupera os dados do banco e os apresenta de forma organizada, facilitando a leitura e o acompanhamento das atividades pendentes de forma ágil.

---

### 📂 Repositório
O código-fonte completo, scripts de banco de dados e arquivos de configuração estão disponíveis neste repositório para fins de avaliação e consulta.

---

### 💡 Dica para o seu projeto:
Como o professor pediu de 2 a 4 classes, uma estrutura comum para um ToDoList nota 10 seria:
1.  *Tarefa* (ID, Título, Descrição, Data, StatusID, CategoriaID)
2.  *Categoria* (ID, Nome, Cor)
3.  *Status* (ID, Descrição - ex: Pendente, Concluído)
