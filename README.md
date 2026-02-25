# 🦷 Lo que nadie te dice cuando te cepillas los dientes

> *Un estudio que comenzó con una pregunta simple — ¿qué hay dentro de tu pasta dental? — y terminó revelando una de las paradojas de salud pública más ignoradas de México.*

---

## ¿De qué trata esto?

Cada mañana, 120 millones de mexicanos se cepillan los dientes con productos que contienen **edulcorantes vinculados al aumento de peso, diabetes tipo 2 y enfermedades cardiovasculares** — las mismas enfermedades que matan a más mexicanos cada año.

Este dashboard es el resultado de un estudio cruzado que analiza las **5 marcas líderes de pasta dental en México** desde un ángulo que ningún comercial de TV te mostrará.

---

## 💥 Los 3 hallazgos que nadie esperaba

**1. El círculo vicioso que nadie ve**
La sacarina está en las 5 marcas del top del mercado. Está documentado que altera la microbiota intestinal y **dispara el antojo por azúcar**. Te cepillas para cuidar tus dientes del azúcar... y terminas queriendo más azúcar. En un país donde el 74% de los adultos tiene sobrepeso, esto no es un detalle.

**2. Tus hijos están tragando edulcorantes todos los días**
Los menores de 6 años no escupen la pasta dental eficazmente. Las 5 marcas líderes del mercado no incluyen advertencias al respecto en sus etiquetas mexicanas. Nadie los está protegiendo regulatoriamente — ni las marcas, ni el gobierno.

**3. La OMS tiene un vacío enorme justo aquí**
La advertencia de la OMS de 2023 sobre edulcorantes **no aplica a dentífricos**. Su lógica: "la pasta no se traga". Problema: los niños sí la tragan. Resultado: millones de usuarios infantiles en un área gris sin regulación.

---

## 📊 Qué encontrarás en el dashboard

| Sección | Qué muestra |
|---|---|
| **Las 5 marcas líderes** | Presencia en mercado, flúor y precio por 100g |
| **Contenido de flúor** | Comparativa visual de ppm entre marcas |
| **Nivel de riesgo** | Ranking basado en evidencia científica OMS 2023 |
| **Matriz de edulcorantes** | Qué edulcorante usa cada marca y por qué |
| **Prevalencia de enfermedades** | Las enfermedades relacionadas y cuántos mexicanos las padecen |
| **Marcas vs enfermedades** | Cruce directo: qué marca está asociada a qué riesgo |
| **Precio vs riesgo** | La pregunta incómoda: ¿pagar más te protege más? |
| **Datos interesantes** | Los 3 hallazgos que el estudio no esperaba encontrar |

---

## 🎯 ¿Para quién es esto?

- Padres de familia que quieren elegir mejor
- Profesionales de la salud bucal y nutrición
- Periodistas e investigadores de salud pública
- Cualquier persona que se cepille los dientes y quiera saber qué está usando realmente

---

## 🔬 Origen de los datos

Todos los datos utilizados en este estudio fueron obtenidos de fuentes públicas, institucionales y científicas verificables:

| Fuente | Datos obtenidos |
|---|---|
| **PROFECO** | Composición química, ppm de flúor, precios por 100g y calificaciones de calidad de pastas dentales en México |
| **OMS 2023** | Directrices y advertencias sobre edulcorantes sin azúcar; aclaración de alcance sobre productos de higiene personal |
| **ENSANUT 2023** | Prevalencia nacional de obesidad, sobrepeso y diabetes tipo 2 en población adulta e infantil mexicana |
| **Euromonitor International** | Porcentajes de presencia en el mercado mexicano de dentífricos por marca |
| **COFEPRIS / NOM-219-SSA1** | Límites regulatorios de flúor (máx. 1,500 ppm) y normativa mexicana para productos de higiene bucal |
| **PubMed / Journal of Toxicology and Environmental Health** | Evidencia científica sobre genotoxicidad de sucralosa-6-acetato, efectos de sacarina en microbiota y riesgos del sorbitol |
| **Etiquetas oficiales de producto** | Ingredientes y composición declarada por cada marca en sus versiones para el mercado mexicano |

---

## 🛠️ Herramientas utilizadas

Este estudio fue desarrollado íntegramente con las siguientes herramientas:

**Claude — Anthropic** *(Investigación, análisis y visualización)*
Utilizado para investigar, cruzar fuentes, redactar hallazgos y generar el dashboard interactivo en HTML con Chart.js. Toda la búsqueda, síntesis de información y código de visualización fue producido mediante conversación con Claude Sonnet (claude.ai).

**Excel / Google Sheets** *(Validación de datos)*
Utilizado para organizar y validar manualmente los datos de composición química, precios y prevalencias antes de integrarlos al dashboard.

---

## 👩‍🔬 Autoría

**Glory Meliza Borges Oropeza**
Estudio de divulgación científica independiente · México 2025

---

## 🚀 Próxima fase del estudio

Esta primera versión del estudio fue construida con datos públicos e institucionales. Una segunda fase podría escalar significativamente con las siguientes herramientas:

**🐍 Python** *(Automatización y datos en tiempo real)*
Mediante librerías como `BeautifulSoup` y `Selenium`, se podría desarrollar un scraper que monitoree precios de las 5 marcas en tiempo real directamente desde Walmart, Chedraui, Soriana y Farmacias del Ahorro. Esto permitiría detectar variaciones de precio por región, temporada o canal de venta, y correlacionarlas con datos de consumo.

**🗄️ SQL** *(Base de datos de composición química)*
Con una base de datos relacional se podría estructurar un catálogo exhaustivo de todas las pastas dentales disponibles en México — no solo las 5 líderes — incluyendo ingredientes, concentraciones, fabricante, país de origen y clasificación de riesgo. Esto convertiría el estudio en una herramienta de consulta pública permanente y actualizable.

**📊 Expansión potencial**
- Ampliar el análisis a enjuagues bucales y hilo dental
- Incluir marcas de farmacia y marcas propias de supermercado
- Cruzar datos de consumo regional con prevalencia de diabetes por estado en México
- Generar alertas automáticas cuando una marca modifique su fórmula

---

## ⚠️ Nota importante

Este estudio no busca generar alarma ni desacreditar a ninguna marca. Su objetivo es informar. Los riesgos documentados están basados principalmente en consumo alimentario, y la exposición a edulcorantes vía pasta dental en adultos que no la tragan es considerada **mínima por las autoridades sanitarias**. La preocupación central del estudio es la **población infantil** y la **ausencia de regulación específica** para ese segmento.

---

*Dashboard interactivo desarrollado como herramienta de divulgación científica accesible. Todos los datos son verificables en las fuentes citadas.*

---

**Abre el dashboard → `dashboard_pastas_dental.html`**

---

> 🔗 Repositorio: [github.com/gloryborges/pasta-dental-veneno-dulce](https://github.com/gloryborges/pasta-dental-veneno-dulce)
