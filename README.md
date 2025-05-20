Gompertz Functions Spreadsheet
© 2025 Andrew D Smith ansmith@ucd.ie	
Educational purposes only. No warranty implied. Use at own risk. I accept no liability for any errors.	
This spreadsheet contains VBA macros associated with Gompertz distribution, together with examples of their use.	
You must enable macros in your security setting for these to work.	
Key functions are:	
GompMean(GompEta, algorithm) 	Mean of Gompertz distributon with shape parameter GompEta and scale parameter b = 1
GompCov(GompEta, algorithm) Coefficient of variation
GompMSkew(GompEta, algorithm)	Moment skewness
GompMKurt(GompEta, algorithm)	Moment excess kurtosis
GompGini(GompEta, algorithm) Gini coeffiicient
GompLSkew(GompEta, algorithm) L-moment skewness
GompLKurt(GompEta, algorithm)	L-moment kurtosis
GompEtafromSurvival(t1, t2, p1, p2)	Eta calculated from two points (t1, p1) and (t2, p2) on the survival function
GompEtafromCoV(CoVtarget	Eta calculated from the Coefficient of Variation; inverse function of GompCov
GompEtafromGini(Ginitarget) 	Eta calculated from the Gini Coefficient; inverse function of GompGini
CriticalEta(IdLower, IdUpper)	Critical value of eta at which location(IdLower) and location(IdUpper) cross over
The algorithm can be 0, 1 or 2. Algorithm 1 applies for small eta, algorithm 2 for large eta, and algorithm 0  picks the best of 1 or 2.
