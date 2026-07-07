# Identificación de Operadores Ineficaces

## Descripción

Este proyecto tiene como objetivo identificar operadores con bajo desempeño dentro del servicio de telecomunicaciones **CallMeMaybe**, mediante el análisis de indicadores operativos, pruebas estadísticas y visualización de datos.

El análisis busca proporcionar información útil para apoyar la toma de decisiones orientadas a mejorar la eficiencia operativa y la experiencia del cliente.

---

## Problema de negocio

La empresa CallMeMaybe necesita identificar objetivamente a los operadores con bajo desempeño para implementar acciones de mejora.

Los principales indicadores analizados fueron:

- Tasa de llamadas perdidas.
- Tiempo promedio de espera.
- Desempeño en llamadas entrantes.

---

## Objetivo

Identificar operadores ineficaces utilizando métricas operativas y análisis estadístico para generar recomendaciones que contribuyan a mejorar el desempeño del centro de atención telefónica.

---

## Conjunto de datos

Se utilizaron dos conjuntos de datos:

- **telecom_dataset_us.csv**
  - Información de llamadas.
  - Operador.
  - Dirección de llamada.
  - Duración.
  - Tiempo de espera.

- **telecom_clients_us.csv**
  - Información de clientes.
  - Plan tarifario.
  - Fechas de contratación.

---
## Metodología

Durante el proyecto se realizaron las siguientes etapas:

1. Limpieza y preparación de datos.
2. Eliminación de registros duplicados.
3. Tratamiento de valores nulos.
4. Conversión de tipos de datos.
5. Análisis Exploratorio de Datos (EDA).
6. Definición de criterios para identificar operadores ineficaces mediante percentiles.
7. Validación mediante pruebas estadísticas.
8. Construcción de dashboard en Tableau.

---

## Resultados principales

Se analizaron **754 operadores**, de los cuales **312 fueron identificados como ineficaces**.

Los operadores con bajo desempeño presentan:

- Mayor tasa de llamadas perdidas.
- Mayor tiempo promedio de espera.
- Menor eficiencia en la atención de llamadas entrantes.

Las pruebas estadísticas confirmaron diferencias significativas entre operadores eficientes e ineficaces (p-value < 0.05).

---

## Recomendaciones de negocio

Como resultado del análisis se proponen las siguientes acciones:

- Implementar monitoreo continuo de indicadores.
- Establecer alertas para operadores con bajo desempeño.
- Reforzar la capacitación en atención de llamadas entrantes.
- Optimizar la distribución de carga de trabajo entre operadores.

---


## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Tableau
- Jupyter Notebook

## Dashboard interactivo

🔗 [Ver Dashboard en Tableau](https://public.tableau.com/app/profile/diego.rivera1654/viz/CallMeMaybe-Anlisisdeoperadores/DesempeodeoperadoresCallMeMaybe)

---
### Tasa de llamadas perdidas

![Tasa de llamadas perdidas](imagenes/Llamadas_perdidas.png)

### Llamadas salientes

![Llamadas salientes](imagenes/Llamadas_salientes.png)

### Tiempo promedio de espera

![Tiempo promedio de espera](imagenes/Tiempo_de_espera.png)


## Estructura del repositorio
📂 imágenes

📂 notebooks

📂 presentación

README.md

---
## Autor

**Diego Rivera Navarro**

Business Analyst | Operations Analyst | Data Analyst
LinkedIn: [Diego Rivera Navarro](https://www.linkedin.com/in/diego-rivera-navarro-350300121)
