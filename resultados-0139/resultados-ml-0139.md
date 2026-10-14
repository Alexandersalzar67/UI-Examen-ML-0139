# Reporte de Análisis de Datos - Pandas

`Alexander salazar machine learning pandas NC = 0139`

## 1. DataFrame Convertido
```text
         Cafeteria  Precio_cafe  Sucursales
0        Starbucks           65         500
1  Cielito Querido           45         100
2       Cafebrería           50           5
3            Local           30           1
4          Italian           55          50
5      Tim Hortons           40          20
```

## 2.1 Primeras Filas (head)
```text
         Cafeteria  Precio_cafe  Sucursales
0        Starbucks           65         500
1  Cielito Querido           45         100
```

## 2.2 Últimas Filas (tail)
```text
     Cafeteria  Precio_cafe  Sucursales
4      Italian           55          50
5  Tim Hortons           40          20
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Cafeteria        str
Precio_cafe    int64
Sucursales     int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column       Non-Null Count  Dtype
---  ------       --------------  -----
 0   Cafeteria    6 non-null      str  
 1   Precio_cafe  6 non-null      int64
 2   Sucursales   6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Precio'
```text
count      6.000000
mean     112.666667
std      193.268380
min        1.000000
25%        8.750000
50%       35.000000
75%       87.500000
max      500.000000
Name: Sucursales, dtype: float64
```

## 4. Ordenar Ascendente por Sucursales
```text
         Cafeteria  Precio_cafe  Sucursales
3            Local           30           1
2       Cafebrería           50           5
5      Tim Hortons           40          20
4          Italian           55          50
1  Cielito Querido           45         100
0        Starbucks           65         500
```

## 5. Ordenar Descendente por Precio_cafe
```text
         Cafeteria  Precio_cafe  Sucursales
0        Starbucks           65         500
4          Italian           55          50
2       Cafebrería           50           5
1  Cielito Querido           45         100
5      Tim Hortons           40          20
3            Local           30           1
```

`Alexander salazar machine learning pandas NC = 0139`