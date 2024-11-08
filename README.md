# Heart Disease Prediction 

We explored various optimization algorithms covered in class and evaluated their performance on different types of complex problems. 

The four optimization algorithms evaluated in this report are as follows:
Random Hill Climbing (RHC): This algorithm selects random starting points and optimizes by climbing to the next highest neighboring point. Although it risks getting trapped in local optima, the random starting points increase the likelihood of reaching a global optimum.
Simulated Annealing (SA): Building on RHC, SA introduces a temperature component to decide if the algorithm should move to a higher neighboring point. This feature enhances exploratory behavior, especially at high temperatures, resembling a random walk. At lower temperatures, SA behaves similarly to RHC.
Genetic Algorithm (GA): This approach uses a fitter population to generate offspring, replacing less fit members in each generation. The goal is to evolve a progressively fitter population, much like natural selection.
Mutual Information Maximizing Input Clustering (MIMIC): Starting with a uniform sample, MIMIC uses a density estimator to improve sampling over iterations. Unique to MIMIC, it retains learning history, making it well-suited for more complex, structured problems.
