# Cardápio Digital

Este projeto é um exemplo de um cardápio digital interativo para um restaurante, permitindo que os clientes escolham itens de diferentes categorias, adicionem ao carrinho e finalizem o pedido. Inclui também a opção de pagamento via Pix, onde é gerado um QR Code para facilitar a transação.

## Funcionalidades

- **Categorias de Itens:** Hambúrgueres, Salgados, Bebidas
- **Carrinho de Compras:** Adicione e remova itens, ajuste a quantidade.
- **Formulário de Pedido:** Capture informações do cliente e método de pagamento.
- **Pagamento com Pix:** Geração de QR Code com base na chave Pix e valor total do pedido.
- **Outros Métodos de Pagamento:** PayPal, Cartão de Crédito, Transferência Bancária (com campos dinâmicos para inserção de dados).

## Estrutura do Projeto

- **HTML:** Estrutura básica da página com seções para seleção de categorias, itens, carrinho de compras, e formulário de pedido.
- **CSS:** Estilos para tornar o layout responsivo e visualmente agradável. Inclui ajustes para diferentes tamanhos de tela e animações suaves.
- **JavaScript:** Lógica para adicionar itens ao carrinho, atualizar a quantidade, gerenciar o formulário de pedido e gerar QR Codes para pagamentos com Pix.

## Como Utilizar

1. **Seleção de Categoria:**
   - Escolha uma categoria do cardápio para visualizar os itens disponíveis.

2. **Adicionar ao Carrinho:**
   - Marque as caixas de seleção para adicionar itens ao carrinho. Ajuste a quantidade com os botões `+` e `-`.

3. **Finalizar Pedido:**
   - Clique em "Finalizar Pedido" para preencher o formulário com seus dados e selecionar o método de pagamento.

4. **Pagamento com Pix:**
   - Selecione a forma de pagamento "Pix", escolha o tipo de chave Pix e insira o valor total do pedido. Um QR Code será gerado para pagamento.

## Requisitos

- Um navegador moderno com suporte a HTML5, CSS3 e JavaScript.

## Desenvolvimento e Customização

- **Customização de Estilo:** Altere o arquivo CSS para personalizar cores, fontes e layout.
- **Aprimoramento de Funcionalidades:** Expanda a lógica JavaScript para incluir novas funcionalidades ou melhorar as existentes.

## Considerações Finais

Este projeto é uma demonstração simples e pode ser expandido para incluir funcionalidades adicionais, como integração com sistemas de pagamento reais, banco de dados para gerenciar inventário e pedidos, e autenticação de usuários.
