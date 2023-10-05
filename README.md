# PSSEcompare
## DESCRIPTION:
Compares PSS®E sav or raw files using python and output difference in excel or py files.This is the commandline version 
based on [Gridcompare](http://www.whit.com.au/gridcompare/) with the added fuctionality to include raw files as inputs.


## HISTORY: 
This is a fork from the [original_repo](https://github.com/sbhowmik7/PSSEcompare), adapted to the PSSE34 version.

## USAGE:
the main file is <i> runPSSECompare.py</i>. Modify this to change the default inputs to or use the command line version
> python -m runPSSEcompare -o {Originalfile} -c {File2compare} -x[WriteoutExcelFile]

## MODIFICATION:
Use *app_settings.py* to change some of the paths as well as some of the settings

## USES: 
Public modules/library:
* openpyxl
* orderdict

## Other:
pssepath

## TESTED:
Tested on Windows with PSS®E 34 and their respective python versions (2.7)

__email:__ *sbhowmik at rocketmail dot com*
