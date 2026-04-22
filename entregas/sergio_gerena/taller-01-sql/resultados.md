# Ejercicio 1

_¿Cuántas pistas hay en total en la base de datos?_
3503

_¿Cuántos géneros distintos existen?_
25

_Obtén el nombre del género, el número de pistas y la duración promedio (en minutos) para cada género. Ordena de mayor a menor número de pistas._
| # | nombre_genero | total_tracks | minutos_promedio |
|----|---------------------|--------------|------------------|
| 1 | Rock | 1297 | 4.73 |
| 2 | Latin | 579 | 3.88 |
| 3 | Metal | 374 | 5.16 |
| 4 | Alternative & Punk | 332 | 3.91 |
| 5 | Jazz | 130 | 4.86 |
| 6 | TV Shows | 93 | 35.75 |
| 7 | Blues | 81 | 4.51 |
| 8 | Classical | 74 | 4.90 |
| 9 | Drama | 64 | 42.92 |
| 10 | R&B/Soul | 61 | 3.67 |
| 11 | Reggae | 58 | 4.12 |
| 12 | Pop | 48 | 3.82 |
| 13 | Soundtrack | 43 | 4.07 |
| 14 | Alternative | 40 | 4.40 |
| 15 | Hip Hop/Rap | 35 | 2.97 |
| 16 | Electronica/Dance | 30 | 5.05 |
| 17 | World | 28 | 3.75 |
| 18 | Heavy Metal | 28 | 4.96 |
| 19 | Sci Fi & Fantasy | 26 | 48.53 |
| 20 | Easy Listening | 24 | 3.15 |
| 21 | Comedy | 17 | 26.42 |
| 22 | Bossa Nova | 15 | 3.66 |
| 23 | Science Fiction | 13 | 43.76 |
| 24 | Rock And Roll | 12 | 2.24 |
| 25 | Opera | 1 | 2.91 |

_¿Cuáles son las 5 pistas más largas? Muestra el nombre, el álbum y la duración en minutos._
| album | nombre_track | duracion_minutos |
|-------------------------------------------|--------------------------------------|------------------|
| Battlestar Galactica, Season 3 | Occupation / Precipice | 88 |
| Lost, Season 3 | Through a Looking Glass | 84 |
| Battlestar Galactica (Classic), Season 1 | Battlestar Galactica, Pt. 1 | 49 |
| Battlestar Galactica (Classic), Season 1 | Battlestar Galactica, Pt. 2 | 49 |
| Battlestar Galactica (Classic), Season 1 | The Man With Nine Lives | 49 |

_¿Cuántas pistas tienen un UnitPrice superior a $0.99? ¿Qué porcentaje representan del total?_
hay 213 pistas que superan ese precio, lo que representa el 6,08\% del total

_Calcula la media, mínimo, máximo y varianza (en SQL) de la duración en milisegundos de todas las pistas._
| promedio | minimo | maximo | varianza |
|----------|--------|--------|---------------|
| 393599.2 | 1071 | 5286953| 286149105505 |

# Ejercicio 2

_¿Cuál es el total de ingresos generados por la tienda? ¿Y el promedio por factura?_
El total de ingresos generado por la tienda es de 2328.6, el promedio por factura es de 5.65

_¿Cuántas facturas se emitieron por año? Ordena cronológicamente._
| año | facturas_totales |
|------|------------------|
| 2021 | 83 |
| 2022 | 83 |
| 2023 | 83 |
| 2024 | 83 |
| 2025 | 80 |

_Identifica los 5 países con más ingresos. Muestra: país, número de facturas, ingreso total y promedio por factura._
| pais | ingreso_total | promedio_por_factura |
|---------|--------------|----------------------|
| USA | 523.06 | 5.75 |
| Canada | 303.96 | 5.43 |
| France | 195.10 | 5.57 |
| Brazil | 190.10 | 5.43 |
| Germany | 156.48 | 5.59 |

_¿Cuál es la desviación estándar del total de facturas? Calcula primero la varianza en SQL y luego obtén la raíz en R o Python_
4.74

_Encuentra los meses con mayor y menor ingreso promedio._
| mes | promedio_mensual |
|---------|------------------|
| 2024-09 | 7.785 |
| 2023-11 | 3.960 |
