# JogoDaForca
Programa em c desenvolvido como forma de avaliação da disciplina de Programação de Computadores do segundo semestre de CC

<b> DESENVOLVIDO POR: </b>
<br>
    BIANCA BEPPLER DULLIUS, CAROLINE SOUZA CAMARGO, MARIA JULIA DUARTE LORENZONI E YASMIN SOUZA CAMARGO

## Como Executar
-> Para executar o código não esquecer de compilar pelo terminal: 
    
    gcc main.c ./bibliotecas/boneco_forca.c ./bibliotecas/jogo.c -o main
    
##  Layout do projeto
![image](https://user-images.githubusercontent.com/88253809/173165803-f5d7b8b8-3c55-4b6a-a594-e0bc7b8ebddd.png)

## Observações Arquivo Palavras:
O aquivo arq_palavras.txt deve possuir a seguinte estrutura: 
- Deve conter apenas letras minúsculas
- As palavras não deverão ser acentuadas 
- Cada linha deve conter a palavra que irá no jogo da forca e a sua respectiva dica
- A palavra e a dica devem ser separadas por um ";" (ponto e virgula)
- No final de cada linha deve existir um ";" (ponto e virgula)
- Exemplo de preenchimento: <br>
    castanho avermelhado;cor; <br>
    liquidificador;objeto;

## Observações Arquivo Histórico:
O aquivo historico.txt deve possuir a seguinte estrutura: 
- As palavras não deverão ser acentuadas 
- Cada linha deve conter a quantidade de jogadas, a palavra do jogo da forca e o modo escolhido (contra o computador ou contra uma pessoa)
- Cada informação deve ser separada por um ";" (ponto e virgula)
- No final de cada linha deve existir um ";" (ponto e virgula)
- Exemplo de preenchimento: <br> 
    6;mosquito;Modo contra o computador; <br>
    2;nutricionista;Modo contra o computador;

## Caracteríscas
- Utilização de bibliotecas próprias
- Manipulação de Arquivos
- Listas encadeadas

