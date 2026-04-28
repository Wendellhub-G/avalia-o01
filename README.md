# avaliação - 01

# DailyFlow

> Estruturar o fluxo de foco e organização diária do usuário, reduzindo a carga cognitiva através da exibição seletiva de tarefas e rotinas de fechamento inteligentes.

![Banner do Projeto](assets/banner.png)

---

# 1. Identificação do Projeto

## Equipe
- Wendell Gabryel
- Karla Cristine
- Matheus Leal
- Luiz Felipe
- Ana Clara

## Disciplina
Projeto Integrador

## Professor
Ely da Silva Miranda

---

# 2. Problema a ser Resolvido

> Dificuldade em manter o foco e organizar as atividades diárias devido ao excesso de informações visíveis simultaneamente, gerando sobrecarga cognitiva e desorganização pessoal.

---

# 3. Objetivo do Projeto

> Desenvolver uma aplicação web que funcione como um gerenciador de tarefas inteligente, onde o sistema exibe inicialmente apenas as atividades prioritárias para manter o foco do usuário, oferecendo ainda uma rotina de fechamento diário para organizar o dia seguinte.

---

# 4. Público-Alvo

- Estudantes
- Profissionais autônomos
- Pessoas que buscam produtividade e organização pessoal
- Usuários que sentem dificuldade em gerenciar múltiplas tarefas

---

# 5. Tecnologias Utilizadas

| Área | Tecnologia |
|------|------------|
| Front-end | HTML / CSS / JavaScript / React |
| Back-end | Node.js |
| Banco de Dados | MySQL |
| Prototipação | Figma |
| Gestão | Organização interna da equipe |

---

# 6. Requisitos do Sistema

## Atores
- **Usuário Final:** Pessoa que utiliza o aplicativo para organizar suas tarefas e rotinas diárias.
- **Sistema:** Responsável pelo armazenamento, processamento e exibição das informações, além de executar as regras de negócio.

## Regras de Negócio
- Cada usuário tem acesso exclusivo apenas aos seus próprios dados e tarefas cadastradas.
- As tarefas são classificadas por níveis de prioridade (1 - Principal, 2 - Secundária, 3 - Terciária), sendo exibidas inicialmente apenas as de maior relevância.
- O cadastro de usuários é realizado em etapas para facilitar o preenchimento e evitar cansaço no processo.
- O campo de endereço é opcional, podendo ser deixado em branco pelo usuário.
- Não é permitido o cadastro de usuários com e-mail ou telefone já registrados no sistema.
- Ao final do dia, o sistema apresenta uma rotina para o usuário definir o destino das tarefas pendentes, podendo ser marcadas como concluídas, adiadas ou descartadas.
- Os dados dos usuários são mantidos de forma segura, com armazenamento da senha apenas no formato de hash.

## Backlog

| ID | Item | Prioridade | Status |
|----|------|------------|--------|
| 1 | Autenticação de usuários (cadastro e login) | Alta | Em desenvolvimento |
| 2 | Operações de criação, leitura, atualização e exclusão de tarefas | Alta | Em desenvolvimento |
| 3 | Lógica de exibição seletiva e filtro de tarefas por prioridade | Alta | Em desenvolvimento |
| 4 | Tela de boas-vindas e criação da primeira tarefa | Média | Planejado |
| 5 | Painel de perfil com dados do usuário e métricas de produtividade | Média | Planejado |
| 6 | Rotina de fechamento diário para organização de pendências | Média | Planejado |

## Histórias de Usuário

- **Registro de Usuário Personalizado:** Como um novo usuário, quero realizar meu cadastro de forma parcelada em etapas, para que o processo de adesão ao app não seja cansativo e meus dados fiquem organizados.
- **Onboarding e Engajamento Inicial:** Como um usuário recém-cadastrado, quero receber uma saudação personalizada e criar minha primeira tarefa imediatamente, para começar minha organização sem barreiras.
- **Gestão de Foco Seletivo:** Como um usuário com muitas atividades, quero que apenas os focos principais apareçam na tela inicial, para reduzir minha carga cognitiva e facilitar o foco no que é mais importante.
- **Rotina de Fechamento Diário:** Como um usuário que encerra seu ciclo de atividades, quero decidir o destino das tarefas acumuladas, para que o dia seguinte comece organizado e limpo.

---

# 7. Modelagem do Sistema

## Diagrama de Casos de Uso
![Casos de Uso](casos-de-uso.png)
> *Em elaboração. O mapeamento das interações entre usuário e sistema já foi definido conceitualmente, e o diagrama visual será finalizado na próxima etapa de desenvolvimento.*

