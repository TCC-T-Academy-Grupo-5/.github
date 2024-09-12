# Backlog de Produto

## 1. Visão do Produto

### Objetivo:
Desenvolver uma plataforma que permita a busca e comparação de veículos novos e usados de lojas online, com base na Tabela FIPE e no monitoramento de ofertas abaixo do valor de referência. A plataforma oferecerá alertas personalizados e gráficos de tendências de preços, permitindo compras mais informadas.

### Ações:
**Público-Alvo:** Consumidores que estão em processo de compra de veículos novos ou usados, buscando as melhores ofertas online, economizando tempo e dinheiro.

### Principais Benefícios
- **Economia de tempo e dinheiro:** Comparação rápida de preços de várias lojas online com base em dados em tempo real e comparação com a Tabela FIPE.
- **Alertas Personalizados:** Monitoramento de preços com alertas automáticos para ofertas abaixo da Tabela FIPE ou de interesse do usuário.
- **Visão clara do mercado:** Gráficos de tendências de preços com histórico, ajudando os usuários a identificar o momento ideal para a compra.
- **Avaliação de Lojas:** Sistema de classificação baseado em avaliações e feedback de outros consumidores, facilitando a escolha das melhores lojas.
- Discutir com as partes interessadas para alinhar as expectativas.

## 2. Stakeholders e Usuários

### Stakeholders
- Usuários finais
- Visitantes
- Membros
- Desenvolvedores
- Investidores (Interessados no sucesso da plataforma)
- Administradores: Gerenciam a plataforma, ajustam configurações de scraping, e monitoram o desempenho do sistema.

### Usuários
- Visitantes (usuários não registrados)
- Membros (usuários registrados)
- Lojas de veículos (Vendedores que desejam listar seus carros no app)
- Administradores (gerenciar usuários e catálogos de veículos)

## 3. Épicos e Temas

### Épicos
- Funcionalidades do usuário
- Comparação, busca e análise de preços
- Web scraping de sites relacionados a carros
- Integração com API da tabela FIPE

## 4. Divisão dos Épicos

### Épico: Funcionalidades do usuário
- **US13** - Eu, como visitante, quero criar cadastro na plataforma, para ter acesso a todas as funcionalidades exclusivas de membros
- **US02** - Eu, como usuário logado, quero configurar alertas para ser notificado quando o preço de um veículo estiver abaixo do valor da tabela FIPE, para não precisar verificar constantemente a plataforma
- **US03** - Eu, como usuário logado, quero adicionar veículos a minha lista de favoritos, assim poderei terei um lugar para verificar os veículos que gostei
- **US11** - Como usuário, quero visualizar veículos por categoria (pick-up, SUV, Sedan, Hatch, Elétrico...), A busca deve ser intuitiva com cards ou algo parecido para um clique rápido.
- **US10** - Como administrador da plataforma, quero gerenciar os veículos cadastrados, para garantir que a plataforma tenha as informações relevantes dos veículos disponíveis
- **US12** - Como usuário logado, quero avaliar lojas de veículos, para ajudar outros usuários a tomarem decisões confiáveis ao escolherem onde comprar.

### Épico: Comparação, busca e análise de preços
- **US01** - Eu, como visitante, quero buscar veículos por marca, modelo, ano e localização, para que eu possa comparar os preços em diferentes sites
- **US04** - Eu, como usuário logado, quero selecionar dois veículos ou mais, para comparar preços e especificações
- **US09** - Como usuário, quero comparar os preços dos veículos disponíveis com os valores da Tabela FIPE, para que eu possa tomar decisões de compra informadas

### Épico: Web scraping de sites relacionados a carros
- **US06** - Como administrador da plataforma, quero que os dados da Tabela FIPE sejam atualizados regularmente, para que as comparações de preços estejam sempre baseadas em informações recentes
- **US07** - Como usuário da plataforma, quero que o sistema colete os preços dos veículos de diversas lojas online, para que eu possa compará-los com a Tabela FIPE

### Épico: Integração com API da tabela FIPE
- **US05** - Como desenvolvedor, quero integrar a plataforma com a API da Tabela FIPE, para que os valores de referência dos veículos estejam disponíveis para comparação.

## 5. Priorização do Backlog

### Prioridade Alta:
- **US01** - Eu, como visitante, quero buscar veículos por marca, modelo, ano e localização, para que eu possa comparar os preços em diferentes sites
- **US13** - Eu, como visitante, quero criar cadastro na plataforma, para ter acesso a todas as funcionalidades exclusivas de membros
- **US04** - Eu, como usuário logado, quero selecionar dois veículos ou mais, para comparar preços e especificações
- **US05** - Como desenvolvedor, quero integrar a plataforma com a API da Tabela FIPE, para que os valores de referência dos veículos estejam disponíveis para comparação.
- **US06** - Como administrador da plataforma, quero que os dados da Tabela FIPE sejam atualizados regularmente, para que as comparações de preços estejam sempre baseadas em informações recentes
- **US07** - Como usuário da plataforma, quero que o sistema colete os preços dos veículos de diversas lojas online, para que eu possa compará-los com a Tabela FIPE
- **US09** - Como usuário, quero comparar os preços dos veículos disponíveis com os valores da Tabela FIPE, para que eu possa tomar decisões de compra informadas

