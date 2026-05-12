# CLASE-5-CULTURA-DIGITAL-
#"3_A Clase 5 Cultura Digital Natasha Codigo

# IMC Paciente codigo
  peso = float(input("Peso (kg): "))
  altura = float(input("Altura (m): "))
  imc = peso / (altura ** 2)
  print(f"IMC: {imc:.2f} - {'Normal' if 18.5 <= imc < 25 else 'Revisar'}")
