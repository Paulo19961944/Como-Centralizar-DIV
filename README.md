# Como centralizar uma DIV (Sem ChatGPT)

Esse é o terror de muitos programadores, tem até aquela piada básica de que não centralizar uma div, me ajude.
Calma, estou aqui para te ajudar. Vou colocar algumas dicas e explico o código para vocês.

    1. Entenda o que está fazendo e o que faz cada propriedade.
    Primeiro de tudo temos que entender o que faz cada coisa, e vou explicar para vocês
        1.1: Flexbox
        É muito comum nós usarmos o flexbox para centralizar elementos, segue alguns itens do flexbox
        - display:flex; -> É o flexbox em si, o que nos possibilita o mundo aberto entre nós programadores
        - flex-direction:row /column; -> Define a direção do elemento, se está em linha (row) ou se está em colunas (column)
        - justify-content:center; -> Alinha o Eixo Principal
        - align-items:center; -> Alinha o Eixo Perpendicular

        1.2: Eixo Principal
        O Eixo Principal é aquele que está a direção do flex, por padrão, o flexbox já vem com o alinhamento em linhas,
        neste caso o Eixo Principal é o Horizontal, pois ele vai seguir o exemplo da linha.
        
        Caso seja em coluna, o Eixo Principal muda, sendo o alinhamento na vertical, que é o sentido da coluna.

        1.3: Eixo Perpendicular
        O Eixo Perpendicular é o eixo oposto ao Flexbox, como por padrão é linha, caso não altere ele irá alinhar na Vertical.
        Caso esteja em coluna, ele muda para o lado oposto do Flexbox, como o Eixo Principal segue o principio da coluna,
        então ele irá alinhar na Horizontal.
    
    2. Esse método é antigo, quando não tinhamos o Flexbox, mas irei mostrar mesmo assim, pois algum código que farão manutenção pode vir desse jeito.

        2.1: Position Absolute
            2.1.1: O position absolute é uma forma de posicionar elementos em relação ao elemento pai.
            Quando não usamos é o nosso próprio body em si, mas se estiver dentro de uma div pai, então irá ser em relação a esta div.
            2.1.2: Utilizamos o (top:50%;) para posicionar em 50% em relação ao topo do elemento pai
            2.1.3: Utilizamos o (left:50%;) para posicionar em 50% a direita do elemento pai
            2.1.4: Utilizamos o (transform:translate(-50%, -50%);) para corrigir  os erros de posição que podem acontecer.
            Pois o ele está mudando o posicionamento em relação ao pai e não ao elemento em si.
            2.1.5: Deste jeito nós alinhamos verticalmente e horizontalmente o nosso elemento, deixando ele no centro da tela.

        OBS: Espero que isso tenha esclarecido a dúvida de centralizar uma div, então estudem bastante, pois a melhor forma de aprendiazado é a prática

        Meu muito obrigado e meu fraternal abraço a todos os devs.
        Att: Paulo Henrique Azevedo do Nascimento.

# Observação
Caso deseje é só copiar e colar o script para server de apoio a vocês, um fraternal abraço a todos os Devs.
