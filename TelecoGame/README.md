Estos son programaciones en el torneo que participaremos de tecnologia.

# Porgramación de PIR

<img src="Imagenes/programacion PIR.png" width="500" height="500" />

# Foto de montaje con sensor de presión.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0860.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0861.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0862.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que tenemos un sensor de presión,, cuando no le hacemmos nada tiene un valor y cuando le pulsamor el valor cami depende dde la fuenta que le metemos al sensor.

# Programación con sensor de presión.

<img src="Imagenes/IMG_0859.png" width="500" height="500" />

Este programa emmpieza con tres int (variables), uno es sensorPIN esta conectado al A2, otro que dice que ell valorsensor es 0 y otro que es solamente presión.

Después tenemos un void stup(inicio de programa en que solo fuciona una vez), dentro de el solo tenemos un Serial.begin(9600) (es la velocidad que traspasa que son 9600 baudios).

Después tenemos un void loop(crear un bucle), dentro tenemos valorsensor = analogRead(sensorPIN) ( significca quue los valores de valorsensor es igual que la lectura analógica del sensorPIN), tenemos que presion = map(valorsensor, 0, 1023, 0, 100) (significa que la prresion es igual quue el mapeo del valorSensor, que es de 0 a 1023 y el 0 y 100 es los valores que ns marquen en el ordenador), después tenemos Serial.print("Valor de presión: ") (significa que en el monitor serie marcará como nombre de vallor de presión), después tenemos Serial.println(presion) (significa que el monitor serie coge valores de la presion) y al final tenemos un delay(500) (para que tenga un tiimpo dde pausa):

# Video de funcionamiento con sensor de presión.

 [![](https://img.youtube.com/vi/cS23Cyq-Ufs/0.jpg)](https://www.youtube.com/watch?v=cS23Cyq-Ufs) 

# Foto de montaje con sensor de humedad.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0816.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0817.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0818.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que al cambiar de humedad de algo, el valr o sube o baja.

# Programación con sensor de humedad.

<img src="Imagenes/programacion de humedad.png" width="500" height="500" />



# Video de funcionamiento con sensor de humedad.

[![](https://img.youtube.com/vi/-ppLgcI7gHQ/0.jpg)](https://www.youtube.com/watch?v=-ppLgcI7gHQ)

# Foto de montaje con sensor de LDR.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0819.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0820.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0821.jpeg" width="300" height="300" /> |

El objetivo de este circuito es que al cambiar la cantidad de luz la que detecta el valoe sube o baja.

# Programación con sensor de LDR.

<img src="Imagenes/sensor de LDR.png" width="300" height="300" />

# Video de funcionamiento con sensor de LDR.

# Foto de montaje con sensor de temperatura.

| Foto 1 | Foto 2 | Foto 3 |
| - | - | - |
| <img src="Imagenes/IMG_0851.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0852.jpeg" width="300" height="300" /> | <img src="Imagenes/IMG_0853.jpeg" width="300" height="300" /> |

# Programación con sensor de temperatura.

<img src="Imagenes/sensor de temperatura.png" width="300" height="300" />

# Video de funcionamiento con sensor de temperatura.

# Foto de montaje con sensor de presión lineal.

 <img src="Imagenes/IMG_0900.jpeg" width="300" height="300" />

 <img src="Imagenes/IMG_0901.jpeg" width="300" height="300" />

 <img src="Imagenes/IMG_0902.jpeg" width="300" height="300" />

# Programación con sensor de presión lineal.

 <img src="Imagenes/programacion de presion.png" width="300" height="300" />

# Video de funcionamiento con sensor de presión lineal.














 