## Fluxo de Telas
![Fluxo de Telas](fluxo-de-telas.png)
> *Definido através do protótipo desenvolvido no Figma. A sequência de navegação entre as telas já foi estabelecida, e o diagrama de fluxo será gerado posteriormente.*

## Arquitetura
![Arquitetura](arquitetura.png)
> *Conceito definido com estrutura dividida em interface com o usuário, regras de negócio e armazenamento de dados. O diagrama detalhado será produzido na fase de implementação.*

## Modelo Entidade-Relacionamento 
![Modelo ER](modelo-er.png)
> *Entidades e seus relacionamentos definidos: Usuários e Tarefas, com vínculo de um para muitos. O diagrama visual será gerado com base na estrutura do banco de dados apresentada.*

## Diagrama de Classes

> *Ainda não elaborado. Será desenvolvido durante a fase de codificação, após a definição completa das classes e estruturas de dados do sistema.*

---

# 8. Protótipos

## Tela de Login
![Tela de Login](<img width="1411" height="797" alt="image" src="https://github.com/user-attachments/assets/95417bb7-fabe-4149-bb58-4a9384d4852d" />
)
> *Tela de acesso ao sistema, com campos para e-mail ou telefone e senha, além de link para cadastro de novos usuários.*

## Tela de Cadastro
![Tela de Cadastro](<img width="1377" height="800" alt="image" src="https://github.com/user-attachments/assets/48d3c13b-706e-47d8-8090-1fd042a43d51" />
)
> *Primeira etapa do cadastro, com campos para dados básicos do usuário, data de nascimento, gênero e endereço (opcional), com navegação para as próximas etapas.*

## Tela Principal - Dashboard
![Tela Principal](<img width="1546" height="849" alt="image" src="https://github.com/user-attachments/assets/71e7515a-9164-49e2-ac73-b65e752567b1" />
)
> *Área principal do sistema, com saudação personalizada, exibição de tarefas prioritárias, opção para visualizar tarefas secundárias e botão para adicionar novas atividades.*

## Tela de Perfil
![Tela de Perfil](<img width="1673" height="805" alt="image" src="https://github.com/user-attachments/assets/64eb9a7f-ec09-43a9-b1ae-85f9858abb5e" />
)
> *Exibição dos dados cadastrados do usuário, objetivo principal definido e métricas de produtividade e desempenho semanal.*

---

# 9. Planejamento do Projeto

## Cronograma
| Etapa | Período | Status |
|------|---------|--------|
| Levantamento de requisitos e definição do escopo | Início do projeto | Concluído |
| Criação de protótipos e definição de fluxos de navegação | Etapa atual | Em andamento |
| Modelagem do sistema e estruturação do banco de dados | Próxima etapa | Concluído conceitualmente |
| Desenvolvimento do código e implementação das funcionalidades | Etapa final | Previsto |
| Testes, ajustes e entrega final | Etapa final | Previsto |

## Sprints
| Sprint | Entregas Previstas |
|-------|----------|
| Sprint 1 | Definição de requisitos, elaboração do documento de escopo e criação dos protótipos de tela. |
| Sprint 2 | Estruturação do banco de dados, definição dos relacionamentos e preparação do ambiente de desenvolvimento. |
| Sprint 3 | Desenvolvimento da interface do usuário, implementação da autenticação e das operações básicas de tarefas. |
| Sprint 4 | Finalização das funcionalidades, ajustes visuais, testes e documentação final. |

## Gestão das Tarefas
Ainda não feito, estara em produção
> *Acompanhamento e divisão das atividades são realizados de forma organizada entre os membros da equipe, sem uso de ferramenta específica de gestão no momento.*

## Histórico de Entregas
- Entrega 1: Documento com definição do objetivo, requisitos e fluxos do sistema.
- Entrega 2: Protótipo completo das telas e fluxos de navegação desenvolvido no Figma.
- Entrega 3: Estruturação do repositório, organização da documentação e definição da estrutura do banco de dados.

---

# 10. Banco de Dados

## Estrutura
Arquivos disponíveis:
- `database/ddl.sql`
- `database/dml.sql`
- `database/schema.sql`
- `database/seeds.sql`

