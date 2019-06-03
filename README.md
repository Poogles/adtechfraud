## Detecting fraudunlent advertising traffic with Entropy.

This is a 20% time reeimplementation of [this](https://botlab.io/wp-content/uploads/2017/08/v1_anonymous_no_tags-1.pdf) paper.
The untitlted notebook attatched shows the implementation which followed the initial half of the paper.  The hypothesis being that
bots show a high level of entropy, with few addresses visiting a large number of times, compared to a lognormal distribution for 
real user activity.

Upon comparison to our existing datasets the analysis strongly correlated a high level of order within the results to bot activity.

![alt text](https://github.com/Poogles/adtechfraud/blob/master/results.png)
