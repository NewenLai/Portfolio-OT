Primer contacto con plataforma Labshock dedicada al aprendizaje de OT mediante guias y laboratorios practicos

![Pantalla inicial](Images/lab1/Pantalla_inicial_Labshock.png)

Tras realizar los tutoriales iniciales y llegar a nivel 10 se procede a comenzar con los laboratorios iniciales, toma de contacto con OT

![Profile](Images/lab1/Profile.png)

Tras revisar la teoria proporcionada por la plataforma descubro lo que es un PLC y cual es su utilidad

![PLC1](Images/lab1/Programmable_Logic_Controler.png)

Paso a entrar al laboratorio inicial de Labshock integrado con OpenPLC (PLC de codigo abierto)

![PLC2](Images/lab1/OpenPLC_login.png)

El laboratorio es una simple toma de contacto, se trata simplemente de entrar y visualizar un entorno PLC. 
Comenzamos en el Dashboard donde comprobamos que el PLC se encuentra en estado de funcionamiento (Running) y podemos echar un vistazo a los logs para irnos familiarizarnos con el entorno. En su guia Labshock nos explica que en esta pestaña podriamos encontrar errores y alarmas.

![PLC3](Images/lab1/PLC_Dashboard.png)

Tras este vistazo inicial y movernos un poco por las distintas pestañas (Programs, Slave Devices...) finalmente entramos en la pestaña Monitoring donde el objetivo es viualizar las Tags:

  True/False: Representa las condiciones logicas, como que una bomba este activa o no.
  
  Integers/Numeros: Estos numeros representan los distintos sensores y sus lecturas.

Nos proporcionan un Switch (Point Name: Station_start) para que encendamos y apaguemos la estacion, el objetivo es ver como varian las Tags (motores, bombas e indicadores) y asi comprender la logica detras de estos sistemas (Input -> Logica -> Output)

![PLC4](Images/lab1/Monitorizacion_True.png)

![PLC5](Images/lab1/Monitorizacion_False.png)
