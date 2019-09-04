-on ios: https://apps.apple.com/us/app/hourstracker-hours-and-pay/id336456412
 on android: https://play.google.com/store/apps/details?id=com.cribasoft.HoursTrackerFree.Android&hl=en

-install latest python
-install latest pip


-install these using pip:
	numpy
	os
	openpyxl

  using:  pip install []

-create run.bat in project root
	cmd /C python .\bin\createWorkhours.py "CSVExport-NN.csv"

-edit bin/Dochazkovy_list_BRIGADNICI.xlsx (name, corp)

in mobile app fill workhours, then export them using *.csv with naming "CSVExport-NN.csv" and replace in project root folder
script loads CSVExport-NN.csv file and updates Dochazkovy_list_BRIGADNICI.xlsx and save as new in project root