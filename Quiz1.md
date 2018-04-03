# *Probability with Applications in Engineering, Science, and Technology* - Carlton & Devore (2nd Edition)
## Chapter 1: Probability
### 1.1 Sample Spaces and Events
* Experiment: any action whose outcome is subject to uncertainty
#### 1.1.1 The Sample Space of an Experiment
* The *sample space*, denonted by S, is the set of all possible outcomes of an experiment
#### 1.1.2 Events
* An *event* is any subset of outcomes contained in the sample space S. An event is *simple* if it consists of only one outcome and *compound* if it consists of more than one outcome.
#### 1.1.3 Some Relations from Set Theory
1. The *complement* of an event A, denoted A', is the set of outcomes in S that are not contained in A
2. The *intersection* of events A and B, denoted by A ∩ B, is the event consisting of all outcomes that are in both A and B
3. The union of two elements A and B, denoted by A ∪ B, is the event consisting of all outcomes that are either in A or in B or in both events
* When A and B have no outcomes in common, they are *disjoint* or *mutually exclusive*. In other words, A ∩ B = ∅
##### De Morgan's Laws
Let A and B be two events in the sample space of S.
1. (A ∪ B)' = A' ∩ B'
2. (A ∩ B)'= A' ∪ B'
### 1.2 Axioms, Interpretations, and Properties of Probability
* For any event A, P(A) ≥ 0
* P(S) = 1
* If A<sub>1</sub>, A<sub>2</sub>, A<sub>3</sub>... is an infinite collection of disjoint events, then: P(A<sub>1</sub> ∪ A<sub>2</sub> ∪ A<sub>3</sub> ...) = [sum from i=1 to infinity of P(A<sub>i</sub>)]
* P(∅) = 0, where ∅is the null event
#### 1.2.1 Interpreting Probability
* Let n(A) denote the number of replications on which A occurs. The ration n(A)/n is called the *relative frequency* of occurence of the event A in the sample of n replications
* As n gets arbitrarily large, n(A)/n approaches a limiting value we refer to as the *long-run relative frequency* of the event A
#### 1.2.2 More Probability Properties
* Complement rule: for any event A, P(A) = 1 - P(A')
* For any event A, P(A) ≤ 1
* For any events A and B, P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
