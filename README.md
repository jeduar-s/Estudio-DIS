# Análisis de Acciones de Disney (DIS)

Este repositorio contiene un análisis de series temporales sobre los precios de las acciones de Disney (DIS), utilizando un modelo AutoRegresivo (AR) para su predicción.

## Descripción del Proyecto
El objetivo de este estudio es modelar y predecir los precios de las acciones de Disney basándose en datos históricos. Se utiliza un modelo AutoRegresivo de orden 19 (AR(19)), seleccionado según los criterios de Akaike (AIC) y Bayesiano (BIC).

## Contenido
- **Notebook:** `Estudi DIS.ipynb` con el análisis completo.
- **Datos:** Se espera que los datos históricos sean obtenidos de fuentes financieras como Yahoo Finance.

## Requisitos
Para ejecutar el análisis, asegúrate de tener instalados los siguientes paquetes de Python:

```bash
pip install pandas numpy matplotlib seaborn statsmodels yfinance
```

## Uso
Para ejecutar el análisis, abre el notebook en Jupyter Notebook o Google Colab y sigue las instrucciones dentro del documento.

```bash
jupyter notebook "Estudi DIS.ipynb"
```

## Conclusiones
- Se ajustó un modelo AR(19) para predecir los precios de Disney.
- El modelo se seleccionó con base en los criterios AIC y BIC, mostrando el menor AIC (84.69).
- Se evaluó el desempeño con métricas de error:
  - **MSE:** 63.89
  - **MAE:** 7.23 USD
- Aunque el modelo AR(19) mejora predicciones previas, su precisión es moderada.
- Se recomienda explorar modelos más avanzados como ARIMA o SARIMA para mejorar la precisión de las predicciones.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el análisis o agregar nuevas funcionalidades, puedes hacer un fork del repositorio y enviar un pull request.

**Autor:** Jose Eduardo Saucedo Martinez


