# Calibration

Boil 3 liters of water with 1kg of sugar to begin with.  
  
Use a hydrometer to water out and creating solutions **1.050**, **1.040**, **1.030**, **1.020**, **1.010** and last clean water **1.000**.  
  
Configure the iSpindel to report in to Ubidots which gives a straight feedback of the variables the iSpindel is sending, set it to report every 60 seconds or so \(_only for calibration_\). Starting out with reading the angle in SG 1.000 and if needed adjusting the weight to give a start angle of around 25 degrees.  
  
After reading out all angles in the different solutions and recording them. Fill in the values in the calibration spreadsheet for the iSpindel project and it will calculate the formula based on your unit.   
  
Copy the formula into your Polynominal under Configuration and start reading out the values in the different solutions again. In Ubidots Gravity is given in Plato so with the above SG solutions you should see values close to 0, 2.5, 5, 7.5, 10 and 12.5 matching the correct SG.

#### Resources

Excel calibration sheet: [https://github.com/universam1/iSpindel/blob/master/docs/Kalibrierung\_en.xlsm](https://github.com/universam1/iSpindel/blob/master/docs/Kalibrierung_en.xlsm)

More info: [https://github.com/universam1/iSpindel/blob/master/docs/Calibration\_en.md\#formula](https://github.com/universam1/iSpindel/blob/master/docs/Calibration_en.md#formula)  
  


