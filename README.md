# SD
SD Assignments for Project Management

# Project

First install this bcrypt library
Steps :

  git clone https://github.com/trusch/libbcrypt
  cd libbcrypt
  mkdir build
  cd build
  cmake .. //
  make
  sudo make install
  sudo ldconfig
  
To compile project.cpp 

  g++ project.cpp -lbcrypt -Wl,-rpath,/home/sampada/
where,"/home/sampada" should be substituted with the path where libcrypt library has been downloaded.
