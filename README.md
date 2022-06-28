# Bases-de-Datos-MySQL

![Data and settings_Two Color](https://user-images.githubusercontent.com/64716417/176060886-07189bec-5e75-4f6e-a02d-a27e2c829e25.svg)

<b>1.  </b> Abrir el script llamado “superhéroes” y ejecutarlo de modo tal que se cree la base de datos y todas sus
tablas. Posteriormente, crear las tablas que se muestran en el siguiente modelo de entidad relación:

<img width="418" alt="Captura de pantalla 2022-06-27 212109" src="https://user-images.githubusercontent.com/64716417/176060983-c76df831-9e9e-487f-9f39-9236e7441a6a.png">

a) Insertar en las tablas creadas los siguientes datos:


<img width="595" alt="Captura de pantalla 2022-06-27 212229" src="https://user-images.githubusercontent.com/64716417/176061080-bb588bda-6f82-48f3-b89c-03f05b3aec89.png">

Una vez insertados todos los registros realizar una selección de todos los atributos para corroborar que
la tablas se encuentren completas.

b) Cambiar en la tabla personajes el año de aparición a 1938 del personaje Superman. A continuación,
realizar un listado de toda la tabla para verificar que el personaje haya sido actualizado.

c) El registro que contiene al personaje Flash. A continuación, mostrar toda la tabla para verificar que
el registro haya sido eliminado.

d) Eliminar la base de datos superhéroes.

<b>2.  </b> Abrir el script llamado “personal-inserts” y ejecutarlo de modo tal que se cree la base de datos
“personal”, se creen las tablas y se inserten todos los datos en las tablas para que quede de la siguiente
manera:

<img width="506" alt="Captura de pantalla 2022-06-27 212321" src="https://user-images.githubusercontent.com/64716417/176061138-19b60db7-1c81-44f8-b902-97b3ce9c3f6b.png">

a) A continuación, realizar las siguientes consultas sobre la base de datos personal:

1. Obtener los datos completos de los empleados.

2. Obtener los datos completos de los departamentos.

3. Listar el nombre de los departamentos.

4. Obtener el nombre y salario de todos los empleados.

5. Listar todas las comisiones.

6. Obtener los datos de los empleados cuyo cargo sea ‘Secretaria’.

7. Obtener los datos de los empleados vendedores, ordenados por nombre alfabéticamente.

8. Obtener el nombre y cargo de todos los empleados, ordenados por salario de menor a mayor.

9. Elabore un listado donde para cada fila, figure el alias ‘Nombre’ y ‘Cargo’ para las respectivas
tablas de empleados.

10. Listar los salarios y comisiones de los empleados del departamento 2000, ordenado por
comisión de menor a mayor.

11. Obtener el valor total a pagar que resulta de sumar el salario y la comisión de los empleados
del departamento 3000 una bonificación de 500, en orden alfabético del empleado.

12. Muestra los empleados cuyo nombre empiece con la letra J.

13. Listar el salario, la comisión, el salario total (salario + comisión) y nombre, de aquellos
empleados que tienen comisión superior a 1000.

14. Obtener un listado similar al anterior, pero de aquellos empleados que NO tienen comisión.
15. Obtener la lista de los empleados que ganan una comisión superior a su sueldo.

16. Listar los empleados cuya comisión es menor o igual que el 30% de su sueldo.

17. Hallar los empleados cuyo nombre no contiene la cadena “MA”

18. Obtener los nombres de los departamentos que sean “Ventas” ni “Investigación” ni
‘Mantenimiento.

19. Ahora obtener los nombres de los departamentos que no sean “Ventas” ni “Investigación” ni
‘Mantenimiento.

20. Mostrar el salario más alto de la empresa.

21. Mostrar el nombre del último empleado de la lista por orden alfabético.

22. Hallar el salario más alto, el más bajo y la diferencia entre ellos.

23. Hallar el salario promedio por departamento.


Consultas con Having

24. Hallar los departamentos que tienen más de tres empleados. Mostrar el número de empleados
de esos departamentos.

25. Mostrar el código y nombre de cada jefe, junto al número de empleados que dirige. Solo los
que tengan más de dos empleados (2 incluido).

26. Hallar los departamentos que no tienen empleados


Consulta con Subconsulta

27. Mostrar la lista de los empleados cuyo salario es mayor o igual que el promedio de la empresa.
Ordenarlo por departamento.

