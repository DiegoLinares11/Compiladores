# Lenguajes_Programacion
Repositorio para el curso lenguajes de programación. 

## Instrucciones para complilación: 

1. Clonar el repositorio y dirigirse a él
2. Una vez en el directorio del repositrio, ejecturar estos comandos:
 ```bash
  rm -rf build
  mkdir build
  cd build
```
3. Si no tienes CMake instalado ejecuta: 
 ```bash
  sudo apt update
  sudo apt install cmake -y
```

4. En la carpeta build, ejecutar este comando:
 ```bash
  cmake ..
```
5. Finalmente, ejecutar el comando (en la carpeta build):
 ```bash
  make
```
6. Para ejecutar el programa, ejecutar:
 ```bash
  ./my_program
```
7. Para compliar nuevamente, simplemente ejecutar el comando:
 ```bash
  make
```
desde la carpeta build

### Si no tienes instalado Graphviz instalalo con 
 ```bash
sudo apt update
sudo apt install graphviz -y
```

## Referencias

- Proyecto 1 Teoría de la computación: https://github.com/PedroPabloGuzmanMayen/Proy1_TC.git
- Proyecto hallado en internet: https://github.com/shakilaust/Project/blob/master/Compiler/Regular%20Expression%20to%20DFA.cpp
