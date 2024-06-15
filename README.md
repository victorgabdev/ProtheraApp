# Projeto de Gestão de Funcionários - AppProthera

Este projeto Java é uma aplicação de exemplo para gerenciamento de funcionários, utilizando as camadas de serviço, modelo e aplicação principal.

## Estrutura do Projeto

O projeto está organizado em três principais camadas:

1. **Modelo (model):**
   - **Funcionario:** Representa a entidade Funcionário, com atributos como nome, data de nascimento, salário e função.
   - **Pessoa:** Classe base que encapsula atributos comuns entre entidades que representam pessoas, como nome e data de nascimento.

2. **Serviço (service):**
   - **FuncionarioService:** Contém a lógica de negócio relacionada aos funcionários, incluindo operações como inserção, remoção, aumento de salários, agrupamento por função, entre outras.

3. **Aplicação (application):**
   - **AppProthera:** Classe principal da aplicação que inicia e controla o fluxo de execução. Esta classe contém o método `main` e utiliza instâncias de `FuncionarioService` para gerenciar os funcionários e imprimir relatórios.

## Funcionalidades Implementadas

O projeto inclui as seguintes funcionalidades:

- Inserção inicial de funcionários.
- Remoção de funcionário por nome.
- Aumento percentual nos salários dos funcionários.
- Agrupamento de funcionários por função.
- Impressão de funcionários aniversariantes de determinados meses.
- Identificação do funcionário mais velho.
- Ordenação dos funcionários por ordem alfabética.
- Cálculo do total de salários.
- Cálculo de salários em relação ao salário mínimo.

## Requisitos

- Java 8 ou superior.
- Biblioteca `java.time` para manipulação de datas.
- Biblioteca `java.math` para manipulação de valores monetários.

## Como Executar

Para executar o projeto:

1. Clone o repositório para sua máquina local.
2. Abra o projeto em sua IDE Java preferida (por exemplo, IntelliJ IDEA, Eclipse).
3. Execute a classe `AppProthera` diretamente ou através do IDE.

Certifique-se de ter configurado corretamente o ambiente de desenvolvimento com Java JDK e todas as dependências necessárias.


## Como Contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/YourFeature`).
3. Faça o commit de suas alterações (`git commit -m 'Add some YourFeature'`).
4. Faça o push para a branch (`git push origin feature/YourFeature`).
5. Abra um Pull Request.

## Contato

Para mais informações, entre em contato através do email: victorgabdev@gmail.com


