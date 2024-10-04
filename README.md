# daniel_arguijo-torres-_3W
practica 12


def main():
    numeros_triunfadores = []

    while True:
        entrada = input("Ingresa un número triunfador de la lotería (o escribe 'salir' para terminar): ")

        if entrada.lower() == 'salir':
            break

        try:
            numero = int(entrada)
            numeros_triunfadores.append(numero)
        except ValueError:
            print("Por favor, ingresa un número válido.")

    # Ordenar la lista de menor a mayor
    numeros_triunfadores.sort()

    print("Números triunfadores ordenados de menor a mayor:")
    for numero in numeros_triunfadores:
        print(numero)

if __name__ == "__main__":
    main() 

![image](https://github.com/user-attachments/assets/0d4cc188-d9d1-4b19-88ce-0d324e839c50) 


![image](https://github.com/user-attachments/assets/cc0aeffe-d30c-412d-a744-e2f2600e0dc9)

