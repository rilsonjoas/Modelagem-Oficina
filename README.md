# Sistema de Controle e Gerenciamento de Ordens de Serviço - Oficina Mecânica

Este projeto tem como objetivo implementar um sistema para controle e gerenciamento da execução de ordens de serviço (OS) em uma oficina mecânica. O sistema foi modelado conforme o diagrama presente em `Oficina.png` e o arquivo de modelagem `Oficina.mwb`.

## Descrição do Sistema

O sistema permite que clientes levem seus veículos à oficina para conserto ou revisão periódica. Cada veículo é designado a uma equipe de mecânicos, que identifica os serviços necessários e preenche uma ordem de serviço (OS) com data de entrega prevista.

A partir da OS, o sistema calcula o valor de cada serviço consultando uma tabela de referência de mão-de-obra. O valor das peças utilizadas também é incluído na OS. O cliente autoriza a execução dos serviços, que são avaliados e executados pela mesma equipe de mecânicos.

### Principais Entidades
- **Mecânico:** Possui código, nome, endereço e especialidade.
- **Equipe:** Responsável pela execução dos serviços.
- **Veículo:** Associado ao cliente e à OS.
- **Cliente:** Proprietário do veículo.
- **Ordem de Serviço (OS):** Contém número, data de emissão, valor total, status e data de conclusão prevista.
- **Serviço:** Associado à OS, com valor calculado conforme tabela de mão-de-obra.
- **Peça:** Valor incluído na OS conforme necessidade do serviço.

## Funcionalidades
- Cadastro de clientes, veículos, mecânicos e equipes.
- Emissão e gerenciamento de ordens de serviço.
- Cálculo automático do valor dos serviços e peças.
- Controle de status e datas de conclusão das OS.

## Modelagem
A modelagem do banco de dados foi realizada utilizando o MySQL Workbench, conforme o arquivo `Oficina.mwb`. O diagrama visual pode ser consultado em `Oficina.png`.

## Como utilizar
1. Abra o arquivo `Oficina.mwb` no MySQL Workbench para visualizar e/ou modificar o modelo de dados.
2. Consulte o diagrama em `Oficina.png` para entender as relações entre as entidades.
3. Implemente o sistema conforme a modelagem proposta, utilizando a linguagem e framework de sua preferência.

## Autor
Projeto desenvolvido por Rilson Joás.