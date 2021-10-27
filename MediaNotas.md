//Calculo de Media de Notas

programa
 
{
	
	funcao inicio()
	{
		
		//Variáveis
		real nota1, nota2, nota3, nota4, media
		cadeia aluno

		//Entradas
    
		escreva("Digite o nome do aluno:")
		leia (aluno)

		escreva("Digite a nota 1:")
		leia (nota1)
		escreva("Digite a nota 2:")
		leia (nota2)
		escreva("Digite a nota 3:")
		leia (nota3)
		escreva("Digite a nota 4:")
		leia (nota4)

    		//Calculo da Media
		media = (nota1+nota2+nota3+nota4) /4
		escreva ("O aluno: " + aluno + "obteve " + media + " de media")
    
    		//Estrutura de decisão
		se(media>=7){
			escreva("Esta Aprovado!")
		}senao {
			escreva("Esta Reprovado!")
		}
	
	}
	
}

