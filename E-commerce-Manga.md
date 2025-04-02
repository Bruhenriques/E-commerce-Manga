## E-Commerce Manga

# Requisitos Funcionais 

- RF1: Cadastro e login de usuários: Permitir cadastro de clientes/login onde eles possam usar telefone, email, endereço e senha;

- RF1: Gerenciamento do inventario de produtos da loja: Tirar, colocar produto em estoque, e poder gerenciar os preços;

- RF8: O sistema deve ter um banco de dados com tabelas dos clientes e produtos;

- RF1: O sistema deve permitir o usuário de fazer o pagamento e checkout;
  
- RF1: Sistema deve validar os dados e o usuário receber um email de confirmação;

- RF3: Carrinho de compras: Adicionar e remover itens do carrinho, exibir valor da compra;

- RF1: Sistema de pesquisa de produtos: O sistema deve permitir procurar por texto ou usar filtros de pesquisa(exemplo: gênero, ano, preço...);

- RF1: Site deve exibir detalhes dos produtos para o usuário (capa, descrição, preço, autor, editora e avaliação);

- RF6: Usuário deve conseguir visualizar o status do pedido: Código de rastreio, enviado e entregue;

- RF5: Suporte ao cliente: Resolver problemas de cadastro, vendas, etc;

- RF8: Recomendação: Site deve usar o histórico do comprador para sugerir mangás populares e lançamentos;

- RF7: Avaliação do usuário: Usuário pode comentar e avaliar o produto.

# Requisitos não funcionais 

- RNF1: Compatibilidade WEB e APP: O site/APP deve estar disponível 99,0% do tempo e ter um plano de recuperação para falhas;

- RNF2: Desempenho do site: Obter respostas a cada click em segundos e suportar pelo menos 500 acessos simultaneos sem perda de desempenho;

- RNF3: Modelo do site/app: Fácil acesso para o consumidor, deve ser intuitiva e fácil de navegar, seguindo padrões de acessibilidade para PCD;

- RNF4: Segurança do site e dados do consumidor: As senhas do usuário devem ser armazenadas e criptografadas;

- RNF5: O site deve ser tolerante a falhas.

# Regras de negocio 

- Gestão de produtos: Somente administradores podem cadastras, editar ou remover mangás do catalogo e produtos esgotados devem ser sinalizados;

- Usuário deve escolher forma de pagamento (cartão, boleto e pix) e informar o CPF;

- Carrinho de compras: O carrinho armazena os produtos por até 30 minutos. Usuário só pode add 10 itens ao carrinho;

- Transações: Parcelamentos podem incluir juros, pedido só será processado após confirmação do pagamento, reembolsos só podem ser permitidos em casos de defeito ou erro do pedido;

- Frete: Prazo de entrega conforme endereço do cliente, frete pode ser gratuito em compras acima de 100 reais e caso o pedido seja devolvido, ele arcará com o frete;

- Fidelidade e promoções: Usuários acumulam pontos a cada compra e podem ser trocados por desconto; cupons podem ter restrições; esses pontos podem ter validade de 12 meses sem uso.
