#Project
This is stage 0 solved tasks folder.
Please feel free to consult official team-rosaling [repo](https://github.com/Team-Rosalind/team-rosalind-project) for more information. More concrete information can be found there.

#Dependencies
The full version of this project relies on 7 different programming languages. In this repo only Julia language is present (given the default behaviour)
To check full dependencies you can run tests.sh script.
This script will check if all Linux software is installed (awk, sed, parallel), all programming languages (C++, C, octave, python, julia, javascript(node), R) and all python libraries with the version check (pandas==1.1.0, xldr==1.2.0). 
Tests relies only on tests folder with contain 7 script from used languages.
By default tests.sh will download official team-rosalind repo, make test.csv from the output of tests folder and delete the cloned repo.

#Usage
The main functionality of the task is hangled by csv-producer script. This script is goinng to clone team-rosalind default repo and make a csv file out of output of individual scripts. We are using power of `parallel` for faster script executing.

#Contributions
Please navigate to team-rosalind official [repo](https://github.com/Team-Rosalind/team-rosalind-project) to see the contributors and their contribution to the project
