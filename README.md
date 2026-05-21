# Nexus-Plataforma
Nexus Cusos
=======================================================================
  NEXUS - PLATAFORMA DE CONTEUDO EDUCACIONAL
  ========================================================================
  
  FUNCIONALIDADES COMPLETAS DA PLATAFORMA
  ----------------------------------------
  
  1. SISTEMA DE AUTENTICACAO
     - Login por email e senha
     - Papeis: Administrador (acesso total) e Usuario (aluno)
     - Logout seguro
     - Senhas padrao: Admin (admin/admin)
  
  2. PAINEL ADMINISTRATIVO
     - Dashboard com estatisticas (videos, livros, audios, cursos, usuarios)
     - Contadores de conteudo premium e acessos expirados
     - Acesso rapido para adicionar conteudo, usuarios e cursos
     - Logs do sistema com timestamps
  
  3. GERENCIAMENTO DE CONTEUDO (Videos, Livros, Audios)
     - Adicionar conteudo de multiplas fontes:
       * YouTube (embed nativo)
       * Google Drive (preview embed)
       * Google Docs, Sheets, Slides (embed)
       * Google Forms (embed)
       * Notion, Miro, Canva, Trello
       * Link externo generico
     - Editar titulo, autor, categoria
     - Excluir conteudo
     - Busca por nome
     - Filtro por categoria
     - Visualizacao em cards com thumbnails
  
  4. SISTEMA DE CURSOS
     - Criar cursos com titulo, descricao, nivel, duracao
     - Adicionar aulas com URL e duracao
     - Marcar aulas como concluidas
     - Barra de progresso (% concluido)
     - Codigo de acesso para protecao de curso
     - Trailers em YouTube
     - Capas personalizadas
     - Status: Iniciante/Intermediario/Avancado
     - Indicadores: aulas, duracao total, data de expiracao
  
  5. SISTEMA DE QUIZZES / AVALIACOES
     - Quiz interno (pergunta + 4 alternativas + resposta correta)
     - Google Forms integrado (avaliacao ou pesquisa)
     - Quiz com navegacao (anterior/proxima)
     - Resultado com porcentagem e status (🎉 aprovado / 📝 reprovado)
     - Opcao de refazer quiz
     - Historico de tentativas
  
  6. GERENCIAMENTO DE USUARIOS
     - Criar usuarios com nome, email, senha
     - Atribuir categorias de acesso (granular)
     - Acesso PREMIUM (acesso a todos os cursos)
     - Editar usuarios (renomear, redefinir senha, categorias)
     - Excluir usuarios
     - Busca por nome/email
     - Filtro por categoria
     - Toggle PREMIUM/Normal
  
  7. SISTEMA DE CATEGORIAS
     - Criar/renomear/excluir categorias
     - Associar usuarios a categorias
     - Associar conteudo a categorias
     - Contagem de cursos e usuarios por categoria
  
  8. SISTEMA DE INSCRICOES E EXPIRACAO
     - Inscrever usuario em curso com duracao customizavel:
       * Dias, Semanas, Meses, Anos
     - Visualizar inscricoes ativas/expiradas
     - Renovar acesso (+30 dias, +6 meses)
     - Remover acesso
     - Preview de duracao antes de confirmar
     - Calculo automatico de data de expiracao
     - Indicadores visuais de status (verde/amarelo/vermelho)
  
  9. CALENDARIO DE PROGRESSO
     - Calendario mensal com atividades
     - Tracking de dias ativos
     - Contagem de streak (dias seguidos)
     - Estatisticas premium: dias ativos, cursos concluidos, total de conteudos
  
  10. CUSTOMIZACAO DA PLATAFORMA
      - Alterar nome da plataforma
      - Alterar tagline/descricao
      - Alterar logo (emoji ou texto curto)
      - Alterar cor primaria e secundaria
      - Paleta de cores pre-definidas
      - Pre-visualizacao em tempo real
      - Aplicar tema global (CSS variables)
  
  11. CUSTOMIZACAO DE LAYOUT (Admin)
      - Habilitar/desabilitar botoes do admin
      - Habilitar/desabilitar botoes do usuario
      - Reordenar botoes (cima/baixo)
      - Editar nome e icone de cada botao
      - Gerenciar modalidades de conteudo
  
  12. EXPORTAR / IMPORTAR DADOS
      - Exportar todo o backup em JSON
      - Importar dados de arquivo JSON
      - Preservar configuracoes, conteudo, usuarios, inscricoes
  
  13. LOGS DO SISTEMA
      - Registro de eventos com timestamps
      - Limpar logs
      - Indicadores visuais (verde=informativo, vermelho=erro)
  
  14. RESPONSIVIDADE
      - Layout responsivo para mobile/tablet
      - Sidebar colapsavel/expandivel
      - Grid adaptavel para conteudo
      - Header fixo com busca
  
  
  PASSO A PASSO - COMO FUNCIONA A PLATAFORMA
  -------------------------------------------
  
  INICIO:
  1. Acesse a pagina de login
  2. Escolha a aba "Usuario" ou "Admin"
  3. Digite email e senha (Admin padrao: admin/admin)
  4. Clique em "Entrar"
  
  PARA O ADMINISTRADOR:
  5. No Dashboard, visualize estatisticas gerais
  6. Para adicionar conteudo: clique em "Adicionar" → escolha a fonte (YouTube, Drive, etc) → cole a URL → preencha titulo/autor/categoria → "Publicar"
  7. Para gerenciar conteudo: clique em "Gerenciar" → edite ou exclua itens via tabela
  8. Para criar curso: "Dashboard" → "Novo Curso" → preencha detalhes → salve → adicione aulas e avaliacoes
  9. Para criar usuario: "Usuarios" → "Novo" → preencha dados → defina categorias e se e premium → "Criar"
  10. Para configurar categorias: "Categorias" → adicione/edite/remova → associe a usuarios e cursos
  11. Para inscricoes: Abra um curso → "Inscricoes" → aba "Inscrever" → selecione usuario, duracao, unidade → "Inscrever"
  12. Para renovar: Lista de inscritos → clique em "+30d" ou "+6m"
  13. Para customizar: "Layout" para botoes → "Plataforma" para nome/cores/logo
  14. Para backup: "Plataforma" → "Exportar Dados"
  
  PARA O USUARIO (ALUNO):
  15. No Inicio, veja conteudos recomendados, seus cursos e calendario
  16. Para ver videos/livros/audios: navegue pela sidebar ou clique nos cards
  17. Para assistir video: clique no card → embed abre com botao "Abrir em nova aba"
  18. Para acessar curso: clique no curso → se protegido, insira codigo → veja aulas e progresso
  19. Para fazer quiz: dentro do curso → "Iniciar Quiz" → responda perguntas → veja resultado
  20. Para ver progresso: barra de progresso no curso + calendario de atividade
  21. Para alterar perfil: "Config" → edite nome/email/senha → "Salvar"
  22. Se expirado: o curso mostra "Acesso Expirado" → contate o administrador para renovar
  
  RECURSOS EXTRAS:
  23. Busca global na header para filtrar conteudos rapidamente
  24. Sidebar colapsavel para mais espaco de tela
  25. Toast notifications para feedback de acoes
  26. Modais de confirmacao antes de acoes destrutivas (excluir, resetar)
  27. Indicadores visuais de fontes (YouTube vermelho, Drive amarelo, etc)
  28. Sistema de categorias granular para controle de acesso por area
  29. Acesso ilimitado ou com duracao configuravel por curso
  30. Sistema premium para usuarios VIP (acesso a tudo)
  
  NOTAS TECNICAS:
  - Dados salvos no localStorage do navegador
  - Embeds via iframes (YouTube, Google, Notion, etc)
  - Fallback para "Abrir em nova aba" se embed falhar
  - Design dark mode com gradientes modernos
  - Icones SVG inline para performance
  - Zero dependencias externas (apenas font Inter via CDN)
  - Totalmente standalone (single HTML file)
  
========================================================================
