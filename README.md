# BELLUM - Sistema Bélico e Logístico de Uso Militar

[![logonamewhite.png](https://i.postimg.cc/RFk5V1F1/logonamewhite.png)](https://postimg.cc/5YSksC8j)

## Documentação Completa para Usuários

**Versão:** 1.0  
**Data:** 28 de maio de 2025  
**Desenvolvido por:** Lucas Gabriel Bellini da Silva

---

## Sumário

1. Introdução
2. Visão Geral do Sistema
3. Dashboard
4. Usuários
5. Unidades
6. Materiais
7. Cronogramas
8. Entradas
9. Saídas
10. Separações
11. Movimentações (AutoCofin)
12. Relatórios
13. Alertas
14. Novidades
15. Sobre
16. Requisitos Técnicos
17. Suporte

---

## Introdução

O BELLUM é uma plataforma completa desenvolvida para otimizar e gerenciar toda a logística de materiais bélicos e táticos, incluindo armas, coletes, munições e outros itens essenciais para a operação. Por meio de uma interface intuitiva, o sistema permite controlar estoque em tempo real, gerenciar cronogramas, registrar movimentações, gerar relatórios detalhados e muito mais.

Desenvolvido inicialmente para atender às necessidades específicas do Centro de Materiais Bélicos da Polícia Militar do Estado de São Paulo, o BELLUM representa um avanço significativo na gestão logística, substituindo processos manuais por uma plataforma digital integrada, reduzindo erros, aumentando a transparência e fornecendo dados em tempo real para tomada de decisões estratégicas.

### Principais Recursos

- Controle de estoque em tempo real
- Gestão de usuários e permissões
- Registro de entradas e saídas
- Cronogramas de distribuição
- Gestão de separações
- Relatórios detalhados
- Dashboard com análises
- Sistema de notificações e alertas
- Rastreabilidade completa de materiais

---

## Visão Geral do Sistema

O BELLUM está organizado em módulos funcionais que atendem diferentes aspectos da gestão logística:

### Gestão de Materiais
Controle completo do inventário com rastreamento de armas, munições e equipamentos.

### Gestão de Pessoas
Administração de usuários, perfis, acessos e escalas de trabalho.

### Logística
Entradas, saídas, separações e movimentações de materiais.

### Interface
O sistema possui uma interface moderna e responsiva, adaptando-se a diferentes tamanhos de tela. A navegação principal é feita através da barra lateral, que dá acesso a todos os módulos do sistema. A experiência é consistente em todo o aplicativo, com elementos visuais padronizados e feedback imediato para ações do usuário.

### Perfis de Acesso
- **Owner:** Acesso total ao sistema, incluindo configurações avançadas e gerenciamento de permissões
- **Administrador:** Acesso completo à gestão e relatórios, sem algumas funcionalidades de configuração
- **Usuário:** Acesso à movimentação de materiais, consultas e relatórios básicos, sem permissão para aprovações
- **Visitante:** Acesso somente para visualização, sem permissão para realizar qualquer alteração no sistema

---

## Dashboard

O Dashboard oferece uma visão geral do sistema com informações em tempo real sobre o estado atual da logística.

### Recursos do Dashboard

- **Resumo do Estoque:** Visualização rápida da quantidade de armas, coletes e munições disponíveis no sistema.
- **Status de Usuários:** Acompanhamento de quantos usuários estão em serviço, de folga e logados recentemente.
- **Separações e Cronogramas:** Visualização do status de separações e cronogramas pendentes ou em andamento.
- **Gráficos e Estatísticas:** Apresentação visual de dados como distribuição de materiais por tipo, movimentações recentes e previsões de necessidades.
- **Alertas Críticos:** Destaque para situações que requerem atenção imediata, como vencimentos próximos ou estoque abaixo do mínimo.

### Ações Disponíveis

- Filtrar visualização por período (hoje, esta semana, este mês)
- Personalizar quais widgets são exibidos
- Acessar detalhes de qualquer informação apresentada clicando no respectivo card
- Exportar gráficos e dados para relatórios
- Alternar entre diferentes visualizações de dados

---

## Usuários

A seção de Usuários permite a administração de contas, perfis e permissões no sistema.

### Principais Funcionalidades

- **Criação de Usuários:** Administradores podem criar novos usuários fornecendo informações como nome, CPF, RE, e-mail, telefone e definindo cargo e setor.
- **Edição de Perfis:** Usuários podem editar seus próprios perfis, enquanto administradores podem editar qualquer perfil, incluindo alterar cargos e redefinir senhas.
- **Gerenciamento de Status:** Permite marcar usuários como ativos, inativos, em serviço ou de folga, facilitando o controle de escala.
- **Controle de Permissões:** Atribuição de diferentes níveis de acesso às funcionalidades do sistema, conforme o cargo e necessidades específicas.
- **Histórico de Atividades:** Registro de todas as ações realizadas por cada usuário no sistema, para fins de auditoria.

### Como Utilizar

1. **Criar Novo Usuário:** Clique em "Novo Usuário", preencha os campos necessários, atribua um cargo e salve.
2. **Gerenciar status:** Clique em "Gerenciar Status" ao lado de um usuário, escolha a data no calendário e selecione o status apropriado. Os dias úteis são "Serviço" por padrão e finais de semana são "Folga".
3. **Alterar senhas:** Na edição de perfil, a seção "Alterar Senha" permite definir uma nova senha. Administradores podem alterar senhas de qualquer usuário sem conhecer a senha atual.

> **Observação:** O sistema possui dois cargos principais: "Administrador" e "Usuário". Administradores têm acesso completo ao sistema, enquanto usuários comuns têm acesso limitado. Apenas administradores podem alterar cargos.

---

## Unidades

O módulo de Unidades permite cadastrar e gerenciar todas as unidades organizacionais que utilizam o sistema ou recebem materiais.

### Principais Funcionalidades

- **Cadastro de Unidades:** Registro completo de unidades com nome, código, localização, telefone e informações de contato.
- **Hierarquia Organizacional:** Estabelecimento de relações hierárquicas entre unidades (matriz, filiais, subunidades).
- **Mapeamento de Responsáveis:** Vinculação de usuários como gestores ou responsáveis por cada unidade.
- **Estatísticas de Distribuição:** Visualização de dados históricos de materiais enviados para cada unidade.

### Como Utilizar

1. **Cadastrar Nova Unidade:** Clique em "Nova Unidade" e preencha as informações necessárias como nome, código, endereço e telefone.
2. **Editar Unidade:** Selecione uma unidade da lista e clique em "Editar" para modificar suas informações.
3. **Vincular Responsáveis:** Na tela de edição da unidade, acesse a seção "Responsáveis" para adicionar os usuários responsáveis.
4. **Visualizar Histórico:** No perfil de cada unidade, consulte o histórico de recebimentos e estatísticas de distribuição.

---

## Materiais

O módulo de Materiais fornece uma visão completa do inventário disponível no sistema, permitindo consultas detalhadas e gestão de itens.

### Principais Funcionalidades

- **Catálogo Completo:** Visualização de todos os materiais cadastrados no sistema, com filtros e busca avançada.
- **Ficha Técnica:** Acesso às especificações detalhadas de cada item, incluindo fotos, documentação e histórico completo.
- **Controle de Status:** Acompanhamento do estado atual de cada material (disponível, em uso, em manutenção, baixado).
- **Rastreabilidade:** Visualização do histórico de movimentações de cada item individual.
- **Gestão de Categorias:** Organização de materiais por tipo, categoria e classificações personalizáveis.

### Como Utilizar

1. **Buscar Materiais:** Utilize os filtros (tipo, status, localização) e a barra de pesquisa para encontrar itens específicos.
2. **Visualizar Detalhes:** Clique em qualquer item para acessar sua ficha completa com todas as informações e histórico.
3. **Editar Material:** (Apenas Administradores) Clique no ícone de edição para modificar as informações de um material.
4. **Excluir Material:** (Apenas Administradores) Clique no ícone de lixeira para excluir um material. Uma confirmação será solicitada.

> **Observação importante:** A adição de novos materiais NÃO é feita nesta página. Para adicionar novos materiais ao sistema, utilize a página de Entradas.

---

## Cronogramas

O módulo de Cronogramas permite gerenciar distribuições programadas e recorrentes de materiais para diferentes unidades.

### Principais Funcionalidades

- **Planejamento de Distribuição:** Criação de cronogramas para entrega regular de materiais às unidades.
- **Periodicidade Configurável:** Definição de frequência (diária, semanal, mensal) para distribuições recorrentes.
- **Automação de Separações:** Geração automática de listas de separação conforme a aproximação das datas programadas.
- **Monitoramento de Execução:** Acompanhamento de cronogramas em diferentes fases (pendente, em andamento, concluído).
- **Relatórios de Cumprimento:** Análise de pontualidade e eficácia na execução dos cronogramas programados.

### Como Utilizar

1. **Criar Novo Cronograma:** Clique em "Novo Cronograma", selecione a unidade de destino e a periodicidade.
2. **Adicionar Materiais:** Na tela de criação, especifique os materiais e quantidades para cada distribuição do cronograma.
3. **Ativar/Desativar:** Controle a execução de um cronograma ativando-o ou desativando-o conforme necessário.
4. **Monitorar Execução:** Acompanhe o andamento dos cronogramas ativos e verifique o histórico de execuções anteriores.

---

## Entradas

O módulo de Entradas gerencia a incorporação de novos materiais ao sistema, registrando todas as informações e atualizando o inventário automaticamente.

### Principais Funcionalidades

- **Registro de Novos Materiais:** Ponto de acesso para incluir novos itens no sistema, registrando todas as informações necessárias como código, número de série e tipo.
- **Documentação de Procedência:** Registro de observações relacionadas, como notas fiscais, termos de doação ou transferências, mantendo o histórico completo.
- **Rastreabilidade Temporal:** Registro automático de data, hora e usuário responsável pelo registro, garantindo auditoria completa.
- **Processamento em Lotes:** Capacidade de registrar múltiplos itens em uma única entrada, agilizando o processo.
- **Validação de Dados:** Verificações automáticas para evitar duplicidades ou inconsistências no cadastro.

### Como Utilizar

1. **Iniciar Nova Entrada:** Clique em "Nova Entrada", selecione o tipo de entrada (compra, transferência, doação, etc.) e preencha as informações do documento de origem.
2. **Adicionar Itens:** Para cada item, preencha os dados requeridos (nome, código, número de série, etc.). O botão "+" permite adicionar múltiplos itens à mesma entrada.
3. **Finalizar e Conferir:** Revise todos os itens antes de finalizar. Após confirmar, a entrada será processada e os itens adicionados ao estoque disponível para uso.

> **Correções Posteriores:** Caso precise corrigir informações de um item após finalizar a entrada, utilize a página de "Materiais" para editar o item específico, não sendo necessário reverter toda a entrada.

### Funcionalidades na Página de Entradas

- **Filtros Avançados:** Pesquise entradas por período, tipo, responsável ou texto contido nos documentos
- **Exportação de Dados:** Exporte listas de entradas para Excel ou PDF para controle ou documentação
- **Visualização Detalhada:** Acesse todos os detalhes de uma entrada específica, incluindo lista completa de materiais
- **Histórico de Alterações:** Visualize quando e por quem cada entrada foi criada ou modificada
- **Validação de Dados:** O sistema verifica automaticamente inconsistências como números de série duplicados

---

## Saídas

O módulo de Saídas controla a destinação de materiais para unidades, manutenção ou baixa definitiva, garantindo documentação apropriada e atualização automática do inventário.

### Principais Funcionalidades

- **Tipos de Saída:** O sistema oferece diversos tipos de saída: distribuição para unidades, transferências, manutenção, baixa por dano ou obsolescência, entre outros.
- **Destinatários:** Registre detalhadamente para quem o material está sendo enviado, seja uma unidade, um usuário específico ou uma empresa externa (no caso de manutenção).
- **Documentação:** Todas as saídas geram documentos automáticos para controle, como guias de remessa, termos de responsabilidade ou relatórios de baixa de material.
- **Validações de Segurança:** Verificações automáticas para garantir que apenas materiais disponíveis possam ser movimentados.

### Como Utilizar

1. **Iniciar Nova Saída:** Clique em "Nova Saída", selecione o tipo de saída e o destinatário. Cada tipo possui campos específicos que devem ser preenchidos.
2. **Selecionar Materiais:** Use a pesquisa para localizar materiais disponíveis no estoque. Selecione cada item e a quantidade a ser transferida.
3. **Confirmar e Documentar:** Revise todos os detalhes, adicione observações se necessário, e confirme a saída. O sistema irá gerar automaticamente os documentos correspondentes.

### Funcionalidades Detalhadas na Página de Saídas

1. **Filtros e Busca**
   - **Busca Textual:** Pesquise por número de ordem, termo, unidade, responsáveis ou detalhes de materiais.
   - **Filtros de Status:** Filtre por saídas pendentes, entregues ou canceladas.
   - **Filtro por Tipo (LCM):** Visualize saídas apenas de determinados tipos de materiais.
   - **Filtro por Data:** Defina um intervalo específico de datas para visualizar as saídas.
   - **Limpar Filtros:** Botão para resetar todos os filtros aplicados.

2. **Gerenciamento de Visualização**
   - **Itens por Página:** Configure quantos registros deseja visualizar por página (5, 10, 15, 25 ou 50).
   - **Paginação:** Navegue entre as diferentes páginas de resultados.
   - **Contador de Registros:** Visualize quantas saídas foram encontradas no total.

3. **Tabela de Saídas**
   - Apresentação detalhada de saídas com colunas para:
     - Número da Ordem
     - Termo
     - Unidade de Destino
     - Data
     - Status (com indicação visual colorida)
     - Materiais
     - Modelo
     - Responsável pela Separação
     - Responsável pela Entrega
     - Responsável pelo Recebimento
     - Ações disponíveis

4. **Ações por Registro**
   - **Visualizar (todos os usuários):** Acesse detalhes completos da saída.
   - **Editar (exceto visitantes):** Modifique informações de saídas pendentes.
   - **Marcar como Entregue (exceto visitantes):** Confirme a entrega dos materiais, atualizando automaticamente o estoque.
   - **Excluir (exceto visitantes):** Remova registros de saídas pendentes.

5. **Visualização Detalhada**
   - Ao clicar em "Visualizar", uma janela modal exibe:
     - Informações gerais da saída (número, termo, destino, datas)
     - Responsáveis por cada etapa do processo
     - Observações registradas
     - Lista completa de materiais com detalhes de cada item
     - Opções para exportar os dados para Excel ou PDF

6. **Edição de Saídas**
   - Para saídas pendentes, é possível editar:
     - Termo
     - Número da NL
     - Data da Saída
     - Responsável pela Entrega
     - Responsável pelo Recebimento
     - Observações
   - A janela de edição também exibe a lista de materiais para referência

7. **Processamento de Entrega**
   - Ao marcar uma saída como entregue, o sistema:
     - Verifica se os responsáveis foram preenchidos
     - Atualiza o estoque, reduzindo quantidades ou alterando status
     - Registra movimentações no histórico de cada material
     - Atualiza o status da saída para "Entregue"
     - Gera documentação correspondente

8. **Exportação de Dados**
   - **Exportar Lista:** Exporte a lista completa de saídas filtradas para Excel
   - **Exportar Detalhes:** Para cada saída individual, exporte detalhes para:
     - **Excel:** Duas planilhas, uma com informações gerais e outra com a lista de materiais
     - **PDF:** Documento formatado com cabeçalho, informações da saída, lista de materiais e área para assinaturas

> **Observação:** O sistema implementa um breve período de espera (cooldown) após processar uma entrega, evitando processamentos duplicados acidentais.

---

## Separações

O módulo de Separações facilita a preparação e organização de materiais para distribuição, com listas de separação, conferência e preparação para despacho.

### Principais Funcionalidades

- **Criação de Separações:** Elaboração de listas detalhadas dos materiais que serão separados para uma destinação específica.
- **Fluxo de Trabalho:** Gerenciamento do processo completo desde a solicitação até a entrega, passando por separação física, conferência e autorização.
- **Integração com Saídas:** Geração automática de registros de saída após a conclusão do processo de separação.
- **Controle de Responsáveis:** Registro de quem solicitou, quem separou e quem autorizou cada processo.

### Como Utilizar

1. **Iniciar Nova Separação:** Acesse "Nova Separação", indique a unidade de destino e preencha os dados da requisição.
2. **Adicionar Materiais:** Selecione os materiais a serem separados, especificando tipo, quantidade e localização no estoque.
3. **Processar Separação:** Quando os itens estiverem fisicamente separados, marque a separação como "Em processamento" e confirme os itens à medida que são separados.
4. **Finalizar e Gerar Saída:** Após a conferência, finalize a separação para gerar automaticamente o registro de saída correspondente.

> **Dica de Produtividade:** Use a função "Lista de Separação" para imprimir um guia físico com todos os itens e suas localizações exatas no estoque, facilitando o trabalho de coleta.

---

## Movimentações (AutoCofin)

O módulo de Movimentações integra com o sistema AutoCofin para registro automatizado de movimentações no sistema oficial, evitando retrabalho e garantindo celeridade nos processos.

### Sobre o AutoCofin

- **Software Local:** O AutoCofin é um aplicativo dedicado que deve ser instalado no computador do usuário, não sendo uma funcionalidade web como as demais seções do BELLUM.
- **Integração com BELLUM:** Apesar de ser uma aplicação separada, o AutoCofin se integra perfeitamente com o BELLUM, sincronizando automaticamente as informações de movimentações e atualizações de inventário.
- **Gerenciamento Completo:** Controle detalhado de todas as movimentações financeiras e físicas de materiais, com ferramentas avançadas para acompanhamento de ativos e passivos.

### Como Utilizar

1. **Instalar o Aplicativo:** Baixe o instalador mais recente do AutoCofin através do link disponível em sua área de usuário. Execute o arquivo e siga as instruções do assistente de instalação.
2. **Configurar Credenciais:** O AutoCofin é simples e sem credencial. Ao iniciar, você precisará inserir as credenciais do site do COFIN. O sistema irá se conectar automaticamente à base de dados central e sincronizar as informações necessárias.
3. **Operações Principais:** Com o AutoCofin você pode registrar movimentações detalhadas, gerar relatórios financeiros avançados, controlar balancetes e acessar funções específicas não disponíveis na web.

> **Requisitos do Sistema:** O AutoCofin requer Windows 10 ou superior, 4GB de RAM e 500MB de espaço em disco. É necessário possuir permissões de administrador para a instalação.

> **Documentação Completa:** Um manual detalhado do AutoCofin está disponível dentro da aba de Movimentações, acessível através da barra lateral. Consulte-o para informações específicas sobre cada função.

---

## Relatórios

O módulo de Relatórios fornece uma ampla gama de relatórios personalizáveis para análise de dados, controle gerencial e atendimento a requisitos de auditoria e conformidade.

### Principais Funcionalidades

- **Relatórios Predefinidos:** Acesso rápido a relatórios comuns como inventário atual, movimentações recentes e distribuição por unidade.
- **Relatórios Customizados:** Criação de relatórios personalizados com seleção de campos, filtros e parâmetros específicos.
- **Gráficos e Visualizações:** Representação visual dos dados em diferentes formatos gráficos para análise facilitada.
- **Exportação Versátil:** Exportação de relatórios em múltiplos formatos (PDF, Excel, CSV) para compartilhamento e arquivamento.

### Como Utilizar

1. **Selecionar Tipo de Relatório:** Escolha entre os relatórios predefinidos ou clique em "Relatório Personalizado".
2. **Configurar Parâmetros:** Defina o período, filtros e detalhes a serem incluídos no relatório.
3. **Gerar Relatório:** Clique em "Gerar" e aguarde o processamento dos dados.
4. **Exportar ou Compartilhar:** Visualize o relatório na tela ou exporte-o no formato desejado para uso externo.

> **Relatórios Programados:** Administradores podem configurar relatórios programados para serem gerados automaticamente em intervalos específicos (diário, semanal, mensal) e enviados por e-mail para os destinatários configurados.

---

## Alertas

O módulo de Alertas monitora prazos de validade e níveis mínimos de estoque, notificando os responsáveis sobre necessidades de ação, como substituição de itens vencidos ou reposição de estoques.

### Principais Funcionalidades

- **Monitoramento Automático:** Verificação contínua de condições críticas como prazos de validade e níveis de estoque.
- **Priorização Visual:** Classificação de alertas por criticidade (alta, média, baixa) com indicadores visuais correspondentes.
- **Notificações Configuráveis:** Definição de quais eventos geram alertas e quem deve ser notificado.
- **Painel de Controle:** Visualização consolidada de todos os alertas ativos com opções de filtro e ordenação.
- **Histórico de Resolução:** Registro de como e quando cada alerta foi resolvido, para análise de processos.

### Como Utilizar

1. **Acessar Alertas:** Visualize todos os alertas ativos no painel principal, organizados por tipo e prioridade.
2. **Verificar Detalhes:** Clique em um alerta específico para ver informações detalhadas e ações recomendadas.
3. **Resolver Alertas:** Após tomar a ação necessária, marque o alerta como resolvido, registrando a solução implementada.
4. **Configurar Notificações:** No menu de configurações, defina quais tipos de alertas você deseja receber e por quais canais (e-mail, sistema).

> **Visualização Rápida:** O dashboard principal exibe contadores com o número total de alertas ativos. As abas "Validade" e "Quantidade" mostram os alertas detalhados, com opções de filtro por tipo de alerta e busca por nome ou modelo.

> **Ações Recomendadas:** Para alertas de quantidade, planeje novas aquisições ou redistribuições. Para alertas de validade, programe a substituição de itens ou seu uso prioritário antes do vencimento.

---

## Novidades

O módulo de Novidades apresenta a plataforma para reporte de problemas e sugestões de melhorias do sistema.

### Funcionalidades do Sistema de Issues

- **Registro de Problemas:** Canal oficial para reportar bugs, falhas ou comportamentos inesperados do sistema.
- **Sugestões de Melhorias:** Mecanismo para envio de ideias de novas funcionalidades ou aprimoramentos.
- **Acompanhamento de Status:** Sistema de rastreamento que permite verificar em que estágio se encontra cada issue reportado.
- **Comunicação Transparente:** Feedback claro sobre prazos estimados e priorização de correções e implementações.
- **Base de Conhecimento:** Acervo de problemas conhecidos e suas soluções, para consulta rápida.

### Como Utilizar

1. **Criar um Novo Issue:** Clique no botão "Novo Issue", selecione o tipo (bug, melhoria, sugestão, etc.), preencha o título e descrição detalhada do problema ou sugestão.
2. **Acompanhar Status:** Verifique o progresso dos issues reportados através dos status (Aberto, Em Análise, Em Desenvolvimento, Resolvido, Fechado) e dos comentários da equipe de desenvolvimento.
3. **Colaborar em Discussões:** Participe ativamente das discussões em issues abertos, fornecendo feedback e informações adicionais que possam ajudar na resolução de problemas.

> **Boas Práticas:** Para reportes mais eficientes, inclua capturas de tela, logs de erro e descreva detalhadamente os passos para reproduzir o problema. Issues bem documentados são resolvidos mais rapidamente.

> **Priorização:** As issues são priorizadas pela equipe de desenvolvimento com base em sua criticidade, impacto nos usuários e viabilidade técnica. Acompanhe o roadmap publicado mensalmente para verificar o planejamento de implementações.

---

## Sobre

A seção Sobre contém informações detalhadas sobre o sistema, incluindo documentação técnica, equipe de desenvolvimento, versão atual e histórico de atualizações.

### Principais Elementos

- **Documentação Técnica:** Acesso à documentação completa do sistema, incluindo arquitetura, requisitos e especificações técnicas.
- **Equipe de Desenvolvimento:** Informações sobre os responsáveis pelo desenvolvimento e manutenção do sistema.
- **Histórico de Versões:** Registro detalhado das atualizações realizadas, com descrição das mudanças e melhorias implementadas.
- **Termos de Uso:** Políticas e condições para utilização adequada do sistema.
- **Suporte Técnico:** Canais e contatos para obtenção de ajuda em caso de problemas ou dúvidas.

### Itens na Documentação Técnica

1. **Introdução:** Apresentação geral do sistema BELLUM, incluindo contexto, motivação e objetivos gerais do projeto

2. **Propósito e Objetivos:**
   - Propósito Geral: Fornecer solução tecnológica completa para gestão logística de materiais bélicos
   - Objetivos Específicos: Rastreabilidade, gestão de inventário, automatização, etc.
   - Benefícios Esperados: Redução de tempo, eliminação de erros, informações em tempo real

3. **Público-Alvo:**
   - Usuários Primários: Oficiais e praças do CMB, gestores de arsenais
   - Usuários Secundários: Comandantes de unidades, equipes de auditoria
   - Perfis de Acesso: Owner, Administrador, Usuário, Visitante

4. **Descrição do Sistema:**
   - Visão Geral: Plataforma web com tecnologias modernas
   - Características Principais: Interface intuitiva, arquitetura baseada em componentes, etc.
   - Fluxos Principais: Entrada de materiais, saída, separação, inventário

5. **Módulos Principais:**
   - Descrição detalhada de cada módulo e suas funcionalidades específicas

6. **Requisitos Funcionais:**
   - Requisitos detalhados para cada área do sistema

7. **Requisitos Não Funcionais:**
   - Usabilidade, desempenho, disponibilidade, segurança, etc.

8. **Modelos e Diagramas:**
   - Arquitetura do sistema e entidades principais

9. **Tecnologias Utilizadas:**
   - Frontend: Next.js, React, TypeScript, etc.
   - Backend: Supabase, PostgreSQL, etc.
   - DevOps e complementares

10. **Conclusão e Recomendações:**
    - Resumo e considerações finais sobre o sistema

---

## Requisitos Técnicos

Para uma experiência otimizada com o sistema BELLUM, recomendamos:

### Requisitos Mínimos

- **Navegador:** Chrome 90+, Firefox 90+, Edge 90+ ou Safari 14+
- **Conexão:** Internet de pelo menos 5 Mbps
- **Resolução:** Mínima de 1280x720 pixels

### Requisitos Recomendados

- **Navegador:** Versão mais recente do Chrome ou Edge
- **Conexão:** Internet de 10+ Mbps
- **Resolução:** 1920x1080 pixels ou superior

### Para o AutoCofin (Aplicativo Local)

- **Sistema Operacional:** Windows 10 ou superior
- **Memória RAM:** 4GB (mínimo)
- **Espaço em Disco:** 500MB disponíveis
- **Permissões:** Acesso de administrador para instalação

---

## Suporte

### Canais de Suporte

- **Suporte Técnico:** Disponível através do e-mail lucas_bellini@hotmail.com.br
- **Documentação:** Acesse o manual completo na seção "Educativo" do sistema
- **Ajuda Contextual:** Botões de ajuda (?) estão disponíveis em todas as telas principais
- **Treinamento:** Materiais de treinamento e tutoriais em vídeo estão disponíveis na seção "Educativo"

### Para Reportar Problemas

1. Utilize o sistema de Issues na seção "Novidades"
2. Forneça detalhes específicos sobre o problema encontrado
3. Inclua capturas de tela quando aplicável
4. Descreva os passos para reproduzir o problema

### Atualizações do Manual

Este manual é atualizado regularmente para refletir as mudanças e melhorias no sistema. Verifique sempre a data da versão para garantir que você está consultando a documentação mais recente.

---

## ⚠️ Aviso

Este repositório é de caráter **informativo e demonstrativo**.  
O código-fonte completo **não está disponível publicamente** por questões de segurança e direitos autorais.

Para demonstrações, parcerias ou informações sobre licenciamento, entre em contato com o autor.

A seguir, segue algumas imagens do sistema (por segurança, algumas informações sensíveis estão cobertas:

# Login

[![LOGIN.png](https://i.postimg.cc/HnbGJJcq/LOGIN.png)](https://postimg.cc/gLctQ2Ks)

---

# Dashboard

[![dashboard.png](https://i.postimg.cc/xdFVBVV4/dashboard.png)](https://postimg.cc/XZFPyhJf)

---

# Entradas

[![entradas.png](https://i.postimg.cc/vBgws2QH/entradas.png)](https://postimg.cc/1nQj0HnL)

---



## 📜 Licença

Este projeto está protegido sob a licença  
**[CC BY-NC-ND 4.0 – Atribuição-NãoComercial-SemDerivações](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.pt-br)**.

> 📌 Você pode visualizar, compartilhar e usar o material **sem fins comerciais**, **sem modificações** e sempre com atribuição ao autor.

---

## 👤 Autor

**Lucas Bellini**  
Policial Militar | Especialista em Gestão de Dados e Logística Operacional  
[🔗 LinkedIn](https://www.linkedin.com/in/Lucas-Bellini)  
📧 contato: lucas_bellini@hotmail.com.br

---

© 2025 BELLUM - Todos os direitos reservados  
Desenvolvido por Lucas Gabriel Bellini da Silva
