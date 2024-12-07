# EXAMEN-POO
-Projecto Buscaminas
-Juego de Buscaminas en Consola

-----Descripción del Proyecto-----
Este proyecto es una implementación en consola del popular juego Buscaminas, desarrollado como parte del examen final de la asignatura de Programación Orientada a Objetos (POO). El juego permite aplicar conceptos clave como clases, herencia, encapsulación, polimorfismo, manejo de excepciones, persistencia de datos y diseño basado en el patrón MVC.
El objetivo del juego es descubrir todas las casillas que no contienen minas en un tablero de 10x10, evitando seleccionar aquellas que las contienen.

-----Características------
-  Tablero de Juego: Tablero dinámico de 10x10 con 10 minas distribuidas aleatoriamente.
-  Cálculo de Vecinos: Indica el número de minas en casillas adyacentes.
-  Interacción con el Usuario: Permite descubrir casillas, marcar minas y verificar el estado del juego.
-  Condiciones de Victoria/Derrota:
-  Victoria: Descubrir todas las casillas seguras.
-  Derrota: Seleccionar una casilla que contenga una mina.
-  Manejo de Excepciones: Control de entradas inválidas y errores comunes.
-  Persistencia de Datos: Guardado y carga del estado del juego.
-  Diseño Modular: Implementación basada en el patrón MVC.
  
----Requisitos Previos-----
1. Java: Instalar Java 11 o superior en el sistema.
2. Eclipse IDE (o cualquier otro IDE compatible con Java).
3. Git: Tener instalado Git para la gestión del repositorio.
   
---Instrucciones de Instalación-----
   Clonar el Repositorio
Código
git clone https://github.com/<usuario>/BuscaminasConsola.git
cd BuscaminasConsola

Importar el Proyecto a Eclipse

1- Abre Eclipse.
--Selecciona File > Import > Existing Projects into Workspace.
--Navega hasta la carpeta del repositorio y haz clic en Finish.
--Compilar y Ejecutar

2- En Eclipse, haz clic derecho sobre la clase Main y selecciona Run As > Java Application.

------Instrucciones de Uso------
Al iniciar el juego, se mostrará un tablero vacío con casillas numeradas y etiquetadas por filas y columnas.
Opciones de Jugador:
Descubrir Casilla: Introducir coordenadas (ejemplo: A5) para descubrir una casilla.
Marcar Mina: Introducir coordenadas y elegir la opción para marcar una mina.
Guardar Juego: Opción para guardar el estado actual del juego.
Cargar Juego: Recuperar un estado de juego previamente guardado.
El tablero se actualizará después de cada acción mostrando las casillas descubiertas y marcadas.
El juego termina automáticamente al cumplir una de las siguientes condiciones:
Descubrir una mina (derrota).
Descubrir todas las casillas seguras (victoria).


-----Ejemplo de Ejecución------

Copiar código
  1  2  3  4  5  6  7  8  9  10
A                        
B                        
C                        
D                        
E                        
F                        
G                        
H                        

Introduce una coordenada (ejemplo: A5): B3
¡Casilla descubierta! No hay minas alrededor.

  1  2  3  4  5  6  7  8  9  10
A                        
B      0                    
C                        
D                        
E                        
F                        
G                        
H 


-----Estructura del Proyecto-----
Modelo: Clases para la lógica del juego (Tablero, Casilla, Jugador).
Vista: Interacción con el usuario mediante la consola.
Controlador: Gestión de la lógica entre el modelo y la vista.

-----Pruebas Unitarias-----
El proyecto incluye pruebas unitarias utilizando JUnit. Para ejecutarlas:
Haz clic derecho en el paquete Test dentro de Eclipse.
Selecciona Run As > JUnit Test.


------Repositorio GitHub------
El repositorio se encuentra disponible en GitHub: Buscaminas.


