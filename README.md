# D2--Menu-de-opciones

# Python
    def mostrarMenu():

        print("Menu")
    
        print("ingresar datos")
    
        print("mostrar datos")
    
        print("salir")
    
        opcion = int(input("ingrese una opcion: "))
        return opcion

    def principal():
        comida = []
        opcion = 0
    
        while opcion != 3:
            opcion = mostrarMenu()
        
            if opcion == 1:
                datos = input("ingrese alimento: ")
                comida.append(datos)
                print("puesto en lista")
            
            elif opcion == 2:
                print("inventario: ")
            
                 for i in comida:
                    print(f"alimento registrado: {i}")





# Java
    import java.util.Scanner; 

    public class MenuPrincipal {
    public static void main(String[] args) {
      
    int opcionSeleccionada = mostrarMenu();
    System.out.println("Elegiste la opción: " + opcionSeleccionada);
    }

    public static int mostrarMenu() {
    Scanner leer = new Scanner(System.in);
    int opcion;

        System.out.println("===== MENÚ =====");
        System.out.println("1. Ingresar datos");
        System.out.println("2. Mostrar datos");
        System.out.println("3. Salir");
        System.out.print("Seleccione una opción: ");
        
    opcion = leer.nextInt();
    return opcion;
    }
}
            
   elif opcion == 3:
   print("cerrando programa")

   principal()
