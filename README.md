# World-Cup-22-Prediction

1. Extracting historical data by web scrapping.
2. Using the data to predict the winner of FIFA World Cup 2022

# Navigation

`./data` This folder contains the data that has been web scrapped.

`main.ipynb` file contains the world-cup-prediction code.

# Poisson Distribution

The poisson distribution is a discrete probability distribution that describes the number of events occuring in a **fixed time interval** or region of opportunity.

In football, we can consider "**GOAL**" as **an event** that might happen in the 90 minutes of a football match.

## Poisson Distibution: Assumptions

1. The number of events can be counted
2. The occurance of events are independent
3. The rate at which events occur is constant
4. Two events cannot occur at exactly the same instant in time

### Formula

$$ P(X=x) = {λ^x e^{-λ} \over x!} $$



`λ : Expected number if events per time interval`

Here, 

λ: median of goals in 90 minutes (Team A and Team B)

x: number of goals in a match that could be scored by Team A or Team B.


# Dependencies

To start with the development, you will need to install the following libraries:

1. Numpy
2. Pandas
3. Selenium
4. Beautiful Soup
5. Seaborn
6. Matplotlib
7. SciPy

# Setup

Try out the project, follow these steps:

1. Clone the repository

   ```
   git clone https://github.com/vaniseth/World-Cup-22-Prediction.git
   ```
2. Change the directory to the project directory.

   ```
   cd World-Cup-22-Prediction
   ```
3. Install the dependencies.
4. Run the python files.
