(13/10/2025-18:20) - LLM: Claude.ai
    Input:
    Explique, em até 4 linhas, a diferença entre elementos block-level e inline-level, com 2 exemplos reais de cada e quando usar DIV e SPAN.

    Output:
    Block-level vs Inline-level:
    Elementos block-level ocupam toda a largura disponível e iniciam em nova linha (ex: <div>, <p>), enquanto inline-level ocupam apenas o espaço do seu conteúdo e permanecem na mesma linha (ex: <span>, <a>).
    Use <div> para agrupar seções e estruturar layouts (containers, cards, grids), e <span> para estilizar pequenos trechos de texto dentro de um parágrafo sem quebrar a linha (destacar palavras, aplicar cores específicas).

(13/10/2025-18:23) - LLM: Claude.ai
    Input:
    Gere uma página mínima sobre “DIV x SPAN”: 3 cartões organizados com DIV (block) e textos/ícones com SPAN (inline). Use HTML semântico, CSS externo e comentários no código. Sem frameworks.

    Output:
    ./docs/sitelog-01/index-01.html
    ./docs/sitelog-01/style-01.css

    Estrutura:

    DIVs (block-level): Usados para criar o container principal, grid de cartões e estruturar cada cartão completo
    SPANs (inline-level): Usados para destaques de texto (.highlight), ícones (.icon), badges (.badge) e código inline (.code)

    Destaques:

    HTML semântico com <header>, <article>, <h1>, <h2>, <p>, <ul>
    CSS externo no <style> com comentários explicativos
    3 cartões organizados em grid responsivo
    Exemplos práticos de quando usar cada elemento
    Zero frameworks - HTML e CSS puros

    A página é totalmente funcional e demonstra visualmente como DIVs estruturam blocos completos enquanto SPANs estilizam pequenos trechos dentro do texto!

    OBS: Devido a uma limitação do proprio modelo, a LLM utilizada gerou o codigo em um unico arquivo, com o CSS interno, codigo esse que foi posteriormente separado em dois arquivos e reconectado para o funcionamento correto da aplicação.

(13/10/2025-18:30) - LLM: Claude.ai
    Input:
    Ajuste o CSS para evidenciar content/padding/border/margin com cores e bordas. Explique em 3 linhas como cada camada afeta o layout.

    Output:
    ./docs/sitelog-01/index-02.html
    ./docs/sitelog-01/style-02.css

    Ajustado! Agora o CSS evidencia visualmente o Box Model:
    Como cada camada afeta o layout:

    CONTENT (branco): Define o tamanho base do elemento onde o conteúdo real (texto/imagens) é renderizado - é a área interna fundamental.
    PADDING (amarelo translúcido): Cria espaço interno entre o conteúdo e a borda, empurrando a borda para fora e aumentando o tamanho total do elemento sem afetar o conteúdo.
    BORDER (azul 5px): Linha visível ao redor do padding que adiciona espessura ao elemento; afeta o tamanho total calculado e serve como delimitador visual claro entre elementos.
    MARGIN (gap de 25px): Espaçamento externo transparente que separa elementos adjacentes sem fazer parte do elemento em si - controla o "respiro" entre componentes no layout.

    OBS: Devido a uma limitação do proprio modelo, a LLM utilizada gerou o codigo em um unico arquivo, com o CSS interno, codigo esse que foi posteriormente separado em dois arquivos e reconectado para o funcionamento correto da aplicação.
