# Udacity Data Scientist Program

## Información Proyecto 1: Publicación en Medium

**Librerías usadas**
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- numpy  

**Descripción Datos (Archivos del Banco Mundial)**

- **API_EG.ELC.ACCS.ZS_DS2_es_csv_v2_41308.csv**  
  Porcentaje de la población con acceso a electricidad.

- **API_IT.NET.USER.ZS_DS2_es_csv_v2_42842.csv**  
  Porcentaje de la población que utiliza Internet.

- **API_NY.GDP.PCAP.CD_DS2_es_csv_v2_30456.csv**  
  PIB per cápita en dólares corrientes.

- **API_SE.ADT.LITR.ZS_DS2_es_csv_v2_42745.csv**  
  Tasa de alfabetización de adultos (% de personas mayores de 15 años).

- **API_SE.XPD.TOTL.GB.ZS_DS2_es_csv_v2_46468.csv**  
  Gasto público total en educación como porcentaje del PIB.

- **API_SP.DYN.LE00.IN_DS2_es_csv_v2_23756.csv**  
  Esperanza de vida al nacer (años).

**Motivación del proyecto**  
Explorar qué tan bien se puede explicar el PIB per cápita usando variables poco convencionales, limitándonos al uso de una regresión lineal múltiple.

**Resultados**  
El modelo explicó menos del 60% de la variabilidad y tuvo un error medio superior a 15.000 USD.  
Si bien no es ideal, el objetivo principal era experimentar y entender la relación entre variables, más que predecir con exactitud.  
El rendimiento podría mejorar con una selección más amplia de variables, normalización de datos y técnicas más avanzadas, como modelos de panel o con rezagos temporales, para capturar efectos que se manifiestan en años posteriores.


