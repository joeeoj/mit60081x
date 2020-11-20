# Two Ingredients to Modeling Uncertainty

Reminder: Whenever we model uncertainty we will assume there is an underlying experiment of interest.

1. Set of all possible outcomes of the experiment - the **sample space** denoted by the greek letter Ω (omega)
    * coin flip Ω = {heads, tails}
2. The probability of each possible outcome represented as ℙ (double bar P)
    * coin flip: ℙ(heads) = 1/2 and ℙ(tails) = 1/2

In general for this course: ℙ(S) = probability of S happening

--------

## In Python

We just need one of the two:

```python
model = { 'head': 0.5, 'tails': 0.5 }

sample_space = set(model.keys())

model['head']  # 0.5
model['tails']  # 0.5
```

## Important notes

Sample space Ω is collectively exhaustive. Means every possible outcome is in Ω. After every experiment is run exactly one outcome in Ω happens.

Probabilities assigned are at least 0 and at most 1.

Probabilities of all outcomes sum to 1. ℙ(heads) + ℙ(tails) = 1