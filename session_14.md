# Frequentist definition of probability

# Law of Large numbers
- The law of large numbers states that the more experiments we run, the closer we will tend to get tot the expected probability

# Events and Sample Spaces
- Coin Toss example
- Dice throwing example

# Dependent and Independent Events
# Joint probability
# Marginal Probability

# Conditional Probability
- Similarity to Hypothesis testing

# Bayes theorem
- Prior
- Likelihood
- Posterior
	
# Difference between conditional probability and Bayes theorem

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