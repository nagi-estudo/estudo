# Resumo de video que vi

https://github.com/mattpocock/skills

## Engenharia reversa

A engenharia reversa permite desvendar o funcionamento de programas compilados, transformando código de máquina em representações compreensíveis para humanos. Ao analisar um executável, o primeiro passo é verificar o tipo de arquivo e listar as funções importadas, o que ajuda a identificar o uso de recursos como a geração de números aleatórios.

Ferramentas de desassemble, como o IDA Pro, permitem visualizar o fluxo do programa, identificando pontos de entrada de dados e a lógica interna. Em cenários onde um programa utiliza uma semente fixa ou previsível para gerar números aleatórios, é possível antecipar os resultados que o sistema espera como validação.

Com essa previsibilidade, cria-se uma tabela de referência que associa possíveis entradas aos resultados gerados. Ao extrair os valores verificadores diretamente do binário, utiliza-se a lógica reversa para comparar esses dados com a tabela, permitindo identificar a sequência exata de caracteres necessária para completar a tarefa pretendida pelo software original.
