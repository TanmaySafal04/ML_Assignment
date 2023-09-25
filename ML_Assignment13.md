1. Provide an example of the concepts of Prior, Posterior, and Likelihood.
2. What role does Bayes&#39; theorem play in the concept learning principle?
3. Offer an example of how the Nave Bayes classifier is used in real life.

4. Can the Nave Bayes classifier be used on continuous numeric data? If so, how can you go about
doing it?

5. What are Bayesian Belief Networks, and how do they work? What are their applications? Are they
capable of resolving a wide range of issues?

6. Passengers are checked in an airport screening system to see if there is an intruder. Let I be the
random variable that indicates whether someone is an intruder I = 1) or not I = 0), and A be the
variable that indicates alarm I = 0). If an intruder is detected with probability P(A = 1|I = 1) = 0.98
and a non-intruder is detected with probability P(A = 1|I = 0) = 0.001, an alarm will be triggered,
implying the error factor. The likelihood of an intruder in the passenger population is P(I = 1) =
0.00001. What are the chances that an alarm would be triggered when an individual is actually an
intruder?

7. An antibiotic resistance test (random variable T) has 1% false positives (i.e., 1% of those who are
not immune to an antibiotic display a positive result in the test) and 5% false negatives (i.e., 1% of
those who are not resistant to an antibiotic show a positive result in the test) (i.e. 5 percent of those
actually resistant to an antibiotic test negative). Assume that 2% of those who were screened were
antibiotic-resistant. Calculate the likelihood that a person who tests positive is actually immune
(random variable D).

8. In order to prepare for the test, a student knows that there will be one question in the exam that
is either form A, B, or C. The chances of getting an A, B, or C on the exam are 30 percent, 20%, and
50 percent, respectively. During the planning, the student solved 9 of 10 type A problems, 2 of 10
type B problems, and 6 of 10 type C problems.

i. What is the likelihood that the student can solve the exam problem?

ii. Given the student&#39;s solution, what is the likelihood that the problem was of form A?

9. A bank installs a CCTV system to track and photograph incoming customers. Despite the constant
influx of customers, we divide the timeline into 5 minute bins. There may be a customer coming into
the bank with a 5% chance in each 5-minute time period, or there may be no customer (again, for
simplicity, we assume that either there is 1 customer or none, not the case of multiple customers). If

there is a client, the CCTV will detect them with a 99 percent probability. If there is no customer, the
camera can take a false photograph with a 10% chance of detecting movement from other objects.

i. How many customers come into the bank on a daily basis (10 hours)?

ii. On a daily basis, how many fake photographs (photographs taken when there is no
customer) and how many missed photographs (photographs taken when there is a customer) are
there?

iii. Explain likelihood that there is a customer if there is a photograph?

10. Create the conditional probability table associated with the node Won Toss in the Bayesian Belief
network to represent the conditional independence assumptions of the Nave Bayes classifier for the
match winning prediction problem in Section 6.4.4.

# Answers

1. Example of Prior, Posterior, and Likelihood:
Let's say you want to estimate the probability of someone having a specific medical condition (Condition C) based on a diagnostic test result (Test T).

Prior Probability (Prior): P(C) is the prior probability of having the condition, which is your initial belief based on general population statistics or previous knowledge.

Likelihood (Likelihood): P(T | C) is the likelihood of getting a positive test result given that the person has the condition. This is determined by the test's sensitivity.

Posterior Probability (Posterior): P(C | T) is the posterior probability, which is your updated belief after considering the test result. It's calculated using Bayes' theorem:
P(C | T) = [P(T | C) * P(C)] / P(T)

For instance, if P(C) is 0.05 (5% of the population has the condition), and P(T | C) is 0.90 (the test is 90% accurate in detecting the condition), and you get a positive test result (T), you can use Bayes' theorem to calculate the updated probability of having the condition (Posterior).

2. Bayes' Theorem in Concept Learning: In concept learning, Bayes' theorem helps in updating our beliefs about a concept based on observed evidence or data. It allows us to calculate the posterior probability of a concept given the prior probability and the likelihood of observing certain data.

3. Example of Naive Bayes Classifier in Real Life:
Naive Bayes classifiers are commonly used in text classification, such as spam email detection. Given an email's content, a Naive Bayes classifier can estimate the probability of it being spam or not based on the words used in the email. Each word is treated as a feature, and the likelihood of observing those words in spam or non-spam emails is calculated. The classifier then assigns a label (spam or not spam) based on the highest probability.

4. Using Naive Bayes with Continuous Numeric Data:
Yes, Naive Bayes can be used with continuous numeric data. To do this, you can assume that the data follows a specific probability distribution (e.g., Gaussian distribution for continuous variables) and estimate the parameters of that distribution (mean and variance) for each class. You can then use these parameters in the likelihood calculation.

5. Bayesian Belief Networks (BBNs):
Bayesian Belief Networks are graphical models that represent probabilistic relationships among a set of variables. They consist of nodes (representing variables) connected by edges (representing probabilistic dependencies). BBNs use Bayes' theorem to update beliefs about variables based on evidence. They find applications in various fields, including healthcare for diagnosis, risk assessment, and decision support, as well as in finance, natural language processing, and more. BBNs can handle a wide range of issues by modeling complex dependencies among variables.

6. Airport Screening System:
To calculate the chances that an alarm would be triggered when an individual is actually an intruder, you can use Bayes' theorem:

P(I = 1|A = 1) = [P(A = 1|I = 1) * P(I = 1)] / [P(A = 1|I = 1) * P(I = 1) + P(A = 1|I = 0) * P(I = 0)]

Substituting the given values:
P(I = 1|A = 1) = [0.98 * 0.00001] / [0.98 * 0.00001 + 0.001 * (1 - 0.00001)] = 0.00970 or 0.97%.


7. Antibiotic Resistance Test:
To calculate the likelihood that a person who tests positive is actually immune, you can use Bayes' theorem:

P(D = 1|T = 1) = [P(T = 1|D = 1) * P(D = 1)] / [P(T = 1|D = 1) * P(D = 1) + P(T = 1|D = 0) * P(D = 0)]

Substituting the given values:
P(D = 1|T = 1) = [0.99 * 0.02] / [0.99 * 0.02 + 0.01 * (1 - 0.02)] = 0.669 or 66.9%.





```python

```
