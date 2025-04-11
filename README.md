**Entidades de Domínio**
**Produto**
ID único
Nome, descrição, tamanho, cor
Estoque atual
Quantidade mínima
Histórico de movimentações
**Estoque**
Produto associado
Quantidade disponível
Quantidade mínima
Histórico de movimentações (entrada/saída)
**Venda**
Produto vendido
Quantidade
Data da venda
Preço/venda unitário e total
Luco
**Ordem de Compra**
Produtos a serem comprados
Quantidade solicitada
Data da ordem
Status (pendente, enviada, recebida)
**Fornecedor**
Nome
Produtos fornecidos
Prazos de entrega
Dados de contato
**Alerta**
Tipo (baixa de estoque)
Produto associado
Canal de notificação (e-mail, sistema)

**Casos de Uso**
Cadastrar/atualizar produtos
Incluir dados como ID único, nome, tamanho, cor, etc.
Definir/editar quantidade mínima de estoque para um produto
Atualizar estoque
Entrada de produtos (compra ou devolução)
Saída de produtos (venda ou perda)
Gerar alertas de baixa de estoque
Enviar notificações por e-mail e no sistema
Visualizar histórico de vendas
Por período, por produto, com lucro e quantidade
Visualizar histórico de estoque
Tendência de movimentação ao longo do tempo
Gerar relatório de produtos mais vendidos por período
Criar ordem de compra automaticamente
Baseada em: produtos com estoque abaixo do mínimo + tendência de vendas
Gerenciar ordens de compra
Criar, editar, acompanhar status
Integrar com fornecedores
Receber atualizações automáticas sobre prazos de entrega
