# WaterRocket-FlightModel

Program that simulates the flight of a water rocket given initial conditions, and exports flight data to a spreadsheet.

Analysis of the relevant physics was done by me.

## How to use

This program uses the library openpyxl to export to an Excel sheet, which can be installed using `pip install openpyxl`.

You can then configure the initial conditions in the parameters.txt text file, and run the program.

The program will create a new sheet in the Excel spreadsheet file flight_model.xlsx, detailing the pressure, thrust, drag, mass, acceleration, velocity, and position of the water rocket.
