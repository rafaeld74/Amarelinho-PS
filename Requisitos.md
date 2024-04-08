# Documento de Requisitos

O aplicativo Amarelinho tem como objetivo conectar autônomos aos seus clientes de forma rápida e acessível, priorizando a simplicidade de uso e a qualidade dos serviços oferecidos. Este documento detalha os requisitos funcionais e não funcionais para o desenvolvimento do aplicativo.

## Requisitos Funcionais

### Autenticação e Usuário

- **RF01 - Registro de Usuário**
    - Como usuário, desejo criar uma conta no aplicativo para acessar os recursos disponíveis.

- **RF02 - Autenticação de Usuário**
    - Como usuário, desejo fazer login usando meu e-mail e senha para acessar minha conta.

- **RF10 - Edição de Perfil do Usuário**
    - Como usuário, desejo editar meu perfil para atualizar informações pessoais, de contato e profissionais.

- **RF11 - Preferências do Usuário**
    - Como usuário, desejo configurar minhas preferências no aplicativo (notificações, idioma, temas) para personalizar minha experiência.

### Exploração e Informações

- **RF03 - Busca de Profissionais**
    - Como cliente, desejo buscar profissionais por categoria ou serviço para encontrar o profissional adequado.

- **RF04 - Visualização de Perfil do Profissional**
    - Como cliente, desejo visualizar o perfil de um profissional para ver informações como serviços oferecidos, avaliações, fotos de trabalhos anteriores e informações de contato.

- **RF05 - Detalhamento do Profissional**
    - Como cliente, desejo ver informações detalhadas sobre um profissional, incluindo descrição, áreas de atuação, horários de disponibilidade e taxas.

- **RF12 - Busca Avançada de Profissionais**
    - Como cliente, desejo filtrar profissionais por localização, avaliação, e outros critérios para encontrar o profissional mais adequado às minhas necessidades.

- **RF13 - Sistema de Recomendação de Profissionais**
    - Como cliente, desejo receber recomendações de profissionais baseadas em minhas buscas anteriores, avaliações e preferências. (ideia a ser maturada)

### Interação e Comunicação

- **RF06 - Avaliação do Profissional**
    - Como cliente, desejo poder avaliar e deixar comentários sobre o profissional após receber o serviço.

- **RF07 - Chat em Tempo Real**
    - Como cliente, desejo poder contatar o profissional em tempo real através de um sistema de chat integrado ao aplicativo.

- **RF14 - Notificações Push**
    - Como usuário, desejo receber notificações push sobre atualizações importantes, mensagens recebidas e lembretes de compromissos. (ideia a ser maturada)

### Gerenciamento e Segurança de Dados

- **RF15 - Backup e Recuperação de Dados do Usuário**
    - Como usuário, desejo que meus dados sejam periodicamente salvos e facilmente recuperáveis em caso de perda ou necessidade de restauração.

- **RF16 - Log do Sistema**
    - Como administrador, desejo manter um registro de atividades do sistema para monitorar ações dos usuários, detectar comportamentos anormais e facilitar a solução de problemas.

### Acessibilidade e Idiomas

- **RF08 - Acessibilidade**
    - Como usuário, desejo acessar o aplicativo com facilidade, incluindo opções de contraste e tamanho de fonte para atender às minhas necessidades específicas.

- **RF09 - Suporte a Idiomas**
    - Como usuário, desejo poder visualizar o aplicativo em diferentes idiomas para atender a uma base diversificada de usuários.

## Requisitos Não Funcionais

### Requisitos de Processo

- **RNF01 - Metodologia de Desenvolvimento**
    - O projeto será desenvolvido utilizando a metodologia ágil Scrum, com iterações bem definidas e entregas incrementais.

- **RNF02 - Arquitetura do Aplicativo**
    - A aplicação seguirá uma arquitetura adequada para garantir a escalabilidade e manutenibilidade do sistema.

- **RNF03 - Design da Aplicação**
    - O design da aplicação será funcional e intuitivo, proporcionando uma experiência de usuário agradável.

### Segurança e Privacidade

- **RNF04 - Segurança dos Dados**
    - Os dados dos usuários serão armazenados de forma segura, utilizando técnicas de criptografia e proteção contra acessos não autorizados.

- **RNF05 - Privacidade do Usuário**
    - As informações dos usuários serão tratadas com confidencialidade e não serão compartilhadas com terceiros sem consentimento explícito.

- **RNF09 - Proteção Contra Fraudes e Ataques**
    - Implementar sistemas avançados de detecção e prevenção contra fraudes e ataques cibernéticos para proteger a integridade dos dados dos usuários e do sistema.

### Desempenho e Confiabilidade

- **RNF06 - Tempo de Resposta**
    - O aplicativo responderá às requisições dos usuários em um tempo máximo de 3 segundos para garantir uma experiência responsiva.

- **RNF10 - Alta Disponibilidade do Sistema**
    - O sistema deve ser projetado para garantir alta disponibilidade, com redundância e failover automático para evitar downtimes.

### Usabilidade e Interface

- **RNF07 - Interface Intuitiva**
    - A interface do aplicativo será intuitiva e fácil de usar, mesmo para usuários menos familiarizados com tecnologia.

- **RNF08 - Design Responsivo**
    - O aplicativo será responsivo e se adaptará a diferentes dispositivos e tamanhos de tela para proporcionar uma experiência consistente em todas as plataformas.

- **RNF11 - Personalização da Interface do Usuário**
    - A interface do aplicativo deve permitir personalizações pelo usuário, como temas claros e escuros, para melhorar a experiência do usuário.

### Extensibilidade e Manutenibilidade

- **RNF12 - Arquitetura Modular**
    - O aplicativo deve ser construído com uma arquitetura modular, facilitando a adição de novas funcionalidades, manutenção e atualizações futuras.

## Considerações Finais

Este documento de requisitos serve como um guia completo para o desenvolvimento do aplicativo Amarelinho. Com as adições feitas, abordamos aspectos importantes para garantir a segurança, usabilidade, personalização e eficiência do aplicativo. A equipe de desenvolvimento deve revisar periodicamente este documento, ajustando-o conforme necessário para refletir mudanças no escopo do projeto, feedback dos usuários e avanços tecnológicos.
