# 🧠 Cuaderno Virtual – Lenguaje de Programación

**Nombre:** Gleny Angélica Condori Mamani  
**Facultad:** Ingeniería Estadística e Informática  
**Universidad:** Universidad Nacional del Altiplano – Puno  
**Curso:** Lenguaje de Programación (Python)  
**Docente:** Leonel  
## 📘TEMA  _ PROGRAMACION ORIENTADA A OBJETOS
Es una paradigma de programacion que organiza el sofware entorno a objetos ,los cuales conbinan datos(atributos)y comportamiento(metodos)en una misma entidad.Estos objetos se basan en clases que funcionan como molde o plantillas que definen sus caracteristicas y acciones.
## Diferencia entre programacion estructurada y P.O.O
## 🧩 Comparación: Programación Estructurada vs Programación Orientada a Objetos

| **Característica** | **Programación Estructurada** | **Programación Orientada a Objetos (POO)** |
|---------------------|-------------------------------|---------------------------------------------|
| **Paradigma** | Se basa en procedimientos y funciones que operan sobre datos. | Se basa en objetos que combinan datos y comportamiento. |
| **Organización del Código** | El programa se divide en funciones o módulos. | El programa se organiza en **clases** y **objetos**. |
| **Enfoque** | Orientado a **procesos**: la secuencia de instrucciones es lo principal. | Orientado a **entidades**: los objetos del mundo real son lo principal. |
| **Datos** | Los datos son **globales o compartidos**, y pueden ser modificados por cualquier función. | Los datos (**atributos**) están **encapsulados** dentro de los objetos y solo son accesibles mediante sus métodos. |
| **Reutilización** | **Baja:** se requiere repetir o copiar funciones. | **Alta:** gracias a la **herencia** y **polimorfismo**. |
| **Mantenimiento** | **Difícil**, porque un cambio en los datos puede afectar muchas funciones. | **Más sencillo**, ya que los cambios se aíslan en las clases u objetos correspondientes. |

## 🧩 ¿Qué es la Programación Orientada a Objetos?

La **POO** es un paradigma de programación que organiza el código en **clases y objetos**.  
- **Clase:** molde o plantilla que define las características y comportamientos de un tipo de objeto.  
- **Objeto:** instancia concreta de una clase.  
- **Atributo:** características o propiedades del objeto.  
- **Método:** funciones que describen el comportamiento del objeto.
## EN RESUMEN 
-La paradigma estructurada organiza en funciones y pasos esenciales siendo mas adecuado para programas pequeños y sencillos.

-La P.O.O organiza el software en clases y objetos,lo cual facilita modularidad , reutilizacion y escalavilidad ,siendo la mas usada en sistemas modernos.
## 🌟 Ventajas de la Programación Orientada a Objetos (P.O.O.)

| **Ventaja** | **Descripción** |
|--------------|----------------|
| **Modularidad** | El código se organiza en **clases y objetos**, lo que facilita la comprensión, depuración y mantenimiento del sistema. |
| **Reutilización de Código** | Gracias a la **herencia** y al **polimorfismo**, se pueden crear nuevas clases a partir de otras sin repetir código. |
| **Encapsulamiento** | Protege los datos internos de los objetos, permitiendo el acceso solo a través de métodos definidos, manteniendo la seguridad de la información. |
| **Abstracción** | Permite representar entidades del mundo real como modelos computacionales, simplificando la complejidad. |
| **Escalabilidad** | Adecuado para sistemas grandes y complejos, ya que permite dividir el trabajo en módulos independientes. |
| **Mantenimiento más sencillo** | Los cambios se realizan en clases específicas sin afectar todo el sistema. |
| **Flexibilidad y Extensibilidad** | Permite adaptar y ampliar sistemas de manera rápida y ordenada. |
| **Productividad** | Facilita el trabajo en equipo: varios programadores pueden desarrollar distintas clases u objetos de forma independiente. |

---

## 💻 Aplicaciones de la Programación Orientada a Objetos

La **P.O.O.** se aplica ampliamente en el desarrollo de software moderno, ya que permite construir **sistemas modulares, reutilizables y escalables**.  
A continuación, algunos ejemplos destacados:

- 🖥️ **1)Desarrollo de aplicaciones de escritorio:**  
  Programas de editores de texto, hojas de cálculo de  software de gestión utilizan P.O.O para organizar **ventanas, menús, botones y acciones como objetos.** 
  
- 🌐 **2)Aplicaciones web y móviles:**  
  Frameworks modernos aplican principios de programacion a objetos para manejar usuarios,productos,pedidos,mensajes,etc.

- 🗄️ **3)Sistemas de bases de datos:**  
  La P.O.O. se utiliza en el diseño de **bases de datos orientadas a objetos** y en los **ORM (Object-Relational Mapping)**, que permiten mapear tablas a objetos de manera sencilla.  
  Ejemplos: *SQLAlchemy (Python)*, *Hibernate (Java)*, *Entity Framework (.NET)*.

- 🎮 **4)Videojuegos:**  
  Cada **personaje, enemigo, escenario o arma** puede representarse como un **objeto** con atributos (vida, posición, puntuación) y métodos (moverse, atacar, desaparecer).

- 🤖 **5)Inteligencia Artificial y Simulaciones:**  
  Los **agentes inteligentes**, **redes neuronales** o **simulaciones físicas** se modelan como objetos que interactúan entre sí, compartiendo estados y comportamientos.

