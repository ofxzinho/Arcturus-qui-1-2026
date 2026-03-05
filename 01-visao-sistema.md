# 📖 Documento de Visão do Sistema — Marketech

## 1. Introdução
O Marketech é um sistema de compras online desenvolvido para supermercados com o objetivo de modernizar e facilitar a experiência de compra dos clientes. A plataforma permite que os usuários visualizem produtos disponíveis, consultem preços e verifiquem a disponibilidade em estoque em tempo real.

Por meio do sistema, os clientes podem realizar compras de forma totalmente digital, sem precisar se deslocar até o supermercado. Após finalizar o pedido, o usuário pode escolher entre retirar os produtos diretamente no estabelecimento ou receber a compra em casa. Além de melhorar a experiência do cliente, o sistema também auxilia na gestão interna do supermercado, oferecendo ferramentas para controle e atualização de estoque.

## 2. Objetivos
O sistema Marketech busca resolver problemas comuns enfrentados por clientes de supermercados e melhorar a eficiência do processo de compras.

Problemas e benefícios esperados:

- Falta de tempo para ir ao mercado: o sistema permite que as compras sejam feitas de qualquer lugar e a qualquer momento.
- Dificuldades físicas ou de mobilidade: usuários com limitações físicas podem realizar compras online e optar pela entrega em domicílio.
- Falta de informação sobre disponibilidade de produtos: o sistema apresenta preços e quantidades atualizadas em tempo real.
- Gastos e tempo com deslocamento: a opção de entrega ou retirada programada reduz custos e otimiza o tempo do cliente.
- Dificuldade em encontrar produtos no mercado: o sistema possui ferramentas de busca e organização por categorias.

## 3. Stakeholders
Os principais interessados no sistema são:

- **Cliente:** usuário que realiza compras online no supermercado, podendo criar conta, navegar pelos produtos, adicionar itens ao carrinho, realizar pagamento e acompanhar o pedido.
- **Trabalhador do Mercado (Operador):** funcionário responsável pela atualização de informações no sistema, como cadastro de produtos, atualização de preços e controle de estoque.
- **Administrador:** responsável pela gestão geral do sistema, incluindo controle de usuários, monitoramento de pedidos e análise de relatórios de vendas e estoque.

## 4. Escopo
As principais funcionalidades previstas para o sistema incluem:

- Cadastro e autenticação de usuários com diferentes níveis de acesso.
- Catálogo de produtos com filtros por categoria, nome e preço.
- Visualização da disponibilidade e quantidade de produtos em estoque em tempo real.
- Carrinho de compras com cálculo automático do valor total e aplicação de cupons de desconto.
- Processo de checkout com escolha entre entrega em domicílio ou retirada no supermercado.
- Integração com meios de pagamento, como cartão de crédito, débito, Pix e pagamento na retirada.
- Acompanhamento do status do pedido em tempo real (confirmado, em preparo, saiu para entrega e entregue).
- Painel de gerenciamento de estoque para funcionários com funcionalidades de cadastro, edição e remoção de produtos.
- Painel administrativo com relatórios de vendas, produtos mais vendidos e gerenciamento de usuários.

## 5. Restrições
O sistema possui algumas restrições que devem ser consideradas durante o desenvolvimento.

- **Técnicas:** o sistema depende de conexão com a internet para funcionamento e será inicialmente compatível com dispositivos Android, iOS e navegadores modernos. A atualização do estoque em tempo real depende da integração com os sistemas internos do supermercado.
- **Prazo:** o desenvolvimento deve seguir o cronograma estabelecido pela instituição de ensino e cumprir os prazos definidos pelo professor responsável.
- **Legais:** o sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD). Além disso, os dados de pagamento devem seguir padrões de segurança como o PCI-DSS e o uso de bibliotecas externas deve respeitar suas licenças.

## 6. Critérios de Sucesso
O sucesso do sistema será avaliado com base nos seguintes indicadores:

- Pelo menos 70% dos clientes do supermercado devem realizar ao menos uma compra pelo aplicativo nos primeiros três meses após o lançamento.
- A diferença entre o estoque exibido no sistema e o estoque físico real deve ser inferior a 5%.
- O sistema deve atingir avaliação média mínima de 4 estrelas nas lojas de aplicativos e pesquisas de satisfação.
- O tempo de resposta das requisições do sistema deve ser de no máximo 3 segundos em condições normais de uso.
- O sistema deve manter disponibilidade mínima de 99% do tempo.
- A taxa de pedidos com erros ou inconsistências deve ser inferior a 2% do total de pedidos.
