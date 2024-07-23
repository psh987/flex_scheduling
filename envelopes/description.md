# Description of the flexibility envelopes

In this folder, all flexibility envelopes that were used for the scalability tests can be found. They are grouped into 50 different collections, corresponding to 50 different days, and each collection contains envelopes from 500 buildings. Each envelope, indexed by its name in the data entry of the collection, contains 
1. metadata:
  - a name
  - the "steps" field, giving the number of simulation steps that a relative request can be applied - here 36 steps, so 3 hours
  - a "flex_index" field, giving the average width of the flexibility envelope as a proxy of the available flexibility of the building
2. actual data:
  - the baseline for one day
  - the increase potential, named "max_traj"
  - the decrease potential, named "min_traj"
