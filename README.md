# Surfs_up

## Purpose
- The purose of this analysis is to get the temperature data for the months of June and December in Oahu from hawaii.sqlite. sQLite database are falt files, which means they don't have relations whip that connect the data to anything else. The main process is to use jupyter notebook to read the SQLite, write query that extract the information we want, then create the statistics as dataframe and generate the summary statistics. 

### Resources
- Jupyter notebook
- hawaii.sqlite
- VS code


## Results
- Result for June
    - Maximum temperture in June was 85°F, minimum temperture in June was 64°F.
    - Average temperture in June was 74.94°F

- Result for December
    - Maximum temperture in December was 83°F, minimum temperture in December was 56°F.
    - Average temperture in December was 71.04°F

- Compare result
    - To compare standard deviation for both June(3.26) and December(3.75), both were in nearly 3 or 4, which means data are clusterd around the average.

    - After compares termperture in June and December, there's not a big difference of temperature change in Oahu. According to this, the surf and ice cream shop business is sustainable year-round

![](https://github.com/helen3121433/Surfs_up/blob/main/Resources/June_summary.PNG) ![](https://github.com/helen3121433/Surfs_up/blob/main/Resources/Dec_summary.PNG)

## Summary
- According to the temperture summary statics for both June and December, it conludes that temperture degrees are mostly stay the similar through out the year. However, there are also other weather data on the SQLite, precipitation and station number. It would be more accurate if there's summary statistics for both preciatation and data of each station.

- Below are average weather data for each locations.      
    -Table includes, average precipitation, average temperture, maximum, and minimum temperture in June.


    - Graph shows that station 516128 has higher avg prcp in June.



- Below are average weather data for each locations.
    -Table includes, average precipitation, average temperture, maximum, and minimum temperture in December.


    - Graph shows that station 518838 and 514830 has higher avg prcp in December.
