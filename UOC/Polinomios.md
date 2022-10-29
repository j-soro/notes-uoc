# Polinomios

## Definición y aspectos generales

### Definición
Un polinomio de una sola variable o, para abreviar, un **polinomio**, es una expresión algebraica con una única letra, llamada variable. Los términos de esta expresión son el producto de un número por una potencia positiva de la variable, excepto en el caso de un único término, que corresponde a la potencia 0 de la variable.

Los polinomios pueden designarse mediante una letra. De este modo se evita escribir todos lso términos de un polinomio cada vez que quire hacerse referencia a este. Esta letra va seguida de la variable, entre paréntesis, del polinomio. Estos paréntesis no tienen que confundirse con los paréntesis que contienen operaciones.

$$p(x) = 5x^3 - 4x^2 + 5x - 1$$
donde $p$ representa el nombre del polinomio, y $x$ entre paréntesis indica la variable del polinomio.

Esta asignación permite referirnos al polinomio $p(x)$ sin necesidad de escribir todos los términos que lo definen. Cabe decir que la variable más usada para expresar polinomios es la $x$. Se trata de una costumbre, por lo que no tiene que considerarse una obligación.

### Elementos y características de un polinomio
Como ya se ha dicho, por **término de un polinomio** se entienden los diferentes elementos de un polinomio (así como cualquier expresión algebraica) que son producto de un coeficiente y una potencia de la variable.

Los tipos de polinomios se distinguen seguún el número de términos que presentan. En particular:
+ Un polinomio con un sólo término se denomina **monomio**.
+ Un polinomio con dos términos se denomina **binomio**.
+ Un polinomio con tres términos se denomina **trinomio**

Los polinomios y sus términos presentan características que es preciso distinguir. Estas características son las siguientes:
+ El **grado** de un término es el exponente de la variable de este término.
+ El **grado del polinomio** es el grado del término de grado máximo. Así, hay polinomios de grado 0, de grado 1 o de primer grado, de grado 2 o de segundo grado, etc. Generalmente, los términos de un polinomio se escriben de izquierda a derecha de mayor a menor grado.
+ El **término independiente** es el término de grado 0 y, por lo tanto, no aparece en la variable.
+ El **coeficiente de un término** es el número que multiplica la variable en este término. El resto del término se denomina **parte literal**.

> **Ejemplo**. Características de un polinomio.
> Sea el polinomio $p(x) = 9x^6 - 3x*4 + x -6$.
> 
> + El término de grado $6$ es $9x^6$, el término de grado $4$ es $-3x^4$, el término de grado $1$ es $x$, y el término independiente es $-6$. Los términos correspondientes a los grados que no aparecen son iguales a $0$.
> + El grado del polinomio es, por lo tanto, $6$.
> + El coeficiente del término de grado $6$ es $9$, y su parte literal es $x^6$.
> + El coeficiente del término de grado $4$ (o, para abreviar, coeficiente de grado $4$) es $-3$, y su parte literal es $x^4$.
> + El coeficiente de grado $1$ es $1$, y su parte literal $x$.
> + Los coeficientes de los otros términos son $0$.

### Valor numérico de un polinomio
El **valor numérico** de un polinomo es el valor que se obtiene al sustituir la variable por un número determinado.

$$p(x)=5x^3-4x^2+5x-1$$ $$p(1) = 5·1^3-4·1^2+5·1-1=5$$
## Operaciones y propiedades básicas
### Operaciones básicas entre monomios
Es importante saber cómo se hacen las operaciones entre monomios porque sirven de base para entender las operaciones entre polinomios. Veamos pues, cómo se operan los monomios.

#### Suma y resta
La suma (o resta) de dos monomios de grado diferente es un binomio en el que los dos únicos términos son exactamente estos dos monomios. Por ejemplo, la suma de los monomios $3x^2$ y $2x$, que se representa por ($3x^2$) + ($2x$), es igual al binomio $3x^4 +2x$.

La suma (o resta) de dos monomios del mismo grado es otro monomio con idéntico grado, y con coeficiente igual a la suma (o resta) de los coeficientes de estos monomios. Por ejemplo, la resta de $5x^3$ y $2x^3$, que se representa por ($5x^3$)-($2x^3$), es igual al monomio $3x^3$.

