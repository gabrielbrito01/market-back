# API do Mercado Unifacisa

## Como iniciar o Back-end

#### --> npm install
#### --> npm start

## Rota de Autenticação

### Login de Funcionário
- **Método**: POST
- **URL**: `/auth/employee`
- **Descrição**: Permite que um funcionário faça login na plataforma.

### Login de Cliente
- **Método**: POST
- **URL**: `/auth/client`
- **Descrição**: Permite que um cliente faça login na plataforma.

## Rotas de Carrinho

### Criar Carrinho
- **Método**: POST
- **URL**: `/car`
- **Descrição**: Cria um novo carrinho.

### Obter Carrinho
- **Método**: GET
- **URL**: `/car/:id`
- **Descrição**: Retorna informações sobre um carrinho específico.

### Atualizar Carrinho
- **Método**: PUT
- **URL**: `/car/:id`
- **Descrição**: Atualiza as informações de um carrinho específico.

### Deletar Carrinho
- **Método**: DELETE
- **URL**: `/car/:id`
- **Descrição**: Deleta um carrinho específico.

## Rotas de Clientes

### Criar Cliente
- **Método**: POST
- **URL**: `/clients`
- **Descrição**: Cria um novo cliente.

### Obter Cliente
- **Método**: GET
- **URL**: `/clients/:cpf`
- **Descrição**: Retorna informações sobre um cliente específico.

### Atualizar Cliente
- **Método**: PUT
- **URL**: `/clients/:cpf`
- **Descrição**: Atualiza as informações de um cliente específico.

### Deletar Cliente
- **Método**: DELETE
- **URL**: `/clients/:cpf`
- **Descrição**: Deleta um cliente específico.

## Rotas de Funcionários

### Criar Funcionário
- **Método**: POST
- **URL**: `/employees`
- **Descrição**: Cria um novo funcionário.

### Obter Funcionários
- **Método**: GET
- **URL**: `/employees`
- **Descrição**: Retorna informações sobre os funcionários.

### Atualizar Funcionário
- **Método**: PUT
- **URL**: `/employees/:cpf`
- **Descrição**: Atualiza as informações de um funcionário específico.

### Deletar Funcionário
- **Método**: DELETE
- **URL**: `/employees/:cpf`
- **Descrição**: Deleta um funcionário específico.

## Rotas de Produtos

### Listar Todos os Produtos
- **Método**: GET
- **URL**: `/products/all`
- **Descrição**: Retorna uma lista de todos os produtos disponíveis.

### Criar Produto
- **Método**: POST
- **URL**: `/products`
- **Descrição**: Cria um novo produto.

### Obter Produto
- **Método**: GET
- **URL**: `/products/:code`
- **Descrição**: Retorna informações sobre um produto específico.

### Configurar Promoção de Produto
- **Método**: PUT
- **URL**: `/products/:code`
- **Descrição**: Configura uma promoção para um produto específico.

### Deletar Produto
- **Método**: DELETE
- **URL**: `/products/:code`
- **Descrição**: Deleta um produto específico.

## Autenticação

A autenticação é necessária para acessar algumas rotas, como aquelas relacionadas a clientes, funcionários e produtos. Certifique-se de incluir as credenciais de autenticação corretas ao fazer as solicitações para essas rotas.

