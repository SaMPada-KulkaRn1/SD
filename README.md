# SD
SD Assignments for Project Management

# Project

First install this bcrypt library

Steps :

 1. git clone https://github.com/trusch/libbcrypt
 2. cd libbcrypt
 3. mkdir build
 4. cd build
 5. cmake .. //
 6. make
 7. sudo make install
 8. sudo ldconfig
  
To compile project.cpp 

  g++ project.cpp -lbcrypt -Wl,-rpath,/home/sampada/
  
where,"/home/sampada" should be substituted with the path where libcrypt library has been downloaded.
