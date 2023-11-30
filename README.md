# Habits
# 

Projeto desenvolvido para a cadeira de Gerencia de Configuração, no qual consiste em um sistema para criar e gerenciar os hábitos diários. O projeto consta com um site construído com Typescript, um app web.


# Requisitos Funcionais

# RF1: Criar H ́abito: Descricao: Os usuarios devem ter a capacidade de criar novos habitos, fornecendo as seguintes informacoes: Nome e frequencia.
# RF2: Nome do habito. Descricao: Selecao dos dias da semana em que o h́abito deve ser praticado.
# RF3: Visualizar Lista de Habitos: Descricao: Os usuarios devem poder visualizar uma lista dos habitos que criaram, incluindo detalhes como nome, descricao e dias da semana selecionados.
# RF4: Registrar Progresso Diario: Descricao: Para cada habito criado, os usuarios devem poder registrar diariamente se praticaram ou nao o h́abito. Isso pode ser feito atraves de checkboxes para cada dia da semana.
# RF5: Visualizar Habitos Passados: Descricao: Os usuarios devem poder visualizar registros anteriores de habitos, incluindo a data, o habito praticado (ou nao) e outros detalhes relevantes.
# RF6: Editar Habito: Descricao: Os usuarios devem ter a capacidade de editar informacoes sobre um habito existente, como nome, descricao e dias da semana selecionados.

# Requisitos Nao-Funcionais
# RNF1: O sistema deve ser responsivo, fornecendo tempos de resposta ŕapidos para acoes
do usuario.
# RNF2: A aplicacao deve suportar um numero significativo de usuarios simultaneos sem degradacao perceptıvel de desempenho.
# RNF3: Todas as transmissoes de dados entre o cliente e o servidor devem ser criptografadas utilizando HTTPS.
# RNF4: O sistema deve implementar praticas seguras, como protecao contra ataques de injecao (por exemplo, SQL injection) e autenticacao robusta.
# RNF5: A aplicacao deve estar disponıvel 24/7, com tempo de inatividade ḿınimo para manutencao programada.
# RNF6: O sistema deve ser projetado para escalabilidade, permitindo facil expansao para acomodar o aumento no numero de usuarios.
# RNF7: A aplicacao deve ser compatıvel com os principais navegadores da web, como Chrome, Firefox, Safari e Edge.
# RNF8: A interface do usuario deve ser acessıvel, seguindo as diretrizes de acessibilidade da Web (WCAG).

# Regras de Negocios
# RN1: Apenas usuarios autenticados podem criar, editar, excluir e visualizar seus habitos.
# RN2: As informacoes pessoais dos usuarios, incluindo habitos e hist́orico de progresso, devem ser armazenadas de forma segura e n ̃ao podem ser compartilhadas com terceiros em consentimento explıcito.
# RN3: Todas as entradas de dados (como nome de habitos e descricoes) devem ser validadas para evitar entradas maliciosas ou incorretas.
# RN4: O historico de progresso dos habitos registrados nao pode ser alterado pelos usuarios apos o registro inicial.
# RN5: As notificacoes e lembretes configurados pelos usuarios sao opcionais e podem ser desativados a qualquer momento.
# RN6: O sistema deve realizar backups regulares para garantir a recuperacao eficiente em caso de falhas ou perda de dados.
# RN7: Os usuarios tem o direito de excluir suas contas, resultando na exclusao permanente de todos os dados associados a essa conta.
# RN8: Cada usuario tem um limite maximo de habitos que podem ser criados para evitar sobrecarga e manter a simplicidade do sistema.
# RN9: O sistema deve garantir a consistencia dos dados, evitando estados inconsistentes de habitos ou progresso.
