# FlightOnTime✈ (Previsión de retrasos de vuelos)
>Equipo: **H12-25-L-Equipo 15-Data Science**

<details open>
<summary>Introducción</summary>

## Descripción general del proyecto: 
El desafío de FlightOnTime es desarrollar una solución predictiva capaz de estimar si un vuelo va a despegar a tiempo o con retraso. Se creará un sistema capaz de estimar la probabilidad de un vuelo para atrasarse o ser puntual. 

### ¿Quienés podrían acceder a este sistema?
>Identificamos nuestro sector de negocio:
```mermaid
block
    columns 3
  a["Sector de negocio"]:3
  block:group1:3
    columns 3
  b("Aviación civil"):1 c("Logística"):1 d("Transporte Aéreo"):1
  end
```

>Identificamos a nuestros clientes:
```mermaid
block
  columns 3
  b["¿A quiénes les afectan los retrasos en los vuelos?"]:3
  block:group1:3
    columns 3
  c("Aeropuertos"):1 d("Aerolíneas"):1 e("Pasajeros"):1
  end
```
Los retrasos en los vuelos causan **insatisfacción** en los pasajeros, **costos extras** para las aerolíneas y **problemas de logística** para los aeropuertos.

### ¿Como podemos anticipar el retraso en un vuelo?
Es una tarea de predicción, por lo que deberíamos preguntarnos: **¿Con que datos podríamos calcular la probabilidad de que un vuelo se retrase?**
```mermaid
block
  columns 4
  a["Información de un vuelo"]:4
  block:group1:2
    columns 2
    b("Aeropuerto de origen"):1 c("Aeropuerto de destino"):1
  end
  block:group2:2
    columns 2
    f("Hora de salida") g("Hora de llegada") h("Distancia") i("Tiempo estimado")
  end
```
### ¿Cuáles son nuestros objetivos?
1. Que los **aeropuertos** puedan planificar mejor el uso de su infraestructura.
2. Que las **aerolíneas** puedan ajustar la operación y minimizen costos extras.
3. Que los **pasajeros** puedan recibir alertas para planear su llegada al aeropuerto.
</details>

<details open>
<summary>Estructura del proyecto (DS)</summary>
  
## Estructura del proyecto (Data Science):
```mermaid
block
  columns 6
  a["Repositorio: flight-on-time-ds "]:2
    block:groupa:6
    columns 2
    b["Data"]:1
    c["Notebooks"]:1
        block:groupb1:1
        b1("Dataset: Flight Delay 2018-2024"):1
        b2("Dataset limpio"):1
        end
        block:groupc1:1
        c1("Análisis exploratorio(.ipynb)"):1
        c2("Entrenamiento(.ipynb)"):1
        c3("Predicción(.ipynb)"):1
        end
    d["Models"]:1
    e["Src"]:1
        block:groupd1:1
        d1("Modelo final entrenado(.joblib)"):1
        d2("Codificador(.joblib)"):1
        end
        block:groupe1:1
        e1("Configuración API (FastAPI)"):1
        e2("Otros"):1
        end
    f["Requiriments.txt"]:1
    g[".gitignore"]:1 
    end
```
</details>












