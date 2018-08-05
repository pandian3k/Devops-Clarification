                                        # Devops-Clarification
                                        
                                        updated Interview questions 

please share your question i will make clear your doubts.

1.Jenkins Pipeline script Doubt:

how to deploy or move the successfull build. ie war file from source directory to destination directory .

Ant war file needs to be moved.
tried this command :

sh cp 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\AntExample.war' 'C:\Program Files (x86)\Jenkins\workspace\Ant Pipeline3\dist\Ant Output'


Getting below error in shell script:
sh  cp 'war:
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
