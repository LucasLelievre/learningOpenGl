Just my little project learning opnGL with Cherno's youtube series

g++ src/Application.cpp -o bin/Application; ./bin/Application


g++ -g -Wall -Wextra -pedantic -ID:\dev\learningOpenGl\include\GLFW32\include -LD:\dev\learningOpenGl\include\GLFW32\lib-mingw -lopengl32 -lglfw3 D:\dev\learningOpenGl\src\Application.cpp -o D:\dev\learningOpenGl\bin\Application.exe

i686-w64-mingw32-g++ -g -Wall -Wextra -pedantic -I${workspaceFolder}\learningOpenGl\include\GLFW32\include ${workspaceFolder}\learningOpenGl\src\Application.cpp -o ${workspaceFolder}\learningOpenGl\bin\Application.exe -L${workspaceFolder}\learningOpenGl\include\GLFW32\lib-mingw -lopengl32 -lglfw3