# Pesquisa-de-Satisfa-o---TudoWeb
Programa em Python que realiza uma pesquisa de opinião sobre o atendimento da empresa de marketing TudoWeb.

O que o programa faz

Para cada entrevistado (50 no total), o programa pede:

Nome
Idade (só aceita números)
Opinião sobre o atendimento (só aceita 1, 2 ou 3):
1 = EXCELENTE
2 = BOM
3 = RUIM

Ao final, exibe na tela:

a) a quantidade de respostas EXCELENTE
b) a quantidade de respostas RUIM

(Também mostra a quantidade de respostas BOM como informação extra.)

Conceitos utilizados
Estrutura de repetição for: uma volta do laço para cada entrevistado.
Estrutura de repetição while: valida a idade e a opinião, repetindo a pergunta enquanto a resposta for inválida.
Estrutura de decisão if / elif / else: verifica a opinião e soma no contador correto.
Variáveis contadoras: excelente, bom e ruim.
Como executar

Pesquisa completa (50 entrevistados):

python pesquisa.py

Teste rápido com 10 entrevistados:

python pesquisa.py 10
Teste com 10 entrevistados
#	Nome	Idade	Opinião
1	Ana Souza	28	1 (EXCELENTE)
2	Bruno Lima	35	2 (BOM)
3	Carla Mendes	41	1 (EXCELENTE)
4	Diego Alves	19	3 (RUIM)
5	Elisa Ramos	52	1 (EXCELENTE)
6	Fábio Costa	30	2 (BOM)
7	Gabriela Nunes	23	3 (RUIM)
8	Henrique Dias	47	1 (EXCELENTE)
9	Isabela Rocha	33	2 (BOM)
10	João Pedro	26	1 (EXCELENTE)

Na entrevistada 3, foram digitados de propósito uma idade inválida (abc) e uma opinião inválida (5) para testar a validação. O programa pediu novamente até receber um valor correto.

Resultado esperado e obtido: EXCELENTE = 5, RUIM = 2 (BOM = 3).

Prints de tela

Código

<img width="1040" height="802" alt="image" src="https://github.com/user-attachments/assets/ed1a29a5-4434-4f72-ae96-45948612bbfd" />

<img width="947" height="797" alt="image" src="https://github.com/user-attachments/assets/01dabb9b-27c8-4a6b-8c44-606aa4745fea" />

Execução do teste (10 entrevistados)
<img width="553" height="802" alt="image" src="https://github.com/user-attachments/assets/f29b697f-d50c-4613-843a-31407cafd760" />

<img width="542" height="801" alt="image" src="https://github.com/user-attachments/assets/201614f8-d77d-4d29-a64a-f31d2fff4568" />
