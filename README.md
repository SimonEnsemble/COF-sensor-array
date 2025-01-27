# Conductive covalent organic frameworks as chemiresistive sensor arrays for the detction and differentiation of gasotransmitters 
:rocket: this repo contains data and code to reproduce the results for:
> Georganna Benedetto, Robert M. Stolz, Zheng Meng, Elissa Shehayeb, Colin T. Morrell, Yu Man Chan, Gbenga Fabusola, Nikolaus Elsaesser, Cory M. Simon, and Katherine A. Mirica "Conductive covalent organic frameworks as chemiresistive sensor arrays for the detction and differentiation of gasotransmitters"

we describe the sequence of steps we took to make our paper reproducible. the output of each step is saved as a file, so you can start at any step.

## required software
required software/packages:
* [Python 3](https://www.python.org/downloads/) version 3.8 or newer
* [Jupyter Notebook](https://jupyter.org/)

## the sensor array response dataset
we obtained the dataset of the response of sensors to gases from experimental collaboration from Dartmouth College led by Dr. Katherine A. Mirica.

## analysis
we run the PCA and performed supervised learning on the sensor array dataset using `sensor_response.ipynb`.

## overview of directories
- `Raw_sensing_data`: contains Microsoft Excel raw response files of sensors to gases at specific carrier at different concentration level [ppm]
- `responses`: contain visualization of the response of sensors to every single experiments (ppm of gas carried in a carrier gas) with the features extracted
