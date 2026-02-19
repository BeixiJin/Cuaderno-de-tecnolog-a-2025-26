Estos son programaciones en el torneo que participaremos de tecnologia.

# Sensor de PIR.

## - Porgramación con sensor de PIR.

<img src="Imagenes/programacion PIR.png" width="500" height="500" />

## - Foto de montaje con sensor de PIR.

<img src="Imagenes/sensor_pir.jpg" width="500" height="500" />

El objetivo de este circuito es que detecta personas, si detecta manda una señal y si no manda otra señal.

# Sensor de presión.

## - Foto de montaje con sensor de presión.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0860.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0861.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0862.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que tenemos un sensor de presión, cuando no le hacemmos nada tiene un valor y cuando le pulsamor el valor cami depende dde la fuenta que le metemos al sensor.

## - Programación con sensor de presión.

<img src="Imagenes/IMG_0859.png" width="500" height="500" />

Este programa emmpieza con tres int (variables), uno es sensorPIN esta conectado al A2, otro que dice que ell valorsensor es 0 y otro que es solamente presión.

Después tenemos un void stup(inicio de programa en que solo fuciona una vez), dentro de el solo tenemos un Serial.begin(9600) (es la velocidad que traspasa que son 9600 baudios).

Después tenemos un void loop(crear un bucle), dentro tenemos valorsensor = analogRead(sensorPIN) ( significca quue los valores de valorsensor es igual que la lectura analógica del sensorPIN), tenemos que presion = map(valorsensor, 0, 1023, 0, 100) (significa que la prresion es igual quue el mapeo del valorSensor, que es de 0 a 1023 y el 0 y 100 es los valores que ns marquen en el ordenador), después tenemos Serial.print("Valor de presión: ") (significa que en el monitor serie marcará como nombre de vallor de presión), después tenemos Serial.println(presion) (significa que el monitor serie coge valores de la presion) y al final tenemos un delay(500) (para que tenga un tiimpo dde pausa):

## - Video de funcionamiento con sensor de presión.

 [![](https://img.youtube.com/vi/cS23Cyq-Ufs/0.jpg)](https://www.youtube.com/watch?v=cS23Cyq-Ufs) 

Este es el video del sensor de presión funcionando.

# Sensor de humedad.

## - Foto de montaje con sensor de humedad.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0816.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0817.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0818.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que al cambiar de humedad de algo, el valor o sube o baja.

## - Programación con sensor de humedad.

<img src="Imagenes/programacion de humedad.png" width="500" height="500" />

Todos los porgramaciones que tenemos a continuación son iguales, sin embargo los sensores que utilizamos y los nombres de algunos variables son diferentes, en este caso usamos el sensor de humedad y que tiene el nombre de variable se llama humedad. También se hace el mapeo, se marca los datos en monitor serie y todos los demas son iguales.

## - Video de funcionamiento con sensor de humedad.

[![](https://img.youtube.com/vi/-ppLgcI7gHQ/0.jpg)](https://www.youtube.com/watch?v=-ppLgcI7gHQ)

Este es el video del sensor de humedad funcionando.

# Sensor de LDR.

## - Foto de montaje con sensor de LDR.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0819.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0820.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0821.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que al cambiar la cantidad de luz la que detecta el valoe sube o baja.

## - Programación con sensor de LDR.

<img src="Imagenes/sensor de LDR.png" width="300" height="300" />

En este caso usamos el sensor de LDR y el nombre de variable se llama cantidadluz, que sirve en cambiar la luminosidad el valor va cambiando,y se cambia entre 0-100, también se usa el mapeo, loa datos se marca en monitor serie y todos los demás son iguales.

## - Video de funcionamiento con sensor de LDR.

[![](https://img.youtube.com/vi/Yh9sCnXlxm4/0.jpg)](https://www.youtube.com/watch?v=Yh9sCnXlxm4)

Este es el video del sensor de LDR funcionando.

# Sensor de temperatura.

## - Foto de montaje con sensor de temperatura.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0851.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0852.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0853.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que al cambiar la temperatura el valor sube o baja.

## - Programación con sensor de temperatura.

<img src="Imagenes/sensor de temperatura.png" width="300" height="300" />

En este caso usamos el sensor de temperatura, consiste en cambiar la temperatura que detecta en sensor y marcarlo en el monitor serie, en el video se puede ver, al acercar el mechero encendido, el valor que da en el monitor serie iba subiendo,y si lo apagamos el valor iba poco a poco bajando.

## - Video de funcionamiento con sensor de temperatura.

[![](https://img.youtube.com/vi/UPrbg1qrWKQ/0.jpg)](https://www.youtube.com/watch?v=UPrbg1qrWKQ)

Este es el video del sensor de temperatura funcionando.

# Sensor de presión lineal.

## - Foto de montaje con sensor de presión lineal.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0900.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0901.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0902.jpeg" width="300" height="300" /> |

El objetivo de este circuito funciona en que al presionarlo el valor sube  baja depende de la fuerza que le metes. 

## - Programación con sensor de presión lineal.

 <img src="Imagenes/programacion de presion.png" width="300" height="300" />

En este caso usamos el sensor de presión lineal, todos los programaciones son iguales, es diferente al de presión normal en que es más largo que es lineal en vez de directo, pero también hace el mapeo, marca los datos en el monitor serie y todos los demás son iguales.

## - Video de funcionamiento con sensor de presión lineal.

[![](https://img.youtube.com/vi/dv9qfSfpy9c/0.jpg)](https://www.youtube.com/watch?v=dv9qfSfpy9c)

Este es el video del sensor de presión lineal funcionando.









 
