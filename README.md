# CALCULADORA BASICA CON MENU

una calculadora basica se puede realizar con condiciones. Se desea realizar alguna de las operacaiones con dos numeros `x, y`. Además se desea calcular la potencia y el logaritmo. Se deben considerar los casos donde `y = 0` donde la division `x/Y` NO se puede realizar y cuando `x<=0` donde NO se puede calcular el `log(x)`. Se desea generar un menú para que el usuario pueda seleccionar la operaciónn a realizar. Una manera de hacerlo es la siguiente:

1. Se reciben los dos numeros `x, Y` para realizar la operación.
2.  Se recibe la operación a realizar mediante la variable `opcion` la que selecciona el menú que operación ejecuta el algoritmo.
3 . se inicializa la variable logica `bandera = false`. Si la division o el logaritmo no  se puede calcular, se hace `bandera = true`.
4. Mediante  condiciones se realiza la operacion deseeada.
    * En el caso de la división, si `y = 0`, NO Se puede realizar la división, se muestra un mensaje y se hace `bandera = true`.
    * En el caso del logaritmo, si `x <= 0`, NO Se puede calcular el logaritmo, se muestra un mensaje y se hace `bandera = true`.
5. Se muestra el resultado en el caso en que `bandera = false`.

"Tomado de Python con aaplicaciones a las matematicas, ingeniería y finanzas. Cervantes 0, Baez D."