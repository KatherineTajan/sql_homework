# Informe sobre Consultas SQL Usando Jupyter Book

Este informe presenta una serie de consultas SQL realizadas utilizando Jupyter Book y la API psycopg2 para interactuar con una base de datos PostgreSQL alojada en un contenedor Docker. La conexión a la base de datos se establece utilizando pgAdmin, con los siguientes detalles de conexión:

Host: localhost
Puerto: 5342
Nombre de la Base de Datos: myname_db
Nombre de Usuario: myname_user
Contraseña: password

Para comenzar, se ha creado una instancia de base de datos en Docker utilizando los parámetros mencionados anteriormente. Cada consulta que se muestra a continuación se ejecutó desde Python utilizando psycopg2, un adaptador de base de datos PostgreSQL para Python.

```{tableofcontents}
```
