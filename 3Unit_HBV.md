# 3. Unit

## Precipitation
* Ice, snow, hail, graupel, sleet and water (rain, drizle)
* Measured at a point (rain gaug) or estimated over an area (satellite or radar)

## Evapotranspiration
* Conversion of a liquid from its surface into a gas
* Traspiration: The transfer of liquid water from plants into the atmosphere as a vapor
* Actual evaporation and 
* potential evaporation: Amount of Evapotranspiration, that would happen, if a unlimited amount of water would be availabel, the Demand of the Atmosphere
## Water Balance
* How do we decide how much water is ther
### Infiltration
* Diagramm: Infiltration Capacity Curve
* More water infiltrated soil, soil gets saturted and can`t absorb that much water
* Variable Infiltration Curve 
* How much is R?
* What portion of the basin has Wm`greater than this value?
  * IfP
* As P increases, so does R
* As E increase, R decreases
### Interflow and Runoff
## Why modelling is reqired?
* Forecast/Prediction
* Instead of expensive and time consuming measurements
* What happens if questions
* summarize and test knowlege
* Education
* Hydrological phenomenon: randomness, three space dimensions, and time

*Essentially, all models are wrong, but some are useful.* **(George Box)**

* Parsimony
  * Scientist cannot obtain a "correct" one by excessive elaboration
* Worrying selectively
  * Must be alert to what is importantly wrong
## Model Structure
* Empirical
* Conceptual
* Physical
### 2. Model calibration
* Calibration Criteria: 
  * Coefficient of determination (R2)
 * Challenges and difficulties: 
   * I. Sometimes you can measure your parameters in the field, other times the parameters are just a conceptual representation
   * III. Calibration criterias can lead to uncertanities, because they can't cover everything
   * IV. Result can be reached by different means
 * Coefficient of determination depends on rang: 
* Calibrate/Train model with time series
* Test model with independet time serise

## Exercise
* Write report
* Input data
  * Precipitation
  * Temperature
  * Potential evaporation
* **Snow routine
  * Input: Precipitation, Temperature
  * Output: Snow pack, snow melt
  * Accumulation of precipitation as snow if temperature --> PTT
  * Simulated snow is multiplied by a correction factor
  * Degree-day method for snowmelt
  * Melt water retention until water ewuivalent of the snowpack
  * When temperatures decreases below Ptt water refreezes again
  * Calculations are carried out seperately
* If there is snow there is less runoff. If there is precipitation there is more discharge (TT = Threshold Temperature)
* Effect of P(cfmax) degree-day factor (mm/(°C day) 
  * Both are influencing the fast response of the hydrograph
* **Soil routine**
* Input: Pot, evaporation, precipitation, snowmelt
* Output: Act. evaporation, soil moisture, grondwater recharge
* if Beta is high, decharge is low
#### Response function
* Input: Ground water recharge (pot. evaporation)
* Output: Runoff to stream, "Groundwater level"
* Threshold parameter (mm): 

