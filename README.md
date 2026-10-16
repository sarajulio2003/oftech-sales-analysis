# portfolio
Business Analysis
OFTech es una empresa estadounidense online fundada en 2015 distribuidor de mobiliario, tecnología y material de oficina en Estados Unidos.

> Nota: la empresa es ficticia. Los datos proceden del dataset público
> Superstore (Kaggle).

En este informe se centra en el análisis de ventas interanual, rendimiento de los productos y el la fidelidad de los clientes.

![Resumen ejecutivo](images/pagina1_resumen.png)

## Demo
![Navegación del informe](images/demo.gif)

## Datos
- **Fuente:**  [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
  
- **Limpieza:** detecté un error de separador decimal que inflaba `Sales`.
Al final queda una tabla de 9400 filas con 21 columnas.
## Modelado de datos
Modelo en estrella: una tabla de medidas (número medio de clientes, Ventas por clientes,pedidos totales, crecimiento de ventas año tras año...), una tabla de hechos (`Facts_Sales`, una fila por línea
de producto en un pedido) y dimensiones de cliente, producto, ubicación y fecha.

![Modelo en estrella](images/imagen2.png)

## Hallazgos
“El análisis de [N] pedidos muestra que las ventas [crecen/caen] un [X] % interanual, con [Y] % concentrado en el último trimestre. [Categoría] genera el mayor volumen, pero [subcategoría] opera con margen [bajo/negativo] debido a descuentos elevados. 12 clientes generan el 10 % de las ventas, por lo que recomiendo mejorar planes de fidelizacion. En el 2018 menos del 2% fueron clientes nuevos convendria centarrase en campañas para captar mas clientes. Los productos mas demandados fueron.. que tambien fueron los más rentables.

## Herramientas
Power BI, Power Query, DAX, modelado dimensional.

## Estructura del repositorio
- `data/`: datos de origen
- `report/`: archivo .pbix
- `images/`: capturas
- `docs/`: PDF del informe
