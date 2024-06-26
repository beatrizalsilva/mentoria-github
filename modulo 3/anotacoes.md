# Colaborando em projetos

## Issues
- As issues são usadas para rastrear solicitações de recursos, relatórios de bugs e perguntas gerais relacionadas a um repositório.
- Elas atuam como um sistema de rastreamento onde os colaboradores podem discutir e coordenar o trabalho.
- Status:
    - Open: aberta e espera ser resolvida.
    - Closed: resolvida e fechada.
- Para classificar uma issue usa-se o "label", é como etiquetas que rastreiam e organizam as issues.
- Podemos atribuir (assignees) até 10 pessoas para uma issue, a pessoa deve ter permissão de gravação no repositório ou ser integrante da organização. 
- Priorize issues com base na importância e urgência.
- Também é possível vincular uma issue com uma solicitação de pull request automaticamente usando uma palavra chave na descrição da solicatação do pull resquest em questão.
- Os colaboradores  podem selecionar o modelo apropriado ao abrir novas issues seguindo  orientações  para abertura de cada tipo de issue. Todos os template são escritos em Markdown e ficam armazenados  em seu repositório  na branch default no diretório .github/ISSUE_TEMPLATE.

## Pull Request
- Os pull requests são propostas para mesclar alterações de uma branch em outra, geralmente do branch de recurso para o branch principal.
- Eles exibem as diferenças entre os conteúdos do branch de origem e de destino., podendo conter vários commits.
- Status:
    - Open: aberto para revisão.
    - Closed: foi fechado sem ser mesclado, ou seja, as alterações propostas não foram adicionadas na branch main.
    - Merged: foi aprovado e as alterações foi adicionadas na main.
- O conversation é onde os revisores e autores do pull resquest podem discutir as alterações propostas, solicitar alterações, deixar comentários ou fazer perguntas.
- Qualquer pessoa com permissões de gravação em um repositório pode vincular manualmente uma solicitação de pulla uma issue.
- Code reviw é o processo no qual os colaboradores do projeto analisam as alterações propostas em um pull request e fornecem feedback, podendo marcar como:
    - Approve: alterações estãp prontas para serem mescladas.
    - Comment: fornecem comentários sem uma decisão formal.
    - Request changes: alterações devem ser feitas antes da mesclagem.
- Podemos criar um pull request draft que indica que as alterações propostas ainda não estão prontas para revisão. Permite que os desenvolvedores compartilhem o andamento no seu trabalho com outros colaboradores antes de estarem prontos para receber o feedback.

## Discussion 
- As discussões são fóruns de comunicação para a comunidade em torno de um projeto interno ou de código aberto.
- Elas são usadas para conversas que precisam ser transparentes e acessíveis, mas não precisam ser rastreadas como um problema ou uma solicitação de recurso específica e não estão diretamente relacionadas ao código.

## Notifications
- As notificações fornecem atualizações sobre a atividade no GitHub que você está acompanhando. Você pode usar a caixa de entrada de notificações para personalizar, filtrar e gerenciar as atualizações.
- Você pode optar por receber notificações para:
    - Uma conversa específica em um issue, pull request ou gist.
    - Todas as atividades em um repositório.
    - Atividade de CI (integração contínua), como o status dos fluxos de trabalho nos repositórios configurados com GitHub Actions.
    - Problemas, pull requests, releases, alertas de segurança ou discussões do repositório (se habilitado).

## Gist
- Os Gists fornecem uma maneira fácil de compartilhar trechos de código com outras pessoas.
- Cada Gisté um repositório Git, o que significa que ele pode ser bifurcado (Fork) e clonado.
- Se você estiver conectado ao GitHub ao criar um Gist, ele será associado à sua conta.
- Tipos:
    - Public: aparecem em discover, onde as pessoas podem navegar por novos Gists conforme são criados. Eles também são pesquisáveis, permitindo que outros encontrem e visualizem seu trabalho.
    - Secret: não são exibidos no discover e não são pesquisáveis, a menos que você esteja conectado e seja o autor do Gist secreto.

## Wiki
- A Wiki é uma seção para criar documentação em um repositório.
- Também pode ser usada para compartilhar informações gerais sobre o projeto, como:
    - Visão geral do projeto
    - Guia do usuário
    - Contribuindo para o projeto
- As Wikis são editáveis por colaboradores com permissões de gravação no repositório.