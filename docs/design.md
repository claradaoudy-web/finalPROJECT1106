# System Design

1. Program takes 3 temperature inputs and 2 inputs for the temperature range
2. printWarning() is run for all 3 temperature inputs
   - within the function, OutOfRange() is called and checks whether the temperature is within range
   - calls light() function -> turns on light
   - Prints warning/normal and on/off
3. CalculateAvg() runs and returns average of all temperatures
4. All printed code is appended to output file
