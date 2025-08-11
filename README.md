Sistema de Gerenciamento de Pedidos e Clientes

Este projeto em Python gerencia clientes, cardápio e pedidos para um estabelecimento comercial, utilizando arquivos CSV para armazenamento.

Funcionalidades

- Cadastro, listagem e descadastramento de clientes
- Visualização do cardápio categorizado
- Registro de pedidos com múltiplos itens
- Atualização automática de pontos para clientes cadastrados
- Visualização da fila de pedidos
- Fechamento (remoção) de pedidos da fila

Estrutura dos arquivos CSV

- Cardapio.csv: contém categorias, itens, preços e promoções
- Clientes.csv: armazena dados dos clientes e seus pontos acumulados
- Pedidos.csv: mantém a fila de pedidos com código, itens e cliente vinculado

Como usar

- Execute o script principal que contém as funções Clientes_(), Cardapio_() e Pedidos_()
- Navegue pelo menu para gerenciar clientes e pedidos
- Para registrar um pedido, informe quantos itens, IDs dos itens e, se o cliente for cadastrado, o ID do cliente
- Para fechar um pedido, informe o código do pedido para removê-lo da fila

Requisitos

- Python 3.x
- Biblioteca padrão CSV
- Rodar em ambiente que suporte input() e print() (terminal ou Jupyter notebook)

Observações

- Os arquivos CSV devem estar no caminho especificado dentro do código, ou ajustar as variáveis de caminho conforme sua estrutura de pastas
- Os IDs de pedidos são gerados automaticamente com base no horário atual
- O sistema utiliza pontos para premiar clientes cadastrados (10 pontos por item pedido)
