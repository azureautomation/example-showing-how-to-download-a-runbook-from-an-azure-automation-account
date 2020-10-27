Example showing how to download a runbook from an Azure Automation account
==========================================================================

            

 


Example showing how to download a runbook from an automation account so you can call it from a parent python script

You could publish the below code as a new python runbook (hello_world) and then call it with this sample.

#!/usr/bin/env python2

def hello(name):
    print name

This can be useful when you want to have separate runbooks perform tasks but use them within other parent runbooks.



** *** *


 


 

 

 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
