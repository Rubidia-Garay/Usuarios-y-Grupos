# Usuarios-y-Grupos
#Creacion de grupo 
groupadd casa

#Creación de usuarios 
Adduser bea
Adduser guadalupe

#Añadiendo al grupo “CASA”
adduser bea casa
adduser guadalupe casa 

#Cambiando el nombre del grupo casa a Familia
groupmod casa -n familia 
