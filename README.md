# Analisis-Mortalidad(Borrador de Proyecto)
Este repositorio está pensado para el análisis de los datos de mortalidad en el MINSA, este trabajo es de interes de el departamento de Vigilancia de la Salud por lo cual se cuenta con el apoyo del mismo en la creación del paquete, para este trabajo la división de Vigilancia nos proporciono con una guía básica de funciones y datos necesarios para la creación de tales bases, y en el caso de la Base de Datos de mortalidad nos proporciono la estructura y un ejemplo de la base de datos para trabajar las funciones. 

Es necesario mencionar que no se manejan las bases de datos reales de mortalidad, ya que debido a la sensibilidad de la información(se trabajan con nombres y cédulas) la información es confidencial y no se puede trabajar directamente con estas bases de datos. Sin embargo se trabaja en conjunto con el Ministerio para asegurarse de que los resultados de la base son validos.

# Objetivos del Proyecto
## Objetivos General 
 * Mejorar la capacidad de analisis de datos del Ministerio de Salud
## Objetivos Especificos
  * Montar una base de diccionarios con las cuales se puedan generar los análisis de mortalidad 
  * Generar una base de población con base en la página de [consulta de población del INEC]( http://www.inec.go.cr/proyeccionpoblacion)
  * Crear funciones que generen de manera automática
    * Bases de datos de mortalidad con base a algunos parámetros predefinidos
    * Gráficos y cuadros para un análisis rápido  
    * Fuciones de consulta
  * Guia para el correcto uso de la base de datos 
  
# Metodología

El proyecto va a desarrollarse de la siguiente manera: 

1. Identificar los métodos para calcular las tasas de mortalidad y cualquier tipo método intermedio para el calculo
2. Hacer un listado de la disponiblidad de las bases de datos y de las caracteristicas de cada una de estas bases, así como cualquier tratamiento que deba realizarse previo a los cálculos.
3. Crear a partir de la información disponible cualquier base de datos adicional(por ejemlplo los diccionarios)
4. Crear las funciones necesarias para los cálculos de tasas de mortalidad.
5. Crear Scripts básicos para hacer un análisis de los datos de Mortalidad. 


# Utilidades del Proyecto
Es claro que le proyecto tiene un interes de parte del ministerio de salud porque le permitiria a la institución una mejora en los tiempos de creación de ciertos boletines epidemiológicos y facilitaría el análisis. Pero más allá de las utilidades que tiene para la institución, la idea de este proyecto es que pueda ser utilizado por cualquier estudiante o facultad para el análisis de la mortalidad en el país. En la buena teoría el proyecto permitira a los potenciales investigadores generar un código sin la necesidad del MINSA y entregarlo para obtener tablas de mortalidad.

Es claro que este paquete va a tener limitantes debido a que no todos los investigadores ocupan los mismos análisis, sin embargo el proyecto no se va a cerrar con la entrega del paquete, sino que se espera que haya una mejora continua del mismo mediante las peticiones de funciones y demás.

