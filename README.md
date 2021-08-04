# Convertidor-de-metros-en-cent-metros-pulgadas-yardas-y-pie
a = float(input("Inserte medida en metros: "))
centimetro = 100*a
pulgada = centimetro/2.54*a
pie = pulgada/12*a
yarda = pie/3*a

print ("En centimetro: ",round(centimetro,2))
print ("En pulgadas: ",round(pulgada,2))
print ("En pie: ",round(pie,2))
print ("En yarda: ",round(yarda,2))

print (f"En centimetro: {centimetro:20.5f}")
print (f"En pulgadas  : {pulgada:20.5f}")
print (f"En pie       : {pie:20.5f}")
print (f"En yarda     : {yarda:20.5f}")
