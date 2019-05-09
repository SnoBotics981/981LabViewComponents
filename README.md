981LabViewComponents

The vi's in this directory are intended for all of the 981 unique code. Unless
the file name has a particular year the intent of that vi would be to be
usable for any year robot.


Control Spread Sheet Notes
--------------------------

The control spread sheet is the core piece for the software to run on
different machine. The global variable 'spreadSheet' is created by reading
the control spreadsheet (controlSpreadSheet.csv) and making that global =
variable available to the code.

For reading and writing files to the roboRIO the Control System Hardware
document (2017 version) on pages 101-102 recommend using FileZilla. The link:

https://filezilla-project.org/download.php?type=client

I'd recommend we have this installed on all of our computers that might
interact with our robots.

The vi 'ReadCvsControlSpreadsheet' reads the ControlSpreadsheet, which is
stored as a comma separated spreadsheet.

The tables have been updated for the 2018 version of the software but
should be compatible with older versions of the software.


