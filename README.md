# cpp-init
A cpp program for creating new Conan2 / CMake projects

# Install & Usage Guide
- Install Conan2 using pip or pipx
- Run profile detection
``` bash
conan profile detect --force
```
- Install CMake
- Install and extract contents of cpp-init folder into desired Projects folder
- Open Projects folder in Console
- Use - / _ instead of spaces for project name, using spaces will ignore the rest of the name

``` bash
./cpp-init project-Name
```
- Change Default Params in cpp-init-templates/ folder
- Build files using cmake
``` bash
cmake --build build/
```
- Release executable is named cpp-build, change default name in cpp-init-templates/
