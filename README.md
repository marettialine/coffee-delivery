# Coffee Delivery

Bem-vindo ao **Coffee Delivery**, uma aplicação de e-commerce fictício para uma cafeteria, que permite ao usuário realizar pedidos de cafés e gerenciar o carrinho de compras de forma simples e intuitiva. A aplicação tem como foco principal a experiência do usuário, desde a visualização dos produtos até a finalização da compra, com funcionalidades como:

- Listagem de produtos (cafés) disponíveis
- Adicionar e gerenciar itens no carrinho
- Exibição do valor total do carrinho
- Formulário de endereço para envio dos pedidos

## Funcionalidades

### 1. Listagem de Produtos

A página inicial exibe uma lista de produtos disponíveis para compra. Cada café possui um nome, preço e imagem, permitindo que o usuário visualize todas as opções de forma clara.

### 2. Adicionar ao Carrinho

O usuário pode adicionar os cafés ao carrinho, especificando a quantidade desejada. O carrinho de compras vai sendo atualizado dinamicamente com a soma dos itens.

### 3. Gerenciamento do Carrinho

Dentro do carrinho, o usuário pode aumentar ou diminuir a quantidade de um item. O total de itens é recalculado automaticamente com base nas mudanças feitas.

### 4. Cálculo do Total do Carrinho

O valor total do carrinho é exibido ao usuário, somando o preço de todos os itens e multiplicando pela quantidade de cada um. O método `reduce` é utilizado para fazer o cálculo de forma eficiente.

### 5. Formulário de Endereço

O usuário preenche um formulário com o endereço de entrega. O formulário coleta as informações necessárias para concluir o pedido, como nome, endereço, cidade e CEP.

### 6. Persistência com LocalStorage

A aplicação utiliza o **LocalStorage** para salvar as informações do carrinho. Assim, mesmo que o usuário recarregue a página ou feche o navegador, os itens adicionados ao carrinho permanecem lá.

## Tecnologias Utilizadas

- **ReactJS**: Biblioteca principal para construção da interface.
- **ContextAPI**: Para gerenciamento de estado global, como o carrinho de compras.
- **LocalStorage**: Para persistir dados entre as sessões.
- **CSS/Styled Components**: Para estilização da aplicação.
- **JavaScript** (**TypeScript**): Linguagem utilizada para desenvolvimento do código.