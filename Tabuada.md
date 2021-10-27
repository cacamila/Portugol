programa
{
	
	funcao inicio()
	{
		//Variáveis
		inteiro contador = 0
		inteiro limite = 10
		inteiro resultado
		inteiro tabuada
		
		//Entrada
		escreva("Insira o numero de qual tabuada você quer resolver?")
		leia (tabuada)
		
		//Estrutura de decisão
		faca{
			resultado = tabuada * contador
			escreva(tabuada + " X " + contador + " = " + resultado + "\n")
			contador ++
			
		}enquanto (contador <= limite)
		
	}
}
