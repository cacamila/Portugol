programa
{
	
	funcao inicio()
	{
		escreva("Selecione sua Stream: 1- Netflix 2- Amazon Prime 3- HBO GO 4- Sair") 
		inteiro valor = 0
		leia(valor)

		escolha (valor)
		{
			caso 1:
			escreva ("Abrir Netflix")
			pare

			caso 2:
			escreva ("Abrir Amazon Prime")
			pare

			caso 3:
			escreva ("Abrir HBO GO")
			pare

			caso 4:
			escreva ("Sair")
			pare

			caso contrario:
			escreva("Escolha apenas as opições existentes , 1,2,3 e 4")
		}
		
		
	}
}
