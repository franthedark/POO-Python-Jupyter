# Repositorio de Ejercicios de POO en Jupyter

Este repositorio contiene los cuadernos Jupyter con la resolución de los 10 ejercicios de Programación Orientada a Objetos (POO) desarrollados en Python.

---

## Contenido del Repositorio

```
├── notebooks/           # Cuadernos Jupyter por problema
│   ├── Problema1.ipynb
│   ├── Problema2.ipynb
│   ├── Problema3.ipynb
│   ├── Problema4.ipynb
│   ├── Problema5.ipynb
│   ├── Problema6.ipynb
│   ├── Problema7.ipynb
│   ├── Problema8.ipynb
│   ├── Problema9.ipynb
│   └── Problema10.ipynb
└── README.md            # Este archivo
```

## Instalación y Configuración

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/repo-poo-jupyter.git
   cd repo-poo-jupyter
   ```

2. Crear y activar entorno virtual (conda o venv):

**Con conda:**
```
   conda create -n poo python=3.10 jupyter ipykernel
   conda activate poo
```
**Con venv:**
```
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .\.venv\\Scripts\\activate # Windows
```

4. Instalar dependencias:

   ```
   pip install -r requirements.txt
   ```

5. Abrir los cuadernos en VS Code o Jupyter Lab:

   ```
   jupyter lab  # o jupyter notebook
   ```

## Uso

* Cada cuaderno (`.ipynb`) está estructurado con:

  1. Título del problema y autor.
  2. Definición de clases y métodos en celdas de código.
  3. Pruebas de funcionamiento y ejemplos de uso.
  4. Sección de autoevaluación con preguntas y respuestas.

* Ejecuta las celdas en orden (`Shift + Enter`) para verificar la implementación y resultados.

## Estructura de Ejemplos

* **Problema1.ipynb:** Sistema de Biblioteca y Gestión de Préstamos de Libros.
* **Problema2.ipynb:** Sistema de Reserva de Hotel.
* **Problema3.ipynb:** Gestión de Inscripciones en Universidad.
* **Problema4.ipynb:** Simulación de Cajero Automático.
* **Problema5.ipynb:** Evaluación Académica de Estudiantes.
* ... (y así hasta el Problema 10)

## Dependencias

* Python 3.10+
* Jupyter
* (Opcional) Extensiones: `jupyter`, `ipykernel` para VS Code

## Referencias

* Material de clase de POO.
* Documentación oficial de Python.

**Autor:** Francisco Mercado

**Fecha:** Junio 2025
