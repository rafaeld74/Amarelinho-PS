# Planejamento de tasks

## Sprint 1: Fundamentos e Autenticação

### Frontend
- **Estruturação inicial do projeto e configuração do ambiente de desenvolvimento (Dev 1)**
  - **Objetivo:** Configurar o ambiente de desenvolvimento frontend, incluindo a instalação de ferramentas necessárias (React Native), criação do repositório Git, e estruturação básica de pastas.
  - **Entregáveis:** Ambiente de desenvolvimento pronto, repositório criado com documentação inicial, e esqueleto do aplicativo com navegação básica.

- **Design e implementação da UI para registro de usuário (RF01) (Dev 2)**
  - **Objetivo:** Criar a interface de usuário para o registro, incluindo formulários para entrada de dados (nome, e-mail, senha) e validação de entrada.
  - **Entregáveis:** Telas de registro de usuário completas, com validação de campos e feedback visual para o usuário.

- **Design e implementação da UI para login de usuário (RF02) (Dev 3)**
  - **Objetivo:** Desenvolver a interface de login, permitindo que o usuário entre com e-mail e senha. Implementar feedback para tentativas de login falhas.
  - **Entregáveis:** Telas de login funcionais, com mecanismos de autenticação e feedback para o usuário.

### Backend
- **Configuração do servidor, banco de dados, e estruturação inicial da API (Dev 1)**
  - **Objetivo:** Configurar o ambiente de desenvolvimento backend, incluindo servidor (Node.js, Express - ver se é isso ou Python), banco de dados (MongoDB, PostgreSQL - a definir), e estruturação inicial das rotas da API.
  - **Entregáveis:** Servidor rodando localmente, conexão com o banco de dados estabelecida, e documentação inicial da API.

- **Implementação dos endpoints de registro de usuário (RF01) (Dev 2)**
  - **Objetivo:** Desenvolver a lógica para o registro de novos usuários, incluindo a validação de dados, criptografia de senha, e armazenamento de dados no banco.
  - **Entregáveis:** Endpoint de registro de usuário funcionando, com validação e segurança implementadas.

- **Implementação dos endpoints de login de usuário (RF02) (Dev 3)**
  - **Objetivo:** Criar a lógica de autenticação de usuário, permitindo o login com e-mail e senha, e a geração de tokens de acesso (JWT).
  - **Entregáveis:** Endpoint de login funcionando, com autenticação JWT e feedback de erros.

## Sprint 2: Exploração, Informação, e Edição de Perfil

### Frontend
- **Design e implementação da funcionalidade de busca de profissionais (RF03) (Dev 1)**
  - **Objetivo:** Criar uma interface de busca que permita aos usuários procurar por profissionais utilizando palavras-chave e filtros.
  - **Entregáveis:** Tela de busca implementada com funcionalidade de filtragem e visualização de resultados.

- **Implementação da UI para visualização e detalhamento de perfil do profissional (RF04, RF05) (Dev 2)**
  - **Objetivo:** Desenvolver telas para visualizar o perfil dos profissionais, incluindo informações detalhadas e galeria de imagens.
  - **Entregáveis:** Telas de perfil de profissionais com detalhamento de informações e visualização de avaliações e trabalhos anteriores.

- **Design e implementação da UI para edição de perfil do usuário (RF10) (Dev 3)**
  - **Objetivo:** Criar uma interface que permita aos usuários editar suas informações de perfil, incluindo dados pessoais, profissionais e preferências.
  - **Entregáveis:** Tela de edição de perfil funcional com validação de entrada e feedback de sucesso/erro.

### Backend
- **Desenvolvimento de APIs para busca de profissionais com filtros básicos (RF03) (Dev 1)**
  - **Objetivo:** Implementar a lógica no backend para permitir a busca de profissionais por nome, categoria, ou outras tags, incluindo filtros.
  - **Entregáveis:** Endpoint de busca com suporte a filtros implementado e documentado.

- **Implementação de endpoints para visualização e detalhamento de perfis profissionais (RF04, RF05) (Dev 2)**
  - **Objetivo:** Criar endpoints para fornecer informações detalhadas dos profissionais, incluindo descrição, avaliações e galeria de imagens.
  - **Entregáveis:** Endpoints para detalhamento de perfil de profissionais implementados, com suporte a múltiplos tipos de conteúdo.

- **Implementação de funcionalidades de edição de perfil do usuário (RF10) (Dev 3)**
  - **Objetivo:** Desenvolver a lógica para permitir que os usuários atualizem suas informações de perfil no sistema.
  - **Entregáveis:** Endpoint para edição de perfil de usuário, com validação e atualização de dados no banco.

## Sprint 3: Interação Avançada e Preferências

### Frontend
- **Implementação da UI para avaliação de profissionais (RF06) (Dev 1)**
  - **Objetivo:** Criar uma interface que permita aos clientes avaliar os profissionais, incluindo a atribuição de estrelas e a escrita de comentários.
  - **Entregáveis:** Tela de avaliação com sistema de estrelas e campo de texto para comentários, integrada ao perfil do profissional.

