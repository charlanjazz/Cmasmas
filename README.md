# Aquí inicio mi camino en la programación con C++

## Pasos para compilar mi primer programa:
    + Hacer ejecutable el archivo: sudo chmod u+x helloworld.cpp 
    + Compilar el archivo con el compilador g++ : 
      g++ -o output-file input-file.cp
      
      en mi caso: 
      
      g++ -o helloworld helloworld.cpp 
      
    + Finalmente compilar el archivo de salida, en mi caso: helloworld
    
```shell
benson@debians ll
total 4.0K
-rw-r--r-- 1 benson benson 111 jul 27 21:11 helloworld.cpp
benson@debians sudo chmod u+x helloworld.cpp 
benson@debians g++ -o helloworld helloworld.cpp 
benson@debians ll
total 24K
-rwxr-xr-x 1 benson benson 17K jul 27 21:16 helloworld
-rwxr--r-- 1 benson benson 111 jul 27 21:11 helloworld.cpp
benson@debians ./helloworld
Hello fucking world!!
```
