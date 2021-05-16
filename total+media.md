\\ Meu primeiro codigo feito no portugol


programa
{
	
	funcao inicio()
	{
		real mes1,mes2,mes3,mes4,mes5,mes6,total,media
		cadeia funcionario

		escreva("Digite seu nome:")
		leia(funcionario)
		escreva("Bem vindo " + funcionario + "\n" )
		escreva("Digite a venda de janeiro: ")
		leia(mes1)
		escreva("Digite a venda de fevereiro: ")
		leia(mes2)
		escreva("Digite a venda de março: ")
		leia(mes3)
		escreva("Digite a venda de abriu: ")
		leia(mes4)
		escreva("Digite a venda de maio: ")
		leia(mes5)
		escreva("Digite a venda de junho: ")
		leia(mes6)

		total =(mes1+mes2+mes3+mes4+mes5)
		escreva("o total de vendas foi " + total + "\n")

		media=total/5
		escreva("A media de vendas foi: "+media)
		
	}
}
