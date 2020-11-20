# Events as sets

Event = subset of outcomes: `A ∈ Ω`

## set operations on events

A intersect B -> `A ∩ B` = overlap of the two events = {HT}

A union C -> `A ∪ B` = either of the two events = {HH, HT, TT}

B complement -> B<sup>c</sup> = Means event B did NOT happen = {TT}

### special events

Ω = all possible outcomes

Φ = (phi) the complement of Ω, which is an empty set

## properties of events

Probability of the whole set is always equal to one: `ℙ(Ω) = 1`

and `ℙ(Φ) = 0`

if A is a subset of B `A ⊂ B` then `ℙ(A) ≤ (B)` such that ℙ(A) ≤ 1

if A and B do not overlap then the probability of the union of the two is the sum of both separate probabilities:

`A ∩ B = Φ` -> `ℙ(A ∪ B) = ℙ(A) + ℙ(B)`

Probability of A complement is equal to 1 minus the probability of A: `ℙ(A<sup>c</sup>) = 1- ℙ(A)`

Later we will think of `ℙ(ω) = ℙ({ω})` meaning we think of the probability of an event as a single element set.

--------

### Exercise: Events

In general, suppose that a probability space has 𝑚 (not infinite) different possible outcomes, i.e., the sample space Ω has size `|Ω|= 𝑚` . How many events are there, in terms of 𝑚?

Answer = 2<sup>𝑚</sup>

To count the number of events, note that to form each event, we go through each of the 𝑚 possible outcomes and we either include the outcome or not.