- **Design e implementação do chat em tempo real (RF07) (Dev 2)**
  - **Objetivo:** Desenvolver a interface de usuário para um sistema de chat em tempo real, permitindo a comunicação entre clientes e profissionais.
  - **Entregáveis:** Interface de chat funcional, com atualização em tempo real das mensagens.

- **Design e implementação das preferências do usuário (RF11) (Dev 3)**
  - **Objetivo:** Criar uma seção nas configurações do aplicativo onde os usuários podem ajustar suas preferências, incluindo notificações e idioma.
  - **Entregáveis:** Tela de configurações de preferências do usuário, com opções personalizáveis.

### Backend
- **Desenvolvimento da lógica e endpoints para avaliação de profissionais (RF06) (Dev 1)**
  - **Objetivo:** Implementar a funcionalidade que permite aos clientes avaliar os profissionais, armazenando as avaliações no banco de dados.
  - **Entregáveis:** Endpoint para criação de avaliações, incluindo lógica para calcular a média das avaliações do profissional.

- **Implementação da infraestrutura e endpoints para o chat em tempo real (RF07) (Dev 2)**
  - **Objetivo:** Desenvolver a lógica backend para suportar um sistema de chat em tempo real, utilizando WebSockets ou algo assim.
  - **Entregáveis:** Infraestrutura de chat em tempo real implementada, incluindo endpoints para enviar e receber mensagens.

- **Implementação de funcionalidades para gerenciamento de preferências do usuário (RF11) (Dev 3)**
  - **Objetivo:** Criar endpoints para que os usuários possam atualizar suas preferências no aplicativo, incluindo notificações e idioma.
  - **Entregáveis:** Endpoints para atualização de preferências do usuário, com validação e atualização de dados no banco.

## Sprint 4: Recomendações, Notificações, e Segurança

### Frontend
- **Design e implementação da interface para notificações push (RF14) (Dev 1)**
  - **Objetivo:** Integrar um sistema de notificações push no aplicativo, permitindo que os usuários recebam alertas sobre mensagens, avaliações e outros eventos relevantes.
  - **Entregáveis:** Sistema de notificações push funcional, testado e integrado ao aplicativo.

- **Integração do sistema de recomendação de profissionais na UI (RF13) (Dev 2)**
  - **Objetivo:** Desenvolver uma interface que mostre recomendações de profissionais baseadas nas preferências e histórico de busca do usuário.
  - **Entregáveis:** Seção de recomendações no aplicativo, exibindo profissionais sugeridos com base no algoritmo de recomendação.

- **Implementação da UI para configurações de backup e recuperação de dados do usuário (RF15) (Dev 3) - A se pensar**
  - **Objetivo:** Criar uma interface que permita aos usuários gerenciar o backup de seus dados e recuperá-los quando necessário.
  - **Entregáveis:** Tela de configurações para gerenciamento de backup e recuperação de dados, com instruções claras e opções de ação.

### Backend
- **Implementação da lógica de notificações push (RF14) (Dev 1)**
  - **Objetivo:** Desenvolver a funcionalidade backend para enviar notificações push para os dispositivos dos usuários, baseadas em eventos específicos.
  - **Entregáveis:** Serviço de notificações push implementado, com capacidade de envio de mensagens segmentadas baseadas em eventos.

- **Desenvolvimento do sistema de recomendação de profissionais (RF13) (Dev 2)**
  - **Objetivo:** Implementar um algoritmo de recomendação que sugira profissionais aos usuários com base em seus interesses, avaliações e histórico de buscas.
  - **Entregáveis:** Sistema de recomendação implementado, com algoritmo testado e integrado à API.

- **Implementação de funcionalidades para backup e recuperação de dados do usuário (RF15), além da implementação inicial do sistema de log (RF16) (Dev 3)**
  - **Objetivo:** Criar mecanismos para backup e recuperação de dados dos usuários, além de um sistema de log para registrar atividades no aplicativo.
  - **Entregáveis:** Funcionalidades de backup e recuperação de dados implementadas, sistema de log operacional para monitoramento de atividades.

## Sprint 5: Polimento, Testes, e Lançamento

### Frontend e Backend
- **Testes de integração e unitários, correção de bugs (Frontend Dev 1, Backend Dev 1)**
  - **Objetivo:** Realizar testes unitários e de integração em todo o aplicativo, identificando e corrigindo bugs.
  - **Entregáveis:** Relatórios de teste detalhados, código atualizado com bugs corrigidos.

- **Otimização de desempenho, segurança, e revisões de código (Frontend Dev 2, Backend Dev 2)**
  - **Objetivo:** Revisar o código para otimizações de desempenho, segurança, e conformidade com as melhores práticas.
  - **Entregáveis:** Código otimizado, relatório de revisão de segurança, atualizações aplicadas conforme as melhores práticas.

- **Preparação para o lançamento: documentação final, ajustes de última hora baseados em feedback de testes beta, e configurações de deploy (Frontend Dev 3, Backend Dev 3)**
  - **Objetivo:** Finalizar a documentação, fazer ajustes finais no aplicativo com base no feedback de testes beta e preparar o ambiente para o deploy.
  - **Entregáveis:** Documentação finalizada, aplicativo ajustado e pronto para o lançamento, estratégia de deploy definida e executada.
