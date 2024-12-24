El dataset Acuario incorpora datos relacionados con varias especies de peces
(tanto de agua dulce como de agua salada) y sus características. Este
conjunto de datos está diseñado para poder alimentar en un acuario a los
peces de las distintas especies en proporción a su peso. Las columnas del
dataset son:
• Especie: esta columna representa las especies de peces. Donde cada
número corresponde a:
 0: Besugo.
 1: Perca.
 2: Rutilo.
 3: Lucio.
 4: Eperlano.
 5: Bagre.
 6: Corégono.
• Peso: Esta columna es el objetivo y representa el peso del pez. Es una
variable numérica que se mide en gramos. Conociendo el peso de un
pez y su especie, podremos calcular la cantidad de comida que necesita.
• Long_vert: Esta columna representa la longitud (vertical) del pez. Es
una variable numérica, medida en centímetros.
• Long_diag: longitud diagonal del pez. Es otra variable numérica
medida en centímetros.
• Long_tras: longitud trasversal del pez. Al igual que las dos columnas
anteriores, es una variable numérica, medida en centímetros.
• Altura: Esta columna representa la altura del pez. Es una variable
numérica, medida en centímetros.
• Ancho: Esta columna representa el ancho (en diagonal) del pez. Al
igual que las demás variables numéricas, también suele medirse en
centímetros.
El conjunto de datos está estructurado de tal manera que cada fila
corresponde a un solo pez con su especie y varias medidas físicas (longitudes).
El objetivo es usar algún estimador de regresión para construir un modelo
predictivo que pueda estimar el peso de un pez en función de su especie y las
medidas físicas proporcionadas. 