- ☁️ **6)Sistemas distribuidos y en la nube:**  
  Los **servicios** se representan como objetos que se comunican entre diferentes nodos, manteniendo **modularidad y escalabilidad**.  
  Ejemplo: microservicios implementados con clases y objetos en *Python Flask* o *Java Spring*.

- 🖥️ **/)Interfaces gráficas de usuario (GUI):**  
  Librerías como **Tkinter (Python)**, **JavaFX (Java)** y **Qt (C++)** organizan elementos gráficos (botones, menús, cuadros de texto) como **objetos reutilizables** con propiedades y métodos.

---

### 🧠 Conclusión

La **P.O.O.** se aplica en cualquier área donde se requiera **organizar y modular entidades complejas del mundo real**.  
Es el **paradigma principal del desarrollo de software moderno**, debido a su **claridad, escalabilidad y capacidad de reutilización**.



### 🔹 Clase

Una **clase** es una **plantilla o molde** que permite crear **objetos**.  
-Define **atributos** (propiedades o características)
-Define **métodos** (acciones o comportamientos).

Los objetos son instancias de una clase es decir ,representaciones concretas creadas a partir de esa plantilla.
En otras palabras la clase es el molde la de la plantilla.

-El objeto es el productor creado apartir de ese molde.

# =======================================
# 🧩 EJEMPLO 1 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Coche` |
# | **Atributos** | `marca`, `modelo`, `color` |
# | **Comportamientos (métodos)** | `arrancar()`, `acelerar()`, `frenar()` |
# | **Objeto (instancia)** | `toyota = Coche("Toyota", "Corolla", "Blanco")` |
# =======================================

class Coche:
    def __init__(self, marca, modelo, color):
        self.marca = marca
        self.modelo = modelo
        self.color = color

    def arrancar(self):
        print(f"El {self.marca} {self.modelo} ha arrancado.")

    def acelerar(self):
        print(f"El {self.marca} {self.modelo} está acelerando... ¡Vruum!")

    def frenar(self):
        print(f"El {self.marca} {self.modelo} está frenando.")


# =======================================
# 🧩 EJEMPLO 2 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Pitagoras` |
# | **Atributos** | `a`, `b` |
# | **Comportamiento (método)** | `calcular_hipotenusa()` |
# | **Objeto (instancia)** | `triangulo = Pitagoras(4, 3)` |
# =======================================

import math

class Pitagoras:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def calcular_hipotenusa(self):
        c = math.sqrt(self.a**2 + self.b**2)
        print(f"La hipotenusa es: {c:.2f}")
        return c


# =======================================
# 🧩 EJEMPLO 3 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Rectangulo` |
# | **Atributos** | `base`, `altura` |
# | **Comportamientos (métodos)** | `area()`, `perimetro()` |
# | **Objeto (instancia)** | `rect = Rectangulo(5, 6)` |
# =======================================

class Rectangulo:
    def __init__(self, base, altura):
        self.base = base
        self.altura = altura

    def area(self):
        return self.base * self.altura

    def perimetro(self):
        return 2 * (self.base + self.altura)


# =======================================
# 🧩 EJEMPLO 4 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Cantidad` |
# | **Atributos** | `longitud`, `altura`, `ancho`, `jv`, `sh` |
# | **Comportamiento (método)** | `calcular_ladrillos()` |
# | **Objeto (instancia)** | `pared = Cantidad(5, 2.5, 0.15, 0.015, 0.015)` |
# =======================================

class Cantidad:
    def __init__(self, longitud, altura, ancho, jv, sh):
        self.longitud = longitud
        self.altura = altura
        self.ancho = ancho
        self.jv = jv
        self.sh = sh

    def calcular_ladrillos(self):
        volumen_pared = self.longitud * self.altura * self.ancho
        volumen_ladrillo = (0.25 + self.jv) * (0.07 + self.sh) * (0.12 + self.jv)
        cantidad = volumen_pared / volumen_ladrillo
        print(f"Cantidad aproximada de ladrillos: {cantidad:.0f}")
        return cantidad
## 📘TEMA  _ ESTRUCTURA SELECTIVA
En el contexto de la programación, una estructura selectiva es aquella que permite tomar decisiones automáticas. Según si se cumple o no una condición, se ejecutarán diferentes bloques de código.
A diferencia de las estructuras selectivas que son esenciales en la programación procedimental, los objetos en la Programación Orientada a Objetos (POO) a menudo se basan en programas embebidos en las clases para controlar el flujo de ejecución.
Definición: Una estructura selectiva en POO en Python es la construcción de métodos que permiten ejecutar diferentes líneas de código o llamar varios procedimientos, dependiendo de si se cumple una o varias condiciones dadas.
Tipos de Estructura Selectiva
## 1. Estructura Selectiva Simple:##
Se ejecuta un bloque de código solo si se cumple la condición, en caso contrario, no hace nada.
Ejemplo:
if (x > 0):
    print("x es positivo")
## 2. Estructura Selectiva Doble:##
Permite dos ramas. Una si la condición es verdadera y otra si es falsa.
Ejemplo:
if (x % 2 == 0):
    print("x es un número par")
else:
    print("x es un número impar")

