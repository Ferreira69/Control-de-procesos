# Control-de-procesos
## Intrducción

Labview es un entorno de programación básica usada por ingenieros y científicos para desarrollar mediciones sofisticadas
pruebas y sistemas de control. Labview puede integrar una gran variedad de dispositivos de hardware. En este curso 
utilizaremos el hardware de comunicación serial y el daq(data adquisición), configurando el hardware en el MAX 
(Measurement y Automation Explorer )  usted puede descargar la versión de labview estudiantil para Windows .
Labview es la contracción de las palabras = Laboratory Virtual Instrument Engineering

Labview es un software de desarrollo gráfico y flexible creado por National Instruments una compañía que crea productos 
de hardware que le permiten a las computadoras ayudar a ingenieros y científicos a tomar mediciones controlar procesos y 
analizar y guardar datos. National Instruments fue fundada hace 39 años en Texas a partir de personas que laboraban en la 
universidad de Texas.

Científicos e ingenieros investigación desarrollo producción pruebas e industrias de servicio como los semiconductores 
automotrices aeroespacial el centro nica, química, comunicaciones y farmacéutica han usado y continúan usando labview para 
desarrollar su trabajo.

Los programas de labview son llamados programas virtuales o VI´s labview es diferente a otros lenguajes de programación 
por ejemplo Python o C ya que labview utiliza un lenguaje de programación grafica conocida como el lenguaje de 
programación c para crear programas basados en símbolos gráficos labview utiliza una terminología familiar para científicos
o ingenieros por lo que sus símbolos o iconos gráficos so fácilmente identificables por inspección visual se puede aprender 
labview incluso si tiene poca experiencia en la programación.  

Para empezar a utilizar nuestro programa abrimos labview creamos un nuevo proyecto principal mente empezaremos haciendo una 
pequeña operación realizando una suma para esto en nuestra plataforma que nos abre labview que se llama front panel con 
nuestro ratón de damos un clic derecho este a su ves nos desplegara un menú este seleccionaremos la primera opción  se llama 
numeric y seleccionamos numeric control  lo que se realiza es que lo arrastramos asta nuestro front panel repetimos la misma 
acción otra ves para que tengamos nuestros 2 números que vamos a sumar de la misma forma que realizamos la acción anterior 
repetiremos una pero a hora vamos a seleccionar otra la cual nos va a permitir visualizar el resultado de nuestra suma  a hora 
le damos control T para que se nos despliegue la otra ventana de labview llamada  Block diagram en el cual se verán nuestros 
dos números que hemos seleccionado junto con el indicador nos vamos a esta ventana de igual manera damos clic derecho y se nos 
desplegara un sub menú del cual cambia al primero que aviamos visto seleccionas el recuadro que dice numeric y como vemos están 
las operaciones seleccionamos la suma  lo que falta es acomodar nuestros recuadros seleccionamos el primero  le damos doble clic 
para poder cambiarle el nombre le ponemos A y hacemos lo mismo con el siguiente y de igual forma con el indicador pero a este le 
ponemos resultado ya tenemos A y B y el resultado en nuestro front panel como podemos observar se cambio automáticamente en 
nuestro block entonces donde tenemos nuestro signo de suma juntamos A y B  y de la salida la conectamos al resultado.

## practica 1

Para empezar a utilizar nuestro programa abrimos labview creamos un nuevo proyecto principal mente empezaremos haciendo una 
pequeña operación realizando una suma para esto en nuestra plataforma que nos abre labview que se llama front panel con nuestro 
ratón de damos un clic derecho este a su ves nos desplegara un menú este seleccionaremos la primera opción  se llama numeric y s
eleccionamos numeric control  lo que se realiza es que lo arrastramos asta nuestro front panel repetimos la misma acción otra ves 
para que tengamos nuestros 2 números que vamos a sumar de la misma forma que realizamos la acción anterior repetiremos una pero a
hora vamos a seleccionar otra la cual nos va a permitir visualizar el resultado de nuestra suma  a hora le damos control T para 
que se nos despliegue la otra ventana de labview llamada  Block diagram en el cual se verán nuestros dos números que hemos 
seleccionado junto con el indicador nos vamos a esta ventana de igual manera damos clic derecho y se nos desplegara un sub menú 
del cual cambia al primero que aviamos visto seleccionas el recuadro que dice numeric y como vemos están las operaciones 
seleccionamos la suma  lo que falta es acomodar nuestros recuadros seleccionamos el primero  le damos doble clic para poder 
cambiarle el nombre le ponemos A y hacemos lo mismo con el siguiente y de igual forma con el indicador pero a este le ponemos 
resultado ya tenemos A y B y el resultado en nuestro front panel como podemos observar se cambio automáticamente en nuestro block 
entonces donde tenemos nuestro signo de suma juntamos A y B  y de la salida la conectamos al resultado.

