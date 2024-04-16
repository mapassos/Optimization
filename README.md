<h2>Multiple Fitting with differential evolution algorithm</h2>

This is an optimization algorithm used to fit the data collected from a espectroscopy experiment that I did at the lab while I was an undergraduate.
I decided to used this algorithm because we had a non-linear equation to fit and only a few experiment data, and the literature on the subject suggested that.

To obtain the correct fitted values, I defined upper and lower bounds for the parameters that I was trying to get, so we could get the global minima.
To encapsulate the functions that makes up the algorithm, I decided to go for a class. I also decided to use a named tuple to make the code not only easier to read.
The main point here is to minimize a function object, and in this case, I was trying to minimize the <a href=https://en.wikipedia.org/wiki/Goodness_of_fit>chi-squared statistics  for goodness of fit<a/>. 

