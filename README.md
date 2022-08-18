# CTD-CSV-Generation

Exports a CSV file containing speed of sound data with respect to depth <br />
Interpolates data to put sound speeds at certain depths<br />
<br />
Takes in a folder of pickle files that contain CTD sound speed data. Put this folder in the working directory of the code.<br />
Exported CSV file will also be placed in the working directory. <br />
<br />
User inputs:<br />
Folder Name <br />
osType <br />
Start Date <br />
End Date <br />
<br />
Folder Name - Input for the name of the folder the pickle files are contained within<br />
osType - Due to differences with how Unix based systems and Windows go through directories, it is necessary to specify a \\ for windows and / for unix based systems
Start Date - Start date which you want your CSV data to begin
End Date - End date where you want your CSV data to end
