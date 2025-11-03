# Projeto Conceitual de Banco de Dados – E-COMMERCE

## Descrição do Desafio

Este projeto conceitual de banco de dados foi desenvolvido como parte de um desafio para aprimorar um esquema de e-commerce existente. O objetivo principal foi refinar o modelo, incorporando requisitos específicos de negócios, como a gestão de diferentes tipos de clientes, múltiplos métodos de pagamento e o rastreamento de entregas.

## Objetivos e Refinamentos Implementados

O modelo de dados foi refinado para incluir os seguintes pontos:

*   **Cliente PJ e PF:** A estrutura foi ajustada para suportar clientes Pessoa Física (PF) e Pessoa Jurídica (PJ). Uma conta de cliente pode ser associada a um tipo ou outro, mas não a ambos simultaneamente. Isso geralmente é tratado com tabelas separadas ou um mecanismo de herança/especialização no modelo conceitual/lógico.
*   **Pagamento:** O modelo permite o cadastro de múltiplas formas de pagamento para um mesmo cliente ou pedido, através de uma tabela ou entidade de relacionamento dedicada.
*   **Entrega:** Foi adicionada uma entidade ou atributos para gerenciar o status da entrega (ex: "Pendente", "Em Trânsito", "Entregue") e um código de rastreio exclusivo para acompanhamento.

## Diagrama do Modelo Conceitual que foi feito por mim 

<img width="969" height="764" alt="imagem-ecommerce" src="https://github.com/user-attachments/assets/a069320d-c024-4f36-8cf2-3f1330184502" />


## Tecnologias/Ferramentas Utilizadas

*   [MySQL Workbench]


