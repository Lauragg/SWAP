# Tema 4: Ejercicio 1

**GitHub:** Lauragg

**Buscar información sobre cuánto costaría en la actualidad un mainframe que tuviera las mismas prestaciones que una granja web con balanceo de carga y 10 servidores finales. Se deja a vuestra elección la capacidad de cómputo del mainframe. Por ejemplo, 10 Raspberry Pi 4 frente a un mainframe.**

**Comparar precio y potencia entre esa hipotética máquina y la granja web de unas prestaciones similares.**

## Granja web con balanceador de carga.
Vamos a seguir el ejemplo que nos ofrece el ejercicio y vamos a tomar como ejemplo 10 *Raspberry Pi 4 Model B*. Para ello, comenzamos viendo el precio de estas y sus prestaciones. Para que nos salga un poco más barata la hipotética compra, nos vamos a ir a la página oficial de Raspberry, seleccionamos el modelo con 4GB de RAM, país España y compra para negocios. Esto nos lleva a elegir entre dos distribuidores y por la ley del primer click aleatorio nos quedamos con [*farnell*](https://es.farnell.com/raspberry-pi/rpi4-modbp-2gb/raspberry-pi-4-model-b-2gb/dp/3051886).

Bajo estas consideraciones, cada raspberry nos costaría 49.64€, haciendo un total de 496.40€ por las diez. Mirando la hoja de datos técnicos que viene en la misma página, sabemos que cada dispositivo tiene las siguientes especificaciones:

+ **Procesador:** Broadcom BCM2711, quad-core Cortex-A72 (ARM v8)  64-bit SoC @ 1.5GHz
+ **RAM:** 4GB LPDDR4

Mirando las diapositivas de la asignatura, consideramos que el balanceador de carga Barracuda Model 240 con un soporte para 10 servidores y un rendimiento máximo de 95Mbps podría ser una buena opción con sus $1,424, o 1313.66€.

Sumando, obtendríamos un coste mínimo de 1,810.06€ por la opción de la granja web con un balanceador de carga.

## Mainframe

Tras una larga búsqueda, nos encontramos con que las páginas oficiales no nos ofrecen un precio directamente en sus webs para sus productos y que nos piden que contactemos con ellos para ofrecernos un servicio personalizado para nuestra compra, como es el caso de IBM sin ir más lejos. Esto hace que tengamos que recurrir a otras webs no tan confiables para obtener la información deseada.

En este caso, hemos recurrido al siguiente [blog](https://blog.mainframe.dev/2019/05/buying-ibm-mainframe.html) de Christian Svensson redactado el 18 de Mayo de 2019, en el cual nos narra su experiencia comprando un mainframe de IBM para uso personal.

Nos cuenta que en su caso compró una *IBM 2818-M05 z114* a un precio de $12,000, o 11,080.02€, y con unas características de:

+ 14 microprocesadores a 3.8GHz
+ 10 módulos de 4GB de RAM

## Comparaciones finales

Esto hace que, partiendo de memorias RAM equivalentes, tendríamos de costes mínimos 11,080.02€ en un mainframe contra los 1,810.06€ de nuestra granja web.

Nos encontramos con que el mainframe dispondría de procesadores de mayor calidad y también dispondría de un mayor rendimiento máximo que nuestro balanceador de carga seleccionado.

La pregunta es, ¿merece la pena pagar tanto dinero extra? Personalmente, opino que no puesto que recordemos que estamos hablando de precios mínimos y que ambas opciones requerirían comprar más materiales sin contar precios de transporte para obtenerlos, que en cuanto a la granja web sería un coste mucho menor por requerir materiales menos pesados. Entre estas y otras consideraciones, quizás nos merezca más la pena comprar alguna que otra raspberry más, en caso de ser necesaria, y mantener la granja web a un coste mucho menor.
