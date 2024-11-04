# NH_Data
## A Repository of New Hampshire Datasets

This project aims to collect and curate various New Hampshire government datasets that are not readily available in machine-readable formats. My goal is to transform these datasets into more accessible formats, such as CSV and JSON, for the benefit of researchers, developers, and the general public.

### Project Overview
This repository will serve as a long-term archive of New Hampshire datasets, including those that are typically short-lived, for example, the Manchester Police logs which only display the past seven days. By regularly pulling and parsing these datasets, I hope to provide a comprehensive resource for users.

**Current Status:** This project is a work in progress. Datasets will be added as they are discovered and can be parsed reliably. Most data will be stored in CSV format and organized with filenames labeled by the date the data covers, but some data will labeled by date of **retrieval, not the date the data covers**. This is due to some datasets containing different date formats but also containing multiple different dates within the data. For an example, see [Energy](Energy/nh-energy-rates-2024-11-02.csv) in which energy rates are updated at different dates and so the `retrieval_date` acts as an "as of" date.  

Most sources will be updated or checked daily.

### Datasets Included

#### Energy
- **Energy Rates:** Current energy rates for residential and small commercial customers are sourced from the [New Hampshire Energy Compare Tool](https://www.energy.nh.gov/engyapps/ceps/shop.aspx), covering all available providers. This includes Residential and Small Commercial rates.

#### Police Data
- **Incident/Interaction Logs:** This section includes police incident and interaction logs, as well as arrest records.
  - **WIP - Concord Arrest Logs:** (https://www.concordnh.gov/848/Records-Division)
    - Appears to be for Purchase only
  - **WIP - Keene Police Logs:** [View Keene Logs](https://keenenh.gov/police/logs)
  - **WIP - Keene Arrest Logs:** (Data to be added)   
  - **Manchester Police Logs:** [View Manchester Logs](https://www.manchesternh.gov/Departments/Police/Police-Log)
  - **WIP - Manchester Arrest Logs:** [View Manchester Arrest Logs](https://www.manchesternh.gov/Portals/2/Departments/police_blog/Police%20Log.pdf)
  - **WIP - Nashua Police Logs:** [View Nashua Logs](https://www.nashuanh.gov/DocumentCenter/Index/2878)
    - Might need OCR for PDF files
  - **WIP - Portsmouth Police Logs** [View Portsmouth Logs](https://www.cityofportsmouth.com/police/police-logs)

  

- **Prison/Inmate Logs:** This section includes prison inmate population records.
  - **WIP - Cheshire County Department of Corrections Population List:** [View Cheshire Inmate List](https://co.cheshire.nh.us/wp-content/uploads/IM-pop.pdf)


*More datasets will be added as they are identified and processed.*

### Contributing
I welcome contributions! If you know of any datasets that would be valuable to include in this repository, please reach out and let me know.  I'm not currently publishing any of the scraping code in this repository, though this may change in the future.

---

Thank you for your interest in NH_Data! Together, we can build a valuable resource for the New Hampshire community.
