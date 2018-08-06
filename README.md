                                        # Devops-Clarification
                                        
                                        updated Interview questions 

please share your question i will make clear your doubts..

Doubt in Jenkins Pipeline : 
How to write the shell script command to deploy or move the any builld war file to destination folder.
ie for example" 
from C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\AntExample.war to C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\Ant output
 sh cp 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist' 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\Ant Output'   this is not working 
 
 Getting error as:
 war:
      [war] Building war: C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\AntExample.war

BUILD SUCCESSFUL
Total time: 2 seconds
[Pipeline] sh
[C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3] Running shell script
+ sh cp 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\AntExample.war' 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\Ant Output'
/usr/bin/cp: /usr/bin/cp: cannot execute binary file
ps: unknown option -- o
Try `ps --help' for more information.
[Pipeline] }
[Pipeline] // node
[Pipeline] End of Pipeline
ERROR: script returned exit code 126
Finished: FAILURE
