import random

Lista = ["Pedra", "Papel", "Tesoura"]

Usuário = input("Usuário escolhe: ")

Computador = random.choice(Lista)
a = ("Computador escolhe: ")
b = (Computador)
c = a + b
print(c)

if Usuário == Computador:
  print("Empate")

elif Usuário == Lista[0] and Computador == Lista[1]:
  print("Computador ganha")

elif Usuário == Lista[0] and Computador == Lista[2]:
  print("Usuário ganha")

elif Usuário == Lista[1] and Computador == Lista[0]:
  print("Usuário ganha")

elif Usuário == Lista[1] and Computador == Lista[2]:
  print("Computador ganha")

elif Usuário == Lista[2] and Computador == Lista[0]:
  print("Computador ganha")

elif Usuário == Lista[2] and Computador == Lista[1]:
  print("Usuário ganha")

else:
  print("Escolha inválida")
