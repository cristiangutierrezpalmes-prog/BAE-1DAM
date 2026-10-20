# ACTIVIDAD 2 MODELOS E/R EXTENDIDOS

## Ejercicio 1. Star Wars: Flota de la Alianza Rebelde

<br><br>

### ENTIDADES:

<br>

**VEHÍCULO** TOTAL DISJUNTA

**BASE**

**MISIÓN**

<br><br><br>

### RELACIONES:

<br>

Un **VEHÍCULO** puede estar asignado o no a una **MISIÓN**

Una **BASE** puede tener **VEHÍCULOS** o no tener ninguno

Una **MISIÓN** debe contar con uno o más **VEHÍCULOS**

Para cada **VEHÍCULO** asignado se guarda la función que desempeña en la **MISIÓN**

<br><br><br>

### ATRIBUTOS
<br>

De cada **VEHÍCULO** se guarda un  *<ins>CÓDIGO<ins>*, Un *AÑO* de fabricación, un *NOMBRE* y un *ESTADO*

De cada **VEHÍCULO** con los subtipos *TERRESTRE* y *DESLIZADORES* se registran los atributos: *NÚMERO DE OCUPANTES* y *VELOCIDAD MÁXIMA*

De cada **VEHÍCULO** con los subtipos *TERRESTRE* y *CAMINANTE* se registran los atributos: *NÚMERO DE PATAS* y *CAPACIDAD DE TRANSPORTE*

De cada **VEHÍCULO** con el subtipo *AÉREO* se registran los atributos: *ALTITUD MÁXIMA* y *TIPO DE PROPULSIÓN*

La entidad **BASE** tiene los atributos *PLANETA*, *CÓDIGO* y *NOMBRE*

La entidad **MISIÓN** tiene los atributos *NOMBRE*, *CÓDIGO* Y *OBJETIVO*

<br><br><br>

### SUBTIPOS
<br>

**VEHÍCULOS** se divide en los subtipos:

*TERRESTRE* TOTSL DISJUNTA

*AÉREO*

Del mismo modo *TERRESTRE* se divide en los subtipos:

*CAMINANTE*

y

*DESLIZADORES*

<br><br><br>

### CARDINALIDADES


Un **VEHÍCULO** puede estar asignado o no a una **MISIÓN** (0,1)

Una **BASE** puede tener **VEHÍCULOS** o no tener ninguno (0.n)

Una **MISIÓN** debe contar con uno o más **VEHÍCULOS** (1,n)

Un vehículo debe estar asignado a una base (1.1)


![Star Wars](IMG/Star_Wars_Bae.drawio.png)



## Ejercicio 1. Stranger Things: Investigaciones en Hawkins

<br><br>

### ENTIDADES:

<br>

**AGENTE**

**INVESTIGACIÓN**

<br><br><br>

### RELACIONES Y CARDINALIDADES:

> El sistema registra agentes, investigaciones y la asignación de cada agente a una investigación.

<br>

Un **AGENTE** puede no estar asignado a ninguna **INVESTIGACIÓN** o participar en varias (0,n)

Toda **INVESTIGACIÓN** debe tener al menos dos **AGENTES**  (2,n)

El grupo registra qué **AGENTES** participan en cada **INVESTIGACIÓN**

De cada **PARTICIPACIÓN** concreta se guarda la función del **AGENTE** en esa **INVESTIGACIÓN**

Cada **PARTICIPACIÓN** concreta debe estar supervisada por un **AGENTE** (1,1)

Un **AGENTE** puede supervisar ninguna, una o muchas **PARTICIPACIONES** (0,n)

Un **AGENTE** no puede supervisar su propia participación en esa misma **INVESTIGACIÓN**

<br><br><br>

### ATRIBUTOS
<br>

De cada **AGENTE** se guarda un  *<ins>CÓDIGO ÚNICO<ins>*, Una *ESPECIALIDAD*, un *NOMBRE* y un *FECHA DE INCORPORACIÓN* 

De cada **INVESTIGACIÓN** se registra un *<ins>CÓDIGO ÚNICO<ins>*, *NOMBRE EN CLAVE*, *DESCRIPCIÓN*, *FECHA DE INICIO*, *ESTADO*

De cada **PARTICIPACIÓN** concreta se guarda la *FUNCIÓN DEL AGENTE*, *EL TURNO ASIGNADO*, *FECHA DE INCORPORACIÓN AL EQUIPO*


<br><br><br>

![Star Wars](IMG/Stranger_Things_BAE.drawio.png)
















