______        _          ______                   ______                                  _               
|  _  \      | |         | ___ \                  | ___ \                                (_)              
| | | | __ _ | |_  __ _  | |_/ /_ __  ___  ______ | |_/ /_ __  ___    ___  ___  ___  ___  _  _ __    __ _ 
| | | |/ _` || __|/ _` | |  __/| '__|/ _ \|______||  __/| '__|/ _ \  / __|/ _ \/ __|/ __|| || '_ \  / _` |
| |/ /| (_| || |_| (_| | | |   | |  |  __/        | |   | |  | (_) || (__|  __/\__ \\__ \| || | | || (_| |
|___/  \__,_| \__|\__,_| \_|   |_|   \___|        \_|   |_|   \___/  \___|\___||___/|___/|_||_| |_| \__, |
                                                                                                     __/ |
                                                                                                    |___/ 

OVERVIEW:

Data preprocessing is the basic operation used for transforming raw data into ungderstandable format. Real world data is most of the times inconsistent and lacks information in certain behaviors and trends. All these issues can be resolved using data preprocessing. It is the most important step in Machine learning. Without this step the machine learning models won't perform correctly. 

Data goes through a series of steps during preprocessing:
# Data Cleaning: Data is cleansed through processes such as filling in missing values, smoothing the noisy data, or resolving the inconsistencies in the data.
# Data Integration: Data with different representations are put together and conflicts within the data are resolved.
# Data Transformation: Data is normalized, aggregated and generalized.
# Data Reduction: This step aims to present a reduced representation of the data in a data warehouse.
# Data Discretization: Involves the reduction of a number of values of a continuous attribute by dividing the range of attribute intervals.

Source of Information : https://www.techopedia.com/definition/14650/data-preprocessing
# Program was done in association with Udemys Machine Learning A-Z course #

WHAT DOES THIS PROGRAM DO:

This program performs the pre-processing of the data supplied to us in the Excel sheet. The data snapshot is given below.

Country	Age	Salary	Purchased
France	44	72000	No
Spain	27	48000	Yes
Germany	30	54000	No
Spain	38	61000	No
Germany	40	Yes
France	35	58000	Yes
Spain		52000	No
France	48	79000	Yes
Germany	50	83000	No
France	37	67000	Yes

This would help fill the missing data and this conventional approach will help us feed this data into any model.

