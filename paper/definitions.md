**pre-image resistant**: Given a hash function and a hash, it is difficult to find an input for the given hash function that outputs the given hash.

**false positive rate**: Given a set $\mathbb{X}$ and an element $x$ that is not a member of $\mathbb{X}$, an approximate set of $\mathbb{X}$ contains $x$ with a probability denoted the *false positive rate*.

**pre-image attack**: Given a hash function and a hash, searching for an input for the given hash function that outputs the given hash.

**random oracle**: A theoretical function that maps every unique input from its domain to a uniform and random output in its range.

**approximate set**: A set $\mathbb{X}(\epsilon)$ is an approximate set of $\mathbb{X}$ if $\mathbb{X}(\epislon) \supset \mathbb{X}$ and an element not in $\mathbb{X}$ is in $\mathbb{X}(\epsilon)$ with a false positive rate $\epsilon$.

**Singular Hash Set**: A theoretically optimal data structure for implementing the *approximate set* abstract data type.

**Singular Hash Map**: A theoretically optimal data structure for implementing the *approximate map* abstract data type.

**perfect hash function**: A hash function that guarantees no collisions among members of a specified set.

**Perfect Hash Filter**: A data structure for implementing the *approximate set* abstract data type that is a function of a *perfect hash function*.

**Bloom filter**: A popular data structure for implementing the *approximate set* abstract data type.

**negative binomial distribution**: A distribution where we are interested in observing the number of Bernoulli trials needed to observe a specific number of "successes".

**geometric distribution**: A distribution where we are interested in observing the number of Bernoulli trials needed to observe a "successes".

**set**: An ordered collection of distinct elements.

**NB**: negative binomial distribution.

**GEO**: geometric distribution.

**SHS**: Singular Hash Set.

**BF**: Bloom filter.

**PHF**: Perfect Hash Filter.

**PH**: Perfect Hash function.
