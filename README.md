# CmakeSkeletonTimeSaver
C++ project's skeleton template for whenever I need to set one up quickly.

It contains the simple standard project structure:

	Project_name(root dir)
	|----README.md etc whatever
	|----CMakeLists.txt(root level)
	|
	|----/docs
	|    |----Documentation		
	|
	|----/src
	|    |----contains all .cpp files and moduels 	
	|    |
	|    |----/module1
	|    |     |----m1a.cpp
	|    |     |----m1b.cpp etc
	|    |     |
	|    |
	|    |----/module2
	|    |     |----m2a.cpp
	|    |     |----m2b.cpp etc
	|    |     |
	| 
	|----/include
	|    |----contains all .h and .hpp files and header only libs etc
	|    
	|----/libs    
	|    |----contain External Libraries (see documentation of the libraries etc)
	|         
	|----/build
	|    |----contains all the binaries related to the project (call cmake .. and make here to make this the bin dir, )	
	|
	|     
	
	
	
Add [Bb][Uu][Ii][Ll][Dd] to .gitignore to ignore this dir completely
