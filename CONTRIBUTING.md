# 🤝 Guía de Contribución

¡Gracias por tu interés en contribuir a este proyecto! Este documento proporciona pautas para contribuir de manera efectiva.

## 📋 Código de Conducta

Al participar en este proyecto, te comprometes a mantener un ambiente respetuoso y colaborativo. Por favor:

- ✅ Sé respetuoso y constructivo en tus comentarios
- ✅ Acepta las críticas constructivas de manera positiva
- ✅ Enfócate en lo que es mejor para la comunidad
- ❌ No uses lenguaje ofensivo o inapropiado
- ❌ No ataques personalmente a otros colaboradores

## 🚀 Formas de Contribuir

### 1. Reportar Errores 🐛

Si encuentras un error:

1. Verifica que el error no haya sido reportado antes en [Issues](https://github.com/DiegoSReco/intro_python_para_economistas/issues)
2. Abre un nuevo issue incluyendo:
   - Descripción clara del error
   - Pasos para reproducirlo
   - Comportamiento esperado vs. comportamiento actual
   - Capturas de pantalla (si aplica)
   - Información del sistema (Python version, OS, etc.)

### 2. Sugerir Mejoras 💡

¿Tienes ideas para mejorar el contenido?

1. Abre un issue con la etiqueta "enhancement"
2. Describe claramente tu propuesta
3. Explica por qué sería útil para los estudiantes
4. Proporciona ejemplos si es posible

### 3. Contribuir con Código 👨‍💻

#### Proceso de Contribución

1. **Fork el repositorio**
   ```bash
   # Haz click en "Fork" en GitHub
   ```

2. **Clona tu fork**
   ```bash
   git clone https://github.com/TU_USUARIO/intro_python_para_economistas.git
   cd intro_python_para_economistas
   ```

3. **Crea una rama para tu feature**
   ```bash
   git checkout -b feature/nombre-descriptivo
   # Ejemplos:
   # - feature/agregar-ejercicio-pandas
   # - fix/corregir-typo-notebook-3
   # - docs/mejorar-readme
   ```

4. **Haz tus cambios**
   - Escribe código claro y bien comentado
   - Sigue las convenciones de estilo (ver más abajo)
   - Agrega docstrings a funciones y clases
   - Incluye ejemplos cuando sea apropiado

5. **Prueba tus cambios**
   ```bash
   # Ejecuta todos los notebooks para verificar que funcionan
   jupyter nbconvert --execute --to notebook *.ipynb
   ```

6. **Commit tus cambios**
   ```bash
   git add .
   git commit -m "Descripción clara de los cambios"
   
   # Ejemplos de buenos mensajes:
   # - "Agrega ejercicios de pandas avanzado"
   # - "Corrige error en cálculo de media ponderada"
   # - "Mejora documentación del módulo 3"
   ```

7. **Push a tu fork**
   ```bash
   git push origin feature/nombre-descriptivo
   ```

8. **Abre un Pull Request**
   - Ve a tu fork en GitHub
   - Click en "New Pull Request"
   - Describe claramente tus cambios
   - Referencia issues relacionados (#número)

## 📝 Estándares de Código

### Notebooks de Jupyter

1. **Estructura**
   - Título claro al inicio
   - Objetivos de aprendizaje
   - Importaciones al principio
   - Código dividido en celdas lógicas
   - Conclusiones al final

2. **Código**
   - Usa nombres descriptivos para variables
   - Comenta código complejo
   - Evita celdas demasiado largas
   - Limpia outputs antes de hacer commit

3. **Markdown**
   - Usa headers apropiadamente (##, ###, etc.)
   - Incluye ejemplos visuales cuando sea útil
   - Explica el "por qué" no solo el "qué"

### Estilo de Python

Seguimos [PEP 8](https://www.python.org/dev/peps/pep-0008/):

```python
# ✅ BUENO
def calcular_media_ponderada(valores, pesos):
    """
    Calcula la media ponderada de un conjunto de valores.
    
    Parameters
    ----------
    valores : array-like
        Valores a promediar
    pesos : array-like
        Pesos para cada valor
        
    Returns
    -------
    float
        Media ponderada
    """
    return np.average(valores, weights=pesos)

# ❌ MALO
def calc(v,p):
    return np.average(v,weights=p)
```

## 🎯 Tipos de Contribuciones Buscadas

### Alta Prioridad 🔴
- Correcciones de errores en el código
- Mejoras en la documentación
- Nuevos ejercicios prácticos
- Ejemplos con datos económicos reales
- Traducciones de comentarios y documentación

### Media Prioridad 🟡
- Nuevos notebooks sobre temas avanzados
- Mejoras en visualizaciones
- Optimización de código existente
- Tests unitarios

### Baja Prioridad 🟢
- Cambios estéticos menores
- Reordenamiento de contenido existente

## 📚 Agregar Nuevo Contenido

Si quieres agregar un nuevo notebook:

1. **Sigue la convención de nombres**
   ```
   script_python_[número]_[tema_descriptivo].ipynb
   ```

2. **Incluye estas secciones**
   - Introducción y objetivos
   - Requisitos previos
   - Contenido teórico
   - Ejemplos prácticos paso a paso
   - Ejercicios para practicar
   - Recursos adicionales
   - Resumen

3. **Usa datasets apropiados**
   - Preferiblemente datos económicos o sociales
   - Incluye fuente y descripción
   - Considera privacidad y licencias

## 🔍 Proceso de Revisión

Cuando abras un Pull Request:

1. Un mantenedor revisará tu contribución
2. Puede haber comentarios y sugerencias
3. Realiza los cambios solicitados
4. Una vez aprobado, se hará merge

**Tiempo de respuesta esperado**: 3-7 días hábiles

## ❓ Preguntas

Si tienes preguntas:

1. Revisa la [documentación existente](README.md)
2. Busca en [Issues cerrados](https://github.com/DiegoSReco/intro_python_para_economistas/issues?q=is%3Aissue+is%3Aclosed)
3. Abre un nuevo issue con la etiqueta "question"
4. Contacta al mantenedor: [Diego Rojas](mailto:diegorodolfo.sanchez@egresados.cide.edu)

## 🙏 Agradecimientos

Gracias a todos los contribuidores que hacen este proyecto posible:

- Estudiantes que reportan errores y sugieren mejoras
- Profesores que usan este material en sus cursos
- Desarrolladores que contribuyen con código y documentación

---

**¡Esperamos tu contribución! 🚀**
