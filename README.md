# Boilerplate code for OpenGL project on mac + vscode

This is a starter boiler plate code for starting OpenGL projects on macos.

```CMD+Shift+B``` for building your code,
then in the terminal, ```cd``` into your project dir, then run ```./app``` to run the project. 

- include this line somewhere in the code to avoid errors ```glfwWindowHint(GLFW_OPENGL_FORWARD_COMPAT, GL_TRUE);```


To run OpenGL programs: (TODO: fix, this command gives some errors. might be library issues)
```
g++ main.cpp -std=c++17 -framework Cocoa -framework GLUT -framework OpenGL -framework IOKit -lglfw3 && ./a.out
```