Con los botones que tenesmo en la parte superior de la plataforma podemos correr nuestro programa y ver como se va ejecutando.
Ahora bien metamos nuestro programa a un siclo while para que se repita esto lo vamos hacer en nuestra ventana de block diagram  
dando clic derecho y seleccionado structures como se ve en la imagen 

Una vez realizada esta acción ponemos el recuadro en la suma quedando enserrada la suma y si corremos el programa veremos que lo 
va realizar una infinidad de veces entonces procedemos a poner un botón de paro lo ponemos en nuestra ventana de front dando clic  
y seleccionado el botón  como hemos visto se pone en las dos ventanas lo que realizamos es coenctarlo pero para que no este 
realizando cada segundo la misma acción ponemos un retardo con delay en la ventana  de igual forma todo se debe encontrar dentro 
del recuadro de nuestro while  le ponemos una constante para poder le dar el retardo que nosotros deseamos con una constante lo 
podemos observar como debe de quedar nuestro recuadro en la siguiente imagen.

Corremos el programa y observamos que lo realiza cada ves que nosotros metemos diferentes valores cambia presionamos nuestro botón 
de stop y se para nuestro código, pongamos un indicador luminoso para saber cuándo ya este terminado el ciclo while.
Lo ponemos en nuestra ventana front lo conectamos a nuestro botón de stop pero afuera del recuadro  para que este nos indique lo 
observamos en la siguiente imagen.

Cuando corramos el programa y le demos stop automáticamente se prendera el led. 
Ágamos lo más difícil pongamos otra operación pero afuera del ciclo igual una suma pero ahora que el resultado que nos mande la que 
se encuentra dentro del ciclo se multiplique por 10 al presionar el botón de stop. Lo observamos en la siguiente imagen.
En la figura 9 se muestra el código ya terminado junto nuestra vetana de front panel que es la que se podría mostrar a un operador.

## Practica 2

Bueno ya tenemos la pequeña introducción hagamos un cálculo de masa corporal primero ponemos en nuestro front panel lo que vamos a 
ocupar recordemos poner control T para que se nos desplieguen las dos ventanas para el cálculo de índice de masa corporal ponemos 3 
de control numérico un slide vertical el botón de stop acomodamos las cosas uno de control numérico le ponemos peso en kg a otro 
altura en m y por ultimo cm a la barra de slide le ponemos los rangos de 10 a 40 esto es solo dando doble clic en los limites y los 
escogemos le agregamos unas líneas donde nos diga que es lo que tenemos como el slide no es exacto selescionamos y damos doble clic 
y le escogemos visible y agregar display le damos clic derecho   queda de la siguiente manera mostrada en la figura 10.
Bien nos pasamos a la ventana de block vemos que ya tenemos nuestras cosas que vamos a ocupar lo que falta es la formula la cual es 
peso entre la altura al cuadrado.

Las letras de la decoración se agregan dando doble clic.
Ya tenemos todo empezamos las operaciones primero tenemos que dividir los cm entre 100 recordemos que nos dará como resultado un numero 
flotante, después eso mismo se lo sumamos a la parte entera que serán los metros y como dice la formula hay que dividir ponemos la 
operación de la división y lo dividimos entre la altura ya con la operación antes realizada. Observemos como debe de quedar.

El resultado de esta operación nos tiene que salir en la barra de slider que es la que nos va a mostrar el índice de masa corporal y 
también si estas bajo o pasado de peso esto lo podemos ver en la figura 12 también el código todo el código lo metemos dentro de un ciclo while para poder ir modificando los valores hasta que nosotros lo paremos con el botón de stop si nosotros no paramos el código con el botón de stop puede que cuando volvamos a correr el programa tengas algún error por eso es recomendable parar primero con el botón de stop y después la simulación.

Recordemos que la división entre 100 para los cm es una constante.

El resultado de esta operación nos tiene que salir en la barra de slider que es la que nos va a mostrar el índice de masa corporal y también si estas bajo o pasado de peso esto lo podemos ver en la figura 12 también el código todo el código lo metemos dentro de un ciclo while para poder ir modificando los valores hasta que nosotros lo paremos con el botón de stop si nosotros no paramos el código con el botón de stop puede que cuando volvamos a correr el programa tengas algún error por eso es recomendable parar primero con el botón de stop y después la simulación.
<ims src¨https://github.com/Ferreira69/Control-de-procesos/issues/1#issue-471367966¨>
