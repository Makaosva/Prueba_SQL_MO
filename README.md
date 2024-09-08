# Prueba SQL - PostgresSQL

---

## Descripción

En esta prueba validaremos nuestros conocimientos de SQL. Para lograrlo, necesitarás aplicar lo aprendido en las unidades anteriores.

La prueba consiste en realizar un video de máximo 10 minutos, explicando cada uno de los requerimientos. Debes ir ejecutando las acciones descritas en requerimientos y explicar lo que estás haciendo. Resuelve los requerimientos previo a grabar y guárdalos en un archivo de texto.

Video en Youtube: https://youtu.be/5VsQlWR212Y

---

### Requerimientos

1. Revisa el tipo de relación y crea el modelo correspondiente. Respeta las clavesprimarias, foráneas y tipos de datos.

2. Inserta 5 películas y 5 tags; la primera película debe tener 3 tags asociados, la segunda película debe tener 2 tags asociados.

3. Cuenta la cantidad de tags que tiene cada película. Si una película no tiene tags debe mostrar 0.

4. Crea las tablas correspondientes respetando los nombres, tipos, claves primarias y foráneas y tipos de datos. 

5. Agrega 5 usuarios y 5 preguntas.
     a. La primera pregunta debe estar respondida correctamente dos veces, por dos usuarios diferentes.
     b. La segunda pregunta debe estar contestada correctamente solo por un usuario.
     c. Las otras tres preguntas deben tener respuestas incorrectas.
Contestada correctamente significa que la respuesta indicada en la tabla respuestas es exactamente igual al texto indicado en la tabla de preguntas.

6. Cuenta la cantidad de respuestas correctas totales por usuario (independiente de la pregunta).

7. Por cada pregunta, en la tabla preguntas, cuenta cuántos usuarios respondieron correctamente.

8. Implementa un borrado en cascada de las respuestas al borrar un usuario. Prueba la implementación borrando el primer usuario.

9. Crea una restricción que impida insertar usuarios menores de 18 años en la base de datos.

10. Altera la tabla existente de usuarios agregando el campo email. Debe tener la restricción de ser único.

---

⌨️Escrito con ❤️ y [Macarena Osses](https://github.com/Makaosva)
