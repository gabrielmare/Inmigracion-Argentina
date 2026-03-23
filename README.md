# Inmigración en Argentina — Análisis histórico de datos

Proyecto integrador de la Diplomatura en Inteligencia de Negocios y Análisis de Datos (Universidad Blas Pascal, 2024).

El objetivo fue validar o refutar el mito/teoría sobre cuáles fueron los picos históricos de emigración argentina, cruzando datos de inmigración y emigración de las últimas décadas con el contexto socioeconómico del país.

---

## Hipótesis

> *¿Coinciden los picos de emigración argentina con las crisis económicas más importantes del país?*

La intuición popular asocia las grandes olas emigratorias con momentos de crisis — el Rodrigazo (1975), la hiperinflación (1989), el Corralito (2001) y la pandemia (2020). Este análisis busca contrastar esa percepción con datos reales.

---

## Limitaciones de los datos

Una de las conclusiones del proyecto es precisamente la dificultad de conseguir datos históricos confiables. Los registros de emigración e inmigración disponibles en fuentes abiertas cubren principalmente las últimas décadas. Para trazar un análisis completo desde el siglo XIX (cuando llegaron las grandes oleadas inmigratorias europeas) sería necesario acceder a registros del INDEC histórico, archivos del Ministerio del Interior y bases de organismos internacionales como la OIM.

---

## Datos utilizados

- Fuentes abiertas de datos de inmigración Argentina (últimas décadas)
- Datos recopilados manualmente de organismos públicos
- Ver carpeta `/Datos` para los datasets crudos

---

## Estructura

```
├── Datos/                      # datasets utilizados en el análisis
├── Entregable/                 # notebooks y visualizaciones finales
├── PROYECTO-INTEGRADOR.pdf     # informe completo del proyecto
└── README.md
```

---

## Stack

- Python · Pandas · Matplotlib
- Jupyter Notebook
- Fuentes: datos abiertos del gobierno argentino, INDEC, OIM

---

## Próximos pasos

- Incorporar datos históricos de inmigración desde el siglo XIX (llegada de inmigrantes europeos)
- Cruzar emigración con indicadores económicos (inflación, desempleo, tipo de cambio)
- Extender el análisis a emigración por país de destino
