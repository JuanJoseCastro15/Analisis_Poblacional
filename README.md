# 📊 Análisis Poblacional: Proyección Demográfica de México (Matriz de Leslie)

## 🏫 Expo Proyectos de Ingeniería 2025-2 | CETYS Universidad
* **Asignatura:** Álgebra Lineal  
* **Autor:** Juan José Castro  

---

### 📝 Descripción del Proyecto
Este proyecto implementa un modelo de simulación demográfica en **Python** para proyectar la población de México a lo largo de **100 años** en intervalos de **20 años**, utilizando una **Matriz de Leslie**.

* **Grupos de edad (5):** 0-19, 20-39, 40-59, 60-79 y 80-99 años.
* **Puntos de control (6):** Genera una gráfica por grupo con 6 puntos en el tiempo: Año 0 (base real INEGI 2020), Año 20, 40, 60, 80 y 100.
* **Ajuste por COVID-19:** Se promediaron los datos de mortalidad del INEGI de los años 2017 a 2019 para evitar que la anomalía atípica del 2020 distorsionara la proyección a largo plazo.

---

### 🛠️ Tecnologías Empleadas
* **Python:** Lógica principal del modelo iterativo.
* **Pandas:** Limpieza y procesamiento de las bases de datos del INEGI (`.csv` y `.xls`).
* **NumPy:** Operaciones de álgebra lineal, manejo de vectores de estado y multiplicaciones matriciales.
* **Jupyter Notebook y Anaconda:** Entorno de desarrollo interactivo por celdas y gestión de entornos virtuales.

---

### 📁 Estructura del Repositorio
* **Archivos de datos:** Documentos `.xls` y `.csv` con los registros de natalidad, defunciones y población del INEGI.
* **Matriz Leslie.ipynb:** Jupyter Notebook con el código fuente y las 5 gráficas generadas.
* **PROYECTO ALGEBRA.pdf:** Reporte con el soporte teórico y matemático del modelo.
* **.gitignore y README.md:** Archivos de configuración y documentación del repositorio.

---

### 📈 Conclusiones y Limitaciones del Modelo
La Matriz de Leslie es una herramienta matemáticamente elegante para proyecciones a corto plazo bajo condiciones estables. Sin embargo, al asumir un sistema demográfico cerrado, revela limitaciones críticas para un horizonte de 100 años, ya que ignora variables del mundo real como los flujos migratorios y los cambios socioeconómicos. La principal lección de ingeniería fue entender que la validez de cualquier software o código está estrictamente delimitada por las fronteras teóricas de su modelo matemático.