### Conteúdo do arquivo `ddl.sql`:
```sql
-- Tabela de Usuários (Registro Completo)
CREATE TABLE usuarios (
    id_usuario SERIAL PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    data_nascimento DATE NOT NULL,
    sexo VARCHAR(20), -- Masculino, Feminino
    email VARCHAR(100) UNIQUE NOT NULL,
    telefone VARCHAR(20) NOT NULL,
    senha_hash VARCHAR(255) NOT NULL,
    endereco VARCHAR(255), -- Campo Opcional
    objetivo_foco TEXT,
    data_criacao TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

-- Tabela de Tarefas
CREATE TABLE tarefas (
    id_tarefa SERIAL PRIMARY KEY,
    id_usuario INTEGER NOT NULL,
    titulo VARCHAR(150) NOT NULL,
    descricao TEXT,
    prioridade INTEGER CHECK (prioridade IN (1, 2, 3)), -- 1: Principal, 2: Secundária, 3: Terciária
    status VARCHAR(20) DEFAULT 'pendente', -- pendente, concluida, descartada, adiada
    data_agendada DATE NOT NULL,
    criado_em TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    CONSTRAINT fk_usuario FOREIGN KEY (id_usuario) REFERENCES usuarios(id_usuario) ON DELETE CASCADE
);
Modelo Visual
Diagrama baseado nas tabelas criadas, demonstrando a relação entre usuários e suas respectivas tarefas.
Observações

• A estrutura foi desenvolvida para garantir a integridade dos dados, com chave estrangeira que vincula cada tarefa ao seu respectivo usuário.

• Foi aplicada restrição de valores na coluna de prioridade, permitindo apenas os níveis definidos nas regras de negócio.

• O campo de senha é armazenado apenas como hash, garantindo a segurança das informações dos usuários.

• Campos opcionais foram definidos sem restrição de preenchimento, conforme solicitado nos requisitos.

• As colunas de data e hora são preenchidas automaticamente no momento do cadastro, facilitando o controle de criação dos registros.
11. Implementação

Backend
Estrutura inicial do servidor em organização. As rotas para autenticação, cadastro de usuários e gerenciamento de tarefas estão sendo planejadas com base na estrutura do banco de dados definida.
Frontend
Interface projetada e definida através dos protótipos. A conversão dos layouts para código está iniciada, com foco na estruturação das telas principais e na definição dos estilos visuais.
Funcionalidades Concluídas

• Definição completa de requisitos, regras de negócio e fluxos do sistema.

• Criação do protótipo de todas as telas e fluxos de navegação.

• Estruturação do banco de dados e criação dos scripts de criação de tabelas.

• Organização da documentação e estruturação do repositório no GitHub.

Funcionalidades em Desenvolvimento

• Codificação da interface gráfica e estilização das telas.

• Implementação da conexão com o banco de dados.

• Desenvolvimento da lógica de filtro e exibição seletiva de tarefas.
12. Evidências do Projeto

Protótipo do Sistema
Layouts e fluxos de navegação definidos e aprovados pela equipe.
Estrutura do Banco de Dados
Definição das tabelas e relacionamentos que compõem a base de dados do sistema.
13. Itens Ainda Não Produzidos

Diagrama de Casos de Uso, Arquitetura e Classes

Motivo da ausência: Esses artefatos dependem da finalização da definição técnica e da estrutura de código do sistema.
Etapa de produção: Sprint 2 e início da Sprint 3.
Previsão de entrega: Até o final da fase de modelagem e início da implementação.
Responsável: Equipe de desenvolvimento.

Arquivos de Inserção de Dados e Exportação Completa

Motivo da ausência: Ainda estamos definindo os dados iniciais e testes para popular o banco.
Etapa de produção: Sprint 2.
Previsão de entrega: Após a conclusão da estrutura das tabelas.
Responsável: Membros responsáveis pela modelagem de dados.

Código Funcional Completo

Motivo da ausência: O desenvolvimento está em fase inicial, com foco atual na definição de requisitos e estruturação técnica.
Etapa de produção: Sprint 3 e Sprint 4.
Previsão de entrega: Final do projeto.
Responsável: Toda a equipe de desenvolvimento.
14. Como Executar o Projeto

O sistema é uma aplicação web que pode ser executada diretamente em navegadores. Para acessar e visualizar o projeto, e configurar o banco de dados:
# Clonar o repositório para o seu computador
git clone https://github.com/Wendellhub-G/DailyFlow.git

# Acessar a pasta do projeto
cd DailyFlow

# Para configurar o banco de dados:
# 1. Acesse o seu gerenciador de banco de dados MySQL
# 2. Crie um novo banco de dados com o nome "dailyflow"
# 3. Execute o conteúdo do arquivo localizado em: /database/ddl.sql

# Para visualizar a interface:
# Abra o arquivo principal no navegador de sua preferência
# Exemplo para Windows:
start index.html

# Exemplo para Linux/macOS:
open index.html
Observação: As funcionalidades completas serão disponibilizadas conforme o desenvolvimento avança. Para execução do sistema com todas as regras e conexão com o banco de dados, será necessário configurar o ambiente de desenvolvimento com as tecnologias definidas.
