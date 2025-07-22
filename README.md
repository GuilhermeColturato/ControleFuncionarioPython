# Sistema de Controle de Funcionários

Este projeto implementa uma classe `Funcionário` que gerencia informações pessoais, horas trabalhadas e salário por hora, com foco no cálculo do salário mensal baseado nos dados mensais.

## Descrição da Classe `Funcionário`

A classe possui os seguintes atributos:

- `nome`: nome do funcionário.
- `email`: e-mail do funcionário.
- `horas_trabalhadas`: dicionário onde as chaves são os meses e os valores são as horas trabalhadas no respectivo mês.
- `salario_por_hora`: dicionário onde as chaves são os meses e os valores são os salários por hora relativos a cada mês.

## Método Principal

- `salario_mensal(mes)`: retorna o salário do funcionário para o mês informado, calculando a partir das horas trabalhadas e do salário por hora correspondentes.

---

## Organização dos Arquivos

O projeto será organizado em dois arquivos:

- Um arquivo contendo a definição da classe `Funcionário`.
- Outro arquivo para a execução e testes dos métodos da classe.
