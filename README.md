# UE4TetrisAT-RT
Autor: Allan Tori  Orientador: Romero Tori 
10/4/18

Este projeto implementa o Tetris 3D usando uma estratégia diferente da usada no StartModel. Em vez de teste de colisão para parar as peças
que caem, é usada uma matriz vetorizada, que funciona como uma máscara do tabuleiro vertical onde as peças vão se acumulando, contendo 0 
ou 1 em cada posição para indicar se há ou não peça ou obstáculo (paredes e chão).

Trata-se de uma versão ainda em elaboração com algumas pendências:
P1 - comentários em protuguês e incompletos
P2 - layout dos blueprints precisam de organização
P3 - algumas funcionalidades ainda não implementadas (rotação contínua da peça enquanto se pressiona a tecla UP; varredura de todas 
as linhas para verificar quais estão completas; destruição das peças quando todos os seus cubos ficarem invisíveis; preenchimento da 
matriz mascara do tabuleiro quando a peça é rotacionada; pontuação; game over etc...)
P4 - há muitas melhorias que podem ser feitas, como simplificação do código, eliminação de redundâncias, reutilização de trechos de 
códigos, criação de funções, parametrização de todas as configurações que agora são fixas (como tamanho dos cubos, número de linhas e 
colunas, cores, fundo, texturas etc), inclusão de sons e efeitos especiais (como peças quebrando ou explodindo quando são eliminadas, fumaça etc..), mudar a matriz mascara para boolean, etc.

Atividades: 
1. Testar o programa e identificar bugs e possíveis melhorias
2. Implementar o máximo de correções, pendências e melhorias que conseguir
3. Fazer um breve relato (no README do projeto) das alterações realizadas 
