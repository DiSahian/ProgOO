
# Tarea Unidad1




## El paradigma OO
En el contexto de los lenguajes de programación, un paradigma es un enfoque o modelo que se utiliza para diseñar y escribir programas de computadora. Cada paradigma tiene sus propias reglas y técnicas específicas para la solución de problemas, que pueden afectar la forma en que se escribe el código, se estructura y se organiza.

Hay varios paradigmas comunes en los lenguajes de programación, que incluyen:

    1.Programación estructurada: se centra en el uso de estructuras de control, como bucles y condicionales, para construir programas.
    2.Programación orientada a objetos: se enfoca en la creación de objetos que tienen propiedades y métodos para interactuar entre sí.
    3.Programación funcional: se basa en funciones puras que no tienen efectos secundarios y se utilizan para resolver problemas mediante la composición y la aplicación de funciones.
    4.Programación lógica: se utiliza para resolver problemas mediante la definición de hechos y reglas, y la creación de consultas para deducir nuevas conclusiones.
    
    
## Programación Orientada a Objetos
La programación orientada a objetos (POO) es un paradigma de programación que se basa en el concepto de objetos, que son entidades que combinan datos y comportamiento en una sola unidad. Cada objeto es una instancia de una clase, que define las propiedades y métodos que los objetos pueden tener.

En la POO, el foco está en el diseño de clases y objetos, y cómo se relacionan entre sí para resolver un problema. El diseño se basa en la identificación de los objetos relevantes en el sistema y cómo interactúan para realizar una tarea.

El primer lenguaje de programación orientado a objetos fue Simula, desarrollado por los científicos noruegos Ole-Johan Dahl y Kristen Nygaard en la década de 1960. El objetivo original de Simula era simular sistemas complejos, como procesos empresariales y de fabricación, y fue el primer lenguaje en introducir el concepto de objetos.

Dahl y Nygaard propusieron la idea de la programación orientada a objetos en un artículo de 1967 titulado "Simula: An Algol-Based Simulation Language". En este artículo, describieron cómo la programación orientada a objetos podía ser utilizada para modelar sistemas en los que las entidades podían ser vistas como objetos y cómo podían interactuar entre sí.


## Abstracción
La abstracción es lo que nos permite ir de lo complejo a algo simple, por ejemplo nosotros como estudiantes de POO debemos aprender a identificar las características de un objeto para poder crear sus clases y definir sus atributos, en el ejemplo que se vio de la bicicleta color, marca, cambio de velocidades y velocidad actual.

La abstracción es una técnica clave en la programación orientada a objetos que ayuda a simplificar entidades complejas y a separar la funcionalidad principal del detalle de implementación.


## Encapsulamiento

![maxresdefault](https://user-images.githubusercontent.com/124094435/225528162-d3672304-9d4e-4f38-baf4-e7577a9628cb.jpg)
El encapsulamiento es un concepto clave en la programación orientada a objetos que se refiere a la capacidad de una clase de ocultar su complejidad interna y proteger sus datos y comportamientos de ser accedidos o modificados por código externo no autorizado

Existen tres niveles de acceso para el encapsulamiento, los cuales son:


    Público (Public): Todos pueden acceder a los datos o métodos de una clase que se definen con este nivel, este es el nivel más bajo, esto es lo que tu quieres que la parte externa vea.
    Protegido (Protected): Podemos decir que estás no son de acceso público, solamente son accesibles dentro de su clase y por subclases.
    Privado (Private): En este nivel se puede declarar miembros accesibles sólo para la propia clase.

** _ _Ejemplo de código SIN ENCAPSULAMIENTO _ _**

![classjava](https://user-images.githubusercontent.com/124094435/225528518-26ab9134-ff6b-43bd-ba52-9a3bd59c8b86.png)
![main](https://user-images.githubusercontent.com/124094435/225529788-fb66e9ad-0529-4938-b194-704d5c47663e.png)


** _ _Ejemplo de código CON ENCAPSULAMIENTO_ _**

![encapsulamientojava](https://user-images.githubusercontent.com/124094435/225529964-5beeabb9-0437-49c0-993d-5f24c3db863f.png)
![main2](https://user-images.githubusercontent.com/124094435/225529976-a0d71e2c-af57-437d-80c0-cb98d9b57a51.png)

Entre sus ventajas tenemos a la ocultación de datos, flexibilidad, reutilización y código más fácil de probar.Al no existir un encapsulamiento los atributos pueden tomar valores inconsistentes, lo cual seria fatal para cualquier sistema. El encapsulamiento nos ayuda a proteger la integridad de los datos y nos asegura que los atributos de nuestra clase solo podran ser accedidos a traves de los metodos definidos en dicha clase. 


## Herencia
La herencia se refiere a la capacidad de una clase de heredar los atributos y métodos de otra clase (clase padre) para evitar la redundancia de código y permitir la reutilización de código.

En la herencia, la clase hija extiende o especializa la clase padre, lo que significa que la clase hija puede añadir nuevos atributos y métodos, o modificar o anular los existentes.


## UML
El Lenguaje de Modelado Unificado (UML, por sus siglas en inglés) es un lenguaje gráfico de modelado de software que fue desarrollado en la década de 1990 por un grupo de expertos en software liderado por Grady Booch, James Rumbaugh e Ivar Jacobson.

UML se utiliza para modelar, diseñar y documentar sistemas de software complejos, incluyendo sistemas de información, sistemas de control de procesos y sistemas de tiempo real. Se utiliza en una amplia variedad de industrias, como la informática, la ingeniería de software, la telecomunicación, la aeronáutica, la medicina y la banca.

UML se ha convertido en un estándar de facto en la industria del software y es ampliamente utilizado en años recientes. Una de sus características más utilizadas es el Diagrama de Clases, que representa las clases del sistema, sus atributos y métodos, y las relaciones entre ellas, como la herencia y la asociación.

Existen varias herramientas para el modelado en UML, tanto comerciales como de código abierto, entre las que se incluyen:

    Diagrams
    StarUML
    LucidChart
    Draw.io
    Canva
    Modelio
    UML Designer
    Entre otros

En resumen, UML es un lenguaje gráfico de modelado de software desarrollado por Booch, Rumbaugh y Jacobson que se utiliza para modelar, diseñar y documentar sistemas de software complejos. Es ampliamente utilizado en la industria del software y su Diagrama de Clases es una de sus características más populares. Hay varias herramientas para el modelado en UML disponibles en la actualidad.
