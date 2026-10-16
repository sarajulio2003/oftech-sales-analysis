# portfolio
Business Analysis
Informe interactivo en Power BI para la dirección de OFTech, distribuidor de mobiliario, tecnología y material de oficina en Estados Unidos.

> Nota: la empresa es ficticia. Los datos proceden del dataset público
> Superstore (Kaggle).

![Resumen ejecutivo](images/pagina1_resumen.png)

## Demo
![Navegación del informe](images/demo.gif)

## Datos
- **Fuente:**  [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Limpieza:** detecté un error de separador decimal que inflaba `Sales`.

## Modelo de datos
Modelo en estrella: una tabla de hechos (`Facts_Sales`, una fila por línea
de producto en un pedido) y dimensiones de cliente, producto, ubicación y fecha.

![Modelo en estrella](images/modelo_estrella.png)

## Hallazgos
[Aquí tu párrafo, ver abajo]

## Herramientas
Power BI, Power Query, DAX, modelado dimensional.

## Estructura del repositorio
- `data/`: datos de origen
- `report/`: archivo .pbix
- `images/`: capturas
- `docs/`: PDF del informe
