# python_plot_style

Repositório com arquivos de estilo para plot em python. O objetivo é importar um estilo de plot que padronize o tamanho da figura para uma coluna ou duas colunas e os tamanhos das fontes. Isso evita que cada figura tenha fontes e linhas em um tamanhos diferentes.

Os arquivos de estilo devem ser salvos dentro da pasta  `~/.config/matplotlib/stylelib/`

No seu .py, basta importar o estilo antes de criar as figuras (pode ser imediatamente antes, caso precise de mais estilos, ou no inicio do código). Por exemplo:

`plt.style.use('paper_single_column')`

A dimensão da figura gerada segue a proporção áurea. Essa proporção pode não ser a mais adequada para figuras com subplots. O arquivo pode ser alterado manualmente ou criado um novo arquivo a partir dos que estão no repositório.