## 3. Estructura Selectiva Múltiple:##
Gestiona más de dos alternativas mutuamente exclusivas. Solo se ejecuta la primera condición verdadera.
Ejemplo:
if (x >= 90):
    print("Aprobado con distinción")
    ... (El ejemplo se corta aquí, pero la estructura completa sería con elif y else)
    if (x >= 90):
    print("Aprobado con distinción")
elif (x >= 70):
    print("Aprobado")
else:
    print("Reprobado")

  # =======================================
# 🧩 EJEMPLO 1 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Numero` |
# | **Atributos** | `valor` |
# | **Comportamiento (método)** | `clasificar()` |
# | **Objetos (instancias)** | `Numero(0)`, `Numero(2)`, `Numero(5)` |
# =======================================

class Numero:
    def __init__(self, valor):
        self.valor = valor

    def clasificar(self):
        if self.valor == 0:
            print(f"El número {self.valor} es **neutro**.")
        elif self.valor % 2 == 0:
            print(f"El número {self.valor} es **par**.")
        else:
            print(f"El número {self.valor} es **impar**.")


# =======================================
# 🧩 EJEMPLO 2 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Persona` |
# | **Atributos** | `nombre`, `edad` |
# | **Comportamiento (método)** | `es_mayor_de_edad()` |
# | **Objeto (instancia)** | `persona1 = Persona("María", 20)` |
# =======================================

class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def es_mayor_de_edad(self):
        if self.edad >= 18:
            print(f"{self.nombre} tiene {self.edad} años → Es **mayor de edad** ✅.")
        else:
            print(f"{self.nombre} tiene {self.edad} años → Es **menor de edad** ❌.")



# =======================================
# 🧩 EJEMPLO 3 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Empleado` |
# | **Atributos** | `nombre`, `cargo`, `sueldo` |
# | **Comportamiento (método)** | `aplicar_aumento()` |
# | **Objeto (instancia)** | `empleado1 = Empleado("Carlos", "Gerente", 2000)` |
# =======================================

class Empleado:
    def __init__(self, nombre, cargo, sueldo):
        self.nombre = nombre
        self.cargo = cargo
        self.sueldo = sueldo

    def aplicar_aumento(self):
        if self.cargo.lower() == "gerente":
            aumento = 0.10
        elif self.cargo.lower() == "supervisor":
            aumento = 0.07
        elif self.cargo.lower() == "operario":
            aumento = 0.05
        else:
            aumento = 0.03  # aumento general por defecto

        nuevo_sueldo = self.sueldo * (1 + aumento)
        print(f"{self.nombre} ({self.cargo}) → Sueldo anterior: {self.sueldo} | Nuevo sueldo: {nuevo_sueldo:.2f}")
        return nuevo_sueldo

# =======================================
# 🧩 EJEMPLO 4 - SIGNOS ZODIACALES 
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Zodiaco` |
# | **Atributos** | `dia`, `mes` |
# | **Comportamiento (método)** | `determinar_signo()` |
# | **Objetos (instancias)** | `Zodiaco(15, 5)` → Tauro |
# =======================================

class Zodiaco:
    def __init__(self, dia, mes):
        self.dia = dia
        self.mes = mes

    def determinar_signo(self):
        if (self.mes == 3 and self.dia >= 21) or (self.mes == 4 and self.dia <= 19):
            signo = "Aries ♈"
        elif (self.mes == 4 and self.dia >= 20) or (self.mes == 5 and self.dia <= 20):
            signo = "Tauro ♉"
        elif (self.mes == 5 and self.dia >= 21) or (self.mes == 6 and self.dia <= 20):
            signo = "Géminis ♊"
        elif (self.mes == 6 and self.dia >= 21) or (self.mes == 7 and self.dia <= 22):
            signo = "Cáncer ♋"
        elif (self.mes == 7 and self.dia >= 23) or (self.mes == 8 and self.dia <= 22):
            signo = "Leo ♌"
        elif (self.mes == 8 and self.dia >= 23) or (self.mes == 9 and self.dia <= 22):
            signo = "Virgo ♍"
        elif (self.mes == 9 and self.dia >= 23) or (self.mes == 10 and self.dia <= 22):
            signo = "Libra ♎"
        elif (self.mes == 10 and self.dia >= 23) or (self.mes == 11 and self.dia <= 21):
            signo = "Escorpio ♏"
        elif (self.mes == 11 and self.dia >= 22) or (self.mes == 12 and self.dia <= 21):
            signo = "Sagitario ♐"
        elif (self.mes == 12 and self.dia >= 22) or (self.mes == 1 and self.dia <= 19):
            signo = "Capricornio ♑"
        elif (self.mes == 1 and self.dia >= 20) or (self.mes == 2 and self.dia <= 18):
            signo = "Acuario ♒"
        elif (self.mes == 2 and self.dia >= 19) or (self.mes == 3 and self.dia <= 20):
            signo = "Piscis ♓"
        else:
            signo = "Fecha inválida ❌"

        print(f"Fecha: {self.dia}/{self.mes} → Signo zodiacal: {signo}")
        return signo

## 📘TEMA  _ ESTRUCTURA REPETITIVA
En Python, estas estructuras (también llamadas bucle o loops) repiten instrucciones que permiten ejecutar un bloque de código varias veces dependiendo de una condición o una secuencia de elementos. Las dos estructuras repetitivas en Python son:
## 1. while (mientras):
Ejecuta un bloque de código mientras una condición sea verdadera.
Ejemplo:
       contador = 0
while (contador < 5):
    print(contador)
    contador = contador + 1
## 2. for (para):
Se utiliza para iterar una secuencia (como una lista, tupla, string o rango de números).
Ejemplo:
      for i in range(5):
    print(i)
# =======================================
# 🧩 EJEMPLO 5 - FACTORIAL
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Factorial` |
# | **Atributos** | `numero`, `resultado` |
# | **Comportamiento (método)** | `calcular()` |
# | **Objeto (instancia)** | `factorial = Factorial(5)` |
# =======================================

