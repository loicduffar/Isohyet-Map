# Isohyet-Map

This python notebook create a isohyet map (isovalues) from precipitation data at several raingauges. 
The data should be stored by column in an excel file (with header row): raingauge NAME in one column, coordinates (longitude/latitude in decimal degrees) in 2 columns, precipitation data (one column for each event day/month/year). Missing values are allowed (blank cell or non numeric value).

1) Run the 1rst cell below to read and display the precipitation data for one or several events (hour/day/month/year)
2) Run the 2nd cell (Interpolate on a grid) to compute the interpolated precipitation on a fine rectangular grid
3) Run the 3rd cell (Map) to plot the contour map with or without watersed(s)

<img src="https://github.com/loicduffar/Isohyet-Map/blob/master/out/isohyet%20map%202019%2011%2023.png" width="50%"></img>
