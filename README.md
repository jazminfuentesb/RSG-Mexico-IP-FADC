# 🧬🐍 Python desde cero para Bioinformática

**Manual interactivo del participante | RSG México**  
**Brindado por:** Jazmín Fuentes Becerril

**Nivel:** Principiante  
**Duración:** 4 horas (2 sesiones de 2 horas)  
**Herramientas:** Python · Google Colab · Pandas · GitHub

¡Bienvenida y bienvenido! Este repositorio contiene un manual práctico para aprender los fundamentos de Python desde cero y comenzar a explorar datos científicos. No necesitas experiencia previa en programación.

> **Nuestra misión:** aprender a leer, escribir y modificar código, explorar datos **simulados** de expresión génica y registrar nuestros avances en GitHub.

## 🎯 ¿Qué aprenderás?

- Comprender la lógica de **entrada → proceso → salida** y ejecutar código en Google Colab.
- Utilizar `print()`, comentarios, variables, tipos de datos y operadores.
- Trabajar con listas, diccionarios y condicionales `if` / `else`.
- Recorrer colecciones con `for` y crear funciones sencillas.
- Introducirte a **Pandas**, DataFrames y archivos CSV.
- Explorar tablas con `head()`, `info()` y `describe()`, e identificar valores faltantes con `isna()`.
- Crear un repositorio y guardar versiones de tu notebook mediante **commits**.

## 📚 Contenido del taller

| Sesión | Temas | Producto |
|---|---|---|
| **1 · De cero a tus primeras líneas de código** (2 h) | Google Colab y GitHub; `print()`; variables; tipos de datos; operadores; listas; diccionarios y condicionales. | Primer mini reto y primer commit. |
| **2 · Del código a los datos científicos** (2 h) | Ciclos `for`; funciones; bibliotecas; Pandas; DataFrames; CSV; exploración y valores faltantes. | Reto **Detectives de datos**, documentación y nuevo commit. |

## 🚀 Cómo abrir y utilizar el manual

1. Entra a [Google Colab](https://colab.research.google.com/) e inicia sesión con tu cuenta de Google.
2. Selecciona **Archivo → Subir notebook** y elige `RSG_Python_Bioinformatica_Manual_Estudiantes.ipynb`. También puedes descargar ese archivo desde este repositorio y subirlo a Colab.
3. Lee las explicaciones de cada apartado antes de ejecutar el código.
4. Ejecuta las celdas en orden con el botón **▶** o con **Shift + Enter**. Algunas celdas utilizan variables creadas anteriormente.
5. Lee los comentarios precedidos por `#`, modifica algunos valores y observa cómo cambia la salida.
6. Resuelve las actividades **✍️ Tu turno** y los retos integradores a tu ritmo.

**Nota:** Colab utiliza un entorno de ejecución temporal. Si se reinicia, tendrás que volver a ejecutar las celdas necesarias desde el principio. El notebook guardado no desaparece por ese motivo.

## 🧪 Datos para practicar

El notebook crea automáticamente un archivo CSV con **12 muestras ficticias** de expresión génica. Por ello, **no necesitas descargar un dataset adicional** para completar los ejercicios. Si lo deseas, también puedes añadir al repositorio `datos_expresion_ejemplo.csv` como archivo independiente.

Los nombres de genes aparecen únicamente como contexto educativo. **Los valores de expresión, grupos y umbrales son simulados**; no deben utilizarse para hacer inferencias biológicas, clínicas o diagnósticas.

## 📂 Archivos del proyecto

```text
python-bioinformatica-rsg/
├── README.md
├── RSG_Python_Bioinformatica_Manual_Estudiantes.ipynb
└── datos_expresion_ejemplo.csv   # Opcional: el notebook ya genera los datos
```

## 💾 Cómo guardar los avances en GitHub

1. Crea una cuenta en [GitHub](https://github.com/) si aún no tienes una.
2. Crea un repositorio; nombre sugerido: `python-bioinformatica-rsg`.
3. Abre el notebook en Google Colab y selecciona **Archivo → Guardar una copia en GitHub**.
4. Autoriza el acceso cuando se solicite, selecciona tu repositorio y escribe un mensaje de commit.
5. Comprueba en GitHub que tu archivo `.ipynb` aparece y que tiene los cambios esperados.

**Mensajes de commit sugeridos:**

- `Inicio del workshop`
- `Sesión 1: fundamentos de Python`
- `Sesión 2: exploración inicial con Pandas`

> ⚠️ **Guardar en Colab no sincroniza automáticamente todos los cambios con GitHub.** Debes guardar explícitamente nuevas versiones cuando quieras publicarlas. Nunca subas contraseñas, tokens, expedientes ni datos privados.

## ✅ Reto final: Detectives de datos

Utiliza Pandas para responder estas preguntas sobre el CSV simulado:

1. ¿Cuántas filas y columnas tiene el dataset?
2. ¿Qué información contiene cada columna?
3. ¿Cómo se ven las primeras cinco filas?
4. ¿Cuántos valores faltantes hay por columna?
5. ¿Qué dos observaciones **descriptivas** puedes hacer sin interpretar biológicamente estos datos ficticios?

## 🛟 Si algo no funciona

- **`NameError`:** verifica que hayas ejecutado la celda donde se creó la variable.
- **`SyntaxError`:** revisa paréntesis, comillas, dos puntos e indentación.
- **`FileNotFoundError`:** confirma la ubicación y el nombre exacto del CSV.
- **Se reinició Colab:** vuelve a ejecutar las celdas en orden.

El propio notebook incluye una **guía de errores frecuentes** y un **glosario** para consultar conceptos después del curso.

## 🌱 ¿Qué sigue después?

Este taller prepara las bases para un siguiente curso de **limpieza de datos con Python**. Aquí aprendemos a **explorar e identificar** problemas; las decisiones sobre cómo corregirlos, eliminar duplicados o tratar valores faltantes requieren criterios específicos que se abordarán después.

---

**Material educativo preparado para el workshop de RSG México.**  
*Aprender a programar no es memorizar comandos: es entender qué queremos hacer, cómo expresarlo y cómo comprobar el resultado.* 💚
