
### BN.01

![image](https://github.com/AdTekDev/AI/assets/18588011/a9857a5f-9a16-43ea-be08-98d8d565bf60)


### BN.02 

Let us have three tram lines - 6, 22 and 24 - regularly coming to the stop in front of the faculty building. Line 22 operates more frequently than line 24, 24 goes more often than line 6 (the ratio is 5:3:2, it is kept during all the hours of operation). Line 6 uses a single car setting in 9 out of 10 cases during the daytime, in the evening it always has the only car. Line 22 has one car rarely and only in evenings (1 out of 10 tramcars).  
Line 24 can be short whenever, however, it takes a long setting with 2 cars in 8 out of 10 cases. DiLinh is available by line 24, lines 6 and 22 are headed in the direction of IP Dallat. The line changes appear only when a tram goes to depot (let 24 have its depot in the direction of IP Dallat, 6 and 22 have their depots in the direction of DiLinh).   
Every tenth tram goes to the depot evenly throughout the operation. The evening regime is from 6pm to 24pm, the daytime regime is from 6am to 6pm.   
- a) Draw a correct, efficient and causal Bayesian network.  
- b) Annotate the network with the conditional probability tables.  
- c) It is evening. A short tram is approaching the stop. What is the probability it will go to DiLinh?  
- d) There is a tram 22 standing in the stop. How many cars does it have?  


### BN.03

A patient has a disease N. Physicians measure the value of a parameter P to see the disease development.   
The parameter can take one of the following values flow, medium, highg.   
The value of P is a result of patient’s unobservable condition/state S.   
S can be {good, poor}. The state changes between two consecutive days in one fifth of cases.   
If the patient is in good condition, the value for P is rather low (having 10 sample measurements, 5 of them are low, 3 medium and 2 high), while if the patient is in poor condition, the value is rather high (having 10 measurements, 3 are low, 3 medium and 4 high).   
On arrival to the hospital on day 0, the patient’s condition was unknown, i.e., P(S0 = good) = 0:5.   
- a) Draw the transition and sensor model of the dynamic Bayesian network modeling the domain under consideration,  
- b) calculate probability that the patient is in good condition on day 2 given low P values on days 1 and 2,  
- c) can you determine the most likely patient state sequence in days 0, 1 and 2 without any additional computations?, justify.
