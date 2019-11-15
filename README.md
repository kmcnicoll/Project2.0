# Using Data from EPA.gov RADNET to compare radation levels across the State of New York



# The data
EPA.gov (https://www.epa.gov/radnet/near-real-time-and-laboratory-data-state) is a government agencies website that duties include testing water throughout the country to moniter radation levels. The goal is to make sure American's and other inhabitants of this land are not being exposed to unsafe Gamma Radation. These tests are done at frequent intervals multiple times a day through out the nation.

# The goal
The aim of this project is to use analyse the water radation data from throughout New York State and see if factors such as time of year or location effects the radation in our water.

# Statistical tests used
Our project focused on 3 major questions. Was the radation levels consistent on a month to month basis throughtout the year, were the radation levels consistent between locations within the State of New York and finally, was the dose expsure of radation (nSv/h) in the outlyer city higher then the rest of the state.

The first question about radation levels on a month to month basis was answered using ANOVA test. As you see the null was rejected here aswell and there is a difference in radation based on month.



After seeing the results of the 1st question we were curious if the outlayers shown above from the month of May, were soley a seasonal anomily or if they were connected to certain locations. To answer this we ran another ANOVA test based on location and the NULL was rejected favoring the alternative hypothisis that locations are not equal. From looking at the below graph you can see that Rochester is responisble for the outlayers.



The final question was answered using a one sample z test. We wanted to see if the Dose exposure was greater in Rochester compared to the rest of the states. Our NULL was the it was equal too the rest of the states. Despite the outlayers, with a P value of .70 we are inclined to accept the null and say the overall radation exposure is equal depending on where you live.



# Future Applications and Importance
Gamma radation is not good for homosapiens. A cumulative exposure of 1000 mSv will cause deadly illness's such as cancer in 5/100 victims exposed years later. Our projects mission was to make sure New York States radation levels are safe and on par with eachother. Interestingly in May, in Rochester New York, radation levels were 3 times higher then everywhere else in the state. While it is still considered to be within safe levels it should still be looked into as it is radation in our drinking water.
