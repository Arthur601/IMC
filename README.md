nome = str(input("qual o nome do paciente?:" ))
peso = float(input("qual o peso do paciente?:" ))
altura = float(input("qual a altura do paciente?: "))
IMC = peso / (altura * altura)

if IMC <= 18.5:
    print("Abaixo do Peso")
elif IMC <= 24.9:
    print("Peso Normal")
elif IMC <= 29.9:
    print("Sobrepeso")
elif IMC <= 34.9:
    print("Oesidade Grai I")
elif IMC <= 39.9:
    print("Obesidade Grau II")
else:
     print("Obesidade Grau III")