class Factorial:
    def __init__(self, numero):
        self.numero = numero
        self.resultado = 1

    def calcular(self):
        if self.numero < 0:
            print("No existe el factorial de un número negativo ❌")
            return None
        elif self.numero == 0 or self.numero == 1:
            self.resultado = 1
        else:
            for i in range(1, self.numero + 1):
                self.resultado *= i

        print(f"El factorial de {self.numero} es: {self.resultado}")
        return self.resultado

# =======================================
# 🧩 EJEMPLO 6 - SERIE DE FIBONACCI
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Fibonacci` |
# | **Atributos** | `n` (número de términos) |
# | **Comportamiento (método)** | `generar_serie()` |
# | **Objeto (instancia)** | `miFibonacci = Fibonacci(10)` |
# =======================================

class Fibonacci:
    def __init__(self, n):
        self.n = n

    def generar_serie(self):
        serie = [0, 1]
        while len(serie) < self.n:
            serie.append(serie[-1] + serie[-2])
        print(f"Serie Fibonacci ({self.n} términos): {serie}")
        return serie


# =======================================
# 🧩 EJEMPLO 7 - TABLAS DE MULTIPLICAR
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `TablaMultiplicar` |
# | **Atributo** | `numero` |
# | **Comportamiento (método)** | `generar_tabla()` |
# | **Objeto (instancia)** | `tabla = TablaMultiplicar(9)` |
# =======================================

class TablaMultiplicar:
    def __init__(self, numero):
        self.numero = numero

    def generar_tabla(self):
        print(f"Tabla de multiplicar del {self.numero}:")
        for i in range(1, 11):
            print(f"{self.numero} x {i} = {self.numero * i}")


# =======================================
# 🧩 EJEMPLO 8 - SUMATORIA
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `SumaLista` |
# | **Atributo** | `lista` |
# | **Comportamiento (método)** | `calcular_suma()` |
# | **Objeto (instancia)** | `miSuma = SumaLista([4, 2, 3, 1, 10])` |
# =======================================

class SumaLista:
    def __init__(self, lista):
        self.lista = lista

    def calcular_suma(self):
        suma = sum(self.lista)
        print(f"Lista: {self.lista}")
        print(f"Suma total: {suma}")
        return suma


# =======================================
# 🧩 EJEMPLO 9 - ESTADÍSTICA
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Estadistica` |
# | **Atributo** | `numeros` |
# | **Comportamientos (métodos)** | `calcular_media()`, `calcular_mediana()`, `calcular_suma()` |
# | **Objeto (instancia)** | `miEstadistica = Estadistica([10, 20, 30, 40, 50])` |
# =======================================

import statistics

class Estadistica:
    def __init__(self, numeros):
        self.numeros = numeros

    def calcular_media(self):
        return statistics.mean(self.numeros)

    def calcular_mediana(self):
        return statistics.median(self.numeros)

    def calcular_suma(self):
        return sum(self.numeros)

    def mostrar_resultados(self):
        print(f"Números: {self.numeros}")
        print(f"Media: {self.calcular_media()}")
        print(f"Mediana: {self.calcular_mediana()}")
        print(f"Suma: {self.calcular_suma()}")

# =======================================
# 🧩 EJEMPLO 10 - INGRESO DE DATOS Y CÁLCULO
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase 1** | `Entrada` |
# | **Atributo** | `valor` |
# | **Comportamiento (método)** | `ingresar()` |
# | **Clase 2** | `Calculador` |
# | **Atributos** | `numeros` |
# | **Comportamientos (métodos)** | `calcular_media()`, `calcular_suma()` |
# | **Objeto (instancia)** | `dato1 = Entrada(Calculador)` |
# =======================================

class Calculador:
    def __init__(self, numeros):
        self.numeros = numeros

    def calcular_media(self):
        return sum(self.numeros) / len(self.numeros)

    def calcular_suma(self):
        return sum(self.numeros)

    def mostrar_resultados(self):
        print(f"Números: {self.numeros}")
        print(f"Suma: {self.calcular_suma()}")
        print(f"Media: {self.calcular_media():.2f}")


class Entrada:
    def __init__(self, calculador):
        self.calculador = calculador

    def ingresar(self):
        print("🔹 Ingreso de datos completado. Resultados:")
        self.calculador.mostrar_resultados()
# =======================================
# 🧩 EJEMPLO 9 - SERIE DE FIBONACCI
# =======================================
class Fibonacci:
    def __init__(self, cantidad):
        self.cantidad = cantidad
        self.a = 0
        self.b = 1
        self.contador = 0

    def generar_serie(self):
        print("Serie Fibonacci:")
        while self.contador < self.cantidad:
            print(self.a, end=" ")
            c = self.a + self.b
            self.a = self.b
            self.b = c
            self.contador += 1
        print()

