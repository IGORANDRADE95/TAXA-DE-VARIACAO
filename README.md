# TAXA-DE-VARIACAO
Programa calcula o tempo que um número alcança outro de acordo com a taxa de variação

A = int(input("Digite a população da cidade A: "))
B = int(input("Digite a população da cidade B: "))
n = 0
cresA = 0.03
cresB = 0.015

while (A < B):
  n += 1
  A = A+(A*cresA)
  B = B+(B*cresB)
  print("Após %i anos o país A ultrapassou o país B em número de habitantes." % n)
