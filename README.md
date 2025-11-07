# 📊 OSIPTEL Long Distance Telephony Dashboard (Excel)

An analytical and interactive **Excel dashboard** that visualizes **national and international long-distance call traffic** by telecom operator and traffic type, based on official data from **OSIPTEL** (Supervisory Agency for Private Investment in Telecommunications – Peru).

<img src="docs/thumbnail.png" alt="Dashboard Overview" width="750px">

---

## Project Overview

This project was developed using **Microsoft Excel**, where a **data cleaning** and **structuring process** was performed prior to creating the interactive dashboard.
The final dataset and Excel dashboard were uploaded to **OneDrive** for visualization and sharing.

The dashboard allows users to explore Peru’s long-distance telephony traffic through **interactive filters** and **dynamic visuals** connected to pivot tables.

---

## Dashboard Filters

The dashboard includes three main slicers/timeline controls:

* **Long-Distance Type (`TIPO_LARGA_DISTANCIA`)**

  * Larga Distancia Nacional
  * Larga Distancia Internacional – Saliente
  * Larga Distancia Internacional – Entrante

* **Traffic Type (`TIPO_TRÁFICO`)** – multiple selection allowed
  Typical dataset values include:
  *Interoperabilidad – 15XX*, *Líneas de telefonía móvil*, *Llamada por Llamada*, *No reportado*, *Otros tráficos no incluidos*, *Preselección*, *Tarjetas de pago*, *Teléfonos de uso público de la empresa*, among others.

* **Year (`AÑO`)**
  Timeline covering **2003–2024**, allowing users to analyze traffic evolution over time.
  You can select a single year or a range (e.g., 2010–2018).

### How to Use (Excel)

1. Click slicer buttons to filter; hold **Ctrl** to multi-select.
2. Use the **Year timeline** to define the analysis period (2003–2024).
3. To clear filters, click the **Clear Filter** icon on each slicer/timeline.
4. Ensure all visuals and KPIs remain connected to slicers via **PivotTable Analyze ▸ Filter Connections**.

---

## Dashboard Features

The dashboard provides a clear overview of traffic distribution, operator participation, and temporal trends:

* 📈 **Traffic Evolution Chart:**
  Displays long-distance call volumes over time (2003–2024).

* 🥧 **Distribution by Service Type:**
  Shows the share of national and international (incoming/outgoing) traffic.

* 🏆 **Top Operators by Traffic Volume:**
  Highlights the main companies in national and international segments.

* 📊 **Operator Ranking:**
  Compares the top telecom companies with the highest participation in total traffic.

* ⚖️ **Traffic Comparison by Type:**
  Breaks down volumes by traffic category (mobile lines, preselection, interoperability, etc.).

Each visualization is dynamically updated according to the filters selected.

---

## 📂 Data Source

* **Dataset:** [Tráfico de telefonía de larga distancia por tipo y empresa operadora – OSIPTEL](https://www.datosabiertos.gob.pe/)
* **Organization:** Organismo Supervisor de la Inversión Privada en Telecomunicaciones (OSIPTEL)
* **Coverage:** Peru, 2003–2024
* **Format:** CSV (Processed in Excel)



