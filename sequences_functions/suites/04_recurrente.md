<!SLIDE>

# Définition récurrente d'une suite

On peut définir une suite à l'aide d'une relation par récurrence.

Par exemple, la suite de Fibonacci (fₙ) est définie par :

 - f₀ = 0
 - f₁ = 1
 - fₙ₊₂ = fₙ + fₙ₊₁

On obtient alors :

 - f₂ = f₀ + f₁ = 0 + 1 = 1
 - f₃ = f₁ + f₂ = 1 + 1 = 2
 - f₄ = f₂ + f₃ = 1 + 2 = 3
 - …

<!SLIDE form=recurrent_exemple>
## Exemple

Prenons la suite (vₙ) définie pour tout n ≥ 1 par :

 - v₁ = 1
 - vₙ₊₁ = -2·vₙ

Calculez quelques termes de la suite.

a -> v₁= = ___[5]

b -> v₂= = ___[5]

c -> v₃= = ___[5]

d -> v₄= = ___[5]

e -> v₅= = ___[5]


~~~FORM:recurrent_exemple~~~

~~~SECTION:notes~~~

v₁=1
v₂=-2
v₃=4
v₄=-8
v₅=16
Demander un gros terme genre v₁₀₀ pour montrer l'utilité de la definition explicite

~~~ENDSECTION~~~
