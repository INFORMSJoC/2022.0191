# Data for replication

This file delinate the way to determine problem instances that are solved using the the Sequential Follower Refinement (SFR) Algorithm and the scenario data for the Sample Average Approximation (SAA) algorithm. 

## Instances for the SFR Algorithm
Excel file _Data-SFR.xlsx_ consists of _6_ excel sheets titled _n=60 d^l_, _n=60 d^o_, _n=40 d^l_, _n=40 d^o_, _n=20 d^l_ and _n=40 d^o_. Sheet _n=60 d^l_ gives the nominal times (_d^l_i_) of all surgries across _10_ instances with _n=60_ sugeries. In this sheet, entry _(i,j)_ gives the nominal surgery time (in minutes) of surgery _j_ in instance _i_. 

Similary, Sheet _n=60 d^l_ contains information on the maximal additional time _(d^o_i)_ over the nominal surgery time  for all surgeries across these same ten instances with _60_ surgeries. Here, each entry _(i,j)_ gives the maximal additional time (in minutes) of surgery _j_ in instance _i_. 

The other four sheets contain similar data for problem instances involving _40_ and _20_ surgeries. Additional parameter values can be found in section 7.1 of the paper.

## Scenario Data for the SAA Algorithm

Excel file _Data-SAA.xlsx_ consists of _12_ excel sheets. Within these sheets, there are _9_ sheets labeled _n=n1, k scenarios_, where n1 can be 60, 40, or 20, and k represents the number of scenarios (10, 50, or 100). Each of these sheets provides surgery times for _k_ scenarios across all _10_ instances with _n=n1_ surgeries. In these sheets, there are _n1_ columns, one for each surgery, and _10k_ rows. The first _k_ rows display the surgery times for scenarios _1_ to _k_ in instance _1_, the next _k_ rows for scenarios _1_ to _k_ in instance _2_, and so on.

Additionally, there are three sheets titled _n=n1, 1000 scenarios_ for each _n1_ (_60_, _40_, and _20_). These sheets contain surgery times for _1000_ scenarios across all _10_ instances with _n=n1_ surgeries. These scenarios are used to determine the average-case performance of solutions obtained from SAA and SFR. The organization of these sheets is consistent with the other nine sheets. For more details, we refer the reader to section 7.4 of the paper.

