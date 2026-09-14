# Modelo Opciones de Pago

## Objectivo
En este repositorio se encuentra el desarrollo para un modelo de clasificion de opciones de pago, el cual busca identificar si un cliente es propenso o no a aceptar un opcion de pago (alternativa). 
Adicionalmente se encuentra el desarrollo de un sistema agentico en N8N, que busca realizar una interaccion con el cliente y lograr que acepte una opcion de pago. 

## Estructura del proyecto
# Proyecto: Modelo Alter Pago

## Descripción
Breve descripción del objetivo del proyecto, alcance y resultados esperados.

---

## Estructura del Proyecto

```text
.
├── data/
├── docs/
├── LLM/
│   └── modelo_alter_pago.json
├── models/
├── scripts/
│   └── analisis.ipynb
│   └── prediction.ipynb
│   └── train_models.ipynb
├── requirements.txt
└── README.md
```

### Directorios

#### 📁 data/
Contiene los datasets utilizados durante el entrenamiento, validación y pruebas del modelo.

#### 📁 docs/
Documentación funcional y técnica del proyecto, diagramas, presentaciones.

#### 📁 LLM/
Archivos de configuracion del modelo agentico para la interacion con cliente.

| Archivo | Descripción |
|----------|-------------|
| `modelo_alter_pago.json` | Archivos de configuración del flujo en N8N. |

#### 📁 models/
Modelos entrenados, serializados y artefactos generados durante el proceso de entrenamiento.

#### 📁 scripts/
Scripts auxiliares para procesamiento de datos, automatizaciones y utilidades del proyecto.

---

## Notebooks

### 📓 analisis.ipynb
Notebook para análisis exploratorio de datos disponibles para el entrenamiento, validaciones y entendimiento de variables.

### 📓 train_models.ipynb
Notebook encargado del pipeline de entrenamiento, ajuste y evaluación de modelos.

### 📓 prediction.ipynb
Notebook para realizar inferencias y predicciones utilizando modelos previamente entrenados.

---

## Instalación

### Crear ambiente virtual

```bash
python -m venv venv
```

### Activar ambiente

Linux / Mac:

```bash
source venv/bin/activate
```

Windows:

```bash
venv\Scripts\activate
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## Flujo de Ejecución

1. Cargar y preparar los datos.
2. Realizar análisis exploratorio (`analisis.ipynb`).
3. Entrenar modelos (`train_models.ipynb`).
4. Evaluar desempeño.
5. Generar predicciones (`prediction.ipynb`).
6. Revisar métricas y resultados en `resultados_test.csv`.

---

## Dependencias Principales

- Python 3.1x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Autor

Jorge Sebastian Mora Lara - jormora@bancolombia.com.co.
