# Note
This is a reproduction project as part of the MSR course 2021/22 at UniKo, CS department, SoftLang Team.

## Names of team/students

**Team:** Oscar  
**Members:** 
- Syed Saad Ahmed (219203029) 
- Daniyal Saleem (219203408)
- Raza Mumtaz (220202948)

## Baseline study
### Aspect of the reproduction project
- Team Oscar is choosing one of the most interesting aspects for the reproduction step, which is visualization using the python code which characterizes abstractions of repositories and visualizes the repositories. As one of our papers in assignment [0] was related to the detection and visualization of API usage in large code repositories. One of the motivations for selecting visualization is all of our team members are hands-on with Python.
### Input data
- Input data will be a Git repository.
- Novetta/CLAVIN  (https://github.com/Novetta/CLAVIN)
### Output data
- The output will be visualization in the form of PDF and a HTML file.

## Findings of replication

### Process delta
There are no major changes but we have to install some pre-requisite packages in order to execute the project properly.

### Output delta
There is no difference in the output of the project, the output file are been generated and save in the   `./data/visualization` folder. 

## Implementation of replication
### Hardware requirements
- Processor: Intel(R) Core(TM) i5-5200U CPU @ 2.20GHz   2.20 GHz
- Installed RAM:	6.00 GB
- System type:	64-bit operating system, x64-based processor
- OS:	Windows 10 Home

### Software requirements
- python==3.10
- kaleido==0.2.1
- numpy==1.22.0
- pandas==1.3.5
- plotly==5.5.0
- py4j==0.10.9.2
- pyspark==3.2.0
- python-dateutil==2.8.2
- pytz==2021.3
- six==1.16.0
- tenacity==8.0.1

Note: 	In the terminal, write the following command `pip install -r requirements.txt` in order to install all the pre-requisite packages.
### Validation
- You can open the output file from the data folder `./data/visualization`and verify the output. 

### Data
- The files which are been created in the previous steps of the thesis project, such as files in the `./data/characterization` ,
 `./data/analyzed_data` and `./data/data` folders are being used in order to generate the visualization.