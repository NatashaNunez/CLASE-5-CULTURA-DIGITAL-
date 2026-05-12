# CLASE-5-CULTURA-DIGITAL-
3_A Clase 5 Cultura Digital Natasha 
# Control de signos vitales

presion = input("Presión arterial: ")
pulso = int(input("Pulso (ppm): "))
temperatura = float(input("Temperatura (°C): "))

print("\n--- Signos Vitales ---")
print(f"Presión: {presion}")

if pulso < 60 or pulso > 100:
    print(f"Pulso: {pulso}  Anormal")
else:
    print(f"Pulso: {pulso}  Normal")
if temperatura > 37.5:
    print(f"Temperatura: {temperatura}°C  Fiebre")
else:
    print(f"Temperatura: {temperatura}°C  Normal")
