# ImGuizmo

Forked version of [ImGuizmo](https://github.com/CedricGuillemet/ImGuizmo) project based on Dear ImGui.

This version uses CMake to be easily integrated to any project using CMake.

Note that ImGuizmo target will be linked to Dear ImGui, so to use it your project needs to make ImGui available for linking.

Build the library by adding its folder location to your CMakeLists.txt and link it with these commands :


```
add_subdirectory(path/to/ImGuizmo)

...

target_link_libraries(<your_project>
    ...
    imGuizmo
)
```
