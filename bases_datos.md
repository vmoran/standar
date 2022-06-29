#Bases de datos

1) Prefijos y nombres de tablas o bases en minúsculas

-users
- user
-
2) separar palabras con guion bajo para los nombres de las tablas:

paciente_historia
user_rol
mnt_usuario_perfil
ctl_pais
ctl_estado

3) nombres de tablas o solo en singular o plural, pero no combinados

users o user
roles o rol


4) prefijos de tablas

ctl para tablas de catalogos  ctl_pais, ctl_departamento
mnt para tablas de mantenimientos mtn_proveedor, mnt_usuario_perfil


creauser -RSDP  username  (en postgres)



pk primary keys
fk foreing keys


id pk
id_rol fk
id_user 

best practices eloquent lumen for foreing key
user_id
rol_id