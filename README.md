# system
Shell commands on Linux etc

### Virtual environment

create: `mkvirtualenv myEnv` <br>
start:  `workon myEnv` <br>
leave:  `deactivate` <br>
list all environments: `lsvirtualenv` <br>

### Find files

find file: `find ~/pathToFolder -name "myfile.txt"`
find and list: `find ~/pathToFolder -name "myfile.txt" -exec ls -ltr {} \;`
