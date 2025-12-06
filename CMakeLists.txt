add_library(imguizmo STATIC
   GraphEditor.cpp
   ImCurveEdit.cpp
   ImGuizmo.cpp
   ImSequencer.cpp
)

target_link_libraries(imguizmo PUBLIC imgui)

target_include_directories(imgui PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
