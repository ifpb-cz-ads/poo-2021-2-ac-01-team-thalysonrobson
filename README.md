1. Explique qual a função da Máquina Virtual Java (JVM).

A JVM é uma máquina virtual que simula a aplicação em uma máquina real. Isso ocorre porque todo código java é compilado para um formato intermediário, o bytecode, dessa forma não precisamos nos preocupar com a portabilidade do código, visto que após instalada a JVM o código será executado sem nenhum envolvimento com o sistema operacional.

2. Qual a diferença entre JRE e JDK?

A diferença entre os dois é que o JRE é o ambiente de execução do código Java, incluindo a JVM e bibliotecas. Já o JDK é voltado para os desenvolvedores e conta com várias ferramentas úteis para eles.

3. Crie um programa Java que imprima o seguinte texto “Terminei a primeira aula com um programa Java!”.

Arquivo do código enviado pelo GitHub.

4. Compile o programa desenvolvido no exercício anterior. A seguir apague 
o arquivo .class gerado e tente executar o programa. O que aconteceu?

Após deletar o arquivo “.class” não é mais possível executar o programa.

5. Mude o nome do método “main” para “start”, compile e execute. O que 
aconteceu? 

Terminal: Não foi possível executar, pois o programa não encontrou o método main (string[]).

Bluej: Ao executar o arquivo com o método main ele abre normalmente, já, ao relizar a mundança de nome do 'main' para 'start' o programa não executa automaticamente e apresenta um erro de parâmetro vazio, de forma que passa a ser necessário a atribuição manual das '{ }' para que o arquivo seja aberto.

6. Crie um programa Java para imprimir duas linhas de texto usando duas 
linhas de código “System.out”, onde aparecerá o seu nome na primeira 
linha e na segunda linha aparecerá o time para o qual você torce.

Criei o programa conforme pedido e funcionou perfeitamente, o meu nome apareceu na primeira linha e na segunda apareceu o nome do meu time.

7. Experimente escrever todo o programa anterior em maiúsculo, compile e 
execute. O que aconteceu?

Ao transformar todo o texto do programa em maiúsculo, tentei compilar mas não funcionou e apresentou class, interface, or enum expected.

8. Experimente salvar o arquivo com um nome diferente do nome da classe, 
compile e execute. O que aconteceu?

Ao diferenciar o nome do arquivo para o nome da class, não foi possível compilar o programa e é apresentado uma mensagem informando que a classe possui erros.