# Avaliação de Redação do ENEM com Python e IA

Este programa em Python utiliza a IA Gemini e técnicas de Processamento de Linguagem Natural (PLN) para avaliar uma redação com base nos critérios estabelecidos pelo Exame Nacional do Ensino Médio (ENEM) e atribuir uma nota de 0 a 1000. A seguir, será explicado o funcionamento do código:

Entrada de Dados:

O programa solicita ao usuário que insira o tema da redação e a própria redação em si. Esses dados serão utilizados para a avaliação.
Função de Avaliação:

A função avaliar_redacao recebe como parâmetros o tema e a redação inseridos pelo usuário. Ela simula a IA para atribuir uma nota com base em cinco critérios principais, cada um avaliado em uma escala de 0 a 200:

* Domínio da escrita formal em língua portuguesa.
* Compreensão do tema e aplicação das áreas de conhecimento.
* Capacidade de interpretação das informações e organização dos argumentos.
* Domínio dos mecanismos linguísticos de argumentação.
* Capacidade de conclusão com propostas coerentes que respeitem os direitos humanos.
* A nota final é calculada somando as notas de cada critério.

Após a avaliação, o programa retorna a nota final da redação sobre o tema especificado pelo usuário, com possíveis melhorias e resumo geral.
