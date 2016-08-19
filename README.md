# atividade.py
01) 
while True:
    nota= int(input("- Entre com uma nota: "))
    if nota>=0 and nota<=10: break
    print (" A nota deve estar entre 0 e 10...")
    print (" - Você digitou a nota ",nota)

02) nome = input ("informe o nome de usuario:")

    while True: 
 
      senha= input ("informe a sua senha:")
 
      if nome == senha :
 	
      print ("senha invalida" )


03) 
while True:
 nome = input("Entre com o seu nome: ")
 if len(nome)<3:
     print ("Nome Inválido! Deve ser maior que 3 digitos.")
     continue
 break
#Idade: entre 0 e 150
while True:
 idade = int(input("entre com a sua idade: "))
 if idade<0 or idade>150:
         print ("Idade Inválida! Deve estar entre 0 e 150.")
         continue
 break
#Salário: maior que zero
while True:
 salario = float(input("entre com o seu salario: "))
 if salario<0:
        print ("Salário inválido! Deve ser maior que zero.")
        continue
 break
#Sexo: 'f' ou 'm'
while True:
 sexo = input("entre com o seu sexo. (Apenas m ou f): ")
 if sexo!='f' and sexo!='m':
        print ("Sexo inválido! Deve ser apenas 'm' ou 'f'.")
        continue
 break
#Estado Civil: 's', 'c', 'v', 'd'
estados = 'scvd'
while True:
 estadoC = input("-"+nome+" entre como seu estado civil: ")
 if estadoC not in estados:
        print ("Estao Civil! Deve ser 's', 'c', 'v' ou 'd'.")
        continue
break

04)
habA,habB,anos=80000,200000,0
while True:
    habA= habA*1.03
    habB= habB*1.015
    anos+=1
    if habA>=habB: break
print (" Demorou %d anos para a população A alcançar a B."%(anos))
print (" População de A: %d\n- População de B: %d"%(habA,habB))

05)
while True:
    habA=int(input("Entre com o número da população A. "))
    taxA=float(input("Entre com a taxa de crescimento da população A. "))
    habB=int(input("Entre com a taxa de crescimento da população B. "))
    taxB=float(input("Entre com o número da população A. "))
    anos=0
    while True:
        habA*=(1-taxA/100)
        habB*=(1-taxB/100)
        anos+=1
        if habA>=habB: break
    print ("Demorou %d anos para a população A alcançar a B."%(anos))
    print ("População de A: %f\n- População de B: %f"%(habA,habB))
    op=input(" - Deseja continuar? (s) ou (n) : ")
    if op=='s': continue
    break
06)



07)
y = int(input(" - Entre com um número: "))
maior=y
for i in range(4):
    y = int(input(" - Entre com um número: "))
    if maior<y: maior=y
print (" O maior dos números: ",maior)

08)
y = int(input("Entre com um número: "))
som, maior=y, y
for i in range(4):
    y = int(input(" - Entre com um número: "))
    if maior<y: maior=y
    som+=y
print (" O maior dos números: ",maior)
print (" Soma dos números: ",som )
print (" A média : ",float(som/5))

09)
Y= 50
N = 1
while  N < Y :
	print (N)
	N = N + 2
10)
