# Create Table Oracle

#### Crearemos una tabla
```sql
create table usuarios(
idusuario int,
nombre char(10),
fecha_nacimiento date,
telefono char(10),
salario number (6,2)
)
```
> table USUARIOS created.

#### Consultamos nuestra tabla
```sql
select * from usuarios;
```
#### 
 | idusuario            | nombre           |  fecha_nacimiento   |   telefono   |   salario   |
 | ---------------------|:----------------:|--------------------:|-------------:|------------:|
 
> una funcion importante que debemos saber es la función **describe**: Esta funcion nos muestra como quedo configurada nuestra tabla al momento de diseñar los campos y los tipos de datos.
```sql
describe usuarios;
```
