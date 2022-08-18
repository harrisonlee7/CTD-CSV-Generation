# CTD-CSV-Generation

Exports a CSV file containing speed of sound data with respect to depth <br />
Interpolates data to put sound speeds at certain depths<br />
<br />
Takes in a folder of pickle files that contain CTD sound speed data. Put this folder in the working directory of the code.<br />
Exported CSV file will also be placed in the working directory. <br />
<br />
NOTE: CSV file has depths moved upwards by 2 due to date label taking up first row and 0 being a depth as well.<br />
For example: a depth of 2 on the CSV file would correlate to a depth of 0 in the data. <br />
<br />
User inputs:<br />
Folder Name <br />
osType <br />
Start Date <br />
End Date <br />
<br />
Folder Name - Input for the name of the folder the pickle files are contained within<br />
osType - Due to differences with how Unix based systems and Windows go through directories, it is necessary to specify a \\ for windows and / for unix based systems<br />
Start Date - Start date which you want your CSV data to begin<br />
End Date - End date where you want your CSV data to end
