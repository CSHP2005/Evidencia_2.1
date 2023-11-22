# Evidencia_2.1
Elaborar una libreta de Jupyter Notebook que contenga la programación para definir una clase, que contenga atributos, propiedades, métodos, y método constructor. Explicar qué hace la clase, y demostrar su uso.

# Importar librerías necesarias
from IPython.display import display

# Definir la clase Persona
class Persona:
    # Método constructor
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    # Método para obtener la información de la persona
    def obtener_informacion(self):
        return f"Nombre: {self.nombre}, Edad: {self.edad} años"

    # Método para saludar
    def saludar(self):
        return f"Hola, soy {self.nombre}."

# Crear una instancia de la clase Persona
persona1 = Persona("Juan", 25)

# Acceder a los atributos y llamar a métodos
nombre_persona = persona1.nombre
edad_persona = persona1.edad
saludo_persona = persona1.saludar()
informacion_persona = persona1.obtener_informacion()

# Mostrar la información en el Notebook
display(nombre_persona)
display(edad_persona)
display(saludo_persona)
display(informacion_persona)

#Atributos : La clase tiene dos atributos, nombrey edad, que representan el nombre y la edad de una persona.

Método constructor ( __init__) : Este método se llama automáticamente cuando se crea una nueva instancia de la clase. Recibe el nombre y la edad como parámetros y asigna esos valores a los atributos correspondientes.

Métodos obtener_informacionysaludar : Estos son métodos que realizan acciones. obtener_informaciondevuelve una cadena que contiene el nombre y la edad de la persona, mientras que saludardevuelve un saludo personalizado.

Demostración de uso : Se crea una instancia de la clase llamada persona1con el nombre "Juan" y la edad 25. Luego, se accede a los atributos y se llaman a los métodos, mostrando la información en el Notebook.
