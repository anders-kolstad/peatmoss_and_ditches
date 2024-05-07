Years: 2017-2022 

Main response variable: moss height

Main explanatory variables: Disturbance category, yearly climate variables, water table depth

Species data only for 2020-2022

18 quadrats 2017-2020, each with its own adjacent water table well; 28 quadrats for 2021 and 2022

Water table depth for all years, but maybe some data missing from autumn 2019.

Climate data from local weather stations.

_Nr 29 and 30 should be exluded from 2021 and 2022_

`data/growthData.xlsx`
Tabs: one per year. 

Columns:
- **ID**. Unique for each pin, but not each measurement. _old/new_ means the pin has been replaced, and you cannot compare them.
- **Plot_no**. Vegetation quadrats, 1-28(-30).
- **Pin_nr**. 1-16, unique within each quadrat. Cranked wire / Shpagnum brush.
- **Treatment**.
  - M = intact bog.
  - T = near peat exatraction site (T1 = 5 m,  and T2 = 15 meters away)
  - R = near ditch (R1 = 5 m away; R2 = 15 m away)
  - K = edge of mire, adjacent to grassland
  - Hollow
  - Hummock
  
M, T, R, and K are all homogeneous bog lawn.

Hollow and Hummock are microtopographic variation, and should be moved to another column. 
They are located close to the centre of the bog, but it might not work to class them as M.
Hollows are not found close to ditches and other hydrological disturbances.

- **HeigthSPRING_***
  - W = west
  - E = east
  - 1,2 and 3 refers to repeated measured on the same pin + direction combination, done by different people, or by the same person but from north and south.
 
- **HeigthFALL_***
  - same as above
- **HeightSUMMER_***
  - only for 2018 and 2019

- **Date***
  - dd.mm.yyyy
- **Observer***
- **Notes***
- **Comments***


`data/*shp`
- grøfter
- hostamyra_myrmassiv
- torvtak
- vegetasjonsruter19-30
- veipunkter_vannbrønner_ruter_2017
 