#### Producto
El producto de dos monomios es otro monomio. Su coeficiente es el producto de los coeficientes de los monomios que se multiplican,  su grado es la suma de grados de los monomios iniciales. Por ejemplo, el producto de los monomios $4x^3$ y $-5x^2$, que se representa por ($4x^3$).($-5x^2$), es $-20x^5$, puesto que $4·(-5)=-20$ y $x^3·x^2=x^{3+2}=x^5$.

#### Cociente
El cociente de dos monomios es otro monomio. Su coeficiente es el producto de los coeficientes de los monomios que se multiplican, y su grado es la suma de grados de los monomios iniciales. En este caso, el grado del numerador no puede ser inferior al grado del denominador. Por ejemplo, el cociente de los monomios $8x^4$ y $2x^3$, que se representa por $\frac{8x^4}{2x^3}$, es el monomio $4x$, puesto que $\frac{8}{2} = 4$ y $\frac{x^4}{x^3} = x^{4-3}=x^1$.

### Operaciones básicas entre polinomios
Visto como se operan los monomios, estudiemos las operaciones básicas entre polinomios.

### Suma y resta de polinomios
La suma (o resta) de dos polinomios es igual al polinomio resultante de la suma (o resta) de los términos que tienen el mismo grado. Cada término resultante corresponde a la suma de los términos del mismo grado de los polinomios que se suman (o restan). De acuerdo con la suma.


> **Ejemplo**. Suma de polinomios
> $$(2x^3-3x^2+4x-6)-(5x^4-2x^3-5x^2-3x+16)$$
> $$-5x^4 +4x^3 +2x^2 +7x -22$$

#### Producto de polinomios
1) Se sitúan los dos polinomios en columna, uno sobre el otro, y se multiplica cada término del segundo polinomio por cada uno de los términos del primer polinomio.
2) El resultado del paso anterior se pone en la fila siguiente, debajo de una línea horizontal. Como en el caso de la suma, es recomendable que todos los términos del mismo grado queden en una misma columna.
3) Finalmente, se suman los términos de cada columna.

#### Cociente de polinomios

1) El primer paso consiste en dividir el término de mayor grado del diviendo, $6x^4$ en este caso, entre el término de mayor grado del divisor, $2x^2$, de forma que queda una división entre monomios.
   
   $$\frac{6x^4}{2x^2}=3x^{4-2}=3x^2$$
2) A continuación se multiplica el divisor por el monomio obtenido,
   $$(2x^2 -3x + 4)·3x^2=6x^4-9x^3+12x^2$$
   y se resta del dividendo.  
   
3) Hecha la resta, se baja el término siguiente del dividendo, en este caso 0 (dado que no hay término de primer grado), y se divide, siguiendo el procedimiento anterior, entre lo que ha quedado como dividendo y el divisor.   
4) Se sigue este procedimiento sucesivamente hasta bajar el último elemento del polinomio dividendo. En el caso del ejemplo, la división completa se escribiría de la manera:
   
   ![[IMI - Cociente de polinomios.png]]
En este caso, diremos que la división es exacta porque el residuo es $0$. Si el residuo es 0, se cumple
$$\frac{6x^4-27x^3+15x^2-48}{2x^2-3x+4}=3x^2-9x-12$$
En casos como este, cuando el residuo de la división es $0$, se dice que el polinomio dividendo, en este caso $6x^4-27x^3+15x^2-48$, es divisible entre el polinomio divisor, y, de forma equivalente, que el polinomio dividendo, es múltiplo del polinomio divisor.

Otra manera de expresarlo es decir que el polinomio dividendo se descompone en los polinomios divisor y cociente. Esto significa que el polinomio dividendo es producto de los polinomios divisor y cociente de la división.

En casos en que el polinomio dividendo no es múltiplo del polinomio divisor, hecha la división, también puede expresarse la descomposición del polinomio dividendo como el producto de los polinomios divisor y cociente, más el polinomio residuo. La siguiente fórmula aprendida en la división de números también se aplica a la división de polinomios

$$D = d·q+r$$
#### Fracciones algebraicas
Una **fracción algebraica** es simplemente una fracción entre polinomios.

Del mismo modo que se han definido fracciones numéricas equivalentes, también se pueden definir las **fracciones algebraicas equivalentes**. Concretamente, si $a(x),b(x),p(x)$ y $q(x)$ son polinomios, diremos que las fracciones algebraicas $\frac{a(x)}{b(x)}$ y $\frac{p(x)}{q(x)}$ son equivalentes si el producto cruzado entre numeradores y denominadores es igual.

