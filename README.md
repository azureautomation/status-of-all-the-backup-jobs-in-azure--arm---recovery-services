Status of all the backup jobs in Azure (ARM ) Recovery services
===============================================================

            

 


  *  This script fetches all the Recovery services vaults in all the subscription and provides status of all the jobs in vaults.

  *  It first fetches all the recovery services vaults in subscriptions. 
  *  Each vault is iterated usign foreach loop and the details of all jobs in a recovery service vault is retrived in an array variable.

  *  Further the script dispays count each for the jobs failed, missed and completed.




 




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
