# Job-Scheduling-Data-Mapping-with-Pandas
Extract data from https://github.com/DIR-LAB/deep-batch-scheduler/tree/master/data , specifically SDSC-SP2-1998-4.2-cln.swf and map the swf data to the pandas dataframe.




## Introduction

#### Super Computers are built to solve complexproblems that require high-speed dataprocessing, such as:
- Spacecraft simulation
- Analyzing cyber attacks and natural disasters
#### This is done by running programs or jobs, which are then scheduled through a process known as job scheduling.

## Why is job scheduling important?
- Minimizes job waiting time, slowdown, or completion time.
- Allows for more complex problems to be solved.

## Objectives
### Methods to improve job scheduling:
- TRIP “Trade-off between Prediction Accuracy and Underestimation Rate in Job Runtime Estimates”
-- ML framework that utilizes data censoring to improve prediction accuracy with a low underestimation rate of job runtimes.
-SchedInspector “SchedInspector: A Batch Job Scheduling Inspector Using Reinforcement Learning”
--Determines the competency of scheduled jobs by examining the decisions of the base job scheduler.

## Method
### Phase 1: Learning
#### During this phase I learned:
- Process of estimating HPC Batch Job Schedulers Runtime
- Methods of improving prediction accuracy and job execution performance
-- TRIP
-- SchedInspector
- Fundamentals of Machine Learning
- Reinforcement Learning
- Pandas
- Jupyter Notebook
### Phase 2: Data Mapping
- Utilized Jupyter Notebook and Pandas to map data from previous traces
- Submit time, Wait time, Run time, Requested Time, User ID, etc
### Phase 3: Machine Learning: Feature Extraction
- Extracted features from previous job traces to determine trends amongst the data

## Results
- Mapped data from previous job traces
- Successfully extracted each of the listed features

## Conclusions
#### This data provides valuable, real-world insight into the performance of job scheduling.
- Features will be compared with other past job traces to determine trends in the data.
- These trends will help in the implementation of the TRIP model and SchedInspector.
- This will allow for a comparison of their benefits and look further into other methods of improving job scheduling performance.

## References
Yuping Fan, Zhiling Lan, Paul Rich, William E. Allcock,
Michael E. Papka Trade-off between Prediction
Accuracy and Underestimation Rate in Job Runtime
Estimates Table III

Di Zhang, Dong Dai, Bing Xie SchedInspector: A Batch
Job Scheduling Inspector Using Reinforcement
Learning

Sample data set: https://raw.githubusercontent.com/DIR-LAB/deep-batch-scheduler/master/data/SDSC-SP2-1998-4.2-cln.swf

