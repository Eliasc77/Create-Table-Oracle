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

##### table USUARIOS created.

#### Consultamos nuestra tabla
```sql
select * from usuarios;
```
#### 
 | idusuario            | nombre           |  fecha_nacimiento   |   telefono   |   salario   |
 | ---------------------|:----------------:|--------------------:|-------------:|------------:|
 
