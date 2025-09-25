# Rouge PQST

**Proyecto:** Videojuego desarrollado en **Unity** y exportado como build para Windows.

---

## Descripción

**Rouge PQST** es un pequeño prototipo de videojuego con inspiración **roguelike**, creado como práctica de desarrollo en Unity. El objetivo es mostrar experiencia en creación de builds con Unity y distribución de ejecutables.

Este repositorio contiene el **ejecutable compilado** y los datos del juego. No incluye el proyecto fuente en Unity (scripts en C# ni escenas `.unity`), sino el build final generado.

---

## Tecnologías utilizadas

- **Unity Engine** (versión no especificada en los metadatos del build)
- **C#** para la lógica del juego
- **IL2CPP** como backend de scripting
- **.NET runtime** embebido en el ejecutable

---

## Estructura del proyecto (build)

```
Rouge PQST.exe              # Ejecutable principal de Windows
Rouge PQST_Data/            # Carpeta de datos del juego
├─ resources.assets         # Recursos empaquetados (sprites, sonidos, escenas, etc.)
├─ globalgamemanagers       # Configuración global de Unity
├─ il2cpp_data/             # Datos generados por IL2CPP
│  ├─ Metadata/             # Información de tipos y assemblies
│  └─ Native/               # Código nativo generado
├─ Managed/                 # Ensamblados gestionados (C# compilado)
└─ ...
UnityPlayer.dll             # Librería principal del runtime de Unity
GameAssembly.dll            # Lógica IL2CPP compilada a C++
baselib.dll                 # Biblioteca base de Unity
```

---

## Ejecución

- Para jugar:

  1. Descarga el repositorio o el build completo.
  2. Ejecuta `Rouge PQST.exe`.

- Requisitos de sistema:

  - Sistema operativo: **Windows 10/11 (64 bits)**
  - Hardware: PC de escritorio o portátil estándar (CPU dual-core, 4 GB RAM, GPU integrada o dedicada)

> No se requiere instalación externa de Unity ni .NET: el runtime está incluido en la build.

---

## Próximos pasos&#x20;

- Publicar los scripts en C# para mostrar la estructura de código.
- Añadir documentación sobre mecánicas, escenas y prefabs.
- Crear un `README` para jugadores con controles, objetivos y capturas de pantalla.
- Exportar versiones multiplataforma (Linux, Mac, WebGL).

---

## Créditos

Desarrollado como práctica personal de **desarrollo de videojuegos con Unity**.\
El objetivo principal es documentar la capacidad de generar builds técnicas y distribuir ejecutables en GitHub.

---


