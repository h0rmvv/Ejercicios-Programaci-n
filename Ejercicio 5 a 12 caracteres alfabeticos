def ingresar_nombre():
    while True:
        nombre = input("Por favor, ingresa tu nombre (debe tener entre 5 y 12 caracteres alfabéticos): ")
        if nombre.isalpha() and 5 <= len(nombre) <= 12:
            return nombre
        else:
            print("El nombre ingresado no cumple con los requisitos. Por favor, intenta de nuevo.")

nombre_usuario = ingresar_nombre()
print("¡Bienvenido,", nombre_usuario + "!")