miFibonacci = Fibonacci(10)
miFibonacci.generar_serie()


# =======================================
# 🧩 EJEMPLO 10 - TABLA DE MULTIPLICAR
# =======================================
class TablaMultiplicar:
    def __init__(self, numero):
        self.numero = numero

    def generar_tabla(self):
        print(f"\nTabla de multiplicar del {self.numero}")
        for i in range(1, 11):
            print(f"{self.numero} x {i} = {self.numero * i}")

tabla = TablaMultiplicar(9)
tabla.generar_tabla()


# =======================================
# 🧩 EJEMPLO 11 - SUMATORIA
# =======================================
class SumaLista:
    def __init__(self, lista):
        self.lista = lista

    def calcular_suma(self):
        print(f"La suma de {self.lista} es: {sum(self.lista)}")

miSuma = SumaLista([4, 2, 3, 1, 10])
miSuma.calcular_suma()


# =======================================
# 🧩 EJEMPLO 12 - ESTADÍSTICA
# =======================================
import statistics
class Estadistica:
    def __init__(self, numeros):
        self.numeros = numeros

    def mostrar_datos(self):
        media = statistics.mean(self.numeros)
        mediana = statistics.median(self.numeros)
        suma = sum(self.numeros)
        print(f"Números: {self.numeros}")
        print(f"Media: {media}, Mediana: {mediana}, Suma: {suma}")

miEstadistica = Estadistica([10, 20, 30, 40, 50])
miEstadistica.mostrar_datos()


# =======================================
# 🧩 EJEMPLO 13 - GESTOR DE TAREAS
# =======================================
class GestorDeTareas:
    def __init__(self):
        self.tareas = []

    def agregar_tarea(self, tarea):
        self.tareas.append(tarea)
        print(f"Tarea '{tarea}' agregada ✅")

    def eliminar_tarea(self, tarea):
        if tarea in self.tareas:
            self.tareas.remove(tarea)
            print(f"Tarea '{tarea}' eliminada ❌")
        else:
            print("La tarea no existe en la lista.")

    def mostrar_tareas(self):
        print("\n📋 Lista de tareas:")
        for i, tarea in enumerate(self.tareas, 1):
            print(f"{i}. {tarea}")

miGestor = GestorDeTareas()
miGestor.agregar_tarea("Estudiar Python")
miGestor.agregar_tarea("Hacer práctica de POO")
miGestor.mostrar_tareas()
miGestor.eliminar_tarea("Estudiar Python")
miGestor.mostrar_tareas()
## 📘TEMA  _ ENCAPSULAMIENTO
En Programación Orientada a Objetos (POO), el encapsulamiento es un principio que permite ocultar o resguardar la información interna de un objeto. Esto se consigue limitando el acceso directo a algunos de sus componentes, exponiendo solo la interfaz necesaria de métodos públicos (visibles).
Definición:
El encapsulamiento agrupa los datos (atributos) y las operaciones (métodos) que manipulan esos datos dentro de una clase. Su función principal es controlar y limitar el acceso y así proteger la estructura interna del objeto.
# Características:
-Ocultamiento de datos: Los atributos de una clase están usualmente declarados como privados, lo que impide que se acceda directamente a ellos desde fuera de la clase.
-Servicios (Métodos): Se utilizan métodos públicos (getters y setters) para permitir la lectura o escritura de los atributos si es necesario.
-Mejora de Seguridad y Mantenimiento: Al proteger los datos internos, se evita que el código externo pueda modificarlos de forma incorrecta o inesperada.
#Ventajas:
Protege la integridad de los datos.
Permite cambiar la implementación interna sin afectar el código externo.
Favorece el diseño modular y la reutilización de código.
⚙️ GETTERS Y SETTERS 
# Los métodos Getters y Setters permiten controlar el acceso a los
# atributos privados de una clase (encapsulamiento).

# 👉 Getter: obtiene (lee) el valor de un atributo.
# 👉 Setter: modifica (escribe) el valor de un atributo, aplicando validaciones si es necesario.

# BENEFICIOS:
# ✅ Evitan acceso directo a los atributos.
# ✅ Protegen los datos con validaciones.
# ✅ Mejoran la seguridad y mantenimiento del código.

# 🧩 EJEMPLO 1 - Cuenta Bancaria
class CuentaBancaria:
    def __init__(self, titular, saldo):
        self.titular = titular
        self.__saldo = saldo  # atributo encapsulado (privado)

    # Método para mostrar saldo
    def mostrar_saldo(self):
        print(f"💰 Saldo actual de {self.titular}: S/{self.__saldo}")

    # Método setter (modificar saldo)
    def depositar(self, monto):
        if monto > 0:
            self.__saldo += monto
            print(f"Depósito exitoso: +S/{monto}")
        else:
            print("❌ El monto debe ser positivo.")

    # Método para retirar
    def retirar(self, monto):
        if monto <= self.__saldo:
            self.__saldo -= monto
            print(f"Retiro exitoso: -S/{monto}")
        else:
            print("❌ Fondos insuficientes.")

# Crear objeto
cuenta1 = CuentaBancaria("Gleny", 500)
cuenta1.mostrar_saldo()
cuenta1.depositar(200)
cuenta1.retirar(100)
cuenta1.mostrar_saldo()

# Intentar acceder directamente (no recomendado)
# print(cuenta1.__saldo)  # ❌ Error: atributo privado


