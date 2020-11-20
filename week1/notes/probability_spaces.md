# Probability space / probability model

(Ω, ℙ) - (sample space and assignment of probabilities)

![test](sample_space_prob_example.png)

1. For each of the outcomes in the sample space we ask that they are at least 0 and at most one: `ω ∈ Ω -> 0 ≤ ℙ(ω) ≤ 1`
2. Sum of all outcomes in the probability space should equal 1: `Σ(ω ∈ Ω)  ℙ(ω) = 1`

### Coin flip

Ω = {H, T}

ℙ(H) = ℙ(T) = 1/2

Table representation:

| outcome | probability |
| ------- | ----------- |
| H       | 1/2         |
| T       | 1/2         |

This table representation fully encodes the probability space.

| outcome | probability |
| ------- | ----------- |
| sunny   | 1/2         |
| rainy   | 1/6         |
| snowy   | 1/3         |

```python
import numpy as np

prob_space = {
    'sunny': 1/2,
    'rainy': 1/6,
    'snowy': 1/3
}

# or outcomes and probabilities separately
outcomes = ['sunny', 'rainy', 'snowy']
probabilities = np.array([1/2, 1/6, 1/3])
```

**These are finite probability models** meaning Ω only has a finite number of outcomes.
