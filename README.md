# NeutrinosML 

**Author**: Maria Grazia Miccoli 
## Overview 
**NeutrinosML** is a project created to tackle the Machine Learning university exam. The main aim is to predict the direction of neutrinos in terms of azimuth and zenith angles, using data from the IceCube telescope at the South Pole. This work was conducted to demonstrate that simple approaches, such as basic neural networks, can achieve valid results compared to complex models. 
The project includes: 
1. **Data preprocessing**: filters to reduce noise and improve the representativeness of the data. 
2. **Predictive models**: neural networks tested on preprocessed data, comparing different architectures. 
## Data 
The original datasets come from the Kaggle competition ‘[IceCube - Neutrinos in Deep Ice](https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice)’. To limit the impact of computational resources, a subset called `icecube_3` was created by merging three initial batches of the training dataset (`batch_1.parquet`, `batch_10.parquet`, `batch_100.parquet`). 

## Project Structure 
- **Preprocessing.ipynb**: notebook for data cleaning, noise removal and construction of input matrices (time and charge). 
- **Models.ipynb**: notebook for construction and evaluation of neural networks for azimuth and zenith angle prediction. 
- **Report.pdf**: comprehensive document describing the entire process, from data preparation to the results obtained.
- 
## How to use 
1. **Clon the repository**: 
``bash 
git clone https://github.com/MariaGraziaMiccoli/NeutrinosML.git '''

3. **Download the datasets**: 
Visit the dataset Kaggle page and place the `.parquet` files in the same directory as the project. 
4. **Execute notebooks**: 
- Run `Preprocessing.ipynb` to generate the input matrices. 
- Run `Models.ipynb` to experiment with the neural network models. 

## Conclusions 
NeutrinosML shows that even simple models can achieve competitive results in predicting neutrino trajectories, paving the way for further studies with complete datasets and greater computational resources. 

## Licence 
[Specify if there is a licence]. 

