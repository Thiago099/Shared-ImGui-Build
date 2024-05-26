## How this repository was done

- cloned
https://github.com/giladreich/cmake-imgui

- updated the imgui to the latest version


- Build debug

cmake .. -DIMGUI_WITH_BACKEND=ON -DIMGUI_BACKEND_PLATFORM=WIN32 -DIMGUI_BACKEND_DX11=ON -DIMGUI_STATIC_LIBRARY=OFF

cmake --build . --config debug --target install

- Build release

cmake .. -DIMGUI_WITH_BACKEND=ON -DIMGUI_BACKEND_PLATFORM=WIN32 -DIMGUI_BACKEND_DX11=ON -DIMGUI_STATIC_LIBRARY=OFF

cmake --build . --config release --target install
