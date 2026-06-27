# Proyecto Centinela

## Clasificación del riesgo académico utilizando Redes Neuronales (MLP)

### Descripción

Este proyecto implementa un modelo de red neuronal multicapa (MLP) desarrollado en Python y PyTorch para clasificar el riesgo académico de estudiantes utilizando los resultados históricos del examen Saber Pro entre los años 2013 y 2025.

El sistema realiza automáticamente la consolidación de las bases de datos, el preprocesamiento de la información, el entrenamiento del modelo y la evaluación de diferentes estrategias para mejorar el desempeño de la clasificación.

---

## Estructura del proyecto

```
Proyecto_Centinela
│
├── Bases/
│   ├── Base-de-datos-de-resultados-agregados...
│   └── ...
│
├── Notebook/
│   └── 01_Fase1_MLP_SaberPro.ipynb
│
├── Documentos/
│
├── requirements.txt
│
└── README.md
```

---

## Requisitos

- Python 3.11 o superior

Instalar las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

---

## Ejecución

1. Clonar el repositorio:

```bash
git clone https://github.com/ojhuertas/Proyecto_Centinela.git
```

2. Entrar al proyecto:

```bash
cd Proyecto_Centinela
```

3. Abrir el notebook ubicado en:

```
Notebook/01_Fase1_MLP_SaberPro.ipynb
```

4. Ejecutar todas las celdas en orden.

Las bases de datos deben permanecer dentro de la carpeta:

```
Bases/
```

---

## Experimentos realizados

### Experimento 1
Modelo MLP base.

### Experimento 2
Ajuste por desbalance de clases utilizando pesos en la función de pérdida.

### Experimento 3
Regularización del modelo mediante Dropout y selección del mejor modelo utilizando Early Stopping.

---

## Tecnologías utilizadas

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- OpenPyXL

---

## Autor

**Oscar Javier Huertas**

Maestría en Ciencia de Datos

Universidad Santo Tomás