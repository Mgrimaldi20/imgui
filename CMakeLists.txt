cmake_minimum_required(VERSION 3.16)
project(imgui)

# Add the IMGUI library
add_library(imgui STATIC
    "imconfig.h"
    "imgui.cpp"
    "imgui.h"
    "imgui_draw.cpp"
    "imgui_internal.h"
    "imgui_tables.cpp"
    "imgui_widgets.cpp"
    "imstb_rectpack.h"
    "imstb_textedit.h"
    "imstb_truetype.h"
)