# 🧩 EJEMPLO 2 - Alumno (con Getters y Setters)
class Alumno:
    def __init__(self, nombre, nota):
        self.__nombre = nombre
        self.__nota = nota

    # Getter para nombre
    def get_nombre(self):
        return self.__nombre

    # Setter para nombre
    def set_nombre(self, nuevo_nombre):
        self.__nombre = nuevo_nombre

    # Getter para nota
    def get_nota(self):
        return self.__nota

    # Setter para nota con validación
    def set_nota(self, nueva_nota):
        if 0 <= nueva_nota <= 20:
            self.__nota = nueva_nota
        else:
            print("❌ La nota debe estar entre 0 y 20.")

    def mostrar_datos(self):
        print(f"👩‍🎓 Alumno: {self.__nombre} | Nota: {self.__nota}")

# Uso del encapsulamiento
alumno1 = Alumno("María", 18)
alumno1.mostrar_datos()

alumno1.set_nota(21)      # No permite valor inválido
alumno1.set_nota(15)
alumno1.set_nombre("Gleny")
alumno1.mostrar_datos()


# 🧩 EJEMPLO 3 - Producto con Descuento
class Producto:
    def __init__(self, nombre, precio):
        self.__nombre = nombre
        self.__precio = precio

    # Getter
    def get_precio(self):
        return self.__precio

    # Setter (con descuento)
    def aplicar_descuento(self, porcentaje):
        if 0 < porcentaje < 100:
            descuento = self.__precio * (porcentaje / 100)
            self.__precio -= descuento
            print(f"🛍️ Descuento aplicado: {porcentaje}% - Nuevo precio: S/{self.__precio:.2f}")
        else:
            print("❌ Porcentaje inválido.")

    def mostrar_producto(self):
        print(f"🧾 Producto: {self.__nombre} | Precio: S/{self.__precio:.2f}")

# Uso
producto1 = Producto("Perfume Yanbal", 120)
producto1.mostrar_producto()
producto1.aplicar_descuento(20)
producto1.mostrar_producto()


# 🧩 EJEMPLO 4 - Temperatura (controlada)
class Temperatura:
    def __init__(self):
        self.__celsius = 0

    # Getter
    def get_celsius(self):
        return self.__celsius

    # Setter con validación
    def set_celsius(self, valor):
        if valor < -273.15:
            print("❄️ Error: No puede ser menor que el cero absoluto (-273.15°C)")
        else:
            self.__celsius = valor

    # Conversión a Fahrenheit
    def a_fahrenheit(self):
        return (self.__celsius * 9/5) + 32

## 📘TEMA  _ METODOS Y SOBRECARGAS
# Los MÉTODOS son funciones que se definen dentro de una clase
# y describen los comportamientos o acciones de los objetos.
#
# Los métodos pueden recibir parámetros, devolver valores,
# y operar sobre los atributos de la clase.
# =======================================


# 🧩 EJEMPLO 1 - MÉTODOS BÁSICOS
# =======================================
# | Elemento | Descripción |
# |-----------|-------------|
# | **Clase** | `Persona` |
# | **Atributos** | `nombre` |
# | **Métodos** | `saludar()` |
# | **Objeto** | `persona1 = Persona("Carlos")` |
# =======================================

class Persona:
    def __init__(self, nombre):
        self.nombre = nombre
    
    def saludar(self):
        print(f"👋 Hola, soy {self.nombre}")

# Crear objeto
persona1 = Persona("Carlos")
persona1.saludar()


# 🧩 EJEMPLO 2 - MÉTODOS CON PARÁMETROS
# =======================================
# Los métodos pueden recibir datos externos al objeto.
# En todo método, el primer parámetro es `self`, que representa al objeto.
# =======================================

class Calculadora:
    def sumar(self, a, b):
        return a + b

# Crear objeto
calculadora1 = Calculadora()
print(f"🧮 La suma es: {calculadora1.sumar(4, 3)}")


# 🧩 RETORNO DE MÉTODOS
# =======================================
# El `return` permite devolver valores que pueden ser
# usados por otras partes del programa.
# =======================================

class Cuadrado:
    def __init__(self, lado):
        self.lado = lado

    def calcular_area(self):
        return self.lado * self.lado

figura = Cuadrado(5)
print(f"📏 El área del cuadrado es: {figura.calcular_area()}")


# 🧩 SOBRECARGA DE MÉTODOS

# La sobrecarga de métodos permite definir varios métodos con el mismo nombre
# pero con diferentes parámetros.
#
# En Python, no existe sobrecarga estricta como en Java o C++,
# pero se puede simular con valores predeterminados o *args.



# 🧩 EJEMPLO 3 - SOBRECARGA USANDO *args
class Operaciones:
    def sumar(self, *valores):
        if len(valores) == 2:
            return valores[0] + valores[1]
        elif len(valores) == 3:
            return valores[0] + valores[1] + valores[2]
        else:
            return "⚠️ Error: Cantidad de argumentos incorrecta."

# Uso
op = Operaciones()
print(f"Resultado (2 valores): {op.sumar(5, 7)}")
print(f"Resultado (3 valores): {op.sumar(2, 4, 6)}")


