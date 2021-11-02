add_library(imGuizmo STATIC
    graphEditor.cpp
    ImCurveEdit.cpp
    ImGradient.cpp
    ImGuizmo.cpp
    ImSequencer.cpp
)

target_include_directories(imGuizmo PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}
)