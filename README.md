# Carregador desenvolvido no Proteus

## Esquemática

![esquematica](/imagens/Esquematica.png)

## Layout do PCB

![pbc](/imagens/LayoutPCB.png)

## Visualização 3D

![3Dsuperior](/imagens/VisaoSuperior3D.jpeg)
![3Dinferior](/imagens/VisaoInferior3D.jpeg)

## Explicação 

### A Energia Inicial:

    A eletricidade chega da tomada como corrente alternada, com 127V, oscilando constantemente entre picos e vales. O objetivo do projeto é fazer com que essa onda se torne uma linha contínua e estável.

### A Ponte (Bridge):
    Funciona como um redirecionador, ela pega a parte da onda que é negativa e a inverte para positiva, fazendo com que toda a energia flua no mesmo sentido.

### Os Capacitores: 
    Atuam como filtros ou reservatórios, estes armazenam energia nos picos e a liberam nos vales, suavizando as subidas e descidas da onda para que o regulador receba uma tensão menos instável.

### O Regulador de Tensão: 
    É o componente de precisão, recebe a onda já suavizada e a plaina quase que totalmente, travando a saída em 12V constantes e prontos para uso.

### O Resistor: 
    Funciona como um limitador de segurança, ele controla o fluxo da corrente para que o LED receba apenas o necessário, evitando que o excesso de energia queime o componente.
