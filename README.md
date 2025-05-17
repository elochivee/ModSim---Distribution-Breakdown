1.	Exponential Distribution 
Problem:
 A support desk gets calls every 10 minutes on average. What is the probability the next call arrives in more than 15 minutes?

Solution:
Formula: P (T>t) = e−λt
λ = average rate of calls per minute
t = time in minutes in testing (15 minutes)
e = euler’s number (2.71828)

λ = 1 call / 10 minutes = 0.1 calls per minute

= P (T>15) = e−0.1x15
= P (T>15) = e−1.5
= P (T>15) = 2.71828-1.5
= 0.2231 or 22.31% 


2.	Normal Distribution 
Problem: 
Test scores are normally distributed with a mean (μ) = 75 and standard deviation (σ) = 10. What is the probability a student scores above 85?

Solution: 
Formula: Z= X−μ / σ
μ = 75 (mean)
σ = 10 (standard deviation)
x = 85 (probability)

Z= X−μ / σ = 85 – 75 / 10
= 10 / 10
= 1

From Z-table look for the corresponding value of 1
P = 1 – 0.84134
= 0.1587 or 15.87%

3.	Poisson Distribution 
Problem: 
A site gets 3 requests per minute. What’s the probability it gets exactly 5 requests in one minute?


Solution:
Formula: P(X=k) = λk ⋅ e−λ / k!
λ = 3 (requests per minute)
k = 5 (probability)

P (5) = 35 x 2.71828-3 / 5!
P (5) = 243 x 0.0498 / 120
P (5) = 12.10 / 120 
P (5) = 0.1008 or 10.08%

4.	Binomial Distribution 
Problem:
A player makes a shot with 70% accuracy. What’s the probability she makes exactly 3 shots out of 5?

Solution:
Formula: P(X=k) = C(n,k) ⋅ pk ⋅ (1−p)n−k
n = 5 (total shots)
k = 3 (success shots)
p = 0.7 or 70% (probability)
1 – p = probability of missing shots

I use combination formula before I integrate it directly with the binomial formula
           C(5,3)= 5! / 3!(5−3)! 
= 5!⋅4!⋅3! / 3!⋅2! 
= 20/2 =10

P = 10 x 0.73 x (1-0.7)5-3
P = 10 x 0.343 x 0.32
P = 10 x 0.343 x 0.09
P = 0.3087 or 30.87%

5.	Triangular Distribution 
Problem: 
Estimated task time:
Minimum: 2 hours
Most likely: 4 hours
Maximum: 6 hours
What’s the expected time?

Solution:
Formula: Expected Time= a+b+c / 3
a = 2 hours, b = 4 hours, c = 6 hours 
Expected Time = 2 + 4 + 6 / 3 
Expected Time = 12 / 3 
Expected Time = 4

6.	Lognormal Distribution 
Problem: 
Log(salary) is normally distributed:
Mean = 10
Std dev = 0.5
What is the median salary?

Solution:
Formula: Median=eμ

Medial = 2.7182810
Median = 22,026

7.	Gamma Distribution 
Problem: 
Earthquakes happen at 2 per year.
What is the probability the 3rd earthquake happens after 2 years?

Solution: 
Formula: P(X>2) = 1 − P(X≤2)
Shape (α or k) = 3 (because we are waiting for the 3rd event),
Rate (λ) = 2 per year,
The scale is 0.5.

I use WolframAlpha - CDF[GammaDistribution[3, 0.5], 2]
P(X≤2) = 0.7619
P(X>2) = 1 − 0.7619 
= 0.2381 or 23.81%

8.	Beta Distribution 
Problem: 
Out of 5 testers, 3 liked a new drink. Use a Beta (4, 3) distribution. What’s the expected success rate?

Solution:
Formula: Expected rate= α / α+β
α = 4, β = 3 
= 4 / 4 + 3
= 4 / 7
= 0.5714 or 57.14%

9.	Weibull Distribution
Problem: 
A lightbulb has a Shape = 2, Scale = 1000
What is the chance it lasts more than 1200 hours?

Solution:
Formula: P(T>t) =e−(t/λ)k
t = 1200 
λ = 1000
k = 2 

P(T>t) =2.71828−(1200/1000)2
P(T>t) =2.71828−(1.2)2
P(T>t) =2.71828−(1.44)
P(T>t) = 0.2369 or 23.69%

10.	Uniform Distribution 
Problem: Pick a number randomly between 10 and 20. What’s the probability it’s less than 13?

Solution: 
Formula: P(a<X<b)= b−a / total range
Total Range = 10 to 20 = 10
a = 13, b = 10 
P = 13 – 10 / 10 
P = 3 / 10
P = 0.3 or 30%



