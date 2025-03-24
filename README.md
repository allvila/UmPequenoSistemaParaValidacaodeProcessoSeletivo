
# Processo Seletivo

Este projeto Java simula um processo seletivo para uma vaga de emprego. Ele realiza as seguintes operações:

* **Seleção de Candidatos:** Seleciona candidatos com base no salário pretendido, comparando-o com o salário base da empresa.
* **Contato com Candidatos:** Simula o contato telefônico com os candidatos selecionados, com um número limitado de tentativas.
* **Impressão de Lista de Candidatos:** Imprime a lista de candidatos com seus respectivos índices.
* **Análise de Candidatos:** Analisa o salário pretendido de um candidato e decide se ele deve ser contactado.

## Aprendizados na DIO

Este projeto foi desenvolvido como parte do meu aprendizado na plataforma DIO (Digital Innovation One). Durante o desenvolvimento, tive a oportunidade de aplicar e aprofundar meus conhecimentos em:

* **Lógica de programação:** Estruturação do código para simular um processo seletivo real.
* **Programação orientada a objetos (POO):** Utilização de classes e métodos para organizar o código de forma modular e reutilizável.
* **Manipulação de arrays:** Utilização de arrays para armazenar e manipular dados dos candidatos.
* **Estruturas de controle de fluxo:** Utilização de loops e condicionais para controlar o fluxo de execução do programa.
* **Geração de números aleatórios:** Utilização da classe `Random` e `ThreadLocalRandom` para simular eventos aleatórios, como o contato telefônico com os candidatos e o salário pretendido.

## Estrutura do Projeto

O projeto consiste em uma única classe Java, `ProcessoSeletivo`, que contém os seguintes métodos:

* `main(String[] args)`: Método principal que inicia o processo seletivo.
* `selecaoCandidatos()`: Seleciona candidatos com base no salário pretendido.
* `valorPretendido()`: Gera um valor aleatório para o salário pretendido de um candidato.
* `analisarCandidato(double salarioPretendido)`: Analisa o salário pretendido de um candidato.
* `imprimirSelecionados()`: Imprime a lista de candidatos com seus índices.
* `entrarEmContato(String candidato)`: Simula o contato telefônico com um candidato.
* `atender()`: Simula se um candidato atendeu o telefone.

## Como Executar

Para executar o projeto, siga estas etapas:

1.  Certifique-se de ter o Java Development Kit (JDK) instalado em seu sistema.
2.  Compile o código Java usando o seguinte comando:
    ```bash
    javac ProcessoSeletivo.java
    ```
3.  Execute o programa Java usando o seguinte comando:
    ```bash
    java ProcessoSeletivo
    ```

## Detalhes do Código

* A seleção de candidatos é feita comparando o salário pretendido de cada candidato com um salário base de R$ 2000,00.
* O contato com os candidatos é simulado com um máximo de 3 tentativas.
* A função `atender()` usa um gerador de números aleatórios para simular se um candidato atende o telefone.
* A função `valorPretendido()` usa a classe `ThreadLocalRandom` para gerar um valor aleatório entre R$ 1800,00 e R$ 2200,00.

## Observações

* O código utiliza a classe `Random` para gerar números aleatórios, simulando a aleatoriedade do processo de contato telefônico.
* O código utiliza a classe `ThreadLocalRandom` para gerar números aleatórios, simulando a aleatoriedade do salário pretendido.
* O código pode ser estendido para incluir mais funcionalidades, como armazenamento de dados dos candidatos em um banco de dados ou em um arquivo.

## Possíveis Melhorias

* Implementar uma interface gráfica para tornar o processo seletivo mais interativo.
* Adicionar mais critérios de seleção, como experiência e qualificações dos candidatos.
* Permitir que o usuário defina o número de tentativas de contato e o salário base.
* Armazenar os dados dos candidatos em um banco de dados ou em um arquivo para análise posterior.
* Adicionar tratamento de exceções para lidar com possíveis erros durante a execução do programa.
* Adicionar testes unitários para garantir a qualidade do código.
