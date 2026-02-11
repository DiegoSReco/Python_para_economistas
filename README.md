<div align="center">

# 🐍 Introducción al Análisis de Datos en Python
## Para Economía y Ciencias Sociales

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/DiegoSReco/intro_python_para_economistas?style=social)](https://github.com/DiegoSReco/intro_python_para_economistas/stargazers)

</div>

---

## 📚 Descripción

Material educativo completo que proporciona una **introducción teórica y práctica** al análisis de datos utilizando Python, específicamente diseñado para estudiantes y profesionales de **economía y ciencias sociales**. 

A través de tutoriales interactivos en Jupyter Notebooks, aprenderás desde las bases de programación en Python hasta técnicas avanzadas de análisis de datos, todo con ejemplos aplicados a problemas económicos y sociales reales.

---

## 🎯 Objetivos de Aprendizaje

Al completar este curso, serás capaz de:

- ✅ Dominar los fundamentos de programación en Python
- ✅ Manipular y analizar conjuntos de datos usando Pandas
- ✅ Crear visualizaciones efectivas con Matplotlib y Seaborn
- ✅ Aplicar análisis numérico con NumPy
- ✅ Trabajar con encuestas complejas y datos ponderados
- ✅ Desarrollar proyectos de investigación cuantitativa
- ✅ Implementar flujos de trabajo reproducibles

---

## 📖 Contenido del Curso

### Módulo 1: Fundamentos de Python
| Notebook | Tema | Descripción |
|----------|------|-------------|
| 📘 [1. Introducción](script_python_1_Introduccion.ipynb) | Conceptos Básicos | Instalación, entornos, sintaxis fundamental |
| 📗 [2.1 Objetos Básicos](script_python_2_1_ObjetosBasicos.ipynb) | Tipos de Datos | Números, strings, booleanos, operadores |
| 📙 [2.2 Estructuras de Datos](script_python_2_2_Estructuras_Datos.ipynb) | Listas, Tuplas, Diccionarios | Estructuras fundamentales de Python |

### Módulo 2: Control de Flujo y Funciones
| Notebook | Tema | Descripción |
|----------|------|-------------|
| 📕 [3. Flujos y Funciones](script_python_3_Flujos_Funciones.ipynb) | Programación Estructurada | Condicionales, loops, funciones, módulos |

### Módulo 3: Análisis Numérico
| Notebook | Tema | Descripción |
|----------|------|-------------|
| 🔢 [4. Numerical Python](script_python_4_numerical_python.ipynb) | NumPy | Arrays, operaciones matriciales, álgebra lineal |

### Módulo 4: Análisis de Datos
| Notebook | Tema | Descripción |
|----------|------|-------------|
| 🐼 [5.1 Pandas - Parte 1](script_python_5_Analisis_Datos_Pandas.ipynb) | Fundamentos de Pandas | DataFrames, Series, importación de datos |
| 🐼 [5.2 Pandas - Parte 2](script_python_5_Analisis_Datos_Pandas_2.ipynb) | Análisis Avanzado | Agrupaciones, joins, reshaping, time series |

### Módulo 5: Visualización de Datos
| Notebook | Tema | Descripción |
|----------|------|-------------|
| 📊 [6. Data Visualization](script_python_6_DataViz_Matplotlib_seaborn.ipynb) | Matplotlib & Seaborn | Gráficos estadísticos, personalización, storytelling |

### Módulo 6: Análisis Especializado
| Notebook | Tema | Descripción |
|----------|------|-------------|
| 📋 [7. Encuestas Complejas](script_python_7_intro_encuestas_complejas.ipynb) | Survey Data | Diseños muestrales complejos, ponderaciones |

---

## 🚀 Inicio Rápido

### Prerrequisitos

```bash
# Python 3.8 o superior
python --version

# Se recomienda usar Anaconda o Miniconda
# Descarga: https://www.anaconda.com/download
```

### Instalación

#### Opción 1: Clonar el repositorio

```bash
# Clonar el repositorio
git clone https://github.com/DiegoSReco/intro_python_para_economistas.git

# Navegar al directorio
cd intro_python_para_economistas

# Crear entorno virtual (opcional pero recomendado)
conda create -n python_econ python=3.10
conda activate python_econ

# Instalar dependencias
pip install -r requirements.txt
```

#### Opción 2: Usar Google Colab (Sin instalación)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiegoSReco/intro_python_para_economistas)

Solo abre los notebooks directamente en Google Colab - ¡No necesitas instalar nada!

### Ejecutar Jupyter Notebooks

```bash
# Iniciar Jupyter Notebook
jupyter notebook

# O Jupyter Lab
jupyter lab
```

---

## 📦 Dependencias Principales

```python
numpy>=1.21.0          # Computación numérica
pandas>=1.3.0          # Análisis de datos
matplotlib>=3.4.0      # Visualización
seaborn>=0.11.0        # Visualización estadística
jupyter>=1.0.0         # Notebooks interactivos
scipy>=1.7.0           # Computación científica
statsmodels>=0.13.0    # Modelos estadísticos
```

Ver [`requirements.txt`](requirements.txt) para la lista completa.

---

## 🎓 Para Instructores

Este material es **ideal para**:

- 📚 Cursos universitarios de introducción a Python para economistas
- 🏫 Talleres intensivos de análisis de datos
- 💼 Capacitación profesional en data science para economía
- 📊 Auto-estudio estructurado

### Estructura Pedagógica

Cada notebook sigue una estructura consistente:
1. **Objetivos** - ¿Qué aprenderás?
2. **Teoría** - Conceptos fundamentales
3. **Ejemplos Prácticos** - Código ejecutable con explicaciones
4. **Ejercicios** - Práctica guiada
5. **Proyecto Integrador** - Aplicación real

---

## 💡 Ejemplos de Uso

### Análisis de Datos Económicos

```python
import pandas as pd
import matplotlib.pyplot as plt

# Cargar datos
df = pd.read_csv('datos_economicos.csv')

# Análisis exploratorio
print(df.describe())

# Visualización
df.plot(x='año', y='pib', kind='line')
plt.title('Evolución del PIB')
plt.show()
```

### Trabajo con Encuestas Complejas

```python
import numpy as np
from scipy import stats

# Calcular estadísticas ponderadas
media_ponderada = np.average(df['ingreso'], weights=df['factor_expansion'])
```

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras errores, tienes sugerencias o quieres agregar contenido:

1. 🍴 Fork el repositorio
2. 🌿 Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. 💾 Commit tus cambios (`git commit -am 'Agrega nueva funcionalidad'`)
4. 📤 Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. 🔁 Abre un Pull Request

Ver [CONTRIBUTING.md](CONTRIBUTING.md) para más detalles.

---

## 📚 Recursos Adicionales

### Documentación Oficial
- [Python Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

### Libros Recomendados
- 📖 "Python for Data Analysis" - Wes McKinney
- 📖 "Python Data Science Handbook" - Jake VanderPlas
- 📖 "Econometrics with Python" - Various Authors
---

## 📧 Contacto

**Mtro. Diego Sánchez Rojas**

- 🌐 LinkedIn: [@diegorojas12](https://www.linkedin.com/in/diegorojas12/)
- 📧 Email: diegorodolfo.sanchez@egresados.cide.edu
- 🐙 GitHub: [@DiegoSReco](https://github.com/DiegoSReco)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

## 📊 Estadísticas del Proyecto

![GitHub last commit](https://img.shields.io/github/last-commit/DiegoSReco/intro_python_para_economistas)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/DiegoSReco/intro_python_para_economistas)
![GitHub repo size](https://img.shields.io/github/repo-size/DiegoSReco/intro_python_para_economistas)

---

<div align="center">

### 🌟 Si este material te ha sido útil, considera darle una estrella ⭐

**Hecho con ❤️ para la comunidad de economistas y científicos sociales**

[⬆ Volver arriba](#-introducción-al-análisis-de-datos-en-python)

</div>
