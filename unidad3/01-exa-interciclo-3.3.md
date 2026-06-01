# Evaluación Programación


## Registro de atención en mesa de ayuda universitaria

Solicitar al usuario el nombre del estudiante, el semestre actual, el tiempo base de resolución en minutos, la cantidad de incidencias reabiertas y si adjuntó ticket validado. Para el ticket validado, ingresar `1` si adjuntó y `0` si no adjuntó.

El programa debe calcular el tiempo final considerando que cada incidencia reabierta aumenta el tiempo base en **3 minutos**. También debe determinar si la solicitud cumple las condiciones mínimas para ser atendida.

Luego determinar la categoría académica:

* Categoría inicial si el semestre está entre 1 y 2.
* Categoría intermedio si el semestre está entre 3 y 6.
* Categoría avanzado si el semestre está entre 7 y 10.
* Semestre inválido si el semestre es menor que 1 o mayor que 12.

Determinar el resultado de atención:

* Rechazado por validación si no adjuntó ticket validado.
* Rechazado por semestre si el semestre es inválido.
* Rechazado por incidencias si tiene más de 5 incidencias reabiertas.
* Atendido excelente si el tiempo final es menor o igual a 30 y no tiene más de 2 incidencias reabiertas.
* Atendido aceptable si el tiempo final es menor o igual a 45.
* Requiere seguimiento si el tiempo final es mayor que 45.

Además, indicar:

* Si el tiempo final es par o impar.
* Si el tiempo final está dentro del rango de atención de 20 a 45 minutos.

### Ejemplos al ejecutar

#### Ejemplo 1 

```text
Ingrese el nombre del estudiante: Camila
Ingrese el semestre actual: 5
Ingrese el tiempo base de resolución en minutos: 28
Ingrese la cantidad de incidencias reabiertas: 1
Ingrese ticket validado: 1
```
```text
Estudiante: Camila | Semestre: 5 | Categoría: Intermedio
Tiempo base: 28 min | Incidencias reabiertas: 1 | Tiempo final: 31 min
Ticket validado: Sí | Tiempo final par: No | Rango de atención: Sí
Resultado: Atendido aceptable
```


#### Ejemplo 2


```text
Ingrese el nombre del estudiante: Mateo
Ingrese el semestre actual: 2
Ingrese el tiempo base de resolución en minutos: 35
Ingrese la cantidad de incidencias reabiertas: 6
Ingrese ticket validado: 1
``` 
```text
Estudiante: Mateo | Semestre: 2 | Categoría: Inicial
Tiempo base: 35 min | Incidencias reabiertas: 6 | Tiempo final: 53 min
Ticket validado: Sí | Tiempo final par: No | Rango de atención: No
Resultado: Rechazado por incidencias
```


## Rubrica de evaluación

## Rúbrica de Evaluación (1 punto)

| Criterio                                                                                         |  Puntaje |
| ------------------------------------------------------------------------------------------------ | -------: |
| Solicita correctamente todos los datos requeridos mediante `input`.                              |     0.5  |
| Calcula correctamente el tiempo final y determina la categoría académica del estudiante.         |     1.5  |
| Aplica correctamente las condiciones para determinar el resultado de atención.                    |     3    |
| Determina correctamente paridad y rango de atención utilizando operadores lógicos y matemáticos. |     3    |
| La salida cumple exactamente con el formato solicitado en el enunciado.                          |     2    |
| **Total**                                                                                        | **1.00** |
