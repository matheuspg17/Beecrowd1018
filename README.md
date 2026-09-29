## Resolução exercicio Beecrowd1018

## Descrição do problema
Leia um valor inteiro. A seguir, calcule o menor número de notas possíveis (cédulas) no qual o valor pode ser decomposto. As notas consideradas são de 100, 50, 20, 10, 5, 2 e 1. A seguir mostre o valor lido e a relação de notas necessárias.

## Como Funciona
1. O usuário insere um valor inteiro, armazenado na variável `valor`.
2. O programa imprime imediatamente o valor lido na primeira linha da saída.
3. O código utiliza divisões inteiras sucessivas combinadas com o operador de resto (`%`) para extrair a quantidade exata de cada cédula em ordem decrescente, atualizando o saldo restante.
4. Por fim, o programa exibe o número de notas necessárias para cada valor de cédula mapeado.
