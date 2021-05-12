# Repositorio de código del Laboratorio de Elementos de Física

Este repositorio contiene los *Jupyter Notebooks* que se utilzarón en el laboratorio de Elementos de Física del [ITAM](https://www.itam.mx/) en el semestre de primavera 2021.

#### Profesor: [Dr. Ante Salcedo](https://facultad.itam.mx/es/facultad/32563-ante-salcedo-gonzalez)
#### Asistente de profesor: [Isaac Alejandro Pimentel Morales](https://www.linkedin.com/in/isaac-alejandro-pimentel-morales/)

## Tabla de contenidos
1. [Códigos de la clase](#Códigos-de-la-clase)
	- [Clase 2: Movimiento de proyectiles](#Clase-2-Movimiento-de-proyectiles)
	- [Clase 5: Simulador de campo electrico](#Clase-5-Simulador-de-campo-electrico)
2. [Ejemplos de código](#Ejemplos-de-código)
	- [Campo vectorial](#Campo-vectorial)
	- [Graficas de contorno y superficies](#Graficas-de-contorno-y-superficies)
	- [Trayectoria en 3D](#Trayectoria-en-3D)
	- [Vectores en 2D](#Vectores-en-2D)

## Códigos de la clase
#### [Clase 2 Movimiento de proyectiles](https://github.com/IsaacAPM/Laboratorio_Fisica_primavera_2021/blob/main/Codigos%20de%20Clase/Clase%202%20Movimiento%20de%20proyectiles.ipynb)
Esta libreta grafica el cambio de la velocidad de un proyectil a lo largo del tiempo en un tiro vertical. Se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/CPW4uUa.png)

#### [Clase 5 Simulador de campo electrico](https://github.com/IsaacAPM/Laboratorio_Fisica_primavera_2021/blob/main/Codigos%20de%20Clase/Clase%205%20Lineas_de_campo_electrico.ipynb)
Esta libreta contiene un simulador de campos electricos. Si se ejecuta la celda 4 grafica un dipolo con una carga positiva y una negativa. Si se ejecuta la celda 5 grafica cualquier distribución de carga finita. Para agregar la distribución deseada se debe agregar una lista en la celda 5 con el siguiente formato [(q1,(x1,y1)),(q2,(x2,y2)),...,(qi,(xi,yi),...,(qn,(xn,yn))]. Por defecto se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/nczQBXA.png)

###  Ejemplos de código
#### [Campo vectorial](https://github.com/IsaacAPM/Laboratorio_Fisica_primavera_2021/blob/main/Graficas%20de%20funciones/Campo%20vectorial.ipynb)
Esta libreta contiene un programa para graficar campos vectoriales en 3 dimensiones. La función F define el campo a graficar. Si se modifica las variables u,v,w en F se puede graficar cualquier campo vectorial R3 a R3. Por defecto se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/oVcJ4bS.png)

#### [Graficas de contorno y superficies](https://github.com/IsaacAPM/Laboratorio_Fisica_primavera_2021/blob/main/Graficas%20de%20funciones/Graficas%20de%20contorno%2C%20superficies.ipynb)
Esta libreta contiene dos programas. El **primer programa** permite graficar curvas de nivel de una función potencial (función real de variable vectorial). La variable zmesh define la función a graficar. Por defecto se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/7mZPHY4.png)

El **segundo programa** grafica superficies en 3D. La superficie se define con una función de R2 a R. Se puede modificar la función, pero no sus dimensiones. Al igual que el programa anterior la función a graficar se define en la varible zmesh. Por defecto se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/regr9HO.png)

#### [Trayectoria en 3D](https://github.com/IsaacAPM/Laboratorio_Fisica_primavera_2021/blob/main/Graficas%20de%20funciones/Trayectoria%20en%203D.ipynb)
Esta libreta contiene un programa que grafica una trayectoria en 3 dimensiones. Es posible cambiar la función que define la trayectoria modificando las entradas del np.array de la función S. Por defecto se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/ppSXh2S.png)

#### [Vectores en 2D](https://github.com/IsaacAPM/Laboratorio_Fisica_primavera_2021/blob/main/Graficas%20de%20funciones/Vectores%20en%202D.ipynb)
Esta libreta contiene un programa que grafica campos vectoriales en 2D. El campo se define con una función de R2 a R2. Es posible modificar la función, pero no sus dimensiones. Para modificar el campo a graficar se debe modificar las variables p y q de la función V. Se incluye el código para darle formato a la gráfica. Por defecto se obtiene la siguiente gráfica:

![Imgur](https://i.imgur.com/UAY8Ge3.png)
