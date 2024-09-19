Como o Jogo Funciona
Escolhas Possíveis: O jogo começa definindo as três opções possíveis: "pedra", "papel" e "tesoura".

Loop de Jogo: Um loop while (true) é utilizado para permitir que o jogador faça várias escolhas até decidir sair digitando "sair".

Entrada do Jogador:

O jogador é solicitado a fazer uma escolha.
A escolha é convertida para minúsculas para evitar problemas de capitalização.
Se o jogador digitar "sair", o loop termina.
Validação da Escolha:

Se a escolha do jogador não estiver entre as opções válidas, uma mensagem de erro é exibida e o loop continua.
Escolha do Computador: O computador escolhe aleatoriamente uma das três opções utilizando a classe Random.

Comparação das Escolhas:

O jogo compara a escolha do jogador com a do computador para determinar o resultado:
Empate: Se as escolhas forem iguais.
Vitória do Jogador: Se a escolha do jogador vencer a do computador.
Derrota do Jogador: Nos outros casos.
Exibição do Resultado: O resultado da rodada é impresso, seguido de uma linha em branco para separar as jogadas.

Encerramento do Jogo: Ao final, quando o jogador digita "sair", uma mensagem de agradecimento é exibida.

Resumo da Lógica do Jogo
Regras:
Pedra vence tesoura.
Tesoura vence papel.
Papel vence pedra.
Esse tipo de jogo é ótimo para praticar lógica de programação, estruturas de controle e manipulação de entrada/saída em C#. 
