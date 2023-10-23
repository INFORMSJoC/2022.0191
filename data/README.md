# Data for replication

This file delinate the way to determine problem instances that are solved using the the Sequential Follower Refinement (SFR) Algorithm and the Sample Average Approximation (SAA) algorithm. 

## Instance Generation for the SFR Algorithm
Excel file _Data-SFR.xlsx_ consists of 6 excel sheets titled _n=60 d^l_, _n=60 d^o_, _n=40 d^l_, _n=40 d^o_, _n=20 d^l_ and _n=40 d^o_. Sheet _n=60 d^l_ gives the nominal times (d^l_i) of all surgries across 10 instances with n=60 sugeries. In this sheet, entry _(i,j)_ gives the nominal surgery time (in minutes) of surgery _j_ in instance _i_. 

Similary, Sheet _n=60 d^l_ contains information on the maximal additional time (d^o_{i}) over the nominal surgery time  for all surgeries across these same ten instances with 60 surgeries. Here, each entry _(i,j)_ gives the maximal additional time (in minutes) of surgery _j_ in instance _i_. 

The other four sheets contain similar data for problem instances involving 40 and 20 surgeries. Additional parameter values can be found in section 7.1 of the paper.