### Prioridade Média:
- **US02** - Eu, como usuário logado, quero configurar alertas para ser notificado quando o preço de um veículo estiver abaixo do valor da tabela FIPE, para não precisar verificar constantemente a plataforma
- **US03** - Eu, como usuário logado, quero adicionar veículos a minha lista de favoritos, assim poderei terei um lugar para verificar os veículos que gostei
- **US12** - Como usuário logado, quero avaliar lojas de veículos, para ajudar outros usuários a tomarem decisões confiáveis ao escolherem onde comprar.

### Prioridade Baixa:
- **US11** - Como usuário, quero visualizar veículos por categoria (pick-up, SUV, Sedan, Hatch, Elétrico...), A busca deve ser intuitiva com cards ou algo parecido para um clique rápido.
- **US10** - Como administrador da plataforma, quero gerenciar os veículos cadastrados, para garantir que a plataforma tenha as informações relevantes dos veículos disponíveis

## 6. Refinamento de Histórias de Usuário

### US01 - Eu, como visitante, quero buscar veículos por marca, modelo, ano e localização, para que eu possa comparar os preços em diferentes sites
**Critérios de aceitação:**
- Usuário pode inserir filtros de busca (marca, modelo, ano, localização)
- Usuário visualiza lista de veículos com preços de lojas diferentes
- A lista destaca quais preços estão abaixo, próximos ou acima do valor da tabela FIPE

### US13 - Eu, como visitante, quero criar cadastro na plataforma, para ter acesso a todas as funcionalidades exclusivas de membros
**Critérios de aceitação:**
- O usuário deve se cadastrar com nome, email, telefone, cidade, tipos de veículo favoritos, estado, e senha

### US02 - Eu, como usuário logado, quero configurar alertas para ser notificado quando o preço de um veículo estiver abaixo do valor da tabela FIPE, para não precisar verificar constantemente a plataforma
**Critérios de aceitação:**
- O usuário pode definir um valor de referência
- O sistema envia notificação por e-mail quando um veículo corresponder aos critérios definidos pelo usuário
- Interface para configurar alertas de preço com base em modelo, ano e valor.

### US03 - Eu, como usuário logado, quero adicionar veículos a minha lista de favoritos, assim poderei terei um lugar para verificar os veículos que gostei
**Critérios de Aceitação:**
- O usuário deve poder adicionar um veículo à lista de favoritos com um único clique em um ícone de "favorito" na página de detalhes do veículo.
- A lista de veículos favoritos deve ser acessível a partir do perfil do usuário, com a capacidade de visualizar todos os veículos adicionados.
- O usuário deve poder remover veículos da lista de favoritos a qualquer momento, e as mudanças devem ser salvas automaticamente.

### US04 - Eu, como usuário logado, quero selecionar dois veículos ou mais, para comparar preços e especificações
**Critérios de aceitação:**
- O usuário deve poder selecionar dois ou mais veículos diferentes de uma lista
- Após selecionar, o usuário clica em um botão para comparar, e visualiza o comparativo
- Cada coluna do comparativo informa o menor preço localizado para o veículo
- O comparativo deve ter links para a página de cada carro

### US05 - Como desenvolvedor, quero integrar a plataforma com a API da Tabela FIPE, para que os valores de referência dos veículos estejam disponíveis para comparação.
**Critérios de Aceitação:**
- A integração com a API da Tabela FIPE deve retornar os valores de referência corretos para cada modelo de veículo disponível, considerando marca, modelo e ano.
- O sistema deve armazenar os valores de referência em um banco de dados para consulta rápida durante as comparações de preços.
- Em caso de falha na conexão com a API da Tabela FIPE, o sistema deve registrar um log de erro e notificar o desenvolvedor.

### US06 - Como administrador da plataforma, quero que os dados da Tabela FIPE sejam atualizados regularmente, para que as comparações de preços estejam sempre baseadas em informações recentes
**Critérios de Aceitação:**
- O sistema deve realizar atualizações automáticas dos dados da Tabela FIPE diariamente, com a opção de ajustar a frequência de atualização conforme necessário.
- O sistema deve enviar uma notificação ao administrador caso uma atualização falhe, com detalhes do erro para resolução.
- O histórico das atualizações de dados deve ser registrado e acessível ao administrador, incluindo a data e a hora de cada atualização.
- Implementar mecanismos de fallback para casos de indisponibilidade da API da FIPE.

