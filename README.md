# 🧠 Cuaderno Virtual – Lenguaje de Programación

**Nombre:** Gleny Angélica Condori Mamani  
**Facultad:** Ingeniería Estadística e Informática  
**Universidad:** Universidad Nacional del Altiplano – Puno  
**Curso:** Lenguaje de Programación (Python)  
**Docente:** Leonel  
## 📘TEMA 1 _ PROGRAMACION ORIENTADA A OBJETOS
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

## 🧩 EJEMPLO 1 
| Elemento | Descripción |
|-----------|-------------|
| **Clase** | `Coche` |
| **Atributos** | `marca`, `modelo`, `color` |
| **Comportamientos (métodos)** | `arrancar()`, `acelerar()`, `frenar()` |
| **Objeto (instancia)** | `toyoto = Coche("Toyota", "Corolla", "Blanco")` |


### 💻 Código en Python
class Coche:
    # Constructor: define los atributos del coche
    def __init__(self, marca, modelo, color):
        self.marca = marca
        self.modelo = modelo
        self.color = color
        print(f"Se ha creado un coche {self.marca} {self.modelo} de color {self.color}.")

    # Métodos (comportamientos)
    def arrancar(self):
        print(f"El {self.marca} {self.modelo} ha arrancado.")

    def acelerar(self):
        print(f"El {self.marca} {self.modelo} está acelerando... ¡Vruum!")

    def frenar(self):
        print(f"El {self.marca} {self.modelo} está frenando.")

    # Destructor (opcional)
    def __del__(self):
        print(f"El coche {self.marca} {self.modelo} ha sido eliminado.")


# Creación del objeto
toyoto = Coche("Toyota", "Corolla", "Blanco")

# Acciones del objeto
toyoto.arrancar()
toyoto.acelerar()
toyoto.frenar()

## 🧩 EJEMPLO 2
