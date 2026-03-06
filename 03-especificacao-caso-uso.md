# 📝 Especificação de Caso de Uso

## 1. Introdução
A Especificação de Caso de Uso tem como objetivo detalhar o comportamento das funcionalidades do sistema. Cada caso de uso descreve como os atores interagem com o sistema para realizar determinadas ações, apresentando pré-condições, fluxo principal, possíveis exceções e regras de negócio.

No sistema **Marketech**, essa especificação ajuda a documentar de forma clara como os usuários realizam ações como login, compra de produtos e gerenciamento do sistema, auxiliando no desenvolvimento e na validação dos requisitos.

---

## 2. Casos de Uso

### Caso de Uso: Realizar Login

| Item | Descrição |
|-----|-----------|
| **Nome** | Realizar Login |
| **Ator Principal** | Cliente / Funcionário / Administrador |
| **Pré-condições** | Usuário já cadastrado no sistema |
| **Fluxo Principal** | 1. Usuário acessa a tela de login <br> 2. Usuário insere e-mail e senha <br> 3. Sistema valida as credenciais <br> 4. Sistema concede acesso ao usuário |
| **Fluxos Alternativos** | Credenciais inválidas → Sistema exibe mensagem de erro e solicita nova tentativa |
| **Pós-condições** | Usuário autenticado e com acesso às funcionalidades do sistema |
| **Regras de negócio** | Senha deve possuir no mínimo 8 caracteres |

---

### Caso de Uso: Buscar Produto

| Item | Descrição |
|-----|-----------|
| **Nome** | Buscar Produto |
| **Ator Principal** | Cliente |
| **Pré-condições** | Usuário acessando o catálogo de produtos |
| **Fluxo Principal** | 1. Usuário acessa o catálogo <br> 2. Usuário digita o nome do produto ou seleciona categoria <br> 3. Sistema apresenta os produtos correspondentes |
| **Fluxos Alternativos** | Produto não encontrado → Sistema exibe mensagem informando que não há resultados |
| **Pós-condições** | Lista de produtos exibida ao usuário |
| **Regras de negócio** | Produtos devem ser exibidos com preço e disponibilidade atualizados |

---

### Caso de Uso: Adicionar Produto ao Carrinho

| Item | Descrição |
|-----|-----------|
| **Nome** | Adicionar Produto ao Carrinho |
| **Ator Principal** | Cliente |
| **Pré-condições** | Usuário autenticado no sistema |
| **Fluxo Principal** | 1. Usuário seleciona um produto <br> 2. Usuário clica em "Adicionar ao carrinho" <br> 3. Sistema adiciona o produto ao carrinho <br> 4. Sistema atualiza o valor total do carrinho |
| **Fluxos Alternativos** | Produto indisponível → Sistema informa que o item está fora de estoque |
| **Pós-condições** | Produto adicionado ao carrinho de compras |
| **Regras de negócio** | A quantidade adicionada não pode ser maior que o estoque disponível |

---

### Caso de Uso: Realizar Compra

| Item | Descrição |
|-----|-----------|
| **Nome** | Realizar Compra |
| **Ator Principal** | Cliente |
| **Pré-condições** | Usuário autenticado e com produtos no carrinho |
| **Fluxo Principal** | 1. Usuário acessa o carrinho <br> 2. Usuário confirma os produtos <br> 3. Usuário escolhe forma de entrega ou retirada <br> 4. Usuário seleciona forma de pagamento <br> 5. Sistema processa o pagamento <br> 6. Sistema confirma o pedido |
| **Fluxos Alternativos** | Pagamento recusado → Sistema solicita outra forma de pagamento |
| **Pós-condições** | Pedido registrado no sistema |
| **Regras de negócio** | O pedido só é confirmado após a validação do pagamento |

---

### Caso de Uso: Atualizar Estoque

| Item | Descrição |
|-----|-----------|
| **Nome** | Atualizar Estoque |
| **Ator Principal** | Funcionário do Mercado |
| **Pré-condições** | Funcionário autenticado com permissão de edição |
| **Fluxo Principal** | 1. Funcionário acessa o painel de gerenciamento <br> 2. Funcionário seleciona um produto <br> 3. Funcionário altera a quantidade em estoque <br> 4. Sistema salva a atualização |
| **Fluxos Alternativos** | Dados inválidos → Sistema solicita correção das informações |
| **Pós-condições** | Estoque atualizado no sistema |
| **Regras de negócio** | Apenas funcionários autorizados podem alterar o estoque |
