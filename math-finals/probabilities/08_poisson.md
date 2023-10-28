<!SLIDE form=variance>
# Poisson

On suppose que si n est suffisamment grand, on peut alors approximer le nombre de paris réussis par une distribution de Poisson de paramètre λ.

distribution3 -> Exprimer P(X = k) = [   ]

esperance3 -> Prouver que l'espérance de X est égale à λ = [   ]

~~~FORM:variance~~~


<!SLIDE supplemental exercises>
# Distribution

Notons X le nombre de paris réussis, n le nombre de lancers, λ l'espérance de X. (La roulette ne contient plus forcément 37 cases).

Exprimer P(X = k) **en fonction de n, k et λ**

# Poisson

Supposons maintenant une infinité de lancers. (n tend vers +infini).

Prouver que X suit maintenant une distribution de Poisson de paramètre λ


<!SLIDE supplemental solutions>

# Distribution

P(X = k) = (k parmi n) (λ/n)<sup>k</sup> (1 - λ/n)<sup>n-k</sup>

# Poisson

P(X = k) = (λ<sup>k</sup> / k!) (n! / (n-k)!) (1 - λ/n)<sup>n</sup> (1 - λ/n)<sup>k</sup>

Quand n devient suffisamment grand, n! / (n-k)! tend vers 1, (1 - λ/n)<sup>n</sup> tend vers e<sup>-λ</sup>, et (1 - λ/n)<sup>k</sup> tend vers 1.
