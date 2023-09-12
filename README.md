# Practical-Assignment-2

The CRISP-DM framework can be used for data mining projects acrosss a variety of industries.
In this case, I need to develop machine learning algortihm that leverages historical data on used cars, including attributes such as model, size, year, region, etc. to predict the selling price of a used car and with that information, predict the kind of buyers for used cars. Using the learning algorithm, we can then predict what factors strongly influence the price of used cars and with that information, various business decisions can be made. 

The VIN number of a car is completely unique. Any rows that have the same VIN number can be considered a duplicate and can be removed.

It is also ideal to remove any rows with the same model, odometer but with a different price so as to not confuse the
learning algorithm.

The id column isn't really a factor that affects the price of a car. The column can be removed completely.

After more data cleaning, I have run a linear regression model on the data.

Here are my conclusions:
Odometer is the number one factor that dictates the price of a car (reverse correlation). The higher the odometer reading,
the lower the price and vice versa. The second most important fasctor is the year the
car was manufactured in. The newer the car, the higher the price. The transmission type is the third most important factor and
condition is the fourth most important factor.

In summary, if a used car dealership is looking to sell higher priced cars, it should consider obtaining cars with low odometer readings that are also relatively new.
