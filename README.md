# Conversiones-monetarias
def pesos mexicanos (pesos)
  return pesos/17.80
def moneda(pesos_mexicanos)
  if (pesos_mexicanos < 17)
  print ("No puedes recibir dinero, favor de ingresa otra cantidad)
  else:
  print ("Gracias por su compra, favor de retirar el efectivo)
  
d =int(input("Inserta la cantidad de dinero que deseas convertir: "))
print("El valor final es de: ", pesos_mexicanos(d))
moneda(d)
