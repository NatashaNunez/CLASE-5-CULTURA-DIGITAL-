# CLASE-5-CULTURA-DIGITAL-
#"3_A Clase 5 Cultura Digital Natasha Codigo
# Sistema básico de notas para estudiantes
  print("===== REGISTRO DE CALIFICACIONES =====")
  
  nombre = input("Nombre del estudiante: ")
  
  nota1 = float(input("Ingrese la nota 1: "))
  nota2 = float(input("Ingrese la nota 2: "))
  nota3 = float(input("Ingrese la nota 3: "))
  
  promedio = (nota1 + nota2 + nota3) / 3
  
  print(f"\n--- Resultados de {nombre} ---")
  print(f"Promedio final: {promedio:.2f}")
  
  if promedio >= 9:
      print("Estado: Excelente")
  elif promedio >= 7:
      print("Estado: Aprobado")
  elif promedio >= 5:
      print("Estado: Supletorio")
  else:
      print("Estado: Reprobado")
  
  # Asistencia
  asistencia = int(input("\nIngrese el porcentaje de asistencia: "))
  
  if asistencia >= 75:
      print("Cumple con la asistencia mínima")
  else:
      print("No cumple con la asistencia mínima")
  
  print("\nGracias por usar el sistema.")
