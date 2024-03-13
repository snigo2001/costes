from cost_of_software_development import calculate_cost

# Definir las variables del proyecto
project_type = "web_application"
project_size = "medium"
team_size = 5
development_time = 6

# Calcular el costo del proyecto
cost = calculate_cost(project_type, project_size, team_size, development_time)

# Imprimir el costo del proyecto
print(f"El costo del proyecto es: {cost}")
