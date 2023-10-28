<!SLIDE>

## Expression d'une Suite Arithmétique

Soit (uₙ) une suite arithmétique de premier terme u₀ = a et de raison r.
Alors, on peut exprimer la suite arithmétique de manière récurrente…

u₀ = a;  uₙ₊₁ = uₙ + r

… ou de manière explicite :

uₙ = a + r·n


Par exemple, soit (uₙ) = (1, 3, 5, 7, 9, 11, …).
Son premier terme est u₀ = 1, et sa raison est égale à 2.

Alors, la définition récurrente de (uₙ) est :

 - u₀ = 1
 - uₙ₊₁ = uₙ + 2

Et sa définition explicite :

 - uₙ = 1 + 2·n

~~~SECTION:notes~~~

Bien détailler que répéter une addition,
c'est pareil que faire une multiplication.

Montrer aussi que dans l'exemple, pour quelques valeurs
de n, ça fonctionne bien dans les deux cas.

~~~ENDSECTION~~~

<!SLIDE form=arithmetique_conversion>

## Exercice

Exprimez les suites arithmétiques suivantes, définies pour n ≥ 0,
avec une relation par récurrence.

a -> (aₙ) = (10, 9, 8, 7, 6, 5, …) = [   4]

b -> (bₙ) = (-5, -1, 3, 7, …) = [   4]

c -> cₙ = n = [   4]

d -> dₙ = (2 + n)·(n - 1) - n² = [   4]

~~~SECTION:notes~~~

Détailler quelques valeurs pour la c et la d.

a₀=10, aₙ₊₁=aₙ - 1
b₀=-5, bₙ₊₁=bₙ + 4
c₀=0, cₙ₊₁=cₙ + 1
d₀=-2, dₙ₊₁=dₙ - 1

~~~ENDSECTION~~~

<!SLIDE form=arithmetique_conversion_2>

## Exercice

Exprimez les suites arithmétiques suivantes, définies pour n ≥ 0,
avec leur formule explicite.

a -> (aₙ) = (10, 9, 8, 7, 6, 5, …) = [   4]

b -> (bₙ) = (-5, -1, 3, 7, …) = [   4]

c -> c₀ = 0, cₙ₊₁ = cₙ + 1 = [   4]

d -> d₀ = -2, dₙ₊₁ = (2 + dₙ)·(dₙ - 1) - dₙ² = [   4]

~~~SECTION:notes~~~

Détailler quelques valeurs pour la c et la d.

aₙ=10 - n
bₙ=-5 + 4n
cₙ=n
dₙ=-2 - 2n

~~~ENDSECTION~~~
