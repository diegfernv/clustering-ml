# ML Clustering
Este proyecto se enfoca en la implementación de tanto algoritmos de Clustering como Machine Learning de clasificación y Regresión.
Adicionalmente se realiza un análisis de explicaibilidad de los modelos de Machine Learning.

## Requisitos

- Python 3.11.11
- NumPy
- Pandas
- scikit-learn
- matplotlib
- seaborn
- shap
- lightgbm
- xgboost
- dice-ml

## Instalación
La instalación debe empezar por la creación de un ambiente con conda o mamba, luego se instalan las librerías necesarias partiendo por DiCE-ML.
```bash
conda install -c conda-forge dice-ml
pip install lightgbm xgboost matplotlib seaborn shap
```

Adicionalmente se puede hacer uso de environment.yml para instalar las librerías necesarias.
```bash
conda env create -f environment.yml
```

## Uso
La ejecución se encuentra ordenada por el nombre de archivo, por lo que se puede ejecutar cada uno de los archivos de manera independiente.
