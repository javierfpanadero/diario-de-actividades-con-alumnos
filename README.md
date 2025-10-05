# diario-de-actividades-con-alumnos
Vídeo explicativo https://youtu.be/LUYXbQ_LCo4

**La versión 4-1 pone enlaces a las asignaturas en la caja supoerior del alumno. A veces tarda en actualizarse. Si te ocurre, mueve una columna de asigantura y se actualizará.

**La versión DiarioCopilotv3-2** es la misma que la 3-1 pero con una paleta de colores aplicada a los botones y una ordenación por si os gusta

**La última versión es la DiarioCopilotv3-1**
Copilot de github ha simplificado y ordenado el código.
Además se ha ampliado la función subir y bajar para que también permita subir y bajar filas de las tablas.
(Problema menor arreglado, consistencia entre el color que pone en el botón y el que se aplica cuando se abre un diario guardado)

Es un archivo html. Se trata de llevar constancia de tareas hechas y pendientes y de comunicación con familias u otros docentes.
<img width="1348" height="656" alt="image" src="https://github.com/user-attachments/assets/a728f90e-5362-4ee5-8d7f-bb6d26ecae5b" />
Lo podréis abrir y editar desde un navegador (Firefox nos dio algún problema, pero en Chrome, Opera y Edge, al menos, funciona bien).
He usado muchos tutoriales, ayudas e IA para generar el código e ir retocándolo.
Está hecho usando CSS y JavaScript, así que tiene unos botoncicos y unas funciones que a mí me solucionan mucho.

El tamaño es dinámico, podéis añadir tantas asignaturas/temas y filas como queráis
Si te desplazas hacia abajo verás que los nombres y los títulos de las asignaturas se mueven para quedar siempre a la vista hasta que pasas a la tabla siguiente.
En horizontal pasa igual. Recuerda que con la rueda del ratón te puedes mover también en horizontal si mantienes apretada "mayúsculas" (shift).
Otra ayuda a la navegación es que si estás escribiendo en una asignatura, el tabulador te pasa a la fecha y a la fila siguiente.

Os describo un poco el funcionamiento, aunque diría que es bastante intuitivo. Lo único con lo que hay que estar con mucho cuidado es con NO OLVIDARSE DE GUARDAR.

Aquí os dejo más detalles

- Cuando lo abráis veréis que está vacío, no se me asusten.
- Le dais al botón "Añadir alumno" y te pedirá un nombre. Se lo das...
- Crea una cajita arriba con el nombre y un enlace a su tabla de tareas.
- Debajo del nombre veréis que hay dos botones, para añadir asignaturas y filas a vuestro gusto. Cada alumno las que se quiera.
- También tenéis un botón para borrar alumno. Se cargará la caja azul de enlaces y su tabla de tareas.
- Para borrar asignatura, pon el cursor en cualquier asignatura de cualquier alumno y pulsa cualquier botón de borrar asignatura. Pedirá confirmación.
- Aunque se hayan hecho enlaces y tal, podéis editar el nombre de los chavales si queréis, eso sí, intentad no dar dos nombres iguales cuando los creéis que tendréis problemas con los enlaces.
- Los títulos de las asignaturas son editables también desde el navegador y todas las celdas donde escribir información.

MUUUUUUY IMPORTANTE
- Todo lo que hagas en el navegador SE PERDERÁ SI NO LO GUARDAS, aunque siempre que intentes cerrar te dará una alerta para que no se te olvide.
- Para guardar tenéis un botón que DESCARGA UNA VERSIÓN DEL DIARIO rellena con lo que TENGÁIS EN LA PANTALLA EN ESE MOMENTO. Con el nombre DIARIO_FECHA_HORA
- Para seguir trabajando otro día, abre el último diario guardado y parte de ahí.
- Sería bueno también que fuéramos subiendo backups a la nube y tener al menos el del día anterior o dos días, por si acaso.

- El resto de botones:
  - TOP te lleva hasta el principio de la página
  - NEGRITA Y RESALTADO hacen lo propio. Pulsando cambias de activado a desactivado.
  - El botón de color, colorea toda la celda, hay que elegir primero qué opción de color.
      - Se elige el color
      - Se pone el cursor en la celda.
      - Se pulsa el botón de cambio de color
  - El botón REINICIAR "reinicia" a un alumno, borra todo el contenido de la asignaturas en todas sus tablas, dejando sólo el título tal y como lo tuvieras y dos celdas vacías debajo. (v. 6-10)
 - El botón BorrarFila elimina la tarea y fecha de la celda donde esté el cursor.
 - Los botones "subir" y "bajar":
    - Si tienes el cursor en una asignatura la pasará un lugar a la izquierda (subir) o a la derecha (bajar).
    - Si tienes el cursor en el nombre del alumno en su tabla, moverá la tabla completa hacia arriba o abajo y cambiará también de posición correspondientemente el cuadro donde está su nombre y el enlace IR.
    - Si tienes el cursor en el cuadro con el nombre y el enlace IR lo moverá a la izquierda o derecha, moviendo también su tabla correspondientemente.
    - Si tienes el cursor en una tarea la moverá hacia arriba o hacia abajo 

- Los botones están siempre flotando a la vista, si no lo ves así podría ser porque no tuvieras el zoom a 100%.

Si abres el archivo html con un editor de texto plano puedes cambiar los nombres de las opciones de color, de los botones, colores, grosores de líneas de tablas, etc. Se han intentado dejar las opciones como variables al principio del CSS para que sea más fácil de personalizar.

Si no sabes mucho, prueba a buscar la palabra que quieres cambiar, por ejemplo, "exámenes" y verás donde aparece y podrás sustituirla con facilidad. Eso sí, haz primero una copia y luego edita... que tocando el código siempre se corre el riesgo de liarla. Los colores están a veces definidos por su nombre y otras veces por su código hexadecimal, si quieres cambiarlos consulta cómo se denominan, no es difícil.

Espero que os sirva. Cualquier sugerencia o comentario será muy bienvenido.
