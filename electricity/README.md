## Data acquisition

* Screenshots of installed capacity and power generation saved as ```installed-capacity.png``` and ```generation.png``` respectively.
* Used ```Data from Picture``` option to create ```installed-capacity-raw``` and ```electricity-generation-raw``` worksheets inside ```electricity.xlsx``` file.
* Calculated ```Annual Ideal Generation (GWh)``` by multiplying ```Installed Capacity (MW)``` by number of hours in a year (8760) and converted it to GWh by multiplying it with 1e-03, for consistency.
* Entered Transmission and Distribution loss data from the article and calculated the ```Annual Electricity Available (GWh)``` by subtracting the loss from the ```Annual Actual Electricity Generation (GWh)```.
* Calculated the ```Annual Electricity Available per capita (kWh)``` for the given fiscal year by dividing the ```Annual Actual Electricity Generation (GWh)``` by the mid-year population of that fiscal year.
* Repeated the same process as above to produce ```Annual Electricity Consumption (GWh)``` and ```Annual Electricity Consumption per capita (kWh)```.
* Note that electricity lost to T & D losses is not to be counted against consumption, however, it is to be counted against the total available electricity.

