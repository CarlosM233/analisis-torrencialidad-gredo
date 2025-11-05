# 📊 Datos del Análisis de Torrencialidad

Esta carpeta contiene todos los archivos CSV generados durante el análisis.

## Estructura de Carpetas

```
datos/
├── estacion_3225/ (Garganta de Alardos)
├── estacion_3226/ (Garganta de Santa María)
└── estacion_3229/ (Garganta de Cuartos)
```

## Tipos de Archivos por Estación

Cada estación contiene los siguientes archivos CSV:

### Índices de Torrencialidad
- **`rbi_anual_*.csv`** - Índice Richards-Baker anual
- **`rbi_estacional_*.csv`** - Índice Richards-Baker por estación del año
- **`rbi_estacion_promedio_*.csv`** - Promedios estacionales del RBI
- **`ri_mensual_*.csv`** - Ratio de Instantaneidad mensual
- **`ct_anual_*.csv`** - Coeficiente de Torrencialidad anual
- **`cv_anual_*.csv`** - Coeficiente de Variación anual
- **`ce_anual_*.csv`** - Coeficiente de Estiaje anual

### Análisis de Eventos
- **`eventos_*.csv`** - Base de datos completa de eventos extremos detectados
- **`top10_eventos_*.csv`** - Los 10 eventos más importantes

### Análisis de Frecuencia
- **`tabla_frecuencia_*.csv`** - Análisis de frecuencia GEV y caudales de diseño
- **`fdc_*.csv`** - Flow Duration Curve (Curva de duración de caudales)

### Resumen General
- **`resumen_general_*.csv`** - Estadísticas generales de la estación

## 📥 Cómo Subir los Archivos

### Opción 1: Por la interfaz de GitHub
1. Entra en cada carpeta de estación
2. Click en "Add file" → "Upload files"
3. Arrastra los archivos CSV correspondientes

### Opción 2: Por línea de comandos
```bash
# Clonar el repositorio
git clone https://github.com/CarlosM233/analisis-torrencialidad-gredos.git
cd analisis-torrencialidad-gredos

# Copiar archivos a cada carpeta
cp rbi_anual_3225.csv datos/estacion_3225/
cp rbi_anual_3226.csv datos/estacion_3226/
cp rbi_anual_3229.csv datos/estacion_3229/
# ... (repetir para todos los archivos)

# Subir cambios
git add datos/
git commit -m "Add CSV data files"
git push
```

## 📋 Lista Completa de Archivos a Subir

### Estación 3225 (Alardos):
- ce_anual_3225.csv
- ct_anual_3225.csv
- cv_anual_3225.csv
- eventos_3225.csv
- fdc_3225.csv
- rbi_anual_3225.csv
- rbi_estacional_3225.csv
- rbi_estacion_promedio_3225.csv
- resumen_general_3225.csv
- ri_mensual_3225.csv
- tabla_frecuencia_3225.csv
- top10_eventos_3225.csv

### Estación 3226 (Santa María):
- ce_anual_3226.csv
- ct_anual_3226.csv
- cv_anual_3226.csv
- eventos_3226.csv
- fdc_3226.csv
- rbi_anual_3226.csv
- rbi_estacional_3226.csv
- rbi_estacion_promedio_3226.csv
- resumen_general_3226.csv
- ri_mensual_3226.csv
- tabla_frecuencia_3226.csv
- top10_eventos_3226.csv

### Estación 3229 (Cuartos):
- ce_anual_3229.csv
- ct_anual_3229.csv
- cv_anual_3229.csv
- eventos_3229.csv
- fdc_3229.csv
- rbi_anual_3229.csv
- rbi_estacional_3229.csv
- rbi_estacion_promedio_3229.csv
- resumen_general_3229.csv
- ri_mensual_3229.csv
- tabla_frecuencia_3229.csv
- top10_eventos_3229.csv

---

**Total: 36 archivos CSV**