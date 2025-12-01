# 🧠 Cuaderno Virtual – Lenguaje de Programación

**Nombre:** Gleny Angélica Condori Mamani  
**Facultad:** Ingeniería Estadística e Informática  
**Universidad:** Universidad Nacional del Altiplano – Puno  
**Curso:** Lenguaje de Programación (Python)  
**Docente:** Leonel  

    **## UNIDAD II ##**

# 🧩 TEMA: Herencia en Programación Orientada a Objetos (P.O.O)

## 📘 Herencia
La **herencia** es un concepto fundamental en la Programación Orientada a Objetos (P.O.O) que permite crear nuevas clases a partir de clases existentes.  
La clase nueva (llamada **clase derivada** o **subclase**) hereda atributos y métodos de la clase original (llamada **clase base** o **superclase**).
👉 Esto facilita:
- La reutilización de código.  
- La organización jerárquica de las clases.  
- La extensión del comportamiento sin necesidad de reescribir código.  

## 🧠 Herencia Simple

En la **herencia simple**, una clase derivada hereda de una única clase base.  
Esto significa que la subclase solo tiene una superclase directa, lo que la convierte en el tipo de herencia más común y sencillo de implementar. 

## 🧠 Herencia Multiple

En la **herencia múltiple**, una clase puede heredar atributos y métodos de varias clases bases al mismo tiempo. Esto permite combinar funcionalidades de diferentes clases en una sola.

<img width="310" height="343" alt="image" src="https://github.com/user-attachments/assets/f79b20d7-a595-404c-84fd-c48b57773302" />



# EJEMPLOS DE CODIGO #

--**CLASS ANIMAL**--

class Animal:
    def hacerSonido(self):
        print("Sonido genérico")
class Perro(Animal):
    def ladrar(self):
        print("¡Guau!")
perro = Perro()
perro.hacerSonido()  # Método heredado de Animal
perro.ladrar()       # Método propio de Perro

<img width="472" height="330" alt="image" src="https://github.com/user-attachments/assets/98c14fcb-bcdf-4fc6-923c-7cfae797e4bf" />


--**CLASS ANIMAL.2** --

class Animal: #clase base
    def _init_(self, nombre):
        self.nombre = nombre
        
    def hacerSonido(self):
        pass 
class Perro(Animal): #herencia derivada
    def hacerSonido(self):
        return "Guau!"
class Gato(Animal): #herencia derivadda
    def hacerSonido(self):
        return "Miau!"
perro =Perro("Rex")
print(f"{perro.nombre} dice {perro.hacerSonido()}")
gato =Gato("Iris")
print(f"{gato.nombre} dice {gato.hacerSonido()}")

<img width="467" height="452" alt="image" src="https://github.com/user-attachments/assets/22b51f1f-79d5-4435-851a-f012a4f5947e" />

--**CLASS FIGURA GEOMETRICA CIRCULO**--
class FiguraGeometrica:
    def __init__(self, nombre):
        self.nombre = nombre
    def area(self):
        raise NotImplementedError("Subclases deben implementar este método")

    def perimetro(self):
        raise NotImplementedError("Subclases deben implementar este método")
class Circulo(FiguraGeometrica):
    def __init__(self, radio):
        super().__init__("Circulo")
        self.radio = radio
    def area(self):
        return 3.141592*(self.radio**2)
    def perimetro(self):
        return 2*3.141592*self.radio
circulo = Circulo(5)
print(f"Nombre : {circulo.nombre}")
print(f"Area : {circulo.area()}")
print(f"Perimetro : {circulo.perimetro()}")
<img width="702" height="495" alt="image" src="https://github.com/user-attachments/assets/7b55da41-1005-43e7-95de-7ba21de1f27c" />


--**CLASS FIGURA GEOMETRICA RESCTANGULO**--
class FiguraGeometrica:
    def __init__(self, nombre):
        self.nombre = nombre
    def area(self):
        raise NotImplementedError("Subclases deben implementar este método")
    def perimetro(self):
        raise NotImplementedError("Subclases deben implementar este método")
class Rectangulo(FiguraGeometrica):
    def __init__(self, base, altura):
        super().__init__("Rectangulo")
        self.base = base
        self.altura = altura
    def area(self):
        # Fórmula del área: base * altura
        return self.base * self.altura
    def perimetro(self):
        # Fórmula del perímetro: 2 * (base + altura)
        return 2 * (self.base + self.altura)
rectangulo = Rectangulo(10, 5) # Base = 10, Altura = 5
print(f"Nombre : {rectangulo.nombre}")
print(f"Area : {rectangulo.area()}")
print(f"Perimetro : {rectangulo.perimetro()}")
<img width="737" height="565" alt="image" src="https://github.com/user-attachments/assets/3e7588da-e08c-49ed-bda3-f298a27e5fbb" />


--**CLASS AVES SONIDO**--

class Nadador: #clase base 1
    def nadar(self):
        print("Nadando en el agua")
class Volador: #clase base 2
    def volar(self):
        print("volando por el aire")
class Pato(Nadador,Volador): #clase derivada
    def graznar(self):
        print("¡Cuac!")
pato = Pato()
pato.nadar()
pato.volar()
pato.graznar()
<img width="442" height="325" alt="image" src="https://github.com/user-attachments/assets/70560ec1-77ab-460b-a9a3-f12372c94fe8" />

--**CLASS AVES(CISNE)**--

cisne.nadar()
cisne.volar()
cisne.cantar()
class Nadador:  # Clase base 1
    def nadar(self):
        print("El cisne se desliza elegantemente en el agua.")
class Volador:  # Clase base 2
    def volar(self):
        print("El cisne surca el cielo con majestuosidad.")
class Cisne(Nadador, Volador):  # Clase derivada (Herencia múltiple)
    def cantar(self):
        print("¡Whoop!")
