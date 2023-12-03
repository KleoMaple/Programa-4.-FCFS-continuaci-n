# Programa-4.-FCFS-continuaci-n


## Requerimientos

1. **Continuación de la Práctica Anterior:**
   - Se utilizará el algoritmo FCFS en la cola de listos.

2. **Cumplimiento de Requisitos de la Actividad 6 (Programa 3)**

3. **Teclas de Operaciones:**

   | Tecla | ¿Qué Indica?                             | ¿Qué Hace?                                                  |
   |-------|------------------------------------------|------------------------------------------------------------|
   | I     | Interrupción por Entrada/Salida          | Proceso en ejecución va a la cola de Bloqueados, espera y luego va a la cola de Listos. |
   | E     | Error                                    | Proceso en ejecución termina por error, pasa a procesos terminados. Se libera espacio en memoria. |
   | P     | Pausa                                    | Detiene la ejecución del programa.                           |
   | C     | Continuar                                | Reanuda el programa pausado con "P".                         |
   | N     | Nuevo                                    | Genera un nuevo proceso con datos aleatorios. El planificador a largo plazo define su ingreso al sistema. |
   | B     | Tabla de Procesos (BCP de cada proceso) | Pausa el programa y muestra la tabla de procesos (BCP). La tecla "C" reanuda la simulación en el punto donde quedó. |

4. **Datos en la Tabla de Procesos (Tecla B):**
   a. Identificador del proceso.
   b. Estado del proceso:
      - Nuevo: Campos siguientes nulos.
      - Terminado: Indica si fue por error o normalmente.
      - Bloqueado: Muestra tiempo restante en dicho estado.
   c. Operación y datos, resultado si el proceso es terminado.
   d. Tiempo de Llegada (si aplica).
   e. Tiempo de Finalización (si aplica).
   f. Tiempo de Retorno (si aplica).
   g. Tiempo de Espera (al momento).
   h. Tiempo de Servicio (al momento).
   i. Tiempo Restante en CPU (si aún no termina).
   j. Tiempo de Respuesta (si aplica).

5. **Visualización en Pantalla:**
   a. Número de Procesos en Estado Nuevo, actualizado por cambios a Listos o ingresos nuevos (tecla "N").
   b. Cola de Listos:
      - Identificador de Proceso.
      - Tiempo Máximo Estimado.
      - Tiempo Restante.
   c. Proceso en Ejecución:
      - Todos los datos del proceso.
      - Tiempo transcurrido en ejecución.
      - Tiempo restante por ejecutar.
   d. Cola de Bloqueados:
      - Identificador de Proceso.
      - Tiempo transcurrido en bloqueado.
   e. Procesos Terminados:
      - Identificador de Proceso.
      - Operación.
      - Resultado de la operación o "ERROR" en caso de terminación con error.
   f. Reloj (Contador General): Tiempo total transcurrido desde el inicio de la simulación.

6. **Finalización del Programa:**
   - El programa termina cuando todos los procesos se han ejecutado (pantalla pausada para observar).

7. **Datos al Finalizar:**
   - Todos los datos de cada proceso.
   - Incluyendo la tabla de procesos.
