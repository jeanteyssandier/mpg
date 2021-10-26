# mpg

This scripts estimates the best price at which to buy players on Mon Petit Gazon and suggests an optimal team.
The data to train the K-Neighbors regressor which estimates the best price was picked from my own leagues' transfer windows.
The data for the on-going season can be found here:
https://www.mpgstats.fr/
(english version available too).
Click on the league you want, then "personalisé" (or "custom"). On the top left you will see a button to export the league as an excel sheet. Do this, open the sheet, and save it in the csv format. In the notebook, I call mine ligue1_21.csv.
