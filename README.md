# French Data Job Market — Analytics Pipeline

End-to-end data pipeline analyzing the French Data job market
to help junior data professionals target their job search.

## Business Need
See [BUSINESS_NEED.md](docs/BUSINESS_NEED.md)

## Architecture (planned)

Sources (LinkedIn, WTTJ, Indeed)
        ↓
Ingestion (Python + Selenium)
        ↓
BigQuery (raw layer)
        ↓
dbt (staging + marts, dimensional modeling)
        ↓
Power BI (dashboard)

## Tech Stack
- **Ingestion:** Python, Selenium, pandas
- **Warehouse:** Google BigQuery
- **Transformation:** dbt Core
- **Visualization:** Power BI
- **Version control:** Git, GitHub

## Roadmap
- [x] Project setup & business need definition
- [ ] Week 1: GCP setup + first ingestion script
- [ ] Week 2: dbt setup + staging models
- [ ] Week 3: dbt marts + quality tests
- [ ] Week 4: Power BI dashboard + documentation

## Author
Hajar Berahou — [LinkedIn](https://linkedin.com/in/hajar-berahou/)
