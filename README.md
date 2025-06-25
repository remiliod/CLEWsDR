# CLEWsDR – Modelo Integrado Clima, Tierra, Energía y Agua para República Dominicana

El modelo **CLEWsDR** (Clima, Tierra, Energía y Agua para República Dominicana) es una herramienta de modelación integrada diseñada para apoyar la planificación multisectorial y resiliente frente al cambio climático. Permite analizar simultáneamente las dinámicas e interdependencias de los sistemas de recursos, facilitando la identificación de sinergias y compensaciones entre políticas sectoriales.

![CLEWSDRModelStructure](https://github.com/remiliod/CLEWsDR/blob/main/CLEWsDR-ModelStructure.png)

## Objetivo del Modelo

Evaluar escenarios futuros de desarrollo sostenible para República Dominicana a través del análisis combinado de:

- Uso del suelo
- Disponibilidad y demanda de agua
- Producción agrícola y pecuaria
- Emisiones de gases de efecto invernadero
- Seguridad alimentaria
- Impactos del cambio climático

---

## Escenarios Evaluados

Se diseñaron tres escenarios prospectivos para orientar la formulación de políticas públicas:

- **BAU** (*Business As Usual*): Escenario base sin mejoras tecnológicas ni nuevas políticas.
- **TNR** (*Transición Nacional Resiliente*): Incorpora acciones de tecnificación del riego y mejoras en la productividad agrícola.
- **DPP** (*Degradación por Proyecciones de Precipitación*): Evalúa los impactos de una disminución en las lluvias basada en proyecciones climáticas.

---

## Estructura del Modelo

- **Cobertura regional:** 6 regiones hidrográficas  
  (Atlántica, Yaque del Norte, Yaque del Sur, Este, Yuna-Camú, Ozama-Nizao)
- **Tecnologías:** 295
- **Commodities:** 175
- **Tipos de emisiones:** 9 (CO₂eq, uso del suelo, residuos, etc.)
- **Estaciones climáticas:** 2 (seca / húmeda)
- **Demandas agrícolas:** 12 productos
- **Demandas pecuarias:** 6 productos
- **Demandas sectoriales de agua:** 36 (6 por región)
- **Grupos tecnológicos:** 8

---

## Nomenclatura del Modelo

Los elementos del modelo siguen la convención:


- **TIPO**
  - `AGR`: Agricultura
  - `LNU`: Uso de suelo
  - `MEE`: Producción pecuaria
  - `TIM`: Importación
  - `TEX`: Exportación
  - `TDM`: Demanda
  - `RSC`: Recurso
  - `CRP`: Cultivo

- **PRODUCTO**
  - `SGC`: Caña de azúcar
  - `BAN`: Banano
  - *(otros disponibles en el modelo)*

- **REGIÓN**
  - `ATL`: Atlántica
  - `YAN`: Yaque del Norte
  - `YAS`: Yaque del Sur
  - `EST`: Este
  - `YUN`: Yuna-Camú
  - `OZA`: Ozama-Nizao

---

## Créditos

Este modelo fue desarrollado en el marco del programa **“Integrated and coherent national recovery strategies promoting social inclusion, macroeconomic stability, effective governance and protection of the environment for selected small island developing states”**. El proyecto DA 2326B (SB-022415) tiene como objetivo fortalecer la capacidad de Mauricio, Seychelles, Guinea-Bisáu y República Dominicana para formular e implementar una planificación y políticas nacionales integradas y coherentes que promuevan la inclusión social, la estabilidad macroeconómica, la gobernanza efectiva, la protección del medio ambiente y movilicen a las partes interesadas. Basado en metodologías de planificación integradas y en los principios de la economía azul y verde, el enfoque será apoyar el desarrollo de economías resilientes, diversificadas y con capacidades productivas fortalecidas.

Como parte de los esfuerzos para abordar los retos identificados en materia de sostenibilidad y planificación multisectorial, el Ministerio de Economía, Planificación y Desarrollo (MEPyD), en colaboración con el Departamento de Asuntos Económicos y Sociales de las Naciones Unidas (ONU DAES), ha impulsado el desarrollo de un modelo CLEWs específico para la República Dominicana. Esta iniciativa forma parte de un proyecto global orientado a fortalecer las capacidades nacionales para una recuperación resiliente e inclusiva, en respuesta a los desafíos estructurales acentuados por la pandemia del COVID-19 y por la crisis climática. En el caso dominicano, el modelo CLEWs ha sido ampliado para incluir los sectores de agua y uso del suelo, permitiendo analizar de manera integrada las interrelaciones entre los sistemas de clima, energía, agricultura y recursos hídricos.

---

## Licencia

Este repositorio se publica bajo la licencia MIT, salvo que se indique lo contrario en archivos específicos.

---

## Contacto

Para dudas, colaboración o sugerencias, por favor contactar a:

**Ramón Emilio De Jesús Grullón**  
r.dejesus@ce.pucmm.edu.do

