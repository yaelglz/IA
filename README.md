# IA

Repositorio de prácticas y proyectos desarrollados para la clase de Inteligencia Artificial.

## Índice de contenidos

- Práctica 1: Redes Neuronales McCulloch-Pitts
- Práctica 2: Perceptrón
- Práctica 3: Redes Multicapa (MLP)
- Práctica 4: Redes Convolucionales (CNN)
- Práctica 5: Redes Recurrentes (RNN/LSTM)
- Recursos y datos
- Cómo ejecutar los notebooks

---

### Práctica 1: Redes Neuronales McCulloch-Pitts

Implementación de neuronas artificiales basadas en el modelo de McCulloch-Pitts para simular compuertas lógicas básicas.

**[Ver carpeta McCullockPitts](./McCullockPitts)**

**Archivos:**
- [McCullockPitts_NOT.ipynb](./McCullockPitts/McCullockPitts_NOT.ipynb) — Implementación de la compuerta lógica NOT
- [McCullockPitts_OR.ipynb](./McCullockPitts/McCullockPitts_OR.ipynb) — Implementación de la compuerta lógica OR

---

### Práctica 2: Perceptrón

Implementación del perceptrón para simular compuertas lógicas básicas (OR y NOT).

**[Ver carpeta Perceptrón](./Perceptrón)**

**Archivos:**
- [Perceptron_OR.ipynb](./Perceptrón/Perceptron_OR.ipynb) — Implementación de la compuerta lógica OR con perceptrón
- [Perceptron_NOT.ipynb](./Perceptrón/Perceptron_NOT.ipynb) — Implementación de la compuerta lógica NOT con perceptrón

---

### Práctica 3: Redes Multicapa (MLP)

Implementaciones con perceptrones multicapa para tareas de clasificación y regresión.

**[Ver carpeta Multicapa](./Multicapa)**

**Archivos:**
- [01_xor.ipynb](./Multicapa/01_xor.ipynb) — Resolución del problema XOR con MLP
- [02_clasificacion_de_la_flor_del_iris.ipynb](./Multicapa/02_clasificacion_de_la_flor_del_iris.ipynb) — Clasificación del conjunto Iris
- [03_clasificacion_de_un_candidato_a_un_empleo.ipynb](./Multicapa/03_clasificacion_de_un_candidato_a_un_empleo.ipynb) — Clasificación de candidatos
- [04_prediccion_de_la_eficiencia_del_combustible.ipynb](./Multicapa/04_prediccion_de_la_eficiencia_del_combustible.ipynb) — Regresión de eficiencia de combustible
- [05_prediccion_de_popularidad_de_una_cancion.ipynb](./Multicapa/05_prediccion_de_popularidad_de_una_cancion.ipynb) — Predicción de popularidad de canciones

---

### Práctica 4: Redes Convolucionales (CNN)

Clasificación de imágenes utilizando redes convolucionales básicas.

**[Ver carpeta Convolucionales](./Convolucionales)**

**Archivos:**
- [Clasificación_de_dígitos.ipynb](./Convolucionales/Clasificación_de_dígitos.ipynb) — Clasificación de dígitos manuscritos (MNIST)
- [Casificación_de_ropa.ipynb](./Convolucionales/Casificación_de_ropa.ipynb) — Clasificación de prendas (Fashion-MNIST)

**Recursos de imagen:**
- [imagen_8x8.png](./Convolucionales/imagen_8x8.png) — Imagen de ejemplo 8x8
- [mi_numero.png](./Convolucionales/mi_numero.png) — Ejemplo de dígito propio

---

### Práctica 5: Redes Recurrentes (RNN/LSTM)

Modelado de series de tiempo con redes recurrentes.

**[Ver carpeta Recurrentes](./Recurrentes)**

**Archivos:**
- [bitcoin.ipynb](./Recurrentes/bitcoin.ipynb) — Predicción de precios de Bitcoin
- [inflacionMX.ipynb](./Recurrentes/inflacionMX.ipynb) — Análisis/predicción de inflación en México
- [humedadSuelo.ipynb](./Recurrentes/humedadSuelo.ipynb) — Predicción de humedad en suelo

**Datos/Consultas:**
- [Consulta_20251121-093940112.xlsx](./Recurrentes/Consulta_20251121-093940112.xlsx)

---

## Cómo ejecutar los notebooks

1. Clona este repositorio o descarga el ZIP.
2. Crea y activa un entorno (opcional pero recomendado), por ejemplo con conda o venv.
3. Instala Jupyter y las dependencias necesarias según cada notebook (p. ej. numpy, pandas, scikit-learn, matplotlib, tensorflow/keras, etc.).
4. Inicia Jupyter Lab/Notebook:
   - `jupyter lab` o `jupyter notebook`
5. Abre el notebook de interés dentro de la carpeta correspondiente y ejecuta las celdas.

Nota: Algunos notebooks requieren descarga de datasets al vuelo (por ejemplo, MNIST/Fashion-MNIST) o archivos incluidos en este repositorio.

---

## Estructura del repositorio

```
IA/
├── McCullockPitts/                 # McCulloch-Pitts (compuertas lógicas)
├── Perceptrón/                     # Perceptrón (OR, NOT)
├── Multicapa/                      # Perceptrón multicapa (MLP)
├── Convolucionales/                # Redes convolucionales (CNN)
├── Recurrentes/                    # Series de tiempo con RNN/LSTM
└── README.md
```

---

## Notas

- Los nombres de archivos y carpetas incluyen caracteres acentuados; si usas sistemas que presentan problemas con codificación, asegúrate de tener UTF-8 configurado.
- Si encuentras algún error o falta de dependencias, por favor abre un issue o envía un PR.