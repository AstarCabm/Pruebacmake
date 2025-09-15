# Proyecto CMake - Ejemplo Hello World

Este repositorio sirve como guía práctica para aprender a usar **CMake** y compilar proyectos C++ en MSYS2/MinGW.  
Incluye un ejemplo básico (`Hello World`) y documentación de los comandos utilizados.

---

## 📂 Contenido

- `CMakeLists.txt` → Archivo principal de configuración de CMake.  
- `main.cpp` → Código de ejemplo.  
- `ComandosCmake.txt` → Explicación de los comandos de CMake y cómo funcionan.  
- `librerias/` → DLLs necesarias para ejecutar el proyecto fuera de MSYS2.  
- `build/` → Carpeta generada automáticamente por CMake (no versionada).

---

## ⚙️ Requisitos

- MSYS2 + MinGW (o cualquier compilador compatible con CMake)  
- CMake 3.XX o superior  
- Las librerías necesarias están incluidas en `librerias/` para ejecución inmediata.

---

## 🛠️ Compilación

<details>
<summary>Mostrar pasos de compilación</summary>

1. Abrir la terminal MSYS2 en la raíz del proyecto.
2. cmake -S . -B build                       | 1.Prepar el Proyecto
3. cmake --build build                       | 2.Compila el proyecto
4  ./build/Ejecutable.exe                    | 3.Ejecuta el ejecutable 
</details>
