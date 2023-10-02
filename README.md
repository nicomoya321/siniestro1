# Análisis de los datos
Iniciamos observando la informacion en las hojas presentes en el archivo homicidios.xlsx, donde observaremos 4 hojas, de las cuales obtenemos información de los HECHOS en la hoja con el mismo nombre; así como información detallada sobre la víctimas del suceso en la hoja VICTIMA.

Observamos entonces la distribución de los datos en el siguiente mapa de calor:


![image](https://github.com/nicomoya321/siniestro1/assets/104875334/7777c653-2f3f-4305-a500-d09f2c7b2e1f)

Posterior a la lectura de los datos procedemos a analizar en primer lugar la hoja de HECHOS, donde primero observaremos la distribución de los datos alrededor de los años en base al tipo de locación donde ocurrió el suceso. Para este y las consecuentes observaciones usaremos filtros en nuestas hojas ahora tomadas como dataframe en Jupyter Notebook de la siguiente manera:

![image](https://github.com/nicomoya321/siniestro1/assets/104875334/db8236e8-c58a-4067-adf7-4699e7c4a3d6)

y si observamos la distribución de accidentes en todos los años, pero en base a las comunas de la data:

![image](https://github.com/nicomoya321/siniestro1/assets/104875334/55f06e62-d867-45e0-8280-ddbd5f2be6f2)

# LA COMUNA 1 ES LA QUE PRESENTA MAYOR CANTIDAD DE VICTIMAS
Ahora veamos la distribución de la hoja de HECHOS en relación al medio de trasnporte por el cual se desplazaba la victima, en el cual obtenemos la siguiente gráfica:


![image](https://github.com/nicomoya321/siniestro1/assets/104875334/39890087-de85-41e2-a3cc-ce24b477590b)

# QUE KPIs VEREMOS?
Reducir la tasa de homicidios con el objetivo de lograr una disminución del 10%

Reducir la cantidad de accidentes mortales de motocicletas en 7%

Reducir la cantidad de accidentes viales en la COMUNA1 en 20%

# Tasa de Homicidios semestral
Se realizaron medidas calculadas semestrales en cada año para poder comparar el avance entre el segundo semestre VS el primero, con el objetivo de observar el aumento/disminución del mismo
Tasa de accidentes mortales en motocicletas
Se realizó una medida calculada de manera anual únicamente tomando en cuenta los accidentes de la hoja de VICTIMAS donde la categoría VICTIMA es MOTO, comparando dichas medidas entre 2 años consecutivos (Año presente vs Año anterior) con el objetivo de medir la tasa de crecimiento/descenso del mismo.
Tasa de accidentes en la COMUNA 1
Se realizó, de manera semejante a la tasa de mortandad en motocicletas, una comparativa anual entre la cantidad de accidentes, únicamente tomando en cuenta los sucesos en la COMUNA 1

# fuente de datos
https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales
