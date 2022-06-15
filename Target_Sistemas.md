1)

Usei somente lógica mesmo. n+1 (partindo de 0) somando no final.

0->1

1->2

2->3

3->4

4->5

5->6

6->7

7->8

8->9

9->10

10->11

11->12

12->13

**=91**



**2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência. **

**IMPORTANTE: Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;** (Java)

public class Fibonacci {

​		static long fibo (int n) {

​				if (n<2) {

​						return n; 

​					} else {

​						return fibo (n-1) + fibo (n-2);

​					}

​		}

​		public static void main(String [] args) {

​		for (int i = 0; i<30; i++) {

​				System.out.print("("+i+"")" + Fibonacci.fibo(i) + "\t");

​				}

​		}

}





**3Dado um vetor que guarda o valor de faturamento diário de uma distribuidora, faça um programa, na linguagem que desejar, que calcule e retorne: • O menor valor de faturamento ocorrido em um dia do mês; • O maior valor de faturamento ocorrido em um dia do mês; • Número de dias no mês em que o valor de faturamento diário foi superior à média mensal. **

**IMPORTANTE: a) Usar o json ou xml disponível como fonte dos dados do faturamento mensal; b) Podem existir dias sem faturamento, como nos finais de semana e feriados. Estes dias devem ser ignorados no cálculo da média;** 

 Não tive conhecimento pra fazer.



**4) Dado o valor de faturamento mensal de uma distribuidora, detalhado por estado: SP – R$67.836,43 RJ – R$36.678,66 MG – R$29.229,88 ES – R$27.165,48 Outros – R$19.849,53 Escreva um programa na linguagem que desejar onde calcule o percentual de representação que cada estado teve dentro do valor total mensal da distribuidora.** (python)

sp = float(67.83643)

​	rj = float(36.67866)

​		mg = float(29.22988)

​			es = float(27.16549)

​				out = float(19.84953)

​					total = float (sp + rj + mg + es + out)

print (total)

psp = ((sp/total)*100)

​	prj = (rj/total)*100)

​		pmg = ((mg/total)*100)

​			pes = ((es/total)*100)

​				pout = ((out/total)*100)



print ('Porcentagem de sp {}' .format (psp))

print ('Porcentagem de rj {}' .format (prj))

print ('Porcentagem de mg {}' .format (pmg))

print ('Porcentagem de es {}' .format (pes))

print ('Porcentagem de out {}' .format (pout))



 **5) Escreva um programa que inverta os caracteres de um string. IMPORTANTE: a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código; b) Evite usar funções prontas, como, por exemplo, reverse;** (python)

int main () {

​		char str [] = "Fabio";

​		char temp;

​		int i; j;

​	assert (strcmp("Caspirro", str) == 0);

​	return (0);

}