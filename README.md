# ocurrencia-especies
Se generan archivos de presencia de especies leñosas en Chile. Para esto, se utilizan datos de presencia de GBIF y se producen poligonos de posible presencia de las especies.
A partir de los puntos de presencia se generan alphahull con los poligonos convexos de la posible presencia de la especie. Se generan archivos raster para cada alpahull y se transforma a una tabla con coordenadas centrales del pixel y presencia (1) o ausencia (0) de la especie.
