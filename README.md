# cleaning-forex-data for journalists

# What is this?
Simple pandas cleaning code for PHP-USD exchange data published daily by the [Bankers Association of the Philippines](https://bap.org.ph/) for easy access by
journalists.

# Recent updates
|column name|definition|
|---|---|
|*Apr 25*|Updated data and reversed y axis of chart to better show currency movements| 
|*Mar 9*|Made a lot of changes beginning with more updated data, cleaned out NaNs and weekend entries containing zero values. Included a sample analysis on 
how to use data| 

# How to use this?

Simply download the CSV files (found in **raw_data** directory and the notebook and store them in the same path in your computer. Run code in Jupyter notebook. The 
code should conclude with a **combined CSV file** of PHP-USD exchange rate from 2018 to 2022.

This was developed for easy access to foreign exchange data in one file, capable of aiding researchers and journalists.

# Definition of terms

The following information are found in the final CSV file generated by the code:

|column name|definition|
|---|---|
|**date**|trading date. This excludes weekends and holidays| 
|**open**|opening rate of the peso against the US dollar. Market trading begins 9 am every weekday|
|**high**|strongest point of trade by the peso against the greenback|
|**low**|lowest rate reached by the peso against the US dollar at a particular day|  
|**close**|closing foreign exchange rate, which is typically, the rate reported in local media|
|**am_volume**|value of dollars traded from 9 am to noon| 
|**pm_volume**|value of dollars traded from noon to 4 p.m. each day|  
|**total_volume**|total value of dollars traded within the day|     

# Contact

Prinz Magtulis, [ppm2130@columbia.edu](mailto:ppm2130@columbia.edu)

**Comments and suggestions are always welcome! All rights reserved.**
