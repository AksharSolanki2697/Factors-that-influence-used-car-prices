# Practical Application 2


## Context

In this second practical application assignment, I explored a dataset from Kaggle that contains information on three million used cars. My goal was to determine which factors make a car more or less expensive. Following your analysis, you should provide clear recommendations to your client—a used car dealership—as to what consumers value in a used car.

To frame the task, throughout these practical applications we will refer back to a standard process in industry for data projects called CRISP-DM. This process provides a framework for working through a data problem.

## Deliverable

After understanding, preparing, and modeling your data, write up a basic report that details your primary findings. Your audience for this report is a group of used car dealers interested in fine-tuning their inventory.


### Data Description

Based on the initial analysis, following are the attributes available to us in the data. These attributes have been manipulated to create statistical models for inferring what factors contribute to teh price of a vehicle. 

#### Text-based Attributes
- Manufacturer: Who built the vehicle (examples: Nissan, Volvo, Cadillac, etc.)
- Model: Name of the model (eg: 'maxima s sedan 4d' , 's60 t5 momentum sedan 4d' etc.)
- Condition: How the vehicle runs and whether any cosmetic damages ('good', 'excellent', 'fair', 'like new', etc.)
- Cylinders: No of cylinders in the engine ('8 cylinders', '6 cylinders', '4 cylinders', '5 cylinders', etc.)
- Fuel: Type of fuel ('gas', 'other', 'diesel', 'hybrid', 'electric', etc.)
- Title Status: Accident information ('clean', 'rebuilt', 'lien', 'salvage', etc.)
- Transmission: What transmission the car uses ('manual','automatic', etc.)
- Drive: Whether the car is Rear-wheel drive or other types ('rwd', '4wd', 'fwd', etc.)
- Size: Size of the Vehicle ('full-size', 'mid-size', 'compact', 'sub-compact', etc.)
- Type: Vehicle Body Style ('pickup', 'truck', 'other', 'coupe', 'SUV', etc.)
- Paint Color: Exterior color of the vehicle ('white','purple', 'red', etc.)

#### Numerical Attribtues
- Odometer: The amount of miles driven on the used vehicle [Min(0); Max(10000000.0); Mean(98043.33); Median(85548.0); std(213881.50)]
- Price: The price of the vehicle [Min(0); Max(3736928711); Mean(75199.03); Median (13950.0); std(12182282.17)]

#### Spatial Attributes
- Region: Cities in the USA
- State: States in the USA

#### Temporal Attributes
- Year: Vehicle Model Year (~1960-2022)


### Data Exploration and Cleaning

1. Count of used cars over the years

  ![image](https://user-images.githubusercontent.com/12669848/187344876-77bdcb0d-bd16-4431-9a1e-03c59f898757.png)

2. Price of used cars over the years

  ![image](https://user-images.githubusercontent.com/12669848/187344976-9a1b2872-2c7c-4a2c-9112-1d61ba084092.png)

3. Odometer Readings of Vehicles over the years

  ![image](https://user-images.githubusercontent.com/12669848/187345017-601f185d-6057-4cf2-8815-7bb490af193c.png)

4. Price of Cars per Manufacturer

  ![image](https://user-images.githubusercontent.com/12669848/187345109-40cd4802-c3b2-4b1a-b955-2b2c5c937f4c.png)

5. Fuel type of used cars and price impact

  ![image](https://user-images.githubusercontent.com/12669848/187345173-be88dc20-c8c3-414e-9f35-8b91b942fd94.png)


### Results

![image](https://user-images.githubusercontent.com/12669848/187345233-b225c8b9-08ff-43e3-b395-b033c42314fc.png)




