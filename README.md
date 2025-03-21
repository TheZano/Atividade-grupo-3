# Atividade-grupo-3
atividades do terceiro grupo de apresentações SENAI

atividade 1 
programa {
  funcao inicio() {
    mensagemboasvindas()

  }

  funcao mensagemboasvindas(){

    escreva("\n\t---------------------------------------\n")
    escreva("\tOlá. seja bem vindos ao nosso sistema!")
    escreva("\n\t---------------------------------------\n")
    
  }
}


atividade 2

programa {
  funcao inicio() {
    inteiro n1, resultado
    escreva("Digite um número ")
    leia(n1)

    resultado = (n1*2)

    escreva("O Dobro desse número é igual a: ", resultado)
    
  }
}

atividade 3

programa {
    funcao inicio() {
        inteiro numero

        escreva("Digite um número: ")
        leia(numero)

        se (numero > 0) 
            escreva("O número é positivo.\n")
        senao se (numero < 0) 
            escreva("O número é negativo.\n")
        senao
            escreva("O número é zero.\n")
        
    }
}

atividade 4

programa {
    funcao inicio() {
        real numero1, numero2, numero3, media

        escreva("Digite o primeiro número real: ")
        leia(numero1)

        escreva("Digite o segundo número real: ")
        leia(numero2)

        escreva("Digite o terceiro número real: ")
        leia(numero3)

        media = calcular_media(numero1, numero2, numero3)

        escreva("A média dos números é: ", media, "\n")
    }

    funcao real calcular_media(real n1, real n2, real n3) {
        real media

        media = (n1 + n2 + n3) / 3

        retorne media
    }
}

atividade 5

programa {
  funcao inicio() {
    inteiro i, y
    escreva("Digite um número: ")
    leia(y)
    para(i=1; i<=10; i++){
      
      escreva(y,"X",i,"=",y*i, "\n")
    }
    
  }
}
