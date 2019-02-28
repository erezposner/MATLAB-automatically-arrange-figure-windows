# MATLAB-automatically-arrange-figure-windows
arrange/align figures automatically.

INPUT : 
NH : number of grid of vertical direction 
NW : number of grid of horizontal direction 
OUTPUT : 
get every figures that are opened now and arrange them.

autoArrangeFigures selects automatically Monitor1. 
If you are dual(or more than that) monitor user, I recommend to set wide 
monitor as Monitor1.

if you want arrange automatically, type 'autoArrangeFigures(0,0)' or 'autoArrangeFigures()'. 
But maximum number of figures for automatic mode is 27.

if you want specify grid for figures, give numbers for parameters. 
but if your grid size is smaller than required one for accommodating 
all figures, this function changes to automatic mode and if more 
figures are opend than maximum number, then it gives error.

Notes 
+ 2017.1.20 use monitor id(Adam Danz's idea)

leejaejun, Koreatech, Korea Republic, 2014.12.13 
jaejun0201@gmail.com
