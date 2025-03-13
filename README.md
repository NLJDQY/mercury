# mercury# mercury
Introduction

Have you ever taken a proper look at the map of the Roman Empire? At its peak, around 117 A.C., it stretched over an area of around 5 million squared kilometers. From the heat in Northern Africa, to the wet and cold shores of Wales. All over this empire, monuments were built. Sometimes for practical purposes, such as fora, aquaducts or gymnasia, sometimes for recreational purposes, such as hippodromes or theaters, and sometimes for religious purposes, such as temples. All of these monuments represent a piece of Roman culture.

Now, the Roman Empire is not just an empire that rose and fall in a single day. Also, over the years it has taken on many geographical, religious and political forms and shapes That's what made me wonder; what can all these dynamics tell us about Roman monuments that have been discovered all over the empire's area? These thoughts are translated into three questions:

1. Are there more monuments found closer to Rome? Or did the Romans built constructions basically everywhere they set foot?
    Hypothesis: The closer to Rome, the stronger the Roman's culture is visible in a city through monuments.
2. Is it true that the longer a city had been part of the Roman Empire, the more monuments have been found?
    Hypothesis: 
3. What is the probability a temple is found in cities that existed after the non-Christian Western Roman Empire fell (476 A.D.)?
    Hypothesis: When Christianity and Islam became the dominant religions in regions that used to be part of the Roman Empire, one could expect a religous artefact - like temples - where more likely to be demolished.

Data

The data used for this analysis comes from the Cities Database (OXREP databases) by Hanson (2016).
We use two datasets from this database:
- cities.csv: a dimensions table with data descriptive data on all Roman cities
- monuments.csv: a facts table with a list of monuments found, by their names.

Analysis
For all three questions, we train a single linear regression model since all of our target variables are continuous variables.
We create train/test splits with 0.8/0.2 ratio, and a random state set so each run give us the same train/test split.

Conclusion
Unfortunately, all of our analyses result in extremely weak model performances.
None of the three hypothesis can be confirmed using Hanson's (2016) datasets.

References
Hanson, J. W. (2016). Cities Database (OXREP databases). Version 1.0. Accessed (date): <http://oxrep.classics.ox.ac.uk/databases/cities/>. DOI: <https://doi.org/10.5287/bodleian:eqapevAn8>
