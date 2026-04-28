Link of Images from Test plan Jmeter and Profiling (before and after optimization)
https://docs.google.com/document/d/1L_bxmUttOGEzmuhvshGNQ1dW27Qj7sBxqY2Xd6iuFnI/edit?usp=sharing

# Question 1
What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

JMeter measures overall performance such as response time and throughput under load, while IntelliJ Profiler analyzes internal code execution and shows which methods consume the most CPU time.

# Question 2
How does the profiling process help you in identifying and understanding the weak points in your application?

Profiling shows which methods take the longest time to execute, making it easier to locate bottlenecks such as repeated database queries or inefficient loops.

# Question 3
Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Yes, it is effective because it provides detailed insights like flame graphs and method lists that clearly highlight the slow parts of the code.

# Question 4
What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

The main challenge is inconsistent results due to caching and JVM warm-up. I overcome this by running the application multiple times and using consistent test conditions.

# Question 5
What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

It helps quickly identify performance bottlenecks, understand method execution time, and visualize performance using graphs.

# Question 6
How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

I compare both results and focus on trends instead of exact numbers. I also rerun tests multiple times to ensure more stable and reliable results.

# Question 7
What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

I optimize by reducing unnecessary database queries and improving logic efficiency. I ensure functionality is not affected by testing the endpoints again and verifying the output remains correct.