In this assignment, I have loaded the train dataset.
As per the given questions I have done the following tasks -

a) Handling Missing Values
Missing values in Mileage, Engine, Power, and Seats were imputed using the median of their respective columns due to the small percentage of data missing.
The New_Price column was dropped due to a high percentage (86.06%) of missing data.

b) Removing Units
Units were removed from Mileage, Engine, and Power during the imputation process. These columns now contain purely numerical values.

c) One-Hot Encoding
Fuel_Type and Transmission were converted into numerical one-hot encoded values, creating new columns to represent these categories.

d) Creating a New Feature
A new feature, Car_Age, was added to represent the current age of the cars by subtracting the Year value from the current year (2024).

e) Performing Various Operations
Select Operation: A subset of columns was chosen to focus on specific attributes.
Filter Operation: Initially attempted to filter cars with a Car_Age less than 5 years but adjusted to less than 10 years due to the sample data.
Rename Operation: The Car_Age column was successfully renamed to Age_of_Car.
