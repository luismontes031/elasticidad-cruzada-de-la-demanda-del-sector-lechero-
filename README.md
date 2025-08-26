# elasticidad-cruzada-de-la-demanda-del-sector-lechero-

# Elasticidad Cruzada en el Sector Lácteo Colombiano (2020–2022)

##  Introducción
Entre 2020 y 2022, el mercado de la leche en Colombia experimentó cambios significativos debido a factores externos que afectaron tanto la producción como el consumo.  
Los pequeños productores campesinos fueron los más afectados por el incremento de los costos, lo que llevó a una contracción de la producción del **5,1%** en 2022.  

**Factores principales que incidieron:**
- Crisis logística global (post-Covid).  
- Conflicto Rusia–Ucrania.  
- Tasa de cambio desfavorable.  
- Condiciones climáticas.  

**Precios y consumo:**
- Diciembre 2021: $1.625 (Región 1) y $1.478 (Región 2).  
- Abril 2022: $1.977 (Región 1) y $1.720 (Región 2).  
- Consumo per cápita pasó de **162 litros (2021)** a **154 litros (2022)** → caída del **4,9%**.  

##  Importaciones de leche en polvo
- **2020**: 32.763 t → USD 84 M.  
- **2021**: 24.771 t → USD 65,3 M.  
- **2022**: 72.589 t → USD 276,67 M (máximos históricos, +52% en valor vs 2021).  

El aumento de importaciones agravó la crisis del sector lechero colombiano.

---

##  Problema identificado
Los microempresarios campesinos del sector lechero atribuyen la crisis a la **competencia de la leche en polvo importada**, que presiona los precios a la baja y reduce la demanda de leche líquida.

---

##  Pregunta de investigación
¿La leche en polvo en Colombia actúa como un **bien complementario** de la leche líquida (UHT), o como un **bien sustituto**?

---

##  Metodología
- Modelo econométrico **log-log** con **Mínimos Cuadrados Ordinarios (MCO)**.  
- Variables:
  - Cantidad demandada de leche en polvo (kg).  
  - Cantidad demandada de leche líquida UHT (litros).  
  - Precios mensuales de ambos productos (2020–2022).  
- Software: **R**.  

---

##  Resultados principales

### 1. Elasticidad precio leche líquida (UHT)
- Coeficiente estimado: **0,5671**.  
- p-valor < 0,05 → estadísticamente significativo.  
- Bien **inelástico**: cambios de precio afectan poco la demanda.  
- Coincide con la teoría: es un bien de primera necesidad.  

### 2. Elasticidad cruzada (leche en polvo vs leche líquida)
- Signo del coeficiente: **positivo**.  
- Interpretación: **bienes sustitutos**.  
- Evidencia empírica: al subir el precio de la leche líquida, aumenta la demanda de leche en polvo.  
- Esto respalda lo denunciado por campesinos: la leche en polvo **sustituye** la leche líquida.  

### 3. Elasticidad precio leche en polvo
- Coeficiente estimado > 1 (valor absoluto).  
- Bien **elástico**: la demanda responde fuertemente a variaciones de precio.  

---

##  Conclusiones
- La producción de leche líquida cayó **5,1%** en 2022 por mayores costos.  
- El consumo per cápita bajó de 162 a 154 litros (-4,9%).  
- Las importaciones de leche en polvo se dispararon en 2022 (+52% en valor), desplazando la producción nacional.  
- La leche líquida es un bien **inelástico**, pero en la práctica fue sustituida por leche en polvo debido a:
  - Precio más bajo.  
  - Mayor durabilidad y facilidad logística.  
- Se confirma que **leche en polvo y leche líquida son bienes sustitutos en el mercado colombiano**.  

---

##  Propuesta económica
1. **Agroindustrialización nacional**: transformar excedentes de leche líquida en leche en polvo local.  
2. **Reducción de dependencia de importaciones**, especialmente en contextos de inestabilidad geopolítica.  
3. **Política comercial coherente**: articular seguridad alimentaria, protección al campesino y soberanía productiva.  
4. **Fortalecimiento de cadenas de valor**: conectar producción local con la industria láctea y exportaciones.  

---

##  Relevancia para consultoría agroindustrial
Este análisis de elasticidad cruzada permite:
- Identificar la relación competitiva entre leche líquida y en polvo.  
- Entender la dinámica de sustitución en escenarios de crisis.  
- Diseñar estrategias de política pública y decisiones privadas para proteger al productor nacional.  

---
✍️ **Autor**: [Luis Alberto Sánchez Montes]  
📅 **Periodo de análisis**: 2020–2022  
🔎 **Herramientas**: R, Econometría aplicada, Análisis de elasticidad  

