alumnos_ciberseguridad = [] 
while True:
    print("\n Menu de alumnos de ciberseguridad ")
    print("1. Ingresar nombres")
    print("2. Actualizar nombres")
    print("3. Eliminar nombres")
    print("4. Mostrar nombres a eleccion")
    print("5. Mostrar todos los nombres")
    print("6. Salir del Menu") 
    opcion = input("seleccionar opcion")

if opcion == "1"
    nombre = input("Ingrese nombre del alumno")
    alumnos_ciberseguridad.append(nombre)
    print("Se agrego al alumno {nombre}.")
    
    elif opcion == "2":
    nombre = input("Ingrese el nombre del alumno que desea actualizar: ")
    if nombre in alumnos_ciberseguridad:
        nuevo_nombre = input("Ingrese el nuevo nombre para {nombre}: ")
        index = alumnos_ciberseguridad.index(nombre)
        alumnos_ciberseguridad[index] = nuevo_nombre
        print("Se ha actualizado el nombre del alumno {nombre} a {nuevo_nombre}.")
    else:
        print("El alumno {nombre} no esta en la lista.")

elif opcion == "3":
    nombre = input("Ingrese el nombre del alumno que desea eliminar: ")
    if nombre in alumnos_ciberseguridad:
        alumnos_ciberseguridad.remove(nombre)
        print("Se ha eliminado al alumno {nombre}.")
    else:
        print("El alumno {nombre} no se encuentra en la lista.")

elif opcion == "4":
    if not alumnos_ciberseguridad:
        print("No hay alumnos registrados.")
    else:
        nombre = input("Ingrese el nombre del alumno que desea mostrar: ")
        if nombre in alumnos_ciberseguridad:
            print("Nombre del alumno: {nombre}")
        else:
            print("l alumno {nombre} no se encuentra en la lista.")
            
