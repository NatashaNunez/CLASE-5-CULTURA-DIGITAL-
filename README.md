# CLASE-5-CULTURA-DIGITAL-
#"3_A Clase 5 Cultura Digital Natasha 
        # Calculadora de IMC 
        nombre = input("Nombre del paciente: ")
        peso = float(input("Peso en kg: "))
        altura = float(input("Altura en metros: "))
        
        imc = peso / (altura ** 2)
        
        print(f"\n--- Resultado para {nombre} ---")
        print(f"IMC: {imc:.2f}")
        
        if imc < 18.5:
            print("Estado: Bajo peso")
        elif imc < 25:
            print("Estado: Peso normal")
        elif imc < 30:
            print("Estado: Sobrepeso")
        else:
            print("Estado: Obesidad")
