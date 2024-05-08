# Encapsulated build of gui parts

Build system for DearImGui (with implot)
and SDL2 OpenGL

## Instructions
`git clone git@github.com:ocornut/imgui.git`
`git clone git@github.com:epezent/implot.git'

Then build in traditional cmake fashion
` mkdir build; cd build; cmake ..; `
` make -jN; make install; `

The library is named dig to avoid
DearImGUI 
Feel free to change the name.

 1. imgui: awesome lightweight immediate mode gui, for the window 
 2. implot: to aid in plotting, for science mostly

 The dependencies, git clone into the sub directories
 1. imgui: 'git@github.com:ocornut/imgui.git'
 2. implot: 'git@github.com:epezent/implot.git'
