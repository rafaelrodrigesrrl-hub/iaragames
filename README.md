RELATÓRIO TÉCNICO DE DESENVOLVIMENTO FRONT-END: PLATAFORMA IARA GAMES
    INTRODUÇÃO E PROPOSTA DE IDENTIDADE VISUAL (ATIVIDADE 01)
A identidade visual da plataforma Iara Games foi concebida com o propósito de unir a riqueza da cultura e do folclore brasileiro à modernidade da indústria de jogos eletrónicos independentes (indie games). O conceito central da marca baseia-se na valorização do ecossistema nacional de desenvolvimento, criando um ambiente digital que transmite inovação, proximidade comunitária e valor cultural.
Conceito e Símbolo: O nome "Iara" remete às raízes brasileiras, enquanto o ecossistema gráfico integra elementos retrofuturistas e referências ao universo arcade (como o joystick e a tipografia geométrica estilizada), simbolizando a fusão entre a identidade cultural do país e a tecnologia de ponta do desenvolvimento de jogos.
Paleta de Cores: O projeto adota uma paleta de tons escuros profundos como base (background), projetada para garantir imersão visual e conforto em longas sessões de navegação, complementada por tons quentes de âmbar, dourado e vermelho vibrante como cores de destaque (accent), evocando energia, criatividade e o calor da produção nacional.
Tipografia: Foram selecionadas famílias tipográficas modernas, geométricas e de alta legibilidade (como Oxanium e Kanit), que reforçam a estética tecnológica e futurista exigida por plataformas de entretenimento digital.
   JUSTIFICATIVAS DAS APLICAÇÕES DOS ELEMENTOS VISUAIS
A aplicação prática dos elementos da identidade visual no desenvolvimento front-end da plataforma obedeceu a rigorosos critérios de ergonomia visual, experiência do utilizador (UX) e consistência de marca:
Logótipo e Cabeçalho (Header):
Aplicação: O logótipo oficial foi posicionado estrategicamente no canto superior esquerdo (ponto inicial do padrão de leitura em "F" do utilizador), servindo também como elemento de hiperligação funcional (../../index.html) para o retorno imediato à página inicial.
Justificativa: Garante o reconhecimento de marca instantâneo (brand awareness) sem comprometer a área útil do cabeçalho, mantendo a proporção visual equilibrada face aos menus de navegação rápida e à barra de pesquisa.
Paleta de Cores e Contraste:
Aplicação: Utilização de fundos escuros padronizados associados a elementos interativos e bordas em tons de âmbar e dourado.
Justificativa: Além de consolidar a identidade visual imersiva da marca, o contraste acentuado entre o fundo escuro e a tipografia clara cumpre rigorosamente as normas de acessibilidade, evitando a fadiga visual e destacando os elementos acionáveis (call-to-actions).
   DESENVOLVIMENTO DAS PÁGINAS WEB E EVOLUÇÃO DO LAYOUT
 Página Principal (Home - index.html) e Evolução Arquitetural
A página principal foi totalmente reestruturada para refletir a identidade visual oficial da Iara Games, priorizando uma experiência de navegação imersiva e moderna em ambiente desktop.
Reestruturação do Cabeçalho (Header):
Evolução: Na versão base inicial, a logomarca e os menus encontravam-se isolados verticalmente. O layout foi otimizado para um formato horizontal e coeso (capsule layout), posicionando o logotipo à esquerda, os botões de navegação rápida ao centro e integrando uma barra de pesquisa dinâmica à direita.
Justificativa (UX): Esta disposição segue o padrão de leitura em "F", permitindo ao utilizador encontrar ferramentas de busca e atalhos vitais instantaneamente sem necessidade de rolagem excessiva.
Componentes de Destaque (Cards e Promoções):
Componentes Utilizados: Estruturas de cartões (cards) em grelha para exibição de produtos, promoções e lançamentos (MousePad IARAGAMES e Super Lançamento de RPG), combinando blocos de imagem, títulos descritivos, preços e botões de chamada para ação (Mais informações).
Justificativa Técnica: A divisão do conteúdo em blocos delimitados cria uma separação clara entre os diferentes produtos em destaque, permitindo que o utilizador escaneie rapidamente ofertas e lançamentos sem sobrecarga cognitiva, mantendo proporções equilibradas e adaptabilidade fluida a diferentes larguras de ecrã.
   Página Extra de Escolha Livre: Área de Publicação de Projetos (B2D - B2D.html)
Como segunda página obrigatória do projeto, foi desenvolvida a área B2D (Business to Developer), dedicada a aproximar criadores independentes e estúdios nacionais da plataforma.
Componentes Utilizados: Classes de grelha e formulários do Bootstrap (row, col-md-6, col-12, form-control, form-label) e elementos personalizados de upload de ficheiros.
Justificativa Técnica:
Arquitetura de Grelha Responsiva: A implementação de colunas dinâmicas permite que o formulário ajuste a sua disposição conforme o ecrã. Campos complementares são dispostos lado a lado em desktops para otimizar o espaço visual.
Consistência e Validação: O uso de classes padronizadas garante dimensões, margens e bordas consistentes, que recebem customização em tons escuros e âmbar para preservar rigorosamente a identidade visual da plataforma.
   INDICATIVO DE RECURSOS DE ACESSIBILIDADE E BOAS PRÁTICAS
Contraste e Legibilidade: Aplicação estrita de uma paleta de cores de alto contraste (fundo escuro com tipografia clara e elementos de destaque em tons quentes), assegurando conforto visual prolongado.
Semântica e Acessibilidade (HTML5/ARIA): Uso correto de tags estruturais semânticas (<header>, <main>, <section>, <footer>, <label>).
