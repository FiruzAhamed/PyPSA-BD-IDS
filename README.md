# PyPSA-BD-IDS  

## Overview  
This repository presents the **PyPSA-BD-IDS** application, an open-source and fully reproducible power system model for Bangladesh. The model is built on the PyPSA-Earth framework and extended to integrate both **demand- and supply-side solutions**, including energy efficiency (EE) and demand-side flexibility (DSF). The model supports strategic planning and policy development by simulating long-term scenarios for a clean, affordable, and reliable electricity system in Bangladesh.  

## Key Features  
- **Integrated Pathways**: First Bangladesh-specific model combining EE and DSF with supply-side expansion to model decarbonization pathway of power sector.  
- **High Resolution**: Spatial resolution of 30 × 30 km and hourly temporal resolution to capture variability in demand and renewables.  
- **Scenario Analysis**: Eight policy-aligned scenarios, including supply-only and integrated demand and supply pathways, to achieve a 100% clean power system by 2050.  
- **System Insights**: Quantifies impacts on installed capacity, generation, costs, land use, jobs, investment, and emissions.  
- **Open & Reproducible**: Fully transparent datasets and workflows to allow replication and extension by other researchers and policymakers.  

## Data Sources  
1. Bangladesh Power Development Board [BPDB](https://bpdb.gov.bd/)
2. Power Grid Bangladesh PLC [PGCB](https://pgcb.gov.bd/)
3. [IEMPM 2023](https://powercell.portal.gov.bd/sites/default/files/files/powercell.portal.gov.bd/page/31883c99_43ce_4c3b_ad66_b51b0f535f4c/2023-12-10-09-41-852dab1f149e15bbf4c0f4d115b8c68e.pdf)
4. [ERA5 Reanalysis Data](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels) 

## How to Replicate the Model  
1. Follow the installation guide for [PyPSA-Earth](https://github.com/pypsa-meets-earth/pypsa-earth).  
2. Use the provided configuration files for each scenario.  
3. Add custom datasets on power plants, costs, demand, and flexibility.  
4. Run scenario optimization using the PyPSA framework.  
5. Review and visualize results
6. Modify config files or input datasets for customized scenario design.  


