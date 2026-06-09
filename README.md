# Global-Solution - Data-Structure

# Fluxograma Simples

<img width="769" height="692" alt="image" src="https://github.com/user-attachments/assets/be3114eb-8972-4b59-9721-43d3d09e3f0d" />


#  Explicação da Lógica Utilizada

O sistema foi desenvolvido na linguagem Python com o objetivo de monitorar informações básicas de uma missão espacial.

O programa utiliza estruturas condicionais (`if` e `else`) para verificar situações críticas, como superaquecimento, baixo nível de energia e falha de comunicação.

Foi utilizado um laço de repetição `while` para manter o menu principal funcionando continuamente até que o usuário escolha encerrar o sistema.

As informações dos sensores são armazenadas em uma lista chamada `historico`, permitindo salvar e visualizar leituras anteriores realizadas durante a execução do programa.

O sistema também utiliza funções para separar cada funcionalidade do programa, como:

* inserir dados;
* visualizar status;
* executar análise;
* mostrar histórico.

Foram adicionadas validações de entrada para impedir valores inválidos no sistema, garantindo maior segurança e organização dos dados.

A análise automática verifica:

* temperatura acima de 80°C;
* energia abaixo de 20%;
* falha de comunicação.

Quando alguma dessas condições ocorre, o sistema exibe mensagens de alerta no terminal.

# Demonstração prática do Sistema

<img width="472" height="859" alt="image" src="https://github.com/user-attachments/assets/fa56f2cd-0911-464c-9b99-6ff6c7a739e0" />
