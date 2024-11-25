# Late 20th and 21st century lake energy balance responses to warming in the tropical high Andes. [Original submission - archived]
A repository for "Late 20th and 21st century lake energy balance responses to warming in the tropical high Andes" (in revision, Global and Planetary Change).

Citation:
Sae-Lim, J., Konecky, B.L., Morrill, C., Michelutti, N., Grooms, C., and Smol, J.P. Late 20th and 21st century lake energy balance responses to warming in the tropical high Andes. (pending)

## Abstract
The response of Andean high-alpine lakes (>4,000 m above sea level) to atmospheric warming is poorly understood, in part due to a lack of long-term limnological and meteorological observations. Here, we use in situ, reanalysis, and climate modeling output data paired with a one-dimensional lake energy balance model to investigate the response of lake thermal properties to observed and projected 20th and 21st century warming in the tropical high Andes of Peru. The lake model configuration is based on Lake Sibinacocha (13.86°S, 71.02°W, 4,860 m a.s.l.), the largest high-alpine lake in the Andes. Relationships between recent air and lake temperature changes were investigated using the model forced with 20th/21st-century ERA5-Land climate reanalysis data, and future relationships were investigated using two CMIP6 future climate scenarios with CESM2 (SSP2-4.5 and SSP5-8.5). Results show that Sibinacocha whole-lake temperature has warmed at a rate of 0.085°C/decade between 1981-2019, which is slower than other published estimates from lakes globally despite its high alpine location. Lake Sibinacocha temperatures display interannual variability that aligns with air temperature variations, suggesting that broad climatic teleconnections that affect Andean air temperatures also influence lake temperature and stratification. Under the SSP2-4.5 and SSP5-8.5 scenarios, the model indicates an acceleration of Lake Sibinacocha’s whole-lake warming rate by 4.2 to 8.6 times relative to the modern rate. By 2091-2100, Lake Sibinacocha is projected to increase 2.7°C to 6.1 °C. Lake Sibinacocha is projected to remain well-mixed throughout the 21st century which contributes to warming at all depths rather than increased stratification. Lake Sibinacocha is anticipated to respond more slowly to warming simply due to its size. Therefore, our results should be considered a conservative end-member for other lakes in the tropical high Andes, which due to their shallower sizes will likely respond more quickly to atmospheric warming.

## Highlights
-	Lake thermal properties are well simulated by 1D lake energy balance model.
-	Lake Sibinacocha has warmed more slowly than global lake warming rate estimates.
-	Whole-lake warming rate will accelerate under the SSP2-4.5 and SSP5-8.5 scenarios.
-	Sibinacocha will remain well-mixed due to weak or absent stratification in the future.
-	Future warming will likely drive shifts in lake ecosystems throughout the Andes.

## Notes
- Lake temperature observation data used for data calibration and validation are provided by Neal Michelutti (Queen's University). 
- Weather observation data used for data bias correction are provided by SENAMHI (https://www.senamhi.gob.pe/?&p=estaciones; air temperature, relative humidity, wind speed), and Douglas Hardy (UMass Amherst; radiation data)
- We use ERA5-Land dataset and CMIP6 CESM2 SSP2-4.5, SSP5-8.5, and historical which can be found at https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-land?tab=overview and https://www.cesm.ucar.edu/models/cesm2, respectively.
- The model used in this research can be found at https://github.com/carriemorrill/lake-model.
- Specific parameters used in the lake model are under the Part-1-calibration folder (lake.inc).
- 1000 combinations of ETA and CDRN used during the calibration can be found in the Part-1-calibration folder (lake-params.txt).
