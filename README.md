# Ejercicio-1.2
webcam betarobots

*Clonamos el repositorio de webcam del perfil de BetaRobots
  
  git clone https://github.com/beta-robots/webcam_capture.git
  
*Para compilarlo crearemos un directorio en la raiz del directorio webcam_capture llamado build

  mkdir build

*Entramos en dicho directorio y compilamos

 dav@dav-VivoBook-15-ASUS-Laptop-X560UD:~/webcam_capture/build$ cmake ..
-- The C compiler identification is GNU 7.4.0
-- The CXX compiler identification is GNU 7.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found OpenCV: /usr (found version "3.2.0") 
-- Configuring done
-- Generating done
-- Build files have been written to: /home/dav/webcam_capture/build
dav@dav-VivoBook-15-ASUS-Laptop-X560UD:~/webcam_capture/build$ make
Scanning dependencies of target webcam_capture
[ 50%] Building CXX object CMakeFiles/webcam_capture.dir/src/webcam_capture.cpp.o
[100%] Linking CXX executable webcam_capture
[100%] Built target webcam_capture
dav@dav-VivoBook-15-ASUS-Laptop-X560UD:~/webcam_capture/build$ 
 cmake ..
 
 *Dentro de la carpeta build tenemos el ejecutable
 
  ./webcam_capture
  
*Lo ejecutamos y con la webcam encendida hacemos un " print pantalla"  y la foto creada la añadimos a nuestro repositorio.


  



  
  
  
