cmake_minimum_required(VERSION 3.29)
project(MarioParty)

set(CMAKE_CXX_STANDARD 20)

include_directories(src/cl/ucn/disc/edd/mario_party/include)


add_executable(MarioParty main.cpp
        src/cl/ucn/disc/edd/mario_party/utils/Nodo.cpp
        src/cl/ucn/disc/edd/mario_party/include/utils/Nodo.h
        src/cl/ucn/disc/edd/mario_party/utils/ArregloDinamico.cpp
        src/cl/ucn/disc/edd/mario_party/include/utils/ArregloDinamico.h
        src/cl/ucn/disc/edd/mario_party/service/Sistema.cpp
        src/cl/ucn/disc/edd/mario_party/include/service/Sistema.h
        src/cl/ucn/disc/edd/mario_party/model/Jugador.cpp
        src/cl/ucn/disc/edd/mario_party/include/model/Jugador.h
        src/cl/ucn/disc/edd/mario_party/utils/Archivo.cpp
        src/cl/ucn/disc/edd/mario_party/include/utils/Archivo.h
        src/cl/ucn/disc/edd/mario_party/utils/Grafo.cpp
        src/cl/ucn/disc/edd/mario_party/include/utils/Grafo.h)
