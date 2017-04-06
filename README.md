clean-homes
==========

Función
-------

Realizar limpieza en directorios home de profesores y/o alumnos utilizando BleachBit  
  
Instalación
-----------

La forma más sencilla de instalarlo es ejecutar estos comandos en el servidor:

   # wget --no-check-certificate -O /usr/local/sbin/clean-homes https://raw.githubusercontent.com/algodelinux/clean-homes/master/clean-homes
   # chmod 755 /usr/local/sbin/clean-homes
  
Uso                   
---

Debe indicar si desea limpiar homes de alumnos, profesores o todos:
   # clean-homes -c profesor
   # clean-homes --clean profesor
   # clean-homes -c alumnos
   # clean-homes --clean alumnos
   # clean-homes -c all
   # clean-homes --clean all

