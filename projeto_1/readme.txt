Readme - Calculadora de Áreas Geométricas
Este é um programa em pseudocódigo que permite calcular a área de três formas geométricas: círculo, triângulo e retângulo. Cada forma geométrica é representada por uma classe correspondente, e o programa principal permite ao usuário escolher qual forma deseja calcular a área.

Classes
Classe Circulo
Atributo raio: Armazena o valor do raio do círculo.
Função CalcularArea(): Calcula a área do círculo e a imprime na tela. Verifica se o raio é um valor positivo antes de calcular a área.

Classe Triangulo
Atributos base e altura: Armazenam os valores da base e altura do triângulo, respectivamente.
Função CalcularArea(): Calcula a área do triângulo e a imprime na tela. Verifica se a base e a altura são valores positivos antes de calcular a área.

Classe Retangulo
Atributos largura e altura: Armazenam os valores da largura e altura do retângulo, respectivamente.
Função CalcularArea(): Calcula a área do retângulo e a imprime na tela. Verifica se a largura e a altura são valores positivos antes de calcular a área.

Função Principal
A função principal começa imprimindo um menu para o usuário, onde ele pode escolher a forma geométrica que deseja calcular.
O usuário seleciona uma das opções digitando o número correspondente.

O programa então solicita os valores necessários para realizar o cálculo da área da forma escolhida.
Com base na opção escolhida, o programa cria uma instância da classe correspondente (Círculo, Triângulo ou Retângulo) e atribui os valores necessários aos atributos.
Finalmente, chama a função CalcularArea() da classe correspondente para calcular e exibir a área da forma escolhida.