# 📦 Gestor de Paquetes - PIP

Este repositorio contiene material de apoyo sobre el uso de **PIP**, el estándar para la gestión de librerías en Python. El contenido principal se encuentra documentado en el archivo `pip.ipynb`.

---

## 🐍 ¿Qué es PIP?

**PIP** (*Preferred Installation Program*) es el gestor oficial para la instalación y administración de paquetes en Python. Es la herramienta que permite descargar, instalar y actualizar bibliotecas externas de forma sencilla.

### 🔑 Conceptos Clave

* **Ecosistema Modular:** Python permite extender sus capacidades base mediante módulos. Mientras que la instalación estándar cubre funciones básicas, el uso de objetos complejos como **DataFrames**, **matrices** o **vectores** requiere librerías externas (como *Pandas* o *NumPy*).
* **Entornos:** PIP facilita que cada proyecto tenga sus propias dependencias, evitando conflictos entre versiones de diferentes aplicaciones.

---

## 🛠️ Ayuda Global

Para conocer el funcionamiento interno y consultar todas las funciones disponibles que ofrece el gestor, se utiliza la siguiente directiva en la terminal:

```bash
pip --help
```
### 🛠️ Comandos de Uso Frecuente

A continuación, se detallan las directivas más comunes de PIP mencionadas en el archivo de prueba:

| Comando | Descripción | Ejemplo de uso |
| :--- | :--- | :--- |
| **`install`** | Descarga e instala un paquete desde PyPI. | `pip install pandas` |
| **`uninstall`** | Elimina un paquete del entorno actual. | `pip uninstall flask` |
| **`list`** | Muestra todos los paquetes instalados y sus versiones. | `pip list` |
| **`freeze`** | Genera un listado de dependencias para replicar entornos. | `pip freeze > requirements.txt` |
| **`show`** | Muestra información detallada (versión, autor, ubicación) de un paquete. | `pip show numpy` |
| **`--help`** | Despliega el listado general de directivas y ayuda. | `pip --help` |
