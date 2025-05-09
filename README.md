# Equipment_energy_consumption_analysis

Problem Overview
You've been hired as a data scientist for SmartManufacture Inc., a leading industrial automation company. The company has deployed an extensive sensor network throughout one of their client's manufacturing facilities to monitor environmental conditions and energy usage.

The client is concerned about the increasing energy costs associated with their manufacturing equipment. They want to implement a predictive system that can forecast equipment energy consumption based on various environmental factors and sensor readings from different zones of the factory.


# Outcomes

1. Dataset contains a large number of noise and outliers.
2. Contains missing values also. (Perhaps due to sensor fault.)
3. No correlation between features of dataset. Hence it also makes it difficult predict accurate energy consumption estimate. Outliers are also a huge cause.
4. 68 redundant datapoints are also found in dataset.
5. Model achieved R2-score and MAE w.r.t 0.07 and 71.79

# Suggestion

1. Install motion sensors for lights to reduce consumption of energy.
2. Maintain temperature in different zones with proper ventillation or using other conditioning system.
3. Set energy consumption threshold based on behavioral energy consumption in a timespan. It helps in monitoring abnormal usage of energy and also finding the cause of issue.
