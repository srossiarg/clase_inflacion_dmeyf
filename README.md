# Clase de ajuste por inflación en churn analysis

La clase completa se ecuentra en el archivo `tratamiento_inflacion_final.nb.html`. Si quieren editar la notebook van a necesitar tener:
* el dataset `../datasets/paquete_premium_dias_1ano.txt` que se encuentra en el dropbox de la materia  
* el dataset `ipc_historico.csv`, incluido en el repositorio

La fuente de los datos de inflación es:

* 1946 - 2007: [INDEC](https://www.indec.gob.ar/) 
* 2007-2012 [FIEL](http://www.fiel.org/) (dataset no público, IPC provincias es buen sustituto ver Ministerio de Hacienda)
* 2012-2016 [DGEyC - GCBA](https://www.estadisticaciudad.gob.ar/eyc/)
* 2016- hoy [INDEC](https://www.indec.gob.ar/)

Recomiendo usar como fuente los datasets de la pagina del [Ministerio de Hacienda](https://www.minhacienda.gob.ar/datos/). Cuenta con series historicas de dólar, salarios e IPC provinciales y nacionales, entre otras variables. Tiene además una [API](https://series-tiempo-ar-api.readthedocs.io/es/latest/) que pueden integrar a R 


