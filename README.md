# Coding-Guidelines

Identacion:
    La identación es muy importante para la legibilidad del código. A pesar de la existencia de lenguajes que permiten "errores" de identación, esta en una muy mala praxis, ya que empeora el entendimiento del codigo y conlleva a una muy mala experiencia a la hora de solucionar bugs.

Nombrar variables/funciones:
    Darle un nombre descriptivo a todas nuestras variables puede resultar un tanto laborioso, pero vale totalmente la pena. Cuando nuestras variables tienen nombre que describen adecuadamente su funcionalidad nos ahorraremos bastante tiempo cuando tengamos que volver a ellas para solucionar algún problema que nos hayamos encontrado posteriormente.

Comentar el codigo:
    Comentar la funcionalidad de los bloques de codigo resulta un una muy buena experiencia para los futuros programadores que se una al proyecto. Además, para los mismos desarrolladores que crearon esos bloques de codigo, les servira para saver como funciona exactamente esa codigo si lelvan bastante tiempo sin visitarlo, incluso para la implementacion de actualizacines de las diferentes librerias que componen el proyecto.

Variables globales:
    Las variables globales ayudan a agiliazar la programación ademas de que evitan la creación de multiples variables que pueden ser totalmente innecesarias. También, nos podemos ahorrar pasarle variables a nuestros metodos con las variables globales. Pero, el abusar de estas puede resultar en el mal funcionamiento del programa, si utilizamos estas variables en el orden erroneo el programa nos puede devolver un resultado totalmente erroneo.

Evitar anidaciones y reducir el uso de else:
    Anidar varios condicionales reduce la legibilidad del codigo, ademas de que muchas veces resultan ser de poca utilidad. Esto tambien se aplica a la premisa 'else', hay muchos casos en los que incluir un else no te lleva a nada, ya que si el 'if' tiene un return entonces el 'else' se ejecutara solo cuando no entre en el if, y si no utilizamos esta premisa y solo ponemos el codigo que estaría dentro, tendriamos el mismo resultado.
    
uso de try-catch:
    El uso de try and catch nos ayudara a identificar los distintos tipos de errores que se puedan producir en un bloque de codigo, además, nos permitirá un manejo de errores muy completo.