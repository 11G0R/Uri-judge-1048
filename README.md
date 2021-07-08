A = float(input(""))
#id dos salarios
if A <= 400:
  soma = (A * 0.15)
  print(f"Novo salario: {A + soma:.2f}")
  print(f"Reajuste ganho: {soma:.2f}")
  print("Em percentual: 15 %")
elif A <= 800:
  soma = (A * 0.12)
  print(f"Novo salario: {A + soma:.2f}")
  print(f"Reajuste ganho: {soma:.2f}")
  print("Em percentual: 12 %")
elif A <= 1200:
  soma = (A * 0.10)
  print(f"Novo salario: {A + soma:.2f}")
  print(f"Reajuste ganho: {soma:.2f}")
  print("Em percentual: 10 %")
elif A <= 2000:
  soma = (A * 0.7)
  print(f"Novo salario: {A + soma:.2f}")
  print(f"Reajuste ganho: {soma:.2f}")
  print("Em percentual: 7 %")
else:
  soma = (A * 0.4)
  print(f"Novo salario: {A + soma:.2f}")
  print(f"Reajuste ganho: {soma:.2f}")
  print("Em percentual: 4 %")
