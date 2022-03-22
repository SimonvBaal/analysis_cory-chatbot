# Cory Chatbot Pilot Project

## Description
In this project I conduct the data analysis for the Cory Chatbot pilot study.
Data was collected through  interaction with a chatbot, in addition to 
data from surveys that were administered before and after interaction.

The chatbot was developed to study whether chatbots could be used to change
behaviour to protect public health. In particular, this chatbot aimed to
not only provide information on COVID-19, but also change people's attitudes
to getting tested when they experience symptoms and to increase their certainty
on the acceptability of leaving their houses in different scenarios during a 
lockdown.

## Installation
### Requirements
R(4.0.5)
RStudio

### Instructions
Please download the entire project. Then, you can open the RStudio application, 
click 'File' in the menubar, then click 'Open Project...'. Navigate towards
the storage location for this project and click the .Rproj file. The environment
should load.

The package management for this project was made using 'renv'. This means that
when you run the following command, all the packages with the correct versions
will be loaded.
> renv::restore()

## Usage
It is possible to run this project in multiple ways. The quickest way is to
run from the analysis_cory.Rmd file directly, after which you may run the 
figures_cory.Rmd script file. 
However, if you would like to run the data cleaning file first, to see how the 
data was handled, you may start by running the cleaning_cory.Rmd file.

## Support
Should you have any problems, please send an email to simon.vanbaal1@monash.edu

## Contributing
This project is not open for contributions. However, if you find a mistake,
please contact me via the email address listed above.

## Authors and acknowledgment
I wrote the code for this project myself, but I would like to thank my
collaborators: Farhad Fatehi, Suong Le, Antonio Verdejo-Garcia and Jakob Hohwy

## License
This project is licensed with CC-BY

## Project status
This project is still under development