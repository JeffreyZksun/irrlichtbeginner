  1. Create project.
    * Create a C++ win 32 console application. Name it `01.HelloWorld.`
  1. Configure the project.
    * General Page
      * Output Directory = `$(SolutionDir)bin\$(ConfigurationName)`
      * Intermediate Directory = `$(SolutionDir)bin\$(ProjectName)\$(ConfigurationName)`
    * C/C++|General Page
      * Additional Include Directories = `..\3p\Irrlicht\include`
    * Linker|General Page
      * Additional Library Directories= `..\3p\Irrlicht\lib\Win32-visualstudio`
    * Linker|Input Page
      * Additional Dependencies = `Irrlicht.lib`
  1. Add code to main() function to implement the functions.
  1. Copy the dynamic linked files to out folder.
    * Copy Irrlicht.dll, sydney.md2, sydney.bmp to output folder.