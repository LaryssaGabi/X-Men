# Selecionador de Personagens

Este é um script JavaScript que permite ao usuário selecionar um personagem em uma página web interativa. O script altera dinamicamente a descrição, o nome e a imagem do personagem selecionado.

## Funcionalidades

- **Seleção de Personagem:** Permite ao usuário selecionar um personagem clicando nele.
- **Atualização Dinâmica:** Atualiza dinamicamente a descrição, o nome e a imagem do personagem selecionado sem recarregar a página.
- **Suporte a Dispositivos Móveis:** Se a largura da janela do navegador for inferior a 450 pixels, a página será automaticamente rolada para o topo quando um personagem for selecionado.

## Como usar

1. Adicione a classe `.personagem` a cada elemento HTML que representa um personagem na sua página.
2. Configure os atributos de dados `data-description`, `data-name` e `id` para cada elemento `.personagem`, contendo a descrição do personagem, o nome do personagem e um identificador exclusivo, respectivamente.
3. Cada elemento `.personagem` deve ter uma imagem associada com um caminho relativo especificado na tag `src`.
4. Quando um personagem é selecionado, a descrição, o nome e a imagem do personagem serão atualizados dinamicamente na página.

## Estrutura do Código

- **`alterarDescricaoPersonagem(personagem)`:** Função que atualiza a descrição do personagem selecionado.
- **`alterarNomePersonagemSelecionado(personagem)`:** Função que atualiza o nome do personagem selecionado.
- **`alterarImagemPersonagemSelecionado(personagem)`:** Função que atualiza a imagem do personagem selecionado.
- **`removerSelecaoDoPersonagem()`:** Função que remove a seleção do personagem previamente selecionado.
- **Evento de Mouse:** Adiciona um ouvinte de eventos de mouse a cada elemento `.personagem`, que aciona as funções acima quando um personagem é selecionado.

## Dependências

- **JavaScript:** Não são utilizadas bibliotecas externas, apenas JavaScript puro.
- **HTML e CSS:** A estrutura e o estilo dos elementos `.personagem` devem ser definidos em HTML e CSS.

