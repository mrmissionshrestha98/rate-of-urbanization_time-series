# Urbanization and Land Cover Change in Pokhara, Nepal (1991-2021)

Bachelor's thesis project (B.Sc. Forestry, Tribhuvan University, 2022). Land cover change in Pokhara Metropolitan City was mapped with Google Earth Engine and a Random Forest classifier, then linked to a household survey on water scarcity.

> **Note:** The original GEE script was lost, and the code in `scripts/` is a partial reconstruction that is not verified against the thesis results. The maps and tables below come from the thesis. My newer, working project is here: **[[link to new project](https://github.com/mrmissionshrestha98/bharatpur-lulc-change-gee)]
## Land Cover Maps
<img width="554" height="402" alt="image" src="https://github.com/user-attachments/assets/3ae85ad5-2ce9-4582-937f-c7bd51dc0c1b" />
<img width="554" height="419" alt="image" src="https://github.com/user-attachments/assets/88546a0e-36c8-4760-8032-e3e5a97c5199" />
<img width="554" height="496" alt="image" src="https://github.com/user-attachments/assets/c5ba36c7-a611-44db-8156-d2c30dc437a0" />

## What I did
- Classified Landsat 5 and 8 imagery (1991, 2006, 2021, 30 m) into Forest, Water, Built-up and Agriculture with Random Forest in Google Earth Engine
- Measured class areas and change in ArcGIS
- Surveyed 67 households in the Pudi Khola watershed (Ward 33) on water scarcity and livelihood
## Key results
 
| Class | 1991 | 2006 | 2021 |
|-------|------|------|------|
| Forest | 37.1% | 40.1% | 44.6% |
| Water | 3.5% | 3.8% | 2.8% |
| Built-up | 7.1% | 10.4% | 14.5% |
| Agriculture | 52.2% | 45.7% | 38.1% |
 
- Built-up area roughly doubled between 1991 and 2021
- 91% of surveyed households reported water scarcity linked to urbanization

## Limitations
- Reported accuracy (about 99%) is probably optimistic, since validation samples were likely not independent of training samples
- Four broad classes, 30 m resolution, and a convenience-sample survey in one watershed
