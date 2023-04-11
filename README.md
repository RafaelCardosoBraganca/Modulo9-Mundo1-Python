# Modulo9 Mundo1 Python
 Dando cores ao Python


Nessa aula, vamos aprender como utilizar os códigos de escape sequence ANSI para configurar cores para os seus programas em Python. Veja como utilizar o código \033[m com todas as suas principais possibilidades.

                        EX: \033[0;33;40m >>> NONE; AMARELO; BRANCO
que são respectivamente         [STYLE; TEXT; BACKGROUNDm

Os estilos são divididos em: Nenhum, Negrito, Sublinhado e Negativo
STYLE  >> O: None || 1: Bold || 4: Underline || 7: Negative

as cores do TEXT vão de 30 à 37 sendo:
TEXT  >> 30: BRANCO  ||  31: VERMELHO  ||  32 VERDE||  33: AMARELO || 34: AZUL ||  35: ROXO  || 36: CIANO  ||  37: CINZA


as cores de background vão de 40 à 47 sendo:
BACK  >> 40: BRANCO  ||  41: VERMELHO  ||  42 VERDE||  43: AMARELO || 44: AZUL ||  45: ROXO  || 46: CIANO  ||  47: CINZA

Ex: caso eu queira uma que aparecesse no terminal um estilo bold; uma cor de texto vermelho;  e um fundo amarelo
eu devo escrever \033[1;31;43m

