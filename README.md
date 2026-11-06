# ☀️ GeoSolar & Aerotermia España — Atlas Climático, Fotovoltaico y Térmico

🌐 **Acceso directo a la plataforma web:** [**https://geosolar-espana.pages.dev/**](https://geosolar-espana.pages.dev/)

**GeoSolar España** es una plataforma de consulta técnica y simulación energética a nivel municipal para instalaciones de **Autoconsumo Solar Fotovoltaico** y **Aerotermia (Bombas de Calor Aire-Agua)** en España, basada en series climáticas horarias y diarias oficiales (**ERA5 / ECMWF** y nomenclátor del **INE**).

---

## 🔬 Metodología Física y Termodinámica

A diferencia de los estimadores comerciales genéricos, cada ficha municipal de [**GeoSolar España**](https://geosolar-espana.pages.dev/) modela las condiciones reales de operación:

### 1. Energía Solar Fotovoltaica
- **Producción específica anual y mensual (`kWh/kWp`):** Calculada a partir de la irradiación global horizontal y el ángulo óptimo de inclinación según latitud y reparto radiativo estacional.
- **Temperatura operativa de célula ($T_{cell}$ — Modelo NOCT):** Cuantificación de la temperatura real alcanzada por el silicio en las horas centrales de radiación.
- **Pérdidas por deriva térmica ($\gamma = -0,38\ \%/^\circ\text{C}$):** Penalización real de rendimiento por calor estival por encima de condiciones estándar ($25\ ^\circ\text{C}$ STC).
- **Horas Solar Pico (HSP) y dimensionamiento de baterías LFP:** Estimación de potencia recomendada (`kWp`) e inversores híbridos según consumo doméstico.

### 2. Aerotermia y Climatización (CTE)
- **Grados-Día de Calefacción ($HDD_{15}$) y Refrigeración ($CDD_{22}$):** Integración térmica diaria para cuantificar la severidad real de invierno y verano.
- **Zona Climática del Código Técnico de la Edificación (CTE):** Clasificación normativa (`A3` a `E1`) y recuento anual de horas de helada ($T < 0\ ^\circ\text{C}$) para evaluar penalizaciones por ciclos de desescarche (*defrost*).
- **Rendimiento Estacional Real ($SCOP$):** Comparativa termodinámica entre emisores de baja temperatura (**Suelo Radiante / Fancoils a $35\ ^\circ\text{C}$**) y alta temperatura (**Radiadores convencionales a $55\ ^\circ\text{C}$**).

---

## 🗺️ Atlas Provincial de Energía Solar y Aerotermia (52 Provincias)

Consulta las comparativas provinciales completas con rankings de irradiación solar, severidad invernal y rendimiento de aerotermia:

| Provincia | Comunidad Autónoma | Enlace al Estudio Provincial |
| :--- | :--- | :--- |
| **A Coruña** | Galicia | [Ver 9 municipios de A Coruña](https://geosolar-espana.pages.dev/provincias/a-coruna) |
| **Albacete** | Castilla-La Mancha | [Ver 6 municipios de Albacete](https://geosolar-espana.pages.dev/provincias/albacete) |
| **Alicante** | Comunitat Valenciana | [Ver 25 municipios de Alicante](https://geosolar-espana.pages.dev/provincias/alicante) |
| **Almería** | Andalucía | [Ver 9 municipios de Almería](https://geosolar-espana.pages.dev/provincias/almeria) |
| **Araba** | País Vasco | [Ver 2 municipios de Araba](https://geosolar-espana.pages.dev/provincias/araba) |
| **Asturias** | Principado de Asturias | [Ver 7 municipios de Asturias](https://geosolar-espana.pages.dev/provincias/asturias) |
| **Badajoz** | Extremadura | [Ver 5 municipios de Badajoz](https://geosolar-espana.pages.dev/provincias/badajoz) |
| **Barcelona** | Cataluña | [Ver 34 municipios de Barcelona](https://geosolar-espana.pages.dev/provincias/barcelona) |
| **Bizkaia** | País Vasco | [Ver 10 municipios de Bizkaia](https://geosolar-espana.pages.dev/provincias/bizkaia) |
| **Burgos** | Castilla y León | [Ver 3 municipios de Burgos](https://geosolar-espana.pages.dev/provincias/burgos) |
| **Cantabria** | Cantabria | [Ver 7 municipios de Cantabria](https://geosolar-espana.pages.dev/provincias/cantabria) |
| **Castellón** | Comunitat Valenciana | [Ver 9 municipios de Castellón](https://geosolar-espana.pages.dev/provincias/castellon) |
| **Ceuta** | Ceuta | [Ver 1 municipios de Ceuta](https://geosolar-espana.pages.dev/provincias/ceuta) |
| **Ciudad Real** | Castilla-La Mancha | [Ver 11 municipios de Ciudad Real](https://geosolar-espana.pages.dev/provincias/ciudad-real) |
| **Cuenca** | Castilla-La Mancha | [Ver 2 municipios de Cuenca](https://geosolar-espana.pages.dev/provincias/cuenca) |
| **Cáceres** | Extremadura | [Ver 2 municipios de Cáceres](https://geosolar-espana.pages.dev/provincias/caceres) |
| **Cádiz** | Andalucía | [Ver 15 municipios de Cádiz](https://geosolar-espana.pages.dev/provincias/cadiz) |
| **Córdoba** | Andalucía | [Ver 8 municipios de Córdoba](https://geosolar-espana.pages.dev/provincias/cordoba) |
| **Gipuzkoa** | País Vasco | [Ver 7 municipios de Gipuzkoa](https://geosolar-espana.pages.dev/provincias/gipuzkoa) |
| **Girona** | Cataluña | [Ver 8 municipios de Girona](https://geosolar-espana.pages.dev/provincias/girona) |
| **Granada** | Andalucía | [Ver 11 municipios de Granada](https://geosolar-espana.pages.dev/provincias/granada) |
| **Guadalajara** | Castilla-La Mancha | [Ver 10 municipios de Guadalajara](https://geosolar-espana.pages.dev/provincias/guadalajara) |
| **Huelva** | Andalucía | [Ver 6 municipios de Huelva](https://geosolar-espana.pages.dev/provincias/huelva) |
| **Huesca** | Aragón | [Ver 3 municipios de Huesca](https://geosolar-espana.pages.dev/provincias/huesca) |
| **Illes Balears** | Illes Balears | [Ver 12 municipios de Illes Balears](https://geosolar-espana.pages.dev/provincias/illes-balears) |
| **Jaén** | Andalucía | [Ver 7 municipios de Jaén](https://geosolar-espana.pages.dev/provincias/jaen) |
| **La Rioja** | La Rioja | [Ver 3 municipios de La Rioja](https://geosolar-espana.pages.dev/provincias/la-rioja) |
| **Las Palmas** | Canarias | [Ver 9 municipios de Las Palmas](https://geosolar-espana.pages.dev/provincias/las-palmas) |
| **León** | Castilla y León | [Ver 4 municipios de León](https://geosolar-espana.pages.dev/provincias/leon) |
| **Lleida** | Cataluña | [Ver 1 municipios de Lleida](https://geosolar-espana.pages.dev/provincias/lleida) |
| **Lugo** | Galicia | [Ver 1 municipios de Lugo](https://geosolar-espana.pages.dev/provincias/lugo) |
| **Madrid** | Comunidad de Madrid | [Ver 72 municipios de Madrid](https://geosolar-espana.pages.dev/provincias/madrid) |
| **Melilla** | Melilla | [Ver 1 municipios de Melilla](https://geosolar-espana.pages.dev/provincias/melilla) |
| **Murcia** | Región de Murcia | [Ver 15 municipios de Murcia](https://geosolar-espana.pages.dev/provincias/murcia) |
| **Málaga** | Andalucía | [Ver 18 municipios de Málaga](https://geosolar-espana.pages.dev/provincias/malaga) |
| **Navarra** | Comunidad Foral de Navarra | [Ver 6 municipios de Navarra](https://geosolar-espana.pages.dev/provincias/navarra) |
| **Ourense** | Galicia | [Ver 1 municipios de Ourense](https://geosolar-espana.pages.dev/provincias/ourense) |
| **Palencia** | Castilla y León | [Ver 1 municipios de Palencia](https://geosolar-espana.pages.dev/provincias/palencia) |
| **Pontevedra** | Galicia | [Ver 9 municipios de Pontevedra](https://geosolar-espana.pages.dev/provincias/pontevedra) |
| **Salamanca** | Castilla y León | [Ver 2 municipios de Salamanca](https://geosolar-espana.pages.dev/provincias/salamanca) |
| **Santa Cruz de Tenerife** | Canarias | [Ver 9 municipios de Santa Cruz de Tenerife](https://geosolar-espana.pages.dev/provincias/santa-cruz-de-tenerife) |
| **Segovia** | Castilla y León | [Ver 1 municipios de Segovia](https://geosolar-espana.pages.dev/provincias/segovia) |
| **Sevilla** | Andalucía | [Ver 22 municipios de Sevilla](https://geosolar-espana.pages.dev/provincias/sevilla) |
| **Soria** | Castilla y León | [Ver 1 municipios de Soria](https://geosolar-espana.pages.dev/provincias/soria) |
| **Tarragona** | Cataluña | [Ver 10 municipios de Tarragona](https://geosolar-espana.pages.dev/provincias/tarragona) |
| **Teruel** | Aragón | [Ver 2 municipios de Teruel](https://geosolar-espana.pages.dev/provincias/teruel) |
| **Toledo** | Castilla-La Mancha | [Ver 14 municipios de Toledo](https://geosolar-espana.pages.dev/provincias/toledo) |
| **Valencia** | Comunitat Valenciana | [Ver 23 municipios de Valencia](https://geosolar-espana.pages.dev/provincias/valencia) |
| **Valladolid** | Castilla y León | [Ver 4 municipios de Valladolid](https://geosolar-espana.pages.dev/provincias/valladolid) |
| **Zamora** | Castilla y León | [Ver 2 municipios de Zamora](https://geosolar-espana.pages.dev/provincias/zamora) |
| **Zaragoza** | Aragón | [Ver 4 municipios de Zaragoza](https://geosolar-espana.pages.dev/provincias/zaragoza) |
| **Ávila** | Castilla y León | [Ver 1 municipios de Ávila](https://geosolar-espana.pages.dev/provincias/avila) |

---

## 🏙️ Estudios Municipales Destacados (Principales Ciudades)

Acceso directo a las calculadoras y fichas técnicas de los 60 municipios más poblados de España (consulta los **465 municipios** en el [**Directorio Completo de Municipios**](./DIRECTORIO_MUNICIPIOS.md)):

- [**Placas Solares y Aerotermia en Madrid (Madrid)**](https://geosolar-espana.pages.dev/municipios/madrid) — Altitud: `657 m`
- [**Placas Solares y Aerotermia en Barcelona (Barcelona)**](https://geosolar-espana.pages.dev/municipios/barcelona) — Altitud: `12 m`
- [**Placas Solares y Aerotermia en València (Valencia)**](https://geosolar-espana.pages.dev/municipios/valencia) — Altitud: `15 m`
- [**Placas Solares y Aerotermia en Sevilla (Sevilla)**](https://geosolar-espana.pages.dev/municipios/sevilla) — Altitud: `14 m`
- [**Placas Solares y Aerotermia en Zaragoza (Zaragoza)**](https://geosolar-espana.pages.dev/municipios/zaragoza) — Altitud: `208 m`
- [**Placas Solares y Aerotermia en Málaga (Málaga)**](https://geosolar-espana.pages.dev/municipios/malaga) — Altitud: `11 m`
- [**Placas Solares y Aerotermia en Murcia (Murcia)**](https://geosolar-espana.pages.dev/municipios/murcia) — Altitud: `43 m`
- [**Placas Solares y Aerotermia en Palma (Illes Balears)**](https://geosolar-espana.pages.dev/municipios/palma) — Altitud: `13 m`
- [**Placas Solares y Aerotermia en Las Palmas de Gran Canaria (Las Palmas)**](https://geosolar-espana.pages.dev/municipios/las-palmas-de-gran-canaria) — Altitud: `8 m`
- [**Placas Solares y Aerotermia en Alicante (Alicante)**](https://geosolar-espana.pages.dev/municipios/alicante) — Altitud: `12 m`
- [**Placas Solares y Aerotermia en Bilbao (Bizkaia)**](https://geosolar-espana.pages.dev/municipios/bilbao) — Altitud: `19 m`
- [**Placas Solares y Aerotermia en Córdoba (Córdoba)**](https://geosolar-espana.pages.dev/municipios/cordoba) — Altitud: `106 m`
- [**Placas Solares y Aerotermia en Valladolid (Valladolid)**](https://geosolar-espana.pages.dev/municipios/valladolid) — Altitud: `690 m`
- [**Placas Solares y Aerotermia en Vigo (Pontevedra)**](https://geosolar-espana.pages.dev/municipios/vigo) — Altitud: `28 m`
- [**Placas Solares y Aerotermia en L'Hospitalet de Llobregat (Barcelona)**](https://geosolar-espana.pages.dev/municipios/l-hospitalet-de-llobregat) — Altitud: `8 m`
- [**Placas Solares y Aerotermia en Gijón (Asturias)**](https://geosolar-espana.pages.dev/municipios/gijon) — Altitud: `10 m`
- [**Placas Solares y Aerotermia en Vitoria-Gasteiz (Araba)**](https://geosolar-espana.pages.dev/municipios/vitoria-gasteiz) — Altitud: `525 m`
- [**Placas Solares y Aerotermia en A Coruña (A Coruña)**](https://geosolar-espana.pages.dev/municipios/a-coruna) — Altitud: `25 m`
- [**Placas Solares y Aerotermia en Elche (Alicante)**](https://geosolar-espana.pages.dev/municipios/elche) — Altitud: `86 m`
- [**Placas Solares y Aerotermia en Granada (Granada)**](https://geosolar-espana.pages.dev/municipios/granada) — Altitud: `684 m`
- [**Placas Solares y Aerotermia en Badalona (Barcelona)**](https://geosolar-espana.pages.dev/municipios/badalona) — Altitud: `6 m`
- [**Placas Solares y Aerotermia en Terrassa (Barcelona)**](https://geosolar-espana.pages.dev/municipios/terrassa) — Altitud: `277 m`
- [**Placas Solares y Aerotermia en Sabadell (Barcelona)**](https://geosolar-espana.pages.dev/municipios/sabadell) — Altitud: `190 m`
- [**Placas Solares y Aerotermia en Cartagena (Murcia)**](https://geosolar-espana.pages.dev/municipios/cartagena) — Altitud: `10 m`
- [**Placas Solares y Aerotermia en Oviedo (Asturias)**](https://geosolar-espana.pages.dev/municipios/oviedo) — Altitud: `232 m`
- [**Placas Solares y Aerotermia en Jerez de la Frontera (Cádiz)**](https://geosolar-espana.pages.dev/municipios/jerez-de-la-frontera) — Altitud: `56 m`
- [**Placas Solares y Aerotermia en Móstoles (Madrid)**](https://geosolar-espana.pages.dev/municipios/mostoles) — Altitud: `660 m`
- [**Placas Solares y Aerotermia en Santa Cruz de Tenerife (Santa Cruz de Tenerife)**](https://geosolar-espana.pages.dev/municipios/santa-cruz-de-tenerife) — Altitud: `35 m`
- [**Placas Solares y Aerotermia en Pamplona (Navarra)**](https://geosolar-espana.pages.dev/municipios/pamplona) — Altitud: `449 m`
- [**Placas Solares y Aerotermia en Almería (Almería)**](https://geosolar-espana.pages.dev/municipios/almeria) — Altitud: `20 m`
- [**Placas Solares y Aerotermia en Alcalá de Henares (Madrid)**](https://geosolar-espana.pages.dev/municipios/alcala-de-henares) — Altitud: `588 m`
- [**Placas Solares y Aerotermia en Leganés (Madrid)**](https://geosolar-espana.pages.dev/municipios/leganes) — Altitud: `665 m`
- [**Placas Solares y Aerotermia en Donostia / San Sebastián (Gipuzkoa)**](https://geosolar-espana.pages.dev/municipios/donostia-san-sebastian) — Altitud: `8 m`
- [**Placas Solares y Aerotermia en Fuenlabrada (Madrid)**](https://geosolar-espana.pages.dev/municipios/fuenlabrada) — Altitud: `664 m`
- [**Placas Solares y Aerotermia en Getafe (Madrid)**](https://geosolar-espana.pages.dev/municipios/getafe) — Altitud: `622 m`
- [**Placas Solares y Aerotermia en Castelló de la Plana (Castellón)**](https://geosolar-espana.pages.dev/municipios/castello-de-la-plana) — Altitud: `27 m`
- [**Placas Solares y Aerotermia en Burgos (Burgos)**](https://geosolar-espana.pages.dev/municipios/burgos) — Altitud: `859 m`
- [**Placas Solares y Aerotermia en Albacete (Albacete)**](https://geosolar-espana.pages.dev/municipios/albacete) — Altitud: `686 m`
- [**Placas Solares y Aerotermia en Santander (Cantabria)**](https://geosolar-espana.pages.dev/municipios/santander) — Altitud: `15 m`
- [**Placas Solares y Aerotermia en Alcorcón (Madrid)**](https://geosolar-espana.pages.dev/municipios/alcorcon) — Altitud: `711 m`
- [**Placas Solares y Aerotermia en San Cristóbal de La Laguna (Santa Cruz de Tenerife)**](https://geosolar-espana.pages.dev/municipios/san-cristobal-de-la-laguna) — Altitud: `546 m`
- [**Placas Solares y Aerotermia en Marbella (Málaga)**](https://geosolar-espana.pages.dev/municipios/marbella) — Altitud: `27 m`
- [**Placas Solares y Aerotermia en Logroño (La Rioja)**](https://geosolar-espana.pages.dev/municipios/logrono) — Altitud: `384 m`
- [**Placas Solares y Aerotermia en Badajoz (Badajoz)**](https://geosolar-espana.pages.dev/municipios/badajoz) — Altitud: `185 m`
- [**Placas Solares y Aerotermia en Salamanca (Salamanca)**](https://geosolar-espana.pages.dev/municipios/salamanca) — Altitud: `798 m`
- [**Placas Solares y Aerotermia en Lleida (Lleida)**](https://geosolar-espana.pages.dev/municipios/lleida) — Altitud: `155 m`
- [**Placas Solares y Aerotermia en Huelva (Huelva)**](https://geosolar-espana.pages.dev/municipios/huelva) — Altitud: `24 m`
- [**Placas Solares y Aerotermia en Dos Hermanas (Sevilla)**](https://geosolar-espana.pages.dev/municipios/dos-hermanas) — Altitud: `42 m`
- [**Placas Solares y Aerotermia en Tarragona (Tarragona)**](https://geosolar-espana.pages.dev/municipios/tarragona) — Altitud: `69 m`
- [**Placas Solares y Aerotermia en Torrejón de Ardoz (Madrid)**](https://geosolar-espana.pages.dev/municipios/torrejon-de-ardoz) — Altitud: `585 m`
- [**Placas Solares y Aerotermia en Parla (Madrid)**](https://geosolar-espana.pages.dev/municipios/parla) — Altitud: `648 m`
- [**Placas Solares y Aerotermia en Mataró (Barcelona)**](https://geosolar-espana.pages.dev/municipios/mataro) — Altitud: `28 m`
- [**Placas Solares y Aerotermia en Algeciras (Cádiz)**](https://geosolar-espana.pages.dev/municipios/algeciras) — Altitud: `20 m`
- [**Placas Solares y Aerotermia en León (León)**](https://geosolar-espana.pages.dev/municipios/leon) — Altitud: `837 m`
- [**Placas Solares y Aerotermia en Santa Coloma de Gramenet (Barcelona)**](https://geosolar-espana.pages.dev/municipios/santa-coloma-de-gramenet) — Altitud: `56 m`
- [**Placas Solares y Aerotermia en Alcobendas (Madrid)**](https://geosolar-espana.pages.dev/municipios/alcobendas) — Altitud: `669 m`
- [**Placas Solares y Aerotermia en Jaén (Jaén)**](https://geosolar-espana.pages.dev/municipios/jaen) — Altitud: `573 m`
- [**Placas Solares y Aerotermia en Cádiz (Cádiz)**](https://geosolar-espana.pages.dev/municipios/cadiz) — Altitud: `11 m`
- [**Placas Solares y Aerotermia en Reus (Tarragona)**](https://geosolar-espana.pages.dev/municipios/reus) — Altitud: `117 m`
- [**Placas Solares y Aerotermia en Roquetas de Mar (Almería)**](https://geosolar-espana.pages.dev/municipios/roquetas-de-mar) — Altitud: `10 m`

👉 **[Ver el Directorio Completo con los 465 Municipios de España](./DIRECTORIO_MUNICIPIOS.md)**

---

## 🌱 Proyecto Climático Hermano: Huerto y Clima España

- 🌐 **Web oficial:** [**https://huerto-clima.pages.dev/**](https://huerto-clima.pages.dev/)
- 📦 **Repositorio de documentación:** [**github.com/naxetem/huerto-clima**](https://github.com/naxetem/huerto-clima)
- **Contenido:** Calendarios de siembra de 22 cultivos hortícolas, fechas seguras de última helada primaveral (percentil 90 a 0 °C y 2 °C con datos de AEMET OpenData y ERA5) y necesidades mensuales de riego ($ET_0$ FAO-56) para los **465 municipios y 52 provincias** de España.

---

## 📄 Aviso Legal y Propiedad Intelectual

© **GeoSolar España** ([geosolar-espana.pages.dev](https://geosolar-espana.pages.dev/)). Todos los derechos reservados.
Este repositorio contiene únicamente la documentación metodológica pública y el directorio geográfico de acceso al portal web. El motor de cálculo termodinámico, las plantillas y el software de compilación son propiedad intelectual privada.