<b>3.  </b> Abrir el script de la base de datos llamada “tienda.sql” y ejecutarlo para crear sus tablas e insertar datos
en las mismas. A continuación, generar el modelo de entidad relación. Deberá obtener un diagrama de
entidad relación igual al que se muestra a continuación:

<img width="502" alt="Captura de pantalla 2022-06-27 212406" src="https://user-images.githubusercontent.com/64716417/176061200-d832ea17-7417-466b-b99c-a6c05db8b187.png">

A continuación, se deben realizar las siguientes consultas sobre la base de datos:

1. Lista el nombre de todos los productos que hay en la tabla producto.

2. Lista los nombres y los precios de todos los productos de la tabla producto.

3. Lista todas las columnas de la tabla producto.

4. Lista los nombres y los precios de todos los productos de la tabla producto, redondeando el valor
del precio.

5. Lista el código de los fabricantes que tienen productos en la tabla producto.

10. Lista el código de los fabricantes que tienen productos en la tabla producto, sin mostrar los
repetidos.

11. Lista los nombres de los fabricantes ordenados de forma ascendente.

12. Lista los nombres de los productos ordenados en primer lugar por el nombre de forma ascendente
y en segundo lugar por el precio de forma descendente.

13. Devuelve una lista con las 5 primeras filas de la tabla fabricante.

14. Lista el nombre y el precio del producto más barato. (Utilice solamente las cláusulas ORDER BY y
LIMIT)

15. Lista el nombre y el precio del producto más caro. (Utilice solamente las cláusulas ORDER BY y
LIMIT)

16. Lista el nombre de los productos que tienen un precio menor o igual a $120.

17. Lista todos los productos que tengan un precio entre $60 y $200. Utilizando el operador BETWEEN.

18. Lista todos los productos donde el código de fabricante sea 1, 3 o 5. Utilizando el operador IN.

23. Devuelve una lista con el nombre de todos los productos que contienen la cadena Portátil en el
nombre.


Consultas Multitabla

1. Devuelve una lista con el código del producto, nombre del producto, código del fabricante y nombre
del fabricante, de todos los productos de la base de datos.

2. Devuelve una lista con el nombre del producto, precio y nombre de fabricante de todos los
productos de la base de datos. Ordene el resultado por el nombre del fabricante, por orden
alfabético.

3. Devuelve el nombre del producto, su precio y el nombre de su fabricante, del producto más barato.

4. Devuelve una lista de todos los productos del fabricante Lenovo.

5. Devuelve una lista de todos los productos del fabricante Crucial que tengan un precio mayor que
$200.

6. Devuelve un listado con todos los productos de los fabricantes Asus, HewlettPackard. Utilizando el
operador IN.

7. Devuelve un listado con el nombre de producto, precio y nombre de fabricante, de todos los
productos que tengan un precio mayor o igual a $180. Ordene el resultado en primer lugar por el
precio (en orden descendente) y en segundo lugar por el nombre (en orden ascendente)


Consultas Multitabla

Resuelva todas las consultas utilizando las cláusulas LEFT JOIN y RIGHT JOIN.

1. Devuelve un listado de todos los fabricantes que existen en la base de datos, junto con los
productos que tiene cada uno de ellos. El listado deberá mostrar también aquellos fabricantes que
no tienen productos asociados.

2. Devuelve un listado donde sólo aparezcan aquellos fabricantes que no tienen ningún producto
asociado.


Subconsultas (En la cláusula WHERE)

Con operadores básicos de comparación

1. Devuelve todos los productos del fabricante Lenovo. (Sin utilizar INNER JOIN).

2. Devuelve todos los datos de los productos que tienen el mismo precio que el producto más caro
del fabricante Lenovo. (Sin utilizar INNER JOIN).

3. Lista el nombre del producto más caro del fabricante Lenovo.

4. Lista todos los productos del fabricante Asus que tienen un precio superior al precio medio de todos
sus productos.


Subconsultas con IN y NOT IN

1. Devuelve los nombres de los fabricantes que tienen productos asociados.
(Utilizando IN o NOT IN).

2. Devuelve los nombres de los fabricantes que no tienen productos asociados.
(Utilizando IN o NOT IN).


Subconsultas (En la cláusula HAVING)

1. Devuelve un listado con todos los nombres de los fabricantes que tienen el mismo número de
productos que el fabricante Lenovo.
