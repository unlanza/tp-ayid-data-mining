# tp-ayid-data-mining
Repositorio para guardar información relevante sobre el trabajo práctico con defensa en 2024/11/06

## Tabla de contenidos
1. Propuesta.
2. Tareas.

## 1. Propuesta 1 - Videojuegos
**Cliente:**
> Gran empresa distribuidora de videojuegos en Argentina.

**Objetivo:**
> Anticipar la demanda de ventas para el año 2025 e informar el establecimiento de contratos con publicantes en 2025.

**Dataset:**

_Fuente_ - [Video Game Sales Data from VGChartz.com](https://www.kaggle.com/datasets/patkle/video-game-sales-data-from-vgchartzcom)

**Descripción (traído de Kaggle):**
```text
This dataset contains the following data about >60.000 video games scraped from [VGChartz](https://www.vgchartz.com/games/games.php?page=1&order=Sales&ownership=Both&direction=DESC&showtotalsales=1&shownasales=1&showpalsales=1&showjapansales=1&showothersales=1&showpublisher=1&showdeveloper=1&showreleasedate=1&showlastupdate=1&showvgchartzscore=1&showcriticscore=1&showuserscore=1&showshipped=1):

- title
- sales (total, North America, Japan, PAL region + other)
- total_shipped
- publisher
- developer
- release_date
- platform
- scores (user, VGChartz & critic score)

The scraper code can be found [here](https://github.com/patkle/VGChartz-Scrapy-Project).
```

**Muestra:**

![image](https://github.com/user-attachments/assets/775462a4-5b1b-48d5-94e5-3cb21f983a16)


**Algoritmos propuestos:**
- _Clustering:_ para identificar los publicistas con mayores ventas `sales`.
- _Canasta de mercado:_ conocer títulos con más ventas (hay que **modificar** el dataset para obtener los 5 juegos más vendidos, `total_shipped`, de cada publicante) e informar el armado de propuestas comerciales en base a números (negociaciones en base a posibles gastos en producto, merch, publicidad local, etc para disminuir el precio total).

## 2 - Proyecto
- [ ] Votar por un dataset.
- [ ] Limpiar dataset elegido.
- [ ] Hacer demo de datos con `Weka` u `Orange` y resultados (aquí validar con los profes ‼‼‼).
- [ ] Armar presentación.
