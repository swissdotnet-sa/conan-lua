# conan-lua

Conan package for [lua](https://www.lua.org)

The packages generated with this **conanfile** can be found on [bintray](https://bintray.com/conan-community).

## Reuse the packages

### Basic setup

```
conan install lua/5.3.3@swissdotnet/stable
```

### Project setup

```
[requires]
lua/5.3.3@swissdotnet/stable

[options]
# Take a look for all avaliable options in conanfile.py

[generators]
cmake
```

Complete the installitation of requirements for your project running:

```
conan install .
```

Project setup installs the library (and all his dependencies) and generates the files conanbuildinfo.txt and conanbuildinfo.cmake with all the paths and variables that you need to link with your dependencies.

Follow the Conan getting started: http://docs.conan.io
