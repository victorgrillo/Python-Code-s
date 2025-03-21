# Python-Code-s

Códigos de estudos que escrevi como iniciante na linguagem Python.

nota1 = float(input("Digite a N1: "))
nota2 = float(input("Digite a N2: "))
nota3 = float(input("Digite a N3: "))
nota4 = float(input("Digite a N4: "))

soma = nota1 + nota2 + nota3 + nota4
media = soma / 4

if media >= 7:
    result = "Aprovado"
else:
    result = "Reprovado"


print(f"A média do aluno foi de: {media:.2f}")
print("Resultado: ", result)