# Crear objeto de la clase Cisne
cisne = Cisne()
# Llamar a los métodos heredados y propios
cisne.nadar()
cisne.volar()
cisne.cantar()
<img width="582" height="447" alt="image" src="https://github.com/user-attachments/assets/ba375cbe-ddc6-4b6b-9dbf-312ff463374a" />


**EJEMPLO :HERENCIA MULTIPLE**
          IMC=PESO /(ALTURA)^2
    CLASE:PESO->clase base 1
    CLASE:ALTURA->clase base 2
    CLASE:IMC->clase derivada 

    
class Peso:
    def _init_(self,peso_kg):
        self.peso_kg =peso_kg
class Altura:
    def _init_(self,altura_m):
        self.altura_m = altura_m

class IMC(Peso,Altura):
    def _init_(self,peso_kg,altura_m):
        Peso._init_(self,peso_kg)
        Altura._init_(self,altura_m)    
    def calcular_imc(self):
        if self.altura_m< 0:
            raise ValorError("La altura debe ser mayor que 0")
        return self.peso_kg/(self.altura_m**2)
    def categoria_imc(self):
        imc = self.calcular_imc()
        if imc < 18.5:
            return "Bajo peso"
        elif 18.5 <= imc <25:
            return "Normal"
        elif 25 <= imc <30:
            return "Sobrepeso"
        else:
            return "Obesidad"
    def mostrar_resultado(self):
        imc = self.calcular_imc()
        categoria = self.categoria_imc()
        return f"IMC: {imc:2f} CATEGRIA: {categoria}"
def leer_float(mensaje):
    while True:
        try:
            valor = float(input(mensaje))
            if valor <=0:
                print("Por favor, ingrese un valor poositivo")
                continue
            return valor
        except ValorError:
            print("Entrada invalida, ingrese un numero valido")
peso = leer_float("Ingrese tu peso en kilometros: ")
altura = leer_float("Ingrese tu altura en metros: ")
persona = IMC(peso_kg = peso,altura_m = altura)
print(persona.mostrar_resultado())

**EJEMPLO HERENCIA MULTIPLE(CLASS PITAGORAS)**
            <img width="175" height="41" alt="image" src="https://github.com/user-attachments/assets/a9a510d8-0f68-4f5d-a542-6a864be97fcd" />
            <img width="172" height="52" alt="image" src="https://github.com/user-attachments/assets/b38520de-410a-4672-ae0d-bfba7d091184" />

CLASE:CATETO_a
CLASE:CATETO_B
CLASE HIPOTENUSA()


import math
# Clase base 1
class CatetoA:
    def __init__(self, cateto_a):
        self.cateto_a = cateto_a
# Clase base 2
class CatetoB:
    def __init__(self, cateto_b):
        self.cateto_b = cateto_b
# Clase derivada
class TrianguloRectangulo(CatetoA, CatetoB):
    def __init__(self, cateto_a, cateto_b):
        CatetoA.__init__(self, cateto_a)
        CatetoB.__init__(self, cateto_b)
    def calcular_hipotenusa(self):
        if self.cateto_a <= 0 or self.cateto_b <= 0:
            raise ValueError("Los catetos deben ser mayores que 0")
        return math.sqrt(self.cateto_a ** 2 + self.cateto_b ** 2)
    def mostrar_resultado(self):
        hipotenusa = self.calcular_hipotenusa()
        return f"Cateto A: {self.cateto_a} | Cateto B: {self.cateto_b} | Hipotenusa: {hipotenusa:.2f}"
# Función para validar entrada de números positivos
def leer_float(mensaje):
    while True:
        try:
            valor = float(input(mensaje))
            if valor <= 0:
                print("Por favor, ingrese un valor positivo.")
                continue
            return valor
        except ValueError:
            print("Entrada inválida. Ingrese un número válido.")
# Programa principal
cateto_a = leer_float("Ingrese la longitud del cateto A: ")
cateto_b = leer_float("Ingrese la longitud del cateto B: ")
triangulo = TrianguloRectangulo(cateto_a, cateto_b)
print(triangulo.mostrar_resultado())


**EJEMPLO HERENCIA MULTIPLE(PERSONA,TRABAJO,ESTUDIO)**
       Clases: Persona, Trabajador, Estudiante
       Clase derivada: PersonaMultirol

class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
    def presentarse(self):
        print(f"Hola, soy {self.nombre} y tengo {self.edad} años.")
class Trabajador:
    def __init__(self, profesion, salario):
        self.profesion = profesion
        self.salario = salario
    def trabajar(self):
        print(f"Estoy trabajando como {self.profesion} y gano {self.salario} al mes.")
class Estudiante:
    def __init__(self, carrera, universidad):
        self.carrera = carrera
        self.universidad = universidad

    def estudiar(self):
        print(f"Estudio {self.carrera} en la Universidad {self.universidad}.")
class PersonaMultirol(Persona, Trabajador, Estudiante):
    def __init__(self, nombre, edad, profesion, salario, carrera, universidad):
        Persona.__init__(self, nombre, edad)
        Trabajador.__init__(self, profesion, salario)
        Estudiante.__init__(self, carrera, universidad)

    def mostrar_informacion(self):
        print("========= INFORMACIÓN DE LA PERSONA =========")
        self.presentarse()
        self.trabajar()
        self.estudiar()
def main():
    persona1 = PersonaMultirol(
        nombre="Juanita",
        edad=25,
        profesion="Desarrolladora de software",
        salario=2500,
        carrera="Ingeniería Estadística e Informática",
        universidad="Universidad Nacional del Altiplano"
    )
    persona1.mostrar_informacion()
if __name__ == "__main__":
    main()


#  ------Herencia Múltiple con Interfaz Tkinter-------------

import tkinter as tk
from tkinter import ttk, messagebox
# ==== CLASES BASE ====
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
    def presentarse(self):
        return f"Hola, soy {self.nombre} y tengo {self.edad} años."
class Trabajador:
    def __init__(self, profesion, salario):
        self.profesion = profesion
        self.salario = salario
    def trabajar(self):
        return f"Trabajo como {self.profesion} y gano {self.salario} soles al mes."
class Estudiante:
    def __init__(self, carrera, universidad):
        self.carrera = carrera
        self.universidad = universidad
    def estudiar(self):
        return f"Estudio {self.carrera} en la Universidad {self.universidad}."
# ==== CLASE DERIVADA (HERENCIA MÚLTIPLE) ====
class PersonaMultirol(Persona, Trabajador, Estudiante):
    def __init__(self, nombre, edad, profesion, salario, carrera, universidad):
        Persona.__init__(self, nombre, edad)
        Trabajador.__init__(self, profesion, salario)
        Estudiante.__init__(self, carrera, universidad)

    def mostrar_informacion(self):
        info = (
            f"========= INFORMACIÓN DE {self.nombre.upper()} =========\n"
            f"{self.presentarse()}\n"
            f"{self.trabajar()}\n"
            f"{self.estudiar()}\n"
        )
        return info
# ==== PERSONAS PREDEFINIDAS ====
persona1 = PersonaMultirol(
    "Juanita", 25, "Desarrolladora de software", 2500,
    "Ingeniería Estadística e Informática", "Universidad Nacional del Altiplano"
)
persona2 = PersonaMultirol(
    "Carlos", 30, "Analista de Datos", 3200,
    "Ciencia de la Computación", "Universidad Nacional Mayor de San Marcos"
)
persona3 = PersonaMultirol(
    "Gleny", 22, "Asistente de sistemas", 1800,
    "Ingeniería Informática", "Universidad Nacional del Altiplano"
)
# ==== FUNCIONES DE INTERFAZ ====
def mostrar_datos(persona):
    """Muestra la información de una persona en el cuadro de texto."""
    text_resultado.delete("1.0", tk.END)
    text_resultado.insert(tk.END, persona.mostrar_informacion())
def agregar_persona():
    """Crea una nueva persona a partir de los datos ingresados en el formulario."""
    nombre = entry_nombre.get()
    edad = entry_edad.get()
    profesion = entry_profesion.get()
    salario = entry_salario.get()
    carrera = entry_carrera.get()
    universidad = entry_universidad.get()
    # Validación de datos
    if not all([nombre, edad, profesion, salario, carrera, universidad]):
        messagebox.showwarning("Error", "Por favor, complete todos los campos.")
        return
    try:
        edad = int(edad)
        salario = float(salario)
    except ValueError:
        messagebox.showerror("Error", "Edad y salario deben ser numéricos.")
        return
    nueva_persona = PersonaMultirol(nombre, edad, profesion, salario, carrera, universidad)
    mostrar_datos(nueva_persona)
    messagebox.showinfo("Éxito", f"Se mostró la información de {nombre}.")
# ==== VENTANA PRINCIPAL ====
ventana = tk.Tk()
ventana.title("🧩 Herencia Múltiple - Tres Personas + Ingreso")
ventana.geometry("620x650")
ventana.resizable(False, False)
# ==== TÍTULO ====
titulo = ttk.Label(
    ventana,
    text="👩‍💻 HERENCIA MÚLTIPLE EN PYTHON (Persona - Trabajador - Estudiante)",
    font=("Arial", 11, "bold")
)
titulo.pack(pady=10)
# ==== BOTONES DE PERSONAS PREDEFINIDAS ====
frame_botones = ttk.Frame(ventana)
frame_botones.pack(pady=10)
ttk.Button(frame_botones, text="Mostrar Juanita 👩‍💻", command=lambda: mostrar_datos(persona1)).grid(row=0, column=0, padx=10)
ttk.Button(frame_botones, text="Mostrar Carlos 👨‍💼", command=lambda: mostrar_datos(persona2)).grid(row=0, column=1, padx=10)
ttk.Button(frame_botones, text="Mostrar Gleny 🧍‍♀️", command=lambda: mostrar_datos(persona3)).grid(row=0, column=2, padx=10)
# ==== CUADRO DE RESULTADOS ====
text_resultado = tk.Text(ventana, width=70, height=12, wrap="word", font=("Consolas", 10))
text_resultado.pack(pady=15)
# ==== SECCIÓN PARA INGRESAR NUEVA PERSONA ====
ttk.Label(ventana, text="🧠 Ingresar nueva persona", font=("Arial", 10, "bold")).pack()
frame_form = ttk.Frame(ventana)
frame_form.pack(pady=10)
labels = ["Nombre:", "Edad:", "Profesión:", "Salario:", "Carrera:", "Universidad:"]
entries = []
for i, texto in enumerate(labels):
    ttk.Label(frame_form, text=texto).grid(row=i, column=0, padx=5, pady=4, sticky="e")
    entrada = ttk.Entry(frame_form, width=40)
    entrada.grid(row=i, column=1, padx=5, pady=4)
    entries.append(entrada)
entry_nombre, entry_edad, entry_profesion, entry_salario, entry_carrera, entry_universidad = entries
ttk.Button(ventana, text="📋 Mostrar Nueva Persona", command=agregar_persona).pack(pady=10)
# ==== INSTRUCCIÓN FINAL ====
ttk.Label(ventana, text="Seleccione una persona o ingrese una nueva para ver su información.").pack()
# ==== EJECUTAR APLICACIÓN ====
ventana.mainloop()

<img width="767" height="848" alt="image" src="https://github.com/user-attachments/assets/f1ff8c16-12d3-4dec-9429-046e6f7df812" />

**DIAGRAMAS OPENGL**
from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def inicializar():
    glClearColor(0.1, 0.1, 0.1, 1.0)
    glPointSize(5)
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    glOrtho(-1.0, 1.0, -1.0, 1.0, -1.0, 1.0)

def dibujar_triangulo():
    glClear(GL_COLOR_BUFFER_BIT)
    glColor3f(1.0, 1.0, 0.0)
    glBegin(GL_POINTS)
    glVertex2f(0.0, 0.5)
    glVertex2f(-0.5, -0.5)
    glVertex2f(0.5, -0.5)
    glEnd()
    glFlush()

