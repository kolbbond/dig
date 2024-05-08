# Encapsulated build of gui parts

Build system for DearImGui (with implot)
and SDL2 and OpenGL as an standalone example.

The library is named dig (DearImGUI)

## Instructions

clone the two dependencies into directory

`git clone git@github.com:ocornut/imgui.git`  
`git clone git@github.com:epezent/implot.git'

Then build in traditional cmake fashion
` mkdir build; cd build; cmake ..; `
` make -jN; make install; `

The header file should be installed 
You should be example to link against ` dig::dig `
and include 
` #include "dig/dig" `

Which should include everything.
This just lets you use the regular ImGui calls.


