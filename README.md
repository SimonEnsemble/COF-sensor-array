# Conductive covalent organic frameworks as chemiresistive sensor arrays for the detction and differentiation of gasotransmitters 
:rocket: this repo contains data and code to reproduce the results for:
> Georganna Benedetto, Robert M. Stolz, Zheng Meng, Elissa Shehayeb, Colin T. Morrell, Yu Man Chan, Gbenga Fabusola, Nikolaus Elsaesser, Cory M. Simon, and Katherine A. Mirica "Conductive covalent organic frameworks as chemiresistive sensor arrays for the detction and differentiation of gasotransmitters"

we describe the sequence of steps we took to make our paper reproducible. the output of each step is saved as a file, so you can start at any step.

## required software
required software/packages:
* [Python 3](https://www.python.org/downloads/) version 3.8 or newer

## the sensor array response dataset
we obtained the dataset of the response of sensors to gases from experimental collaboration from college of Darthmouth lead by Dr.Katherine A. Mirica.

### analysis and visualizations
we run the PCA and performed supervised learning on the sensor array dataset using `sensor_response.ipynb`. the outputted figures are stored in the `figs` directory. 

## overview of directories
- `Raw_sensing_data`: contains excel raw response files of sensors to gases at specific carrier at different concentration level [ppm]
- `responses`: contain visualization of every single experiments(ppm of gas carried in a carrier gas expose to a COF) with the features extracted