def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(600, 600)
    glutInitWindowPosition(100, 100)
    glutCreateWindow(b"Triangulo de puntos en OpenGL")
    inicializar()
    glutDisplayFunc(dibujar_triangulo)
    glutMainLoop()

if __name__ == "__main__":
    main()
<img width="747" height="781" alt="image" src="https://github.com/user-attachments/assets/4e65399c-7f68-47b2-af1e-14461bfe774e" />

----------EJEMPLO 2--------------
from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def inicializar():
    """Configura el entorno OpenGL"""
    glClearColor(0.1, 0.1, 0.1, 1.0)  # Fondo gris oscuro
    glPointSize(5)                    # Tamaño de los puntos (aumentado para mejor visibilidad)
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    glOrtho(-1.0, 1.0, -1.0, 1.0, -1.0, 1.0)  # Vista ortográfica 2D

def dibujar_triangulo():
    """Dibuja 3 puntos formando un triángulo"""
    glClear(GL_COLOR_BUFFER_BIT)

    glColor3f(1.0, 0.0, 0.0)  # Color amarillo
    glBegin(GL_QUADS)

    # Tres vértices del triángulo
    glVertex2f(-0.5, 0.5)    # Vértice superior
    glVertex2f(-0.5, -0.5)  # Vértice inferior izquierdo
    glVertex2f(0.5, -0.5)
    glVertex2f(0.5, 0.5)# Vértice inferior derecho

    glEnd()
    glFlush()       #obliga para que todo funcione

def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(600, 600)
    glutInitWindowPosition(100, 100)
    glutCreateWindow(b"Triangulo de puntos en OpenGL")
    inicializar()
    glutDisplayFunc(dibujar_triangulo)
    glutMainLoop()

if __name__ == "__main":  # CORRECCIÓN: __name en lugar de name
    main()
<img width="748" height="775" alt="image" src="https://github.com/user-attachments/assets/47c8ea39-f104-47c6-962d-8d45bb4f9174" />

--------------EJEMPLO 3-------------
from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def inicializar():
    glClearColor(0.0, 0.0, 0.0, 1.0)  # Fondo negro
    glColor3f(0.0, 1.0, 0.0)          # Letras verdes
    glLineWidth(3)                    # Grosor de línea
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    glOrtho(-1.0, 1.0, -1.0, 1.0, -1.0, 1.0)

def dibujar_UNA():
    glClear(GL_COLOR_BUFFER_BIT)
    glBegin(GL_LINES)

    # Letra U
    glVertex2f(-0.8,  0.5); glVertex2f(-0.8, -0.5)
    glVertex2f(-0.8, -0.5); glVertex2f(-0.6, -0.5)
    glVertex2f(-0.6, -0.5); glVertex2f(-0.6,  0.5)

    # Letra N
    glVertex2f(-0.5, -0.5); glVertex2f(-0.5,  0.5)
    glVertex2f(-0.5,  0.5); glVertex2f(-0.3, -0.5)
    glVertex2f(-0.3, -0.5); glVertex2f(-0.3,  0.5)

    # Letra A
    glVertex2f(-0.1, -0.5); glVertex2f(0.0,  0.5)
    glVertex2f(0.0,  0.5);  glVertex2f(0.1, -0.5)
    glVertex2f(-0.05, 0.0); glVertex2f(0.05, 0.0)

    glEnd()
    glFlush()

def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(600, 600)
    glutInitWindowPosition(100, 100)
    glutCreateWindow(b"UNA en OpenGL (coordenadas)")
    inicializar()
    glutDisplayFunc(dibujar_UNA)
    glutMainLoop()

if __name__ == "__main__":
    main()
<img width="748" height="793" alt="image" src="https://github.com/user-attachments/assets/fc05743a-2b85-4718-a417-0f3e1409755e" />


**TRABAJO DE LOBO**
from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def inicializar():
    """Configura el entorno OpenGL"""
    glClearColor(1.0, 1.0, 1.0, 1.0)  # Fondo blanco
    glPointSize(7)
    glLineWidth(2.5)
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    glOrtho(-1.0, 1.0, -1.15, 1.15, -1.0, 1.0)

# --- Coordenadas de los ojos (más grandes) ---
left_eye = [(-0.40, -0.05), (-0.27, 0.06), (-0.15, -0.08)]
left_eye_inner_lines = [(-0.40, -0.05), (-0.30, -0.02), (-0.23, -0.05), (-0.27, 0.06)]

right_eye = [(0.40, -0.05), (0.27, 0.06), (0.15, -0.08)]
right_eye_inner_lines = [(0.40, -0.05), (0.30, -0.02), (0.23, -0.05), (0.27, 0.06)]

