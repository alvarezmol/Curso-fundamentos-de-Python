# Juego de Piedra, Papel o Tijera

print("Bienvenido al Juego Piedra-Papel-Tijera")
print("El que gane 3 es el ganador absoluto")

import random

victorias = 0
derrotas = 0

while victorias < 3 and derrotas < 3 :

  opciones=( ["piedra", "papel", "tijera"])
  maquina = (random.choice(opciones))
  tu_eleccion = (input("Elige piedra, papel o tijera: ")).lower()

  print("la maquina escogió: " + maquina)

  if tu_eleccion == "piedra" and maquina == "papel":
    print("la maquina gana, lo siento :( ")
    derrotas += 1
  elif tu_eleccion == "piedra" and maquina == "piedra":
    print("empate! ")
  elif tu_eleccion == "piedra" and maquina == "tijera":
    print("tu ganas !")
    victorias += 1
  else:
    if tu_eleccion == "papel" and maquina == "tijera":
      print("la maquina gana, lo siento :( ")
      derrotas += 1
    elif tu_eleccion == "papel" and maquina == "papel":
      print("empate! ")
    elif tu_eleccion == "papel" and maquina == "piedra":
      print("tu ganas !")
      victorias += 1
    else:
      if tu_eleccion == "tijera" and maquina == "piedra":
        print("la maquina gana, lo siento :( ")
        derrotas += 1
      elif tu_eleccion == "tijera" and maquina == "tijera":
        print("empate! ")
      elif tu_eleccion == "tijera" and maquina == "papel":
        print("tu ganas !")
        victorias += 1
      else:
        print("Resultado no esperado! escogiste: " + tu_eleccion + " elige un opcion valida")


print("*************")
print("MARCADOR FINAL")
print("Maquina: " + str(derrotas) + " " + "Usuario: " + str(victorias))
if derrotas > victorias:
   print("Ganador....")
   print("Maquina :(")
else:
   print("Ganador....")
   print("Tú!!!")
print("*************")
