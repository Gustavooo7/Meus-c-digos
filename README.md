# Meus-codigos
&lt;3
# O que é Python e onde é usado

# O que é Python
Python é uma linguagem de programação de alto nível, criada por Guido van Rossum em 1991.  
Ela é conhecida por ser fácil de aprender, versátil e ter uma sintaxe simples, parecida com o inglês.  
Python é interpretada e pode ser usada de forma estruturada, orientada a objetos ou funcional.

# Onde é usado
Python é uma das linguagens mais populares do mundo e pode ser usada em várias áreas, como:

- Desenvolvimento Web  
- Inteligência Artificial e Dados  
- Automação de Tarefas 
- Jogos e Aplicativos

# Instalação do Python 
Entre no site oficial do Python, procure a versão mais recente que seja compatível com seu sistema e baixe.
Durante a instalação, click na caixinha "Add python to path".
Prontinho.

# Instalando o VsCode
Baixe o Vscode no site oficial deles,  ao abrir o vscode no pc, instale a extensão "Python".
A partir daí, você já pode criar arquivos .py

# varieveis e tipos de dados
Variaveis são usadas para guardar informações na memoria do pc, funcionam como se fossem "caixas" para você guardar algum valor que desejar usar depois.
ex: nome = gustavo
    idade = 21
    altura = 2.00

# Tipos de dados
int -- Números inteiros  ex:10,-5,0
float -- Números deciemais  ex:3.14,-2.43
string -- Textos entre aspas ex: "eu te amo"
bool -- Valores lógicos(verdadeiro ou falso) True, False

Para facilitar, podemos ver qual é o tipo de uma variável usando type()
print(type(nome))  #str
print(type(idade)) # int

#Input e output básico
Output:(sáida de dados)
para exibir alguma coisa na tela, usamos a função "print()"
ex: print("eu te amo")
O "Print()" pode mostar textos, números e variáveis


Input: (receber dados)
Para receber dados, usamos "Input()":
ex: Time_do_coracao = input("Digite seu time do coração: ")
    print(f"Eu sabia que seria o {Time_do)coracao}!")


# Primeiro programa:
Print("I love you").

# *Primeira calculadora de IMC:*

altura = float(input("Digite sua altura: "))
peso = float(input("Digite seu peso: "))
imc = peso / (altura ** 2)
if imc < 18.5:
    print(f"Você está abaixo do peso e seu IMC é {imc:.2f}.")
elif imc >= 18.5 and imc <= 24.9:
    print(f"Seu IMC é: {imc:.2f} e você está com peso normal.")
elif imc >= 25 and imc <= 29.9:
    print(f"Seu IMC é {imc:.2f} e você está sobrepeso.")
elif imc >= 30:
    print(f"Seu IMC é {imc:.2f} e você está obeso.")

# *Programa que recebe um número e verifica:*
#- Se é positivo, negativo ou zero
#- Se é par ou ímpar
#- Se é múltiplo de 3 e/ou 5
#- Se está entre 10 e 50 (inclusive)

# *ver se é positivo, negativo ou zero.*
n = int(input("Digite um número inteiro:"))
if n > 0:
    print(f"{n} é um número positivo.")
elif n < 0:
    print(f"{n} é um número negativo")
else:
    print("Seu número é zero.")

#ver se é par ou impar
if n % 2 == 0:
    print(f"{n} é um número par.")
else:
    print(f"{n} é um número ímpar")

#ver se é multiplo de 3 e/ou 5
if (n % 3 ==0) and (n % 5 ==0):
    print(f"O número {n} é divisivel por 3 e 5. ")
elif (n % 3 ==0) and (n % 5 !=0):
    print(f"O número {n} é divisivel apenas por 3.")
elif (n % 3 !=0) and (n % 5 ==0):
    print(f"O número {n} é divisivel apenas por 5.")
else:
    print(f"O número {n} não é divisivel nem por 3, nem por 5.")

#verificar se está entre 10 e 50
if n >= 10 and n <= 50:
    print(f"O número {n} está entre 10 e 50.")
else:
    print(f"O número não está entre 10 e 50.")

#Programa que:
#1. Pede um número N
#2. Mostra todos os números de 1 até N
#3. Para cada número, diz se é par ou ímpar
#4. No final, mostra:
   #- Quantos pares
   #- Quantos ímpares
   #- Soma total

impar = 0
par = 0
soma = 0
n = int(input("Digite um número: "))
for c in range(1, n+1):
    print(c)
    if c % 2 == 0:
        par = par+1
        print("Par")
        
    
    else:
        impar = impar +1
        print("Impar")

    soma = soma + c
    



    

print(f"Números pares: {par}")
print(f"Números ímpares: {impar}")
print(f"Soma do total dos pares e ímpares: {soma}")


