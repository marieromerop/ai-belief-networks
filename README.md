# ai-belief-networks

Hello, 

This repos is for resume purposes-- to show the past work i have completed in the domain of Artificial Intelligence. The purpose of this project was to play around with Bayesian Belief Networks on a software called Netica. We use joint probability tables to draw inferences given specific events. 

The preface of the problem solved was as such:


Assume we have 3 astronomers in different parts of the world who make measurements M1, M2, and M3 of the number  of stars N in some region of the sky. Normally, there is a probability of 0.2 (20%) that the astronomer undercounts by one star; you can assume that the three astronomers never overcount, unless drunk; moreover, if there is no star visible (N=0) the astronomer does not undercount). Moreover, there is a 5% probability that the astronomer is drunk (P(Di=1)=0.05 for i=1,2,3) represented using Boolean random variables D1, D2, and D3), in which case the astronomer overcounts by 0 or 1 or 2 stars but never undercounts, even if N=0 (e.g. if N is 2 a drunk astronomer will count 2 or 3 or 4  stars). Moreover, you can assume if information is missing that each case has the same probability. Design a belief network, and compute the probability of the other variables assuming the following pieces of evidence are given (feel free to use Netica (http://www.norsys.com/download.html ) or any another belief network tool to compute your answers !): 

1.	M1=3 M2=3 M3=1 
2.	M1=3 M2=3 M3=0
3.	N=2, M2=1, M3=0
4.	D1=1 D2=0 M3=3
5.	M1=6 M2=4 D1=1


In order to use this bayesian network, you must install Netica. It is a rather older software, i'm currently working to transfer this into python.

Please check out the report to read my findings/deductions