$$\frac{a(x)}{b(x)}=\frac{p(x)}{q(x)}\text{ si } a(x)·q(x)=b(x)p(x)$$

##### Propiedades de las fracciones algebraicas
Al igual que en el caso de los números fraccionarios, las fracciones algebracias verifican estas propiedades:
+ Al multiplicar numerador y denominador por un mismo polinomio, la fracción resultante es equivalente a la inicial.
+ Al dividir de manera exacta numerador y denominador por un mismo polinomio, la fracción resultante es equivalente a la inicial. Este proceso se denomina simplificación.

> **Ejemplo**. Simplificar fracciones algebraicas
> Dada la fracción algebraica
> $$\frac{x^3-2x^2+4x-8}{x^2+x-6}$$
> notamos que numerador y denominador se pueden descomponer como producto de otros polinomios de menor grado.
> 
> $$x^3-2x^2+4x-8=(x-2)·(x^2+4)$$
> $$x^2+x-6=(x-2)·(x+3)$$
> Como numerador y denominador tienen factores comunes, $(x-2)$, resulta
> $$\frac{x^3-2x^2+4x-8}{x^2+x-6}=\frac{(x-2)·(x^2-4)}{(x-2)·(x+3)}=\frac{x^2+4}{x+3}$$

+ **Producto y cociente de fracciones algebraicas**. Para hacer la multiplicación y división de fracciones algebraicas se siguen las mismas reglas que para multiplicar y dividir fracciones numéricas.
  La fracción producto es aquella que tiene como numerador el producto de numeradores y como denominador el producto de denominadores, es decir, aquella en la uqe se multiplican linealmente numeradores y denominadores.
  La fracción cociente es aquella que como numerador tiene el producto del primer numerador por el segundo denominador, y como denominador el producto del primer denominador por el segundo numerador, es decir, aquella en la que se multiplican numeradores y denominadores en cruz.
  
> **Ejemplo**. Producto y cociente de fracciones algebraicas.
> Producto
> $$\frac{3x-2}{2x^2+3}·\frac{7x+1}{2x+2}=\frac{(3x-2)·(7x+1)}{(2x^2+3)·(2x+2)}=\frac{21x^2-11x-2}{4x^3+4x^2+6x+6}$$
> Cociente
> $$\frac{3x-2}{2x^2+3}:\frac{7x+1}{2x+2}=\frac{(3x-2)·(2x+2)}{(2x^2+3)·(7x+1)}=\frac{6x^2+2x-4}{14x^3+2x^2+21x+3}$$

+ **Suma y resta de fracciones algebraicas**. Para sumar (o restar) dos fracciones algebraicas, se sigue el mismo procedimiento que para sumar (o restar) fracciones numéricas. Por eso conviene diferenciar si tienen el mismo denominador o no.
  + Si las fracciones algebraicas tienen el mismo denominador, se suman o restan los numeradores y se deja el mismo denominador
    $$\frac{3x-2}{4x^2-x+1}-\frac{2x+6}{4x^2-x+1}=\frac{(3x-2)-(2x+6)}{4x^2-x+1}=\frac{x-8}{4x^2-x+1}$$
  + Si las fracciones algebraicas tienen denominador diferente, hace falta ante todo transformarlas en fracciones equivalentes con el mismo denominador, como en el caso de las fracciones numéricas. Para hacerlo, se calcula el MCM de los polinomios que son en el denominador. Una vez encontradas las fracciones equivalentes con el mismo denominador, se suman de la manera anterior.
    Ejemplo: queremos sumar
    $$\frac{3x-4}{x^2+5x+6}+\frac{5x-2}{x^2+3x+2}$$
    1) Buscamos el MCM de los denominadores.
       $$x^2+5x+6=(x+2)·(x+3)$$
       $$x^2+3x+2=(x+1)·(x+2)$$
       Por lo tanto,
       $\\mcm(x^2+5x+6x^2+3x+2)=(x+1)·(x+2)·(x+3)=x*3+6x^2+11x+6$
       2) Una vez que el MCM, reescribimos las fracciones algebraicas originales por sus equivalentes de igual denominador.