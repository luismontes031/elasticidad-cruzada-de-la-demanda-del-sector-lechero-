# Análisis del Mercado Lechero en Colombia (2020–2022)

## 📌 Introducción
Entre 2020 y 2022, el mercado de la leche en Colombia experimentó cambios significativos debido a diversos factores que afectaron tanto la producción como el consumo.  
Aunque existieron varios factores en el alza de los costos de producción de leche líquida —mayoritariamente a los pequeños productores campesinos colombianos— en el último trimestre de 2021 y en 2022, la producción se contrajo un **5,1%** debido al incremento en los costos de producción.  

Factores que influyeron en esto:
- Crisis logística global  
- Conflicto entre Rusia y Ucrania  
- Tasa de cambio  
- Condiciones climáticas  

### 📊 Precios y consumo
El precio de la leche presentó incrementos significativos:  
- En diciembre de 2021, el precio nacional se ubicó en **$1.625** para la región 1 y **$1.478** para la región 2.  
- Para abril de 2022, estos precios aumentaron a **$1.977** y **$1.720** respectivamente.  

Estos aumentos contribuyeron a una disminución en el **consumo per cápita de leche**, que pasó de **162 litros anuales por persona en 2021** a **154 litros en 2022**, representando una caída del **4,9%**.  

---

## 📦 Importación de leche en polvo (2020–2022)

**2020**  
- Se importaron **32.763 toneladas** de leche en polvo descremada, con un valor superior a **USD 84 millones**.  
- De este total, **26.640 toneladas** provinieron de Estados Unidos, representando un costo de más de **USD 67,5 millones**.  

**2021**  
- Hasta octubre, las importaciones alcanzaron **24.771 toneladas**, con un valor que superó los **USD 65,3 millones**.  
- De estas, **20.806 toneladas** fueron originarias de Estados Unidos, con un costo cercano a **USD 52,8 millones**.  

**2022**  
- Al finalizar el año, ingresaron al país **72.589 toneladas** de productos lácteos por un valor de **USD 276,67 millones**.  
- Esto representó un **incremento del 19,5% en volumen** y del **52% en valor** en comparación con 2021.  
- Este aumento hizo que las importaciones lácteas de 2022 fueran las más costosas en la historia del país.  

---

## 🚨 Identificación del problema
**Crisis del sector lechero en Colombia (2020–2022):**  
Los microempresarios, mayoritariamente campesinos del sector lechero, manifiestan que la crisis del mercado se debe principalmente a las **importaciones de leche en polvo**.  

---

## ❓ Pregunta / Hipótesis
**Pregunta:**  
¿El mercado de leche en polvo frente al mercado de leche líquida (UHT) está actuando como un bien complementario o como un bien sustituto?  

**Hipótesis:**  
El mercado de leche en polvo y el de leche líquida se analizarán mediante un modelo log-log para determinar si son **sustitutos o complementarios**.  

---

## 📐 Propuesta de análisis
Se plantea la creación de un **modelo log-log de elasticidad cruzada** para el sector lechero colombiano.  
Este modelo calcula el logaritmo de la variable dependiente (Y) y el logaritmo de la variable independiente (X), generando una estimación con el **modelo de Mínimos Cuadrados Ordinarios (OLS)**.  

El objetivo es identificar cómo cambia Y (variable dependiente) en términos porcentuales respecto a X (variable independiente), y analizar su efecto en el mercado.  

Los datos incluyen:  
- Cantidad demandada mensual de leche en polvo entera (kg).  
- Cantidad demandada mensual de leche líquida UHT (litros).  
- Precios totales por mes (2020–2022).  

---

## 🛠️ Método para solución del problema
Mediante el software **R**, se construyen varios modelos log-log para:  
- Analizar la elasticidad propia de la demanda de leche en polvo y leche líquida.  
- Estimar la **elasticidad cruzada de la demanda**, que mide cómo la cantidad demandada de un bien responde al cambio de precio de otro.  

Esto permitirá identificar si la leche en polvo y la leche líquida son bienes **sustitutos** (elasticidad cruzada positiva) o **complementarios** (elasticidad cruzada negativa).  

---

### 🔹 Ejemplo de modelado
1. Modelar el **logaritmo de la cantidad demandada de leche entera líquida** en función del **logaritmo del precio de la leche entera** para todos los meses.  
   - Esto refleja qué tipo de elasticidad tiene este bien.  
![primer modelo](imagenes/elasti5.png)

---
✍️ **Autor**: [Luis Alberto Sánchez Montes]  
📅 **Periodo de análisis**: 2020–2022  
🔎 **Herramientas**: R, Econometría aplicada, Análisis de elasticidad  

