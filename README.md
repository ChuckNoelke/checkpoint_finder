# Chnage Point Finder

The module reads measurement data for part tempering and identfies change points in along the process.

## Change Points in Tempering Process

In tempering processes of metal parts after welding typically the following phases apply:

- heating up with controled maximum possible gradient to a target temperature
- holding the target temperature within a certain tolerance
- cooling down the part with controled maximum possible cooling rate

## Applied Algorithm

For finding the respective start points for above phases the Rupture module was selected.

[Ruptures on Github](https://github.com/deepcharles/ruptures.git)

## Description of files

- milestone_finder.py: Main Python module to read libraries and time series data. The output result is displayed on the screen.
- TemperingTestdaten_var3.xlsx: Sample test data 

## Requirements

- motplotlib
- openpyxl
- ruptures