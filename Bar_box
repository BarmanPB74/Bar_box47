#!/usr/bin/env python3

if __name__ == "__main__":
    print("Hello from Python")
def iniciar_bar_box():
    print("Iniciando bar box...")
    fecha_hoy = input("ingrese la fecha del inventario (dd/mm/aaaa): ")

    inventario = {}

    print("Ingrese los productos a continuacion y presione enter para finalizar: ")
    print("Presione salir para terminar de ingresar productos: ")
    

    print("Ingrese los productos a continuacion y presione enter para finalizar: ")
    while True:
        producto = input("producto: ").lower()
        if producto == "salir":
            break
            try:
            cantidad = float(input(f"cantidad de {producto}: ")).lower()
            except ValueError:
                print("Por favor ingrese un numero valido para la cantidad.")
                continue

                print("\n===================================")
    print(f"📊 REPORTE DE INVENTARIO - {fecha_hoy}")
    print("===================================")
    if not inventario:
        print("El inventario está vacío.")
    else:
        for prod, cant in inventario.items():
            print(f"- {prod.capitalize()}: {cant} unidades")
            
    print("===================================")

# Esto ejecuta la aplicación
if __name__ == "__main__":
    iniciar_bar_box()
    