# This project is about how to inject dll into the process.
#### Enveironment: Visual Studio Pro 2017, Windows10 x64.
## Injecting dll has six main steps.

1. Get the process ID.
2. Get the handle to the process.
3. Allocate the memory for the dll path.
4. Write the dll path to the memory.
5. Get address of "LoadLibraryA".
6. Create remote thread to load the dll.

Please feel free to use these repositories if you want to know how to [build a dll](https://github.com/weirenxue/dll-dllmain-and-function) and [use a dll](https://github.com/weirenxue/dll-load-in-cpp) in VC++.  
Or refer to [dll injection in VC++ version.](https://github.com/weirenxue/dll-injector)