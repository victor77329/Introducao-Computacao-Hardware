# Atividade: Compra em um E-commerce

## Cenário

Um cliente acessa uma loja virtual para comprar um produto. Ele seleciona o item desejado, informa seus dados de entrega e realiza o pagamento. Após a confirmação, o sistema processa o pedido e envia as informações para separação e entrega.

## Entradas (Inputs)

* Dados do cliente (nome, endereço, e-mail e telefone).
* Produto selecionado.
* Quantidade desejada.
* Dados de pagamento (cartão, PIX ou boleto).
* Cupom de desconto (opcional).

## Processamento

1. Verificação da disponibilidade do produto em estoque.
2. Cálculo do valor total da compra.
3. Aplicação de descontos ou cupons promocionais.
4. Validação do pagamento.
5. Registro do pedido no banco de dados.
6. Atualização da quantidade disponível em estoque.
7. Geração do número do pedido.
8. Envio da solicitação para separação e entrega.

## Saídas (Outputs)

* Confirmação da compra.
* Número do pedido.
* Comprovante de pagamento.
* Atualização do estoque.
* Notificação por e-mail ou SMS ao cliente.
* Informações de rastreamento da entrega.

## Classificação do Sistema

### Tipo: SPT (Sistema de Processamento de Transações)

### Justificativa

O sistema de compra em um e-commerce é classificado como um Sistema de Processamento de Transações (SPT), pois sua principal função é registrar, processar e armazenar transações rotineiras da empresa. Cada compra realizada pelo cliente gera uma transação que envolve atualização de estoque, registro de pagamento e emissão de comprovantes. Essas operações são executadas de forma rápida, precisa e em grande volume, características típicas dos sistemas SPT.

Embora os dados gerados possam ser utilizados posteriormente por sistemas SIG, SAD ou SIE para análises e tomada de decisão, o processo de compra em si pertence à categoria de Sistema de Processamento de Transações (SPT).
