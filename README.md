                                        # Devops-Clarification
                                        
                                        updated Interview questions 

please share your question i will make clear your doubts..

Doubt in Jenkins Pipeline : 
How to write the shell script command to deploy or move the any builld war file to destination folder.
ie for example" 
from C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\AntExample.war to C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\Ant output
 sh cp 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist' 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\Ant Output'   this is not working 
 
Solutation:-
select SH shell script and give like below.
cp -r "sorce path" "destination path"
