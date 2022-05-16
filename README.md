#1. Conversor de medidas
#metros = float(input("Digite uma medida em metros para converter para centímetros: "))
#cm = (metros*100)

#print(metros,"é igual a ",cm, "cm", "em centímetros")

#2. Calculo de área do circulo
#"""A = Pi * R**2"""

#Raio = float(input("Indique o RAIO do círculo: "))
#Area = (3.14 * Raio**2)

#print("O valor aproximado da área desse círculo é:", Area)

#3. Area do circulo (hard)
import math

#Raio = float(input("Indique o RAIO do círculo: "))
#Area = (math.pi * Raio**2)

#print("O valor da área desse círculo é:", Area)


#4. Conversor de temperatura

#TempF = float(input("Indique a temperatura em Farenheit: "))
#TempC = 5 * ((TempF-32)/9)

#print("A temperatura em graus Celsius é: ", TempC, "º")

#5. Conversor de temperatura Cº para Fº
#TempC = float(input("Indique a temperatura em Celsius: "))
#TempF = (TempC*1.8) + 32


#print("A temperatura em graus Farenheit é: ", TempF, "º")

#6. Imprima um numero em tela

#n1 = float(input("Digite um número para obter ele em tela: "))

#print(n1)

#7. Crie uma variavel com um numero inteiro e imprima

#n1 = int(input("Digite um numero inteiro: "))

#print(n1)

#8. Peça um numero e imprima ele em tela

#n1 = float(input("Digite um número para obter ele em tela: "))

#print(n1)

#9. Peça 2 numeros e imprima a soma

#n1 = float(input("Digite um numero: "))
#n2 = float(input("Digite outro numero para obter a soma: "))
#soma = n1 + n2

#print("A soma dos dois numeros é: ", soma, sep="")

#10. Peça 4 notas e calcule a média e depois imprima a media
#n1 = float(input("Digite a nota 1: "))
#n2 = float(input("Digite a nota 2: "))
#n3 = float(input("Digite a nota 3: "))
#n4 = float(input("Digite a nota 4 para obter a média: "))
#media = ((n1+n2+n3+n4)/4)

#print(media)

#if media >= 7:
  #  print("Aprovado!")
#elif media > 5 < 7:
  #  print("Recuperação!")
#else:
 #   print("Reprovado!")

#11. Faça um programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00. Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total.
#"""1 Litro de tinta para 3m² / 1 Lata tem 18 Litros / 18 litros custa R$ 80,00"""

#"""Imprimir custo total de pintura"""

#Area = float(input("Qual o tamanho da area a ser pintada em m²: "))
#Tinta = float((Area/3))
#Lata = float(Tinta/18)
#Custo = Lata * 80

#print(Tinta)
#print(Lata)
#print("Para pintar a área vai custar: R$",Custo)

#12.Peça ao usuário uma velocidade em Km/h (Quilômetro por hora) e converta para M/s (Metros por segundo).
#"""K = M * 3.6 -> M = K/3.6"""
#Vel = float(input("Digite a velocidade em km/h para converter para m/s: "))
#K2M = Vel/3.6

#print("A velocidade em m/s é: ", K2M, end="m/s")

#13. Altere o acima para converter de m/s para km/h
#"""K = M * 3.6 -> M = K/3.6"""
#Vel = float(input("Digite a velocidade em m/s para converter para km/h: "))
#K2M = Vel*3.6

#print("A velocidade em km/h é: ", K2M, end="km/h")

#14. A soma de 3 números
#n1 = float(input("Digite um número: "))
#n2 = float(input("Digite outro número: "))
#n3 = float(input("Digite mais um número: "))

#soma = n1+n2+n3

#print("A soma dos 3 números digitados é: ", soma)

#15.Um funcionário recebeu um aumento de 25% no seu salário. Peça o salário atual e mostre em tela o salário com o aumento.

#Salario = float(input("Qual o valor em R$ do salário: "))
#Aumento = float(Salario*1.25)

#print("O valor do salário com aumento de 25% é igual a: R$", Aumento)

#16. Um prêmio da loteria de R$ 540.000,00 será dividido entre três pessoas. Informe o valor recebido por cada pessoa.

#Ganho = float(540000/3)

#print("O valor do prêmio divido entre os 3 ganhadores é: R$", Ganho)

#17. (HARD) O prêmio acima foi entregue à três ganhadores de um concurso.
#O primeiro receberá: 47%
#O segundo receberá: 31%
#O terceiro receberá o restante
#Calcule e mostre em tela o valor recebido por cada ganhador.

#print("Em um concurso valendo R$ 540.000.00, tiveram 3 ganhadores, abaixo o valor em Reais que cada um recebeu:")
#Premio = 540000
#n1 = float(540000 * 0.47)
#n2 = float(540000 * 0.31)
#n3 = float(540000 * 0.22)

#print("O primeiro colocado receberá R$",n1, sep="")
#print("O segundo colocado receberá R$",n2, sep="")
#print("O terceiro colocado receberá R$",n3, sep="")

#18. (HARD) Faça um Programa que peça 2 números inteiros e um número real. Calcule e mostre:

# 1) o produto do dobro do primeiro com metade do segundo.
#   2) a soma do triplo do primeiro com o terceiro.
#  3) o terceiro elevado ao cubo.

#n1 = int(input("Digite um número inteiro: "))
#n2 = int(input("Digite outro número inteiro: "))
#n3 = float(input("Agora digite um número real: "))

#Q1 = float((n1*2)*(n2/2))
#Q2 = float((n1*3)+n3)
#Q3 = float(n3**3)

#print("O produto do dobro do primeiro com metade do segundo é: ", Q1)
#print("A soma do triplo do primeiro com o terceiro é: ",Q2)
#print("O terceiro elevado ao cubo é",Q3)

#19. Peça três valores (um int, um float, uma string) ao usuário e ao final, mostre em tela o valor e o TIPO de cada um.

#INT = int(input("Digite um número inteiro: "))
#FLOAT = float(input("Digite um número real: "))
#STR = str(input("Digite seu nome: "))

#print(INT)
#print(type(INT))
#print(FLOAT)
#print(type(FLOAT))
#print(STR)
#print(type(STR))

#20. Mostre em tela o valor da divisão de um número inteiro digitado pelo usuário por dois. OBS: A operação é por módulo: número MÓDULO 2.

#n1 = int(input("Digite um número inteiro: "))
#Valor = (n1 % 2)

#print(Valor)