### US07 - Como usuário da plataforma, quero que o sistema colete os preços dos veículos de diversas lojas online, para que eu possa compará-los com a Tabela FIPE, para saber se estou fazendo um bom negócio.
**Critérios de Aceitação:**
- O sistema deve coletar os preços de veículos de pelo menos três sites de lojas online diferentes (por exemplo: OLX, Webmotors) e armazená-los para comparação.
- Os dados coletados devem incluir o preço, características do veículo (marca, modelo, ano), e informações da loja (nome, localização).
- Em caso de erro na coleta de dados, o sistema deve continuar a tentar coletar informações de outras lojas e notificar o administrador sobre o site que falhou.

### US08 - Como administrador da plataforma, quero que os preços dos veículos sejam atualizados periodicamente, para que os usuários tenham acesso a informações atuais
**Critérios de Aceitação:**
- O sistema deve atualizar os preços dos veículos a cada 24 horas ou em um intervalo configurável pelo administrador.
- Durante a atualização, o sistema deve verificar se há novos preços ou mudanças significativas e registrar essas alterações no banco de dados.
- O sistema deve enviar um relatório diário ao administrador detalhando as atualizações realizadas, incluindo qualquer falha ou inconsistência detectada.

### US09 - Como usuário, quero comparar os preços dos veículos disponíveis com os valores da Tabela FIPE, para que eu possa tomar decisões de compra informadas
**Critérios de Aceitação:**
- O usuário deve poder selecionar um veículo e ver uma comparação clara entre o preço de mercado atual e o valor de referência da Tabela FIPE.
- A comparação deve destacar visualmente se o preço está acima, abaixo ou próximo do valor de referência da Tabela FIPE.
- O sistema deve permitir que o usuário filtre as comparações por diferentes critérios, como localidade, ano do veículo, e faixa de preço, para refinar a decisão de compra.

### US11 - Como usuário, quero visualizar veículos por categoria (pick-up, SUV, Sedan, Hatch, Elétrico...), A busca deve ser intuitiva com cards ou algo parecido para um clique rápido. Além de buscar veículos por marca, modelo e ano, para encontrar carros que atendam às minhas preferências.
**Critérios de Aceitação:**
- Filtros de busca por tipo de veículo, marca, modelo, ano e localização.
- Paginação e organização dos resultados.
- Exibição de preços comparados com a Tabela FIPE.

### US12 - Como usuário logado, quero avaliar lojas de veículos, para ajudar outros usuários a tomarem decisões confiáveis ao escolherem onde comprar.
**Critérios de Aceitação:**
- Sistema de classificação e comentários sobre lojas.
- Exibição da nota média de cada loja no catálogo de veículos.

### US13 - Eu, como visitante, quero criar cadastro na plataforma, para ter acesso a todas as funcionalidades exclusivas de membros
**Critérios de aceitação:**
- O usuário deve se cadastrar com nome, email, telefone, cidade, tipos de veículo favoritos, estado, e senha

## 7. Tarefas Técnicas
- Documentar API do backend
- Configurar banco de dados
- Modelagem de dados
- Pesquisar sites para web scraping
- Integração com API da tabela FIPE
- Biblioteca ApexCharts.js para gráficos

## 8. Ferramentas de Gestão de Projetos
- **Trello:** Registrar ideias, dividir tarefas, gerenciar backlog, etc.
    - [Trello Board](https://trello.com/b/QSpi80Uf/tcc-grupo-05)
- **GitHub:** Versionamento de código, CI/CD
    - [GitHub Repository](https://github.com/TCC-T-Academy-Grupo-5)
- **Figma:** Wireframes
    - [Figma Design](https://www.figma.com/design/DG357tYR7C60tgSHbzx3LW/TCC---Grupo-05---Template?node-id=54-778&node-type=section&t=JGI0e26BLOXqzmQx-0)
- **apicur.io:** Documentação de API usando Open API
    - [apicur.io API Documentation](https://studio.apicur.io/apis/111070)
- **Lucid:** Cronograma
    - [Cronograma](https://lucid.app/lucidchart/a2b3841f-596a-45eb-9275-373e0e1dcd19/edit?viewport_loc=-2138%2C-594%2C3328%2C1582%2C0_0&invitationId=inv_5a7c6119-cfc3-452d-8ee3-702a2bf55134)

## 9. Disivão Geral de Tarefas
- **Backend e integração com tabela FIPE:** <ins>Gabriel</ins>
    - Integração com API da Tabela FIPE
    - Web Scraping
- **Frontend:** <ins>Emily</ins>
    - Alertas
    - Favoritos
    - Integração com Backend
    - Gráficos
- **Gestão de usuários:** <ins>Paulo Henrique</ins>
    - Cadastro de usuários
    - Autenticação
    - Autorização
- **Gestão do projeto e qualidade:** <ins>Alex</ins>
    - Gerenciamento das tarefas
    - Versionamento
    - Testes
  
