# pfa
Python Framework of Automation  
Automation of python scripts with time parameters

## Required Packages
    prettytable
## Installation
    pip install -r requirements.txt
## How Does It Work?
Code add scripts to its list and runs them in order with given try interval.
Type 'help' and 'info' for further information

## Important
In sites.txt the proper form must be the following:  
>a:Name  
>b:Path  
>c:Interval  

In each new line:  
>a  b  c  

To run the scripts properly
each script must return a **'success'** value
after a succesful run.
