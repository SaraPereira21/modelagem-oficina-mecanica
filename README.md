# Modelagem Oficina Mecanica
Projeto de Modelagem Conceitual de Banco de Dados para Oficina Mecânica.

## Descrição
Este projeto envolve a criação de um modelo conceitual de banco de dados para gerenciar eficientemente as operações de uma oficina mecânica. O modelo inclui tabelas essenciais para armazenar informações sobre clientes, mecânicos e ordens de serviço (OS), além de outros detalhes operacionais.

## Estrutura do Banco de Dados
### Entidades Principais:
- **Clientes**:
  - Nome
  - Endereço
  - Modelo do veículo
  - Telefone
  - CPF
- **Mecânicos**:
  - Nome
  - Endereço
  - Especialidade
- **Ordens de Serviço (OS)**:
  - Id
  - Serviço
  - Valor da mão de obra (MDO)
  - Valor das peças
  - Data de emissão
  - Data de entrega
  - Modelo do veículo
  - Tempo de execução do serviço
  - Mecânico responsável
  - Status de aprovação do orçamento
  - Status do serviço

## Objetivo
O objetivo principal deste projeto é criar uma base de dados que possibilite a gestão eficiente dos clientes e suas respectivas ordens de serviço, garantindo uma operação fluida e bem documentada dentro da oficina mecânica.

## Ferramentas Utilizadas
- **MySQL Workbench**: Utilizado para criar e visualizar o modelo conceitual do banco de dados.
- **PDF**: Simples visualização.
