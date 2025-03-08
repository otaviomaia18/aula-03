programa
{
	
	funcao inicio()
	{
		   // Declarar as variáveis
    inteiro numero, i
    
    // Solicitar ao usuário o número
    escreva("Digite um número para ver a sua tabuada de 1 a 10: ")
    leia(numero)
    
    // Mensagem inicial
    escreva("Tabuada do ", numero)
    
    // Exibir a tabuada de 1 a 10 usando a estrutura do PARA com a condição de parada
    para(i = 1; i <= 10; i = i + 1) {
        escreva(numero, " x ", i, " = ", numero * i)
    }
	}
}
