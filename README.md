# Individual-Homework-Assignment-1
This program uses the Monte Carlo integration method to estimate the value of π and compute the value of a second integral, ∫0 to 1,  10 / (1 + 100x^2) dx

Monte Carlo integration works by randomly sampling points within the integration bounds, evaluating the integrand at each point, and averaging the results to approximate the area under the curve. In this code, π is estimated by evaluating ∫0 to 1,  1 / (1 + x^2) dx = π / 4  and multiplying the result by four, while the second integral demonstrates the method’s performance on a function with a sharper curve. The program includes assertion-based tests to verify the accuracy of the results within a specified tolerance, and a fixed random seed ensures reproducibility. 

To run the program, save the code in a Python file, such as monte_carlo.py , and execute it in a terminal with the command python monte_carlo.py . The output will display the results of both integrals using different sample sizes, showing how accuracy improves with more points.

