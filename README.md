# Encapsulated build of gui parts

Build system for DearImGui (with implot)
with SDL2 and OpenGL 
intended as a standalone example.

The library is named dig (DearImGUI)

## Instructions

clone the two dependencies into directory  

`git clone git@github.com:ocornut/imgui.git`  
`git clone git@github.com:epezent/implot.git`

Then build in traditional cmake fashion  
` mkdir build; cd build; cmake ..; `  
` make -jN; `
` make test; `
` make install; `

The header file ` dig ` should be installed 
so you can include everything.
` #include "dig/dig" `

link against ` dig::dig `

This just lets you use the regular ImGui calls.