def dibujar_zorro():
    glClear(GL_COLOR_BUFFER_BIT)

    # --- CONTORNO PRINCIPAL ---
    glColor3f(0.0, 0.0, 0.0)
    glBegin(GL_LINE_STRIP)
    glVertex2f(-0.7, 0.1)
    glVertex2f(-0.8, -0.2)
    glVertex2f(-0.9, -0.6)
    glVertex2f(-0.8, -0.7)
    glVertex2f(-0.7, -0.6)
    glVertex2f(-0.4, -0.9)
    glVertex2f(-0.1, -1.0)
    glVertex2f(0.1, -1.0)
    glVertex2f(0.4, -0.9)
    glVertex2f(0.7, -0.6)
    glVertex2f(0.8, -0.7)
    glVertex2f(0.9, -0.7)
    glVertex2f(0.8, -0.3)
    glVertex2f(0.7, 0.1)
    glVertex2f(0.3, 0.4)
    glVertex2f(0.0, 0.1)
    glVertex2f(-0.3, 0.4)
    glVertex2f(-0.7, 0.1)
    glVertex2f(-0.8, 0.4)
    glVertex2f(-0.9, 0.7)
    glVertex2f(-0.8, 1.0)
    glVertex2f(-0.7, 1.0)
    glVertex2f(-0.5, 0.9)
    glVertex2f(-0.3, 0.7)
    glVertex2f(-0.2, 0.6)
    glVertex2f(0.0, 0.7)
    glVertex2f(0.2, 0.6)
    glVertex2f(0.3, 0.7)
    glVertex2f(0.5, 0.9)
    glVertex2f(0.7, 1.0)
    glVertex2f(0.8, 1.0)
    glVertex2f(0.9, 0.7)
    glVertex2f(0.7, 0.1)
    glEnd()

    # --- HOCICO ---
    glColor3f(0.85, 0.85, 0.85)
    glBegin(GL_POLYGON)
    glVertex2f(-0.1, -0.8)
    glVertex2f(-0.2, -0.6)
    glVertex2f(-0.1, -0.5)
    glVertex2f(0.1, -0.5)
    glVertex2f(0.2, -0.6)
    glVertex2f(0.1, -0.8)
    glEnd()

    glColor3f(0.0, 0.0, 0.0)
    glBegin(GL_LINE_LOOP)
    glVertex2f(-0.1, -0.8)
    glVertex2f(-0.2, -0.6)
    glVertex2f(-0.1, -0.5)
    glVertex2f(0.1, -0.5)
    glVertex2f(0.2, -0.6)
    glVertex2f(0.1, -0.8)
    glEnd()

    # --- OREJAS ---
    glColor3f(0.85, 0.85, 0.85)
    glBegin(GL_POLYGON)
    glVertex2f(-0.4, 0.6)
    glVertex2f(-0.7, 0.9)
    glVertex2f(-0.7, 0.4)
    glVertex2f(-0.6, 0.3)
    glVertex2f(-0.4, 0.5)
    glEnd()

    glBegin(GL_POLYGON)
    glVertex2f(0.4, 0.6)
    glVertex2f(0.7, 0.9)
    glVertex2f(0.7, 0.4)
    glVertex2f(0.6, 0.3)
    glVertex2f(0.4, 0.5)
    glEnd()

    glColor3f(0.0, 0.0, 0.0)
    glBegin(GL_LINE_LOOP)
    glVertex2f(-0.4, 0.6)
    glVertex2f(-0.7, 0.9)
    glVertex2f(-0.7, 0.4)
    glVertex2f(-0.6, 0.3)
    glVertex2f(-0.4, 0.5)
    glEnd()

    glBegin(GL_LINE_LOOP)
    glVertex2f(0.4, 0.6)
    glVertex2f(0.7, 0.9)
    glVertex2f(0.7, 0.4)
    glVertex2f(0.6, 0.3)
    glVertex2f(0.4, 0.5)
    glEnd()

    # --- OJOS más grandes ---
    glColor3f(0.0, 0.0, 0.0)
    glBegin(GL_LINE_LOOP)
    for x, y in left_eye:
        glVertex2f(x, y)
    glEnd()

    glBegin(GL_LINES)
    for i in range(len(left_eye_inner_lines) - 1):
        glVertex2f(*left_eye_inner_lines[i])
        glVertex2f(*left_eye_inner_lines[i + 1])
    glEnd()

    glBegin(GL_LINE_LOOP)
    for x, y in right_eye:
        glVertex2f(x, y)
    glEnd()

    glBegin(GL_LINES)
    for i in range(len(right_eye_inner_lines) - 1):
        glVertex2f(*right_eye_inner_lines[i])
        glVertex2f(*right_eye_inner_lines[i + 1])
    glEnd()

    glFlush()

def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(600, 700)
    glutInitWindowPosition(100, 100)
    glutCreateWindow(b"Zorro con ojos grandes")
    inicializar()
    glutDisplayFunc(dibujar_zorro)
    glutMainLoop()

if __name__ == "__main__":
    main()
    <img width="750" height="910" alt="image" src="https://github.com/user-attachments/assets/cd8fa32e-a782-40af-9b85-4bffc61faedb" />


**EJERCICIO Y=X^2**
 from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def inicializar():
    """Configura el entorno OpenGL"""
    glClearColor(1.0, 1.0, 1.0, 1.0)  # Fondo blanco
    glPointSize(6.0)                  # Tamaño de los puntos
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    glOrtho(-2.5, 2.5, -0.5, 5.5, -1.0, 1.0)  # Rango visible (x,y)

def texto(x, y, texto):
    """Dibuja texto en pantalla"""
    glRasterPos2f(x, y)
    for ch in texto:
        glutBitmapCharacter(GLUT_BITMAP_HELVETICA_12, ord(ch))

def dibujar_funcion():
    glClear(GL_COLOR_BUFFER_BIT)

    # ============================
    # Ejes X y Y
    # ============================
    glColor3f(0.0, 0.0, 0.0)
    glBegin(GL_LINES)
    glVertex2f(-2.5, 0.0)
    glVertex2f(2.5, 0.0)   # Eje X
    glVertex2f(0.0, -0.5)
    glVertex2f(0.0, 5.5)   # Eje Y
    glEnd()

    # --- Marcas en el eje X ---
    for i in range(-2, 3):
        glBegin(GL_LINES)
        glVertex2f(i, -0.05)
        glVertex2f(i, 0.05)
        glEnd()
        if i != 0:
            texto(i - 0.05, -0.25, str(i))

    # --- Marcas en el eje Y ---
    for j in range(0, 6):
        glBegin(GL_LINES)
        glVertex2f(-0.05, j)
        glVertex2f(0.05, j)
        glEnd()
        if j != 0:
            texto(0.1, j - 0.05, str(j))

    # ============================
    # Función y = x²
    # ============================

    # Línea azul que une los puntos
    glColor3f(0.0, 0.0, 1.0)
    glLineWidth(2.0)
    glBegin(GL_LINE_STRIP)
    x = -2.0
    while x <= 2.0:
        y = x * x
        glVertex2f(x, y)
        x += 0.05
    glEnd()

    # Puntos rojos y coordenadas
    glColor3f(1.0, 0.0, 0.0)
    glBegin(GL_POINTS)
    x = -2.0
    while x <= 2.0:
        y = round(x * x, 2)
        glVertex2f(x, y)
        x += 0.5
    glEnd()

    # Mostrar coordenadas (x, y)
    x = -2.0
    while x <= 2.0:
        y = round(x * x, 2)
        texto(x + 0.05, y + 0.1, f"({x:.1f},{y:.1f})")
        x += 0.5

    # Etiquetas
    glColor3f(0.0, 0.0, 0.0)
    texto(2.1, -0.3, "X")
    texto(-0.2, 5.2, "Y")
    texto(0.5, 4.8, "y = x²")

    glFlush()

def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(700, 700)
    glutInitWindowPosition(100, 100)
    glutCreateWindow(b"Grafico de y = x^2 con coordenadas")
    inicializar()
    glutDisplayFunc(dibujar_funcion)
    glutMainLoop()

if __name__ == "__main__":
    main()
<img width="873" height="881" alt="image" src="https://github.com/user-attachments/assets/a7245d67-6345-4bd9-b941-b0422f88102e" />

**EJERCICIO DE Y=X^3**
from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def inicializar():
    """Configura el entorno OpenGL"""
    glClearColor(1.0, 1.0, 1.0, 1.0)  # Fondo blanco
    glPointSize(6.0)                  # Tamaño de los puntos
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    glOrtho(-2.5, 2.5, -10.0, 10.0, -1.0, 1.0)  # Rango visible (x,y)

def texto(x, y, texto):
    """Dibuja texto en pantalla"""
    glRasterPos2f(x, y)
    for ch in texto:
        glutBitmapCharacter(GLUT_BITMAP_HELVETICA_12, ord(ch))

def dibujar_funcion():
    glClear(GL_COLOR_BUFFER_BIT)

    # ============================
    # Ejes X y Y
    # ============================
    glColor3f(0.0, 0.0, 0.0)
    glBegin(GL_LINES)
    glVertex2f(-2.5, 0.0)
    glVertex2f(2.5, 0.0)   # Eje X
    glVertex2f(0.0, -10.0)
    glVertex2f(0.0, 10.0)  # Eje Y
    glEnd()

    # --- Marcas en el eje X ---
    for i in range(-2, 3):
        glBegin(GL_LINES)
        glVertex2f(i, -0.3)
        glVertex2f(i, 0.3)
        glEnd()
        if i != 0:
            texto(i - 0.1, -1.0, str(i))

    # --- Marcas en el eje Y ---
    for j in range(-9, 10, 3):
        glBegin(GL_LINES)
        glVertex2f(-0.1, j)
        glVertex2f(0.1, j)
        glEnd()
        if j != 0:
            texto(0.2, j - 0.3, str(j))

    # ============================
    # Función y = x³
    # ============================

    # Línea azul continua
    glColor3f(0.0, 0.0, 1.0)
    glLineWidth(2.0)
    glBegin(GL_LINE_STRIP)
    x = -2.0
    while x <= 2.0:
        y = x ** 3
        glVertex2f(x, y)
        x += 0.05
    glEnd()

    # Puntos rojos
    glColor3f(1.0, 0.0, 0.0)
    glBegin(GL_POINTS)
    x = -2.0
    while x <= 2.0:
        y = round(x ** 3, 2)
        glVertex2f(x, y)
        x += 0.5
    glEnd()

    # Coordenadas (x, y)
    x = -2.0
    while x <= 2.0:
        y = round(x ** 3, 2)
        texto(x + 0.05, y + 0.4, f"({x:.1f},{y:.1f})")
        x += 0.5

    # Etiquetas
    glColor3f(0.0, 0.0, 0.0)
    texto(2.1, -1.5, "X")
    texto(-0.2, 9.5, "Y")
    texto(0.7, 8.0, "y = x³")

    glFlush()

def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(700, 700)
    glutInitWindowPosition(100, 100)
    glutCreateWindow(b"Grafico de y = x^3 con coordenadas")
    inicializar()
    glutDisplayFunc(dibujar_funcion)
    glutMainLoop()

if __name__ == "__main__":
    main()
<img width="875" height="901" alt="image" src="https://github.com/user-attachments/assets/dfb44f5e-b9c8-434d-af97-d12530e273cc" />

**EJERCICIO DE TRIANGULO**
from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *
import numpy as np

angulo = 0.0  # Ángulo de rotación inicial

def init():
    glClearColor(0.0, 0.0, 0.0, 1.0)  # Fondo negro
    glMatrixMode(GL_PROJECTION)
    glLoadIdentity()
    gluOrtho2D(-1.5, 1.5, -1.5, 1.5)  # Coordenadas 2D
    glMatrixMode(GL_MODELVIEW)

def display():
    global angulo
    glClear(GL_COLOR_BUFFER_BIT)
    glLoadIdentity()

    # Aplicar rotación
    glRotatef(angulo, 0.0, 0.0, 1.0)

    # Dibujar un triángulo
    glColor3f(1.0, 0.0, 0.0)  # Rojo
    glBegin(GL_TRIANGLES)
    glVertex2f(0.0, 0.5)
    glVertex2f(-0.5, -0.5)
    glVertex2f(0.5, -0.5)
    glEnd()

    glFlush()

def specialKeys(key, x, y):
    global angulo
    if key == GLUT_KEY_LEFT:   # Flecha izquierda
        angulo += 2
    elif key == GLUT_KEY_RIGHT:  # Flecha derecha
        angulo -= 2
    glutPostRedisplay()
# 
def main():
    glutInit()
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
    glutInitWindowSize(600, 600)
    glutCreateWindow(b"Transformacion Geometrica - Rotacion")
    init()
    glutDisplayFunc(display)
    glutSpecialFunc(specialKeys)
    glutMainLoop()

