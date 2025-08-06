# Lista de Compras

Um aplicativo web simples e responsivo para gerenciar listas de compras em supermercados, desenvolvido com HTML, CSS e JavaScript. O app permite adicionar, editar, excluir e limpar itens, com armazenamento local via `localStorage`, temas claro/escuro, e exportação/importação de listas em formato JSON. É compatível com dispositivos móveis e hospedado no GitHub Pages.

## Funcionalidades

- **Adicionar Itens**: Registre produtos com nome, preço (padrão 0.00), supermercado e data (padrão: data atual).
- **Editar e Excluir**: Edite ou remova itens individuais da lista.
- **Limpar Lista**: Botão para excluir todos os itens com confirmação.
- **Soma Total**: Exibe o valor total dos preços dos itens.
- **Tema Claro/Escuro**: Alterne entre temas, com preferência salva localmente.
- **Exportar/Importar**: Exporte a lista como JSON (com data no nome do arquivo, ex.: `lista_compras_2025-08-06.json`) e importe listas salvas.
- **Responsividade**: Interface adaptada para desktops e dispositivos móveis.
- **Armazenamento Local**: Dados salvos no navegador via `localStorage`, funcionando offline.

## Tecnologias Utilizadas

- **HTML5**: Estrutura da interface.
- **CSS3**: Estilização com animações (fadeIn, slideIn) e responsividade.
- **JavaScript**: Lógica do aplicativo, manipulação do DOM e `localStorage`.
- **Font Awesome**: Ícones para botões e interface.
- **VSCode**: Desenvolvimento e testes com a extensão Live Server.
- **GitHub Pages**: Hospedagem do aplicativo.
