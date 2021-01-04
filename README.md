# Proyectos [EN PROCESO]
    Primero destacar que [###] Representa donde o para quién fue desarrollado dicho código.

    Aquí se encuentran los diferentes códigos que he desarrollado para distintos proyectos de la Universidad o Particulares, ya sea individualmente o con colaboraciones. Desde ya quedo atento a cualquier tipo de duda o feedback. 

# 1. Análisis del movimiento de la ciudadanía y su relación con las defunciones a causa de COVID-19 en Chile. [Herramientas Computacionales]
    Destacar que se recomienda solo ver los outputs ya presentes en el código (No correr denuevo), ya que se requiere de mayor expertiz para importar las diferentes bases de datos.
    


    [Codigo principal.ipynb] desarrollado en conjunto con Ignacio Díaz y Camila Vargas, es un código desarrollado en Jupyter con el objetivo de poder visualizar rápidamente cada uno de los pasos efectuados. Es un proyecto que se pudo llevar acabo gracias a que se nos facilitó acceso a información macro sobre la movilidad de la población chilena. Esta movilidad es obtenida por medio de las antenas celulares, en simples palabras si un usuario de X compañía cambiaba a la antena a la cual estaba conectado significó que este se desplazó.

    Es así, como al limpiar y manejar esta información fue posible cruzarla con data sobre las defunciones de los chilenos a causa del COVID-19 (información de libre acceso en el MINSAL). Como se puede observar en el código nosotros consideramos 2 casos de muerte, cuando el virus alcanzó a ser confirmado y cuando no, ya que como lo estableció la OMS, se marcaría como 'U071' con virus identificado y 'U072' con virus no identificado pero con todos los sintomas que dan a entender que es una muerte producto de COVID-19.

    Ya teniendo ambas datas empezamos a trabajar. Nos damos cuenta que la metrica de mortalidad no es didactica, ya que son valores pequeños, dificiles de comprender con facilidad e interpretar. Para solucionar este problema decidimos realizar la tasa de letalidad. La cual se comprende como: Muertos COVID-19 por comuna/ Casos totales de COVID-19 por comuna.
    
    En el código queda expuesto como vamos descartando escenarios que no entregaban conclusiones apropiadas, como por ejemplo casos de Letalidad del 100% pero es solo 1 caso.

    De esta forma llegamos a generar mapas de calor que representan la Letalidad para cada una de las comunas de Chile. Luego usando la data de Movilidad hacemos que cada centroide de cada comuna posea un circulo, el cual dependiendo de la cantidad de movilidad afecta el tamaño, es decir si el circulo rojo es más grande es debido a que existió más movilidad en promedio en esa comuna.

    En forma de resumen, en este misma carpeta se encuentra un PDF con la Presentacion Resumen.pdf, donde se observan las comunas más relevantes.

    Breve conclusion final: Tras el analisis y visualizacion de la data, como grupo investigador se cree que gran parte de la sociedad chilena se ha logrado adaptar en cierta medida a esta nueva normalidad, puesto a que se ha vuelto a movilizar, pero ahora de manera segura. Esto se infiere debido a que nuestra data contempla desde el 26 de febrero hasta el 30 de agosto. Es asi como se deduce que la poblacion ha logrado tener altos niveles de movimiento pero con una baja tasa de letalidad por comuna. 
    
    En otras palabras, no existe una relación directa que muestre que entre mayor movimiento de la población mayores son los casos de muerte producto de COVID-19, esto queda expuesto en diferentes comunas, como lo podemos ver en el PDF resumen, hay casos como la Region de Antofagasta o Ohiggins, donde hay comunas "Blancas", es decir muy baja letalidad pero con mucha movilidad, y por otro lado hay comunas como Maipú o Pichilemu con menor movilidad promedio pero mucha mayor tasa de Letalidad.

    Ahora los invito a reflexionar, ¿Las cuarentenas totales funcionan realmente? Con lo expuesto por medio de este proyecto a nuestro parecer no son la medida más eficaz.