# 🧩 EJEMPLO 4 - CLASE RECTÁNGULO (con simulación de sobrecarga)
class Rectangulo:
    def __init__(self, base=None, altura=None):
        self.base = base
        self.altura = altura

    def calcular_area(self, lado=None):
        # Si recibe un argumento, se trata de un cuadrado
        if lado is not None:
            return lado * lado
        # Si tiene base y altura, se trata de un rectángulo
        elif self.base and self.altura:
            return self.base * self.altura
        else:
            return "❌ Datos insuficientes para calcular el área."

# Uso
r1 = Rectangulo(4, 5)
print(f"Rectángulo: Área = {r1.calcular_area()}")
r2 = Rectangulo()
print(f"Cuadrado: Área = {r2.calcular_area(10)}")


# 🧩 EJEMPLO 5 - CLASE CÍRCULO
import math
class Circulo:
    def __init__(self, radio):
        self.radio = radio
    
    def calcular_area(self):
        return math.pi * self.radio ** 2
    
    def calcular_perimetro(self):
        return 2 * math.pi * self.radio
    
    def mostrar_informacion(self):
        print(f"⚪ Radio: {self.radio}")
        print(f"Área: {self.calcular_area():.2f}")
        print(f"Perímetro: {self.calcular_perimetro():.2f}")

# Uso
c1 = Circulo(6)
c1.mostrar_informacion()


# 🧩 EJEMPLO 6 - CLASE TRIÁNGULO
import math
class Triangulo:
    def __init__(self, a, b):
        self.a = a
        self.b = b
    
    def calcular_hipotenusa(self):
        return math.sqrt(self.a ** 2 + self.b ** 2)
    
    def mostrar_informacion(self):
        print(f"🔺 Cateto a: {self.a}")
        print(f"Cateto b: {self.b}")
        print(f"Hipotenusa: {self.calcular_hipotenusa():.2f}")
## 📘TEMA  _ METODO OPERATIVO 
Un **método operativo** es una **función definida dentro de una clase** que realiza una acción o proceso específico sobre los **atributos del objeto** o los **parámetros externos** que recibe.

📘 En resumen:  
Un método operativo “**hace algo**” — calcula, imprime, suma, resta, muestra información, etc.
| Símbolo | Operador | Descripción |
|----------|-----------|-------------|
| `__str__` | `print()` | Mostrar información legible del objeto |
| `__eq__` | `==` | Comparar dos objetos |
| `__gt__` | `>` | Verificar si un objeto es mayor que otro |
| `__add__` | `+` | Sumar o combinar objetos |

## 🧠 Estructura General
class NombreClase:
    def __init__(self, atributos):
        self.atributo = atributos

    def metodo_operativo(self, parametros):
        return resultado
        
🧮 Ejemplo 1: Clase Calculadora
python
Copiar código
class Calculadora:
    def __init__(self):
        pass
 # Método operativo que suma dos números
    def sumar(self, a, b):
        return a + b
# Método operativo que multiplica dos números
    def multiplicar(self, a, b):
        return a * b

# #📏 Ejemplo 2: Clase Rectángulo
python
Copiar código
class Rectangulo:
    def __init__(self, base, altura):
        self.base = base
        self.altura = altura

    # Método operativo: calcula el área
    def calcular_area(self):
        return self.base * self.altura

    # Método operativo: calcula el perímetro
    def calcular_perimetro(self):
        return 2 * (self.base + self.altura)


# Uso
r1 = Rectangulo(4, 5)
print(f"📐 Área: {r1.calcular_area()}")
print(f"🔲 Perímetro: {r1.calcular_perimetro()}")
✅ Descripción:
Los métodos calcular_area() y calcular_perimetro() usan los atributos del objeto para realizar operaciones.

🏦 Ejemplo 3: Clase Banco (Depósitos y Retiros)
python
Copiar código
class Banco:
    def __init__(self, titular, saldo):
        self.titular = titular
        self.saldo = saldo
    def depositar(self, monto):
        self.saldo += monto
        print(f"💰 Depósito exitoso. Nuevo saldo: {self.saldo}")
    def retirar(self, monto):
        if monto <= self.saldo:
            self.saldo -= monto
            print(f"🏦 Retiro exitoso. Nuevo saldo: {self.saldo}")
        else:
            print("❌ Saldo insuficiente.")


# Uso
cuenta1 = Banco("Gleny", 500)
cuenta1.depositar(300)
cuenta1.retirar(200)
✅ Descripción:
Los métodos depositar() y retirar() son operativos porque ejecutan acciones concretas que modifican el estado del objeto.

⚗️ Ejemplo 4: Clase Persona (Método Operativo con Retorno)
python
Copiar código
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre

    def saludar(self):
        return f"Hola, soy {self.nombre}"


# Uso
persona1 = Persona("Carlos")
print(persona1.saludar())
✅ Explicación:
El método saludar() no necesita parámetros externos; actúa directamente sobre el atributo nombre.

💡 Ejemplo 5: Clase Calculadora con Encabezados
python
Copiar código
class Calculadora:
    def sumar(self, a, b):
        return a + b

calculadora1 = Calculadora()
print(f"La suma es: {calculadora1.sumar(4, 3)}")
✅ Nota:
Los métodos pueden recibir parámetros externos y siempre incluyen self como primer parámetro para representar al objeto mismo.

🌀 Ejemplo 6: Sobrecarga de Métodos
En Python, la sobrecarga no existe de forma estricta como en otros lenguajes (Java o C++),
pero se puede simular usando parámetros variables (*args o valores por defecto).

🔹 Ejemplo: Clase Operaciones
python
Copiar código
class Operaciones:
    def sumar(self, *valores):
        if len(valores) == 2:
            return valores[0] + valores[1]
        elif len(valores) == 3:
            return valores[0] + valores[1] + valores[2]
        else:
            return "Error: cantidad de argumentos incorrecta"

📐 Ejemplo 7: Clase Rectángulo (Área y Sobrecarga)
python
Copiar código
class Rectangulo:
    def __init__(self, base=0, altura=0):
        self.base = base
        self.altura = altura
    def calcular_area(self, lado=None):
        if lado is not None:
            return lado * lado
        else:
            return self.base * self.altura


🔵 Ejemplo 8: Clase Círculo
python
Copiar código
import math

class Circulo:
    def __init__(self, radio):
        self.radio = radio

    def calcular_area(self):
        return math.pi * self.radio ** 2

    def calcular_perimetro(self):
        return 2 * math.pi * self.radio

    def mostrar_informacion(self):
        print(f"🔵 Radio: {self.radio}")
        print(f"📏 Área: {self.calcular_area():.2f}")
        print(f"📏 Perímetro: {self.calcular_perimetro():.2f}")

🔺 Ejemplo 9: Clase Triángulo (Teorema de Pitágoras)
python
Copiar código
import math

class Triangulo:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def calcular_hipotenusa(self):
        return math.sqrt(self.a ** 2 + self.b ** 2)

    def mostrar_informacion(self):
        print(f"Cateto a: {self.a}")
        print(f"Cateto b: {self.b}")
        print(f"Hipotenusa: {self.calcular_hipotenusa():.2f}")



## 📘TEMA  _ CONSTRUIR Y DESTRUIR
 **CONSTRUCTOR**

Un **constructor** es un método especial que se ejecuta **automáticamente** al **crear** (instanciar) un objeto de una clase.  
Se utiliza para **inicializar los atributos** del objeto.

### 🔹 Sintaxis:
def __init__(self, ...):
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
        print(f"Se ha creado a {self.nombre}, de {self.edad} años.")

class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
        print(f"Se ha creado a {self.nombre}, de {self.edad} años.")
persona1 = Persona("Gleny", 20)

### 🔹 DESTRUCTOR:

El destructor es un método especial que se ejecuta automáticamente cuando un objeto está a punto de ser eliminado o ya no se usa más.
Sirve para liberar recursos o mostrar mensajes antes de la eliminación.
SINTAXIS
def __del__(self):
    # Código de limpieza o mensaje final
EJEMPLO
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre
        print(f"El objeto {self.nombre} ha sido creado.")

    def __del__(self):
        print(f"El objeto {self.nombre} fue eliminado.")

# Crear y eliminar objeto
persona1 = Persona("Carlos")
del persona1
🔄 CICLO DE VIDA DE UN OBJETO

El ciclo de vida de un objeto describe las etapas que atraviesa un objeto desde su creación hasta su destrucción.

Etapa	Descripción	Método Relacionado
🧱 Creación	El objeto se construye e inicializa.	__init__()
⚙️ Uso	Se ejecutan métodos y se accede a los atributos.	Métodos definidos en la clase
🧹 Destrucción	El objeto se elimina de la memoria.	__del__()
🔹 Ejemplo Completo del Ciclo de Vida
class EjemploCiclo:
    def __init__(self, nombre):
        self.nombre = nombre
        print(f"🧱 Objeto '{self.nombre}' creado.")

    def usar(self):
        print(f"⚙️ Usando el objeto '{self.nombre}'.")

    def __del__(self):
        print(f"🧹 Objeto '{self.nombre}' destruido.")

# Ciclo de vida
objeto = EjemploCiclo("Prueba")
objeto.usar()
del objeto


✅ Salida esperada:

🧱 Objeto 'Prueba' creado.
⚙️ Usando el objeto 'Prueba'.
🧹 Objeto 'Prueba' destruido.


## 📘TEMA  _ Relaciones entre Clases
En la Programación Orientada a Objetos en Python, las relaciones permiten modelar cómo los objetos interactúan entre sí en un sistema. Existen 3 relaciones fundamentales que indican cómo una clase puede relacionarse con otra:
1. AGREGACIÓN
Es una relación general entre dos clases, donde una utiliza a otra. Esta relación no implica propiedad o dependencia fuerte.
CARACTERÍSTICAS:
 * Los objetos están relacionados pero son independientes.
 * Puede ser unidireccional o bidireccional.
 * Se basa en el uso de instancias de otra clase.
2. COMPOSICIÓN
La agregación es un tipo especial de relación de todo-parte, donde una clase (el todo) contiene a las partes (la parte), pero las partes pueden existir independientemente del todo.
CARACTERÍSTICAS:
 * Relación tiene un (has-a).
 * El objeto contenido no es destruido si el objeto contenedor desaparece.
 * Los objetos se pueden reutilizar en otras partes.
3. COMPOSICIÓN:
Es un caso más fuerte que la agregación. También es una relación (todo-parte) pero con propiedad total y dependencia de ciclo de vida. Si el objeto contenedor se destruye, las partes también.
CARACTERÍSTICAS:
 * Relación fuerte de pertenencia.
 * Se crean y destruyen con el objeto contenedor.
















=================================================================
    ## UNIDAD II ##
=================================================================
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


