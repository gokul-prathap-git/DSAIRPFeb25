# Frequentist definition of probability

# Law of Large numbers
- The law of large numbers states that the more experiments we run, the closer we will tend to get tot the expected probability

# Events and Sample Spaces
- Coin Toss example
- Dice throwing example

# Dependent and Independent Events
Dependent Events: These are events where the occurrence of one event affects the probability of the other. For example, drawing two cards from a deck without replacing the first card— the outcome of the first draw influences the second draw.

𝑃
(
𝐴
∩
𝐵
)
=
𝑃
(
𝐴
)
⋅
𝑃
(
𝐵
∣
𝐴
)
Independent Events: These are events where the occurrence of one event does not affect the probability of the other. For instance, rolling a die and flipping a coin are independent actions.

𝑃
(
𝐴
∩
𝐵
)
=
𝑃
(
𝐴
)
⋅
𝑃
(
𝐵
)
# Joint probability
The probability of two events occurring together. It’s denoted as 
𝑃
(
𝐴
∩
𝐵
)
, meaning the probability of 
𝐴
 and 
𝐵
 happening simultaneously.
# Marginal Probability
The probability of a single event occurring, irrespective of any other event. It’s essentially the sum of joint probabilities over all possible outcomes of the other variable(s).
# Conditional Probability
- Similarity to Hypothesis testing

# Bayes theorem
- Prior
- Likelihood
- Posterior
	
# Difference between conditional probability and Bayes theorem
Conditional probability is about calculating 
𝑃
(
𝐴
∣
𝐵
)
, while Bayes' theorem is a tool to reverse 
𝑃
(
𝐴
∣
𝐵
)
 into 
𝑃
(
𝐵
∣
𝐴
)
 using prior and marginal probabilities.
# Expected value

# Essense of Information theory
- Quantifying uncertainity
- Entropy
- Entropy curve calculation
- Cross entropy

# Problem 1: Medical Test Accuracy
A certain disease affects 1% of population. A test of the disease is 99% accurate meaning
- If a person has the disease the test will be positive 99%
- If the person does not have disease, the test will be negative 99%

$P(D)$ : Probability of person has disease
$P(T)$ : Probablity of test is positive

$P(D)$ = 0.01

$P(D')$ = 1-$P(D)$ = 1-0.01 = 0.99

$P(T|D)$ = 0.99

$P(T'|D')$ = 0.99

$P(T|D')$ = 1-$P(T|D)$ = 1-0.99 = 0.01

Find $P(D|T)$  and $P(D|T')$


# Problem 2: Spam Email Classification

Suppose and email is classified as spam if it contains the word "money". Past statistics show:
- 5% of all emails are spam
- 2% non-spam emails contains the word money
- 60% spam emails contains the word money

Find $P(Spam|money)$ and $P(Spam|money')$


# Problem 3 : Sample Space
- List the sample space for tossing two coins 
- What is the sample space for rolling two dice?
- How many possible outcomes exist in selecting a card from a standard deck of 52 playing cards?
- If an experiment consists of flipping a coin and rolling a die, what is the total number of outcomes?

# Problem 4 :Dependent and Independent Events**
- A bag contains 4 red balls and 6 blue balls. If you pick one ball and then another with replacement, are the events independent or dependent?


# Problem 5: Joint and Marginal Probability**
- A dataset shows that 40% of customers purchase Product A, 25% purchase Product B, and 15% purchase both. What is the probability that a customer purchases at least one product? 






# Problem 6:  Expected Value**
- A lottery ticket costs ₹10 and has a 1% chance of winning ₹500. What is the expected value of the ticket?**  
  

# Problem 7:  Entropy & Information Theory**
- What is the entropy of a fair coin toss?**  
 $H(X) = - (0.5 \log_2 0.5 + 0.5 \log_2 0.5)$ = 1

- A probability distribution is $P(X) = (0.8,0.2)$. Calculate its entropy 




