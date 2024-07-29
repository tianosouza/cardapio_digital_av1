# Cardápio Digital Interativo

Este projeto cria um sistema de cardápio digital interativo para um restaurante fast food. Utiliza HTML, CSS, e JavaScript para estruturar a interface e gerenciar a interação do usuário, permitindo que os clientes visualizem o cardápio, gerenciem seus pedidos e finalizem as compras com diversas opções de pagamento.

## Estrutura do Sistema

### 1. Apresentação do Cardápio

- **Categorias**: O cardápio é organizado em três categorias principais:
  - **Burguers**: Inclui itens como Burguer Gourmet, Burguer de Costela, e Burguer de Grão-de-Bico.
  - **Lanches**: Inclui opções como Cachorro-Quente Completo, Sanduíche Natural, e Tapioca de Frango com Catupiry.
  - **Bebidas**: Inclui opções como Chá Gelado, Suco Detox, e Smoothie de Morango.

- **Itens do Cardápio**: Cada item possui uma descrição, preço e um checkbox para seleção. Os itens selecionados são adicionados ao carrinho de compras.

### 2. Gerenciamento do Pedido

- **Carrinho de Compras**: Exibe os itens selecionados, suas quantidades e o total acumulado. Inclui botões para ajustar a quantidade dos itens.
- **Formulário de Finalização do Pedido**: Aparece após o cliente clicar em "Finalizar Pedido" e coleta informações do cliente, como nome completo e endereço.

### 3. Finalização do Pedido

- **Método de Pagamento**: Oferece as seguintes opções:
  - **Cartão de Crédito**: Campos para número do cartão, data de expiração e código de segurança.
  - **PayPal**: Campo para o email associado à conta do PayPal.
  - **Pix**: Campo para inserir a chave Pix e gerar um QR Code para pagamento.
  - **Transferência Bancária**: Campos para número da conta e CPF.

- **Resumo do Pedido**: Mostra o resumo do pedido para confirmação, incluindo os itens selecionados, o total do pedido e as informações do cliente.

## Tecnologias e Ferramentas Utilizadas

- **HTML & CSS**: Estrutura e estilização da interface.
- **JavaScript (jQuery)**: Manipulação do DOM e interatividade.
- **jquery.qrcode**: Biblioteca para geração de QR Codes para o pagamento via Pix.
- **Responsividade**: Media queries para adaptar a interface a diferentes tamanhos de tela.

## Funcionalidades

- **Filtragem de Categorias**: Usuários podem filtrar o cardápio por categorias usando um dropdown.
- **Atualização Dinâmica do Carrinho**: Itens podem ser adicionados ou removidos do carrinho com atualização automática do total.
- **Gestão de Quantidade**: Possibilidade de aumentar ou diminuir a quantidade dos itens no carrinho.
- **Exibição Dinâmica de Campos de Pagamento**: Campos específicos são exibidos com base no método de pagamento selecio
