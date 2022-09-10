# CREANDO-GRUPOS-USUARIOS-EN-DEBIAN

como primer paso vamos a crear un grupo llamado Casa y otro grupo llamado Familia 

utilizaremos el siguiente comando.

 # groupadd Casa
 
 # groupadd Familia

Ahora vamos a crear usuarios con el nombre de oaoa o mama y el otro usuario con mi nombre 

lo realizamos con la singuiente linea de comando 

# useradd Rosario

# useradd Dember 

Enseguida vamos a incluir a los usuarios creados a el grupo llamado Casa

lo vamos a realizar con la siguiente lineas de comando 

# adduser Rosario Casa

# adduser Dember Casa

Y para finalizar vamos a cambiar de grupo Casa a el grupo Familia 

lo realizamos con la siguiente linea de comando 

# groupmod -n Familia Casa

PRACTICA FINALIZADA 
