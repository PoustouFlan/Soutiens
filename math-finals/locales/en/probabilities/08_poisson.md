<!SLIDE form=variance>
# Poisson

We suppose that if n is sufficiently large, we can then approximate the number of wins with a Poisson distribution of parameter λ.

distribution3 -> What is P(X = k) ? = [   ]

esperance3 -> Prove that the expected value of X is equal to λ = [   ]

~~~FORM:variance~~~


<!SLIDE supplemental exercises>
# Distribution

Let X be the number of games won, n be the number of rolls, and λ the expected value of X. (The roulette does not necessarily contains 37 boxes anymore).

Compute P(X = k) **only using n, k and λ**

# Poisson

Suppose an infinite amount of rolls (n approaches infinity).

Prove that X is now following a Poisson distribution of parameter λ


<!SLIDE supplemental solutions>

# Distribution

P(X = k) = (n chose k) (λ/n)<sup>k</sup> (1 - λ/n)<sup>n-k</sup>

# Poisson

P(X = k) = (λ<sup>k</sup> / k!) (n! / (n-k)!) (1 - λ/n)<sup>n</sup> (1 - λ/n)<sup>k</sup>

When n is sufficiently large, n! / (n-k)! approaches 1, (1 - λ/n)<sup>n</sup> approaches e<sup>-λ</sup>, and (1 - λ/n)<sup>k</sup> approaches 1.