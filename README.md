# 🌊 Simulación de Rutas de Evacuación en Zonas Inundadas
> **Actividad:** Cuando el camino más corto no es el mejor  
> **Materia / Proyecto:** Fundamentos de Inteligencia Artificial

Prototipo interactivo en Python (`.ipynb`) para evaluar y comparar estrategias de búsqueda de rutas de evacuación frente a inundaciones, considerando niveles de riesgo y transitabilidad del terreno.

---

## 👥 Integrantes del Equipo

* **Antonella** - [@antodollparts](https://github.com/antodollparts/)
* **Nombre 2** - [@usuario2](https://github.com/usuario2)
* **Nombre 3** - [@usuario3](https://github.com/usuario3)

---

## 🚀 Guía de Configuración Local

Sigue estos pasos para clonar el repositorio y configurar tu entorno de desarrollo en **Visual Studio Code**.

### 1. Requisitos Previos

Asegúrate de tener instalado en tu computadora:
* [Python 3.10+](https://www.python.org/) *(En Windows, recuerda marcar "Add Python to PATH" al instalar)*
* [Git](https://git-scm.com/)
* [Visual Studio Code](https://code.visualstudio.com/)
* Extensiones de VS Code: **Python** y **Jupyter** (de Microsoft)

---

### 2. Clonar el Repositorio

Abre la terminal de tu computadora o la terminal de VS Code y ejecuta:

```bash
git clone [https://github.com/antodollparts/fundamentos-ia-practica2.git](https://github.com/antodollparts/fundamentos-ia-practica2.git)

cd fundamentos-ia-practica2
````
---
### 3. Crear y Activar el Entorno Virtual (venv)


Para evitar problemas de compatibilidad con paquetes locales, crea un entorno virtual dentro de la carpeta del proyecto:

En Windows:
    Bash

    python -m venv venv
    .\venv\Scripts\activate

En macOS / Linux:
    Bash

    python3 -m venv venv
    source venv/bin/activate

(Sabrás que está activo porque aparecerá (venv) al inicio de tu terminal).

---
### 4. Instalar Dependencias

Con el entorno virtual activado, instala las librerías necesarias:
Bash

    pip install jupyter numpy matplotlib pandas

---
### 5. Configurar el Kernel en VS Code

Abre el archivo principal del cuaderno: proyecto_simulacion.ipynb.

En la esquina superior derecha del cuaderno, haz clic en Select Kernel (o Seleccionar Kernel).

Selecciona Python Environments... y elige el entorno virtual que acabas de crear (venv).

