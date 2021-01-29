# Performance-Analysis-of-Genetic-Algorithms
Here, I use a genetic algorithm to guess the contents of a string. The probability of guessing a 3-letter word (e.g., "cat") is (1/26)^3. For a string like "grocery store", with spaces included and 13 characters, the probability of randomly guessing correctly is (1/27)^13, or 2.5e-19. A genetic algorithm, however, can do this quite quickly. In this project, I vary factors such as pool size, mutation rate, and the way fitness is scaled to gain a deeper understanding of genetic algorithms and how they may be optimized.


## Results
![LinearVsExponentialFitness](https://user-images.githubusercontent.com/55513603/106339257-9ec21e80-625b-11eb-84d3-38b20f3059e8.png)
![MutationRateAnalysis](https://user-images.githubusercontent.com/55513603/106339258-9f5ab500-625b-11eb-8149-ef7f78118acf.png)
![ResultsByPoolSize](https://user-images.githubusercontent.com/55513603/106339260-9ff34b80-625b-11eb-95cf-3c9c3eeae2ce.png)
