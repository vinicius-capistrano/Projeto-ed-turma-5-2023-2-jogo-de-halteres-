# Projeto-ed-turma-5-2023-2-jogo-de-halteres-
Título do projeto:
o projeto é um jogo chamado empilha halter, nele você é um professor de academia que tem a função de ordenar a pilha de halteres dos alunos
que quase sempre deixam ela fora de ordem depois de usar, você também precisa atender seus pedidos por halteres, verificando se estão disponíveis ou 
sendo usados por outros alunos.

Autores:
Vinícius Capistrano Soares
Aluno da turma 05 2023/2 da disciplina estruturas de dados, matrícula:221018998

Contexto de aplicação e estrutura de dados escolhida:
Foi utilizada uma lista duplamente encadeada com comportamento de pilha neste projeto, foram utilizadas
as funções de inserção, busca, impressão e ordenção pós inserção(insertion sort), a função inserção 
serviu para criar uma pilha de números que no contexto do jogo são pesos desordenados, a função busca é utilizada
na pilha criada anteriormente para procurar alguns números que são importantes pro jogador, os resultados dessa busca são
comparados com as entradas do jogador para verificar se estão corretas, a funcão de ordenação pós inserção é utilizada para 
determinar o comportamento do programa em um caso específico do código onde a pilha original desordenada é igual a pilha ordenada(utilizando a função), 
a função de impressão serve para exibir no shell do ide a pilha desordenada para o jogador ver.

Instruções de execução:
Para executar é só colar o código em algum ambiente de desenvolvimento(que execute código python 3.8 ou superior),
o programa pode ser executado em qualquer ide(como vs code, thoony, py charm), é ideal configurar o ide de forma que fique visível somente 
o shell/terminal do ide de forma que o código não sejá vísivel durante o jogo , a visualização das instruções do jogo ficam melhor se 
o shell preencher a maior parte da tela do computador, o jogo instrui apertar a tecla F5 para iniciar outra partida, mas é preciso 
verificar se essa é a tecla do seu ide para rodar código, executar programas

Instruções de Uso:
Para que o jogo seja melhor aproveitado, é ideal jogar sem qualquer calculadora e com um papel e caneta, no jogo é necessário que o jogador
realize conversões entre pesos de unidades diferentes, no caso libras para kilogramas, você pode escolher seu método de conversão mas lembre que
o número resultante da conversão deve ter três números depois da vírgula(8,618 por exemplo).
Ao iniciar o jogador vai ver a pilha de pesos desordenados e com unidades diferentes(caso todas já estejam em kg é só ordenar), o jogador é instruido 
a inserir os números convertidos na ordem do menor até o maior,lembrando dos detalhes importantes presentes nas intruções dentro do jogo, se o jogador
inserir os números de forma correta vai passar pra fase 2 onde deve responder os pedidos de halteres feitos pelos alunos dentro do jogo, o desafio está em 
lembrar se o número e a unidade do peso requisitadas estão presentes na pilha, se não lembrar pode verificar no shell a pilha original ou a que ele ordenou,
deve responder os alunos com 'sim' ou 'não' para chegar ao fim do jogo.

Referências:
Chat GPT--foi utilizado no projeto uma implementação de lista duplamente encadeada com comportamento de pilha e operações requisitadas na especificação do projeto,
a implementação foi gerada pelo chat GPT, a partir da linha 53 todo o código é de minha autoria
