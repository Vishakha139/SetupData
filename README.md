
script to help automate setup_data.yaml generation from excel sheets

Place the script in the same directory as the excell sheet with all the info.
Run the script with 2 arguments: excel file name, and tab name with the pod details.

It will output the setup_data with most of the repititive tasks done.

Example output:

python3 convert.py 
Opening excel file...
Reading sheet...
Collecting server information...
Collecting control information...
Collecting compute information...
Collecting HDD storage information...
Collecting HDD storage information...
Collecting SSD storage information...
Collecting SSD storage information...
Writing temporary servers.yaml file...
Applying Hack1...
Applying Hack2...
Removing temporary files...
setup_data.yaml generated.
All done!