main()
<img width="750" height="787" alt="image" src="https://github.com/user-attachments/assets/ada2682e-15b3-4128-8f22-1392bb27aff6" />
**EXCEPCIONES EN PYTHON**

EJEMPLO 
-import math

def calcular_hipotenusa(cateto_a, cateto_b):
    # Fórmula correcta: h = sqrt(a^2 + b^2)
    return math.sqrt(cateto_a**2 + cateto_b**2)

def main():
    try:
        a = float(input("Ingrese el valor de A: "))
        b = float(input("Ingrese el valor de B: "))
        
        if a <= 0 or b <= 0:
            raise ValueError("Los catetos deben ser números positivos")
        
        hipotenusa = calcular_hipotenusa(a, b)
        
        print(f"La hipotenusa es: {hipotenusa:.2f}")
    
    except ValueError as ve:
        print("Error:", ve)
    
    except Exception as e:
        print("Ocurrió un error inesperado:", e)

if __name__ == "__main__":
    main()
    
EJEMPLO
-import tkinter as tk
from tkinter import messagebox
import math

def calcular():
    try:
        a = float(entry_a.get())
        b = float(entry_b.get())

        if a <= 0 or b <= 0:
            raise ValueError("Los catetos deben ser números positivos")

        hipotenusa = math.sqrt(a**2 + b**2)
        label_resultado.config(text=f"Hipotenusa: {hipotenusa:.2f}")

    except ValueError as ve:
        messagebox.showerror("Error", str(ve))
    except Exception as e:
        messagebox.showerror("Error inesperado", str(e))

# Ventana principal
ventana = tk.Tk()
ventana.title("Cálculo de Hipotenusa")
ventana.geometry("300x230")
ventana.resizable(False, False)

# Etiquetas y cajas de texto
tk.Label(ventana, text="Ingrese Cateto A:").pack(pady=5)
entry_a = tk.Entry(ventana)
entry_a.pack()

tk.Label(ventana, text="Ingrese Cateto B:").pack(pady=5)
entry_b = tk.Entry(ventana)
entry_b.pack()

# Botón calcular
tk.Button(ventana, text="Calcular Hipotenusa", command=calcular).pack(pady=15)

# Resultado
label_resultado = tk.Label(ventana, text="Hipotenusa: ---", font=("Arial", 12, "bold"))
label_resultado.pack(pady=10)

# Ejecutar ventana
ventana.mainloop()
<img width="377" height="322" alt="image" src="https://github.com/user-attachments/assets/958048ba-8d71-4bc2-a8bd-d82e2ee90f68" />

EJEMPLO
-def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        print(a, end=" ")
        a, b = b, a + b

def main():
    try:
        n = int(input("Ingrese cuántos términos desea mostrar: "))
        if n <= 0:
            raise ValueError("El número debe ser positivo")
        fibonacci(n)

    except ValueError as ve:
        print("Error:", ve)

if __name__ == "__main__":
    main()

EJEMPLO TKINTER
-import tkinter as tk
from tkinter import messagebox

def generar_fibonacci(n):
    a, b = 0, 1
    resultado = ""
    for _ in range(n):
        resultado += str(a) + " "
        a, b = b, a + b
    return resultado

def dibujar_grafico(n):
    canvas.delete("all")  # limpiar

    a, b = 0, 1
    x = 20   # posición inicial

    # calcular valores para la escala
    max_val = 0
    temp_a, temp_b = 0, 1
    for _ in range(n):
        if temp_a > max_val:
            max_val = temp_a
        temp_a, temp_b = temp_b, temp_a + temp_b

    if max_val == 0:
        max_val = 1

    for _ in range(n):
        altura = int((a / max_val) * 180)  # escala al canvas
        canvas.create_rectangle(x, 200 - altura, x + 20, 200, fill="skyblue")
        canvas.create_text(x + 10, 200 - altura - 10, text=str(a), font=("Arial", 8))
        a, b = b, a + b
        x += 30

def calcular():
    try:
        n = int(entry_n.get())
        if n <= 0:
            raise ValueError("Debe ingresar un número positivo.")

        serie = generar_fibonacci(n)
        label_resultado.config(text=f"Serie: {serie}")

        dibujar_grafico(n)

    except ValueError as ve:
        messagebox.showerror("Error", str(ve))

# Ventana principal
ventana = tk.Tk()
ventana.title("Serie Fibonacci Gráfica")
ventana.geometry("600x400")
ventana.resizable(False, False)

# Entrada
tk.Label(ventana, text="Cantidad de términos:", font=("Arial", 11)).pack(pady=5)
entry_n = tk.Entry(ventana, width=10)
entry_n.pack()

tk.Button(ventana, text="Generar", command=calcular).pack(pady=10)

# Resultado
label_resultado = tk.Label(ventana, text="Serie: ---", font=("Arial", 10))
label_resultado.pack(pady=5)

# Canvas del gráfico
canvas = tk.Canvas(ventana, width=560, height=220, bg="white")
canvas.pack(pady=10)

ventana.mainloop()
<img width="747" height="537" alt="image" src="https://github.com/user-attachments/assets/3c21353c-8e98-413b-a4ac-8a2eaca79951" />





**PROGRAMACION GENERICA**

  La programacion generica es un paradigma que permite escribir codigo flexible y reutilizable mediante el uso de t8ipos genericos su objetivo esz disenar
  algoritmos y estructura de datos qu e puedan operar con distintos tipos de datos sin necesidad de reescribir el codigo para cada tipo especifico en python 
  este enfoque se implementa principalmente a traves del uso de tipos genericos en el moldo typing talez como list,dic,set,tuple y tyvar los cuales permiten       definir clases y funciones que trabajan de forma segura con diferentes tipos de datos.

  EJEMPLO
  -
from typing import TypeVar

T = TypeVar('T', int, float)

def sumar(a: T, b: T) -> T:
    return a + b

print(sumar(5, 10))
print(sumar(3.5, 2.5))

EJEMPLO
-
from typing import TypeVar
import math

T = TypeVar('T', int, float)

def calcular_hipotenusa(cateto_a: T, cateto_b: T) -> T:
    return math.sqrt(cateto_a**2 + cateto_b**2)

print("Hipotenusa =", calcular_hipotenusa(3, 4))
print("Hipotenusa =", calcular_hipotenusa(5.5, 2.2))

EJEMPLO
-
from typing import TypeVar, Generic
T = TypeVar('T', int, float)
class CalculadoraFactorial(Generic[T]):
    def __init__(self, numero: T):
        self.numero = numero
    def calcular_factorial(self) -> int:
        n = int(self.numero)
        if n < 0:
            raise ValueError("El factorial no está definido para números negativos.")
        resultado = 1
        for i in range(1, n + 1):
            resultado *= i
        return resultado
def main():
    try:
        n = float(input("Ingrese un número: "))

        cal = CalculadoraFactorial(n)
        print(f"El factorial de {n} es: {cal.calcular_factorial()}")

    except ValueError as e:
        print(f"Error: {e}")


if __name__ == "__main__":
    main()
    
EJEMPLO TKINTER
-
import tkinter as tk
from tkinter import messagebox
from typing import TypeVar, Generic
T = TypeVar('T', int, float)
class CalculadoraFactorial(Generic[T]):
    def __init__(self, numero: T):
        self.numero = numero
    def calcular_factorial(self) -> int:
        n = int(self.numero)
        if n < 0:
            raise ValueError("El factorial no está definido para números negativos.")
        resultado = 1
        for i in range(1, n + 1):
            resultado *= i
        return resultado

def calcular():
    try:
        n = float(entry_numero.get())
        calc = CalculadoraFactorial(n)
        resultado = calc.calcular_factorial()
        label_resultado.config(text=f"Factorial: {resultado}")
        dibujar_grafico(int(n))
    except ValueError as e:
        messagebox.showerror("Error", str(e))
def dibujar_grafico(n):
    canvas.delete("all")
    if n < 1:
        return
    # Calcular valores del factorial hasta n para el gráfico
    valores = []
    fact = 1
    for i in range(1, n + 1):
        fact *= i
        valores.append(fact)
    max_val = max(valores)
    x = 20
    # Dibujar barras
    for i, val in enumerate(valores, start=1):
        altura = int((val / max_val) * 180)
        canvas.create_rectangle(x, 200 - altura, x + 25, 200, fill="lightblue")
        canvas.create_text(x + 12, 205, text=str(i), font=("Arial", 9))
        x += 35
ventana = tk.Tk()
ventana.title("Calculadora de Factorial")
ventana.geometry("500x400")
ventana.resizable(False, False)
tk.Label(ventana, text="Ingrese un número:", font=("Arial", 11)).pack(pady=5)
entry_numero = tk.Entry(ventana, width=10)
entry_numero.pack()
tk.Button(ventana, text="Calcular Factorial", command=calcular).pack(pady=10)
label_resultado = tk.Label(ventana, text="Factorial: ---", font=("Arial", 12, "bold"))
label_resultado.pack(pady=10)
canvas = tk.Canvas(ventana, width=460, height=230, bg="white")
canvas.pack(pady=10)
ventana.mainloop()
<img width="626" height="540" alt="image" src="https://github.com/user-attachments/assets/ccda23b2-471e-435b-99fc-987694f83eb7" />

EJEMPLO
-
from typing import TypeVar, Generic
import math
T = TypeVar('T', int, float)
class TrianguloRectangulo(Generic[T]):
    def __init__(self,cateto_a: T, cateto_b: T):
        self.a = cateto_a
        self.b = cateto_b
    def hipotenusa(self) -> float:
        return math.sqrt(self.a*2 + self.b*2)
    def area(self) ->float:
        return (self.a * self.b) / 2
    def perimetro(self) ->float:
        return self.a + self.b + self.hipotenusa()
def main():
    try:
        a = float(input("Ingrese cateto A: "))
        b = float(input("Ingrese cateto B: "))
        tri = TrianguloRectangulo(a,b)
        h= tri.hipotenusa()
        area=tri.area()
        perimetro = tri.perimetro()
        print(f"A = {a}")
        print(f"B = {b}")
        print(f"H = {h:.2f}")
        print(f"ÁREA = {area:.2f}")
        print(f"PERÍMETRO = {perimetro:.2f}")
    except ValueError as e:
        print(f"Error: {e}")
if __name__ == "__main__":
    main()
from typing import TypeVar, Generic
import math

T = TypeVar('T', int, float)

class TrianguloRectangulo(Generic[T]):

    def __init__(self, cateto_a: T, cateto_b: T):
        self.a = float(cateto_a)
        self.b = float(cateto_b)

    def hipotenusa(self) -> float:
        # Fórmula correcta: √(a² + b²)
        return math.sqrt(self.a**2 + self.b**2)

    def area(self) -> float:
        return (self.a * self.b) / 2

    def perimetro(self) -> float:
        return self.a + self.b + self.hipotenusa()


def main():
    try:
        a = float(input("Ingrese cateto A: "))
        b = float(input("Ingrese cateto B: "))

        if a <= 0 or b <= 0:
            raise ValueError("Los catetos deben ser positivos.")

        tri = TrianguloRectangulo(a, b)

        h = tri.hipotenusa()
        area = tri.area()
        perimetro = tri.perimetro()

        print(f"A = {a}")
        print(f"B = {b}")
        print(f"H = {h:.2f}")          # ← Hipotenusa correcta
        print(f"ÁREA = {area:.2f}")
        print(f"PERÍMETRO = {perimetro:.2f}")

    except ValueError as e:
        print(f"Error: {e}")


if __name__ == "__main__":
    main()
