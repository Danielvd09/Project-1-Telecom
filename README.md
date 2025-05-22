# Telco KPI Dashboard – Analyse van Opzegging & Klantgedrag (NL/ENG)

**NL (Nederlands)**  
Een realistisch BI-project voor een fictief telecombedrijf. Van ruwe data tot dashboards en aanbevelingen aan management.  
Doel: churn begrijpen, serviceproblemen signaleren, omzetdaling verklaren.

**EN (English)**  
A realistic BI project for a fictional telecom firm. From raw CSVs to dashboards and executive insights.  
Goal: Understand churn, spot support issues, and explain revenue decline.

---

## Zakelijke Context / Business Context

> “Het management van een telecombedrijf maakt zich zorgen over toenemende klantopzeggingen, slechte klantervaringen en dalende omzet.  
> Jij bent de data-analist die moet uitzoeken:  
> - Waarom haken klanten af?  
> - Waar gaat het fout met support?  
> - Welke klantsegmenten zijn winstgevend?  
> - Wat moeten we nú doen?”

---

##  Dataoverzicht

| Bestand | Omschrijving |
|--------|--------------|
| `klanten.csv` | Klantgegevens incl. regio en segment |
| `contracten.csv` | Abonnementen, looptijd en kosten |
| `support_tickets.csv` | Klachten, oplostijd, tevredenheid |
| `maandgebruik.csv` | Maandelijks verbruik (GB/minuten) |
| `productcatalogus.csv` | Producten en abonnementstypes |
| `opzeggingen.csv` | Wie is opgezegd en wanneer |

---

##  Tools Gebruikt

- Python (pandas, matplotlib, seaborn)
- Power BI 
- GitHub (versiebeheer)
- Markdown (documentatie)

---

##  Projectstructuur

```bash
data/raw/               # Originele CSV-bestanden
notebooks/              # Jupyter notebooks voor analyse
dashboard/              # Power BI bestand of Streamlit app
insights/               # Aanbevelingen aan management
assets/screenshots/     # Grafieken en dashboards
scripts/                # Eventuele Python scripts

