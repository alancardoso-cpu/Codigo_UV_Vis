# 

instrucciones: 

Para que el notebook funcione bien los archivos deben venir el formato ".txt" y con numero secuanciado.
el rango esta definivo con base al numero de archivos que tengas:
ejemplo si tienes nombre1.txt ... mombre 10.txt, ences el rango seria
range(1,11) esto porque empieza en 1 y termina en 10. ya que no se lee el 11.

Despues defines los datos experimentales de tu experimento(En Grafica_lineal Son los mismos datos que se requieren en Grafica_modular, pero se definen de forma directa (sin el self.)):

En Grafica_modular:
self.m es la masa del catalizador(g), self.M es la masa del catalizador(g),self.masa_molar_catalizador, es la masa_molar_catalizador, self.masa_molar_contaminante es la masa del contaminate, y self.T es la temperatura en la que hisiste el experimento(k).

Despues defines los datos de la grafica UV-Vis, tales como 
self.valores_primera = [] y self.valores_ultima = [] endonde defines sobre que linea y en que valores se colocaran las lineas punteadas al graficar.

self.lambda_objetivo = en donde defines el valor de longitud de onda el cual se usara para hacer los calculos cataliticos.

Finalmente se edita las flechas y sus etiquetas en la seccion de "graficar UVVis(si estan en Graficar_modular) o ". en donde uno define manaulmente el timepo y porcentaje que se degrado.

Con 



