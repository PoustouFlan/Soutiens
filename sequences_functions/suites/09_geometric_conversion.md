<!SLIDE>

## Expression d'une Suite Géométrique

Soit (uₙ) une suite géométrique de premier terme u₀ = a et de raison q.
Alors, on peut exprimer la suite géométrique de manière récurrente…

u₀ = a;  uₙ₊₁ = q · uₙ

… ou de manière explicite :

uₙ = a · qⁿ


Par exemple, soit (uₙ) = (1, 2, 4, 8, 16, 32, …).
Son premier terme est u₀ = 1, et sa raison est égale à 2.

Alors, la définition récurrente de (uₙ) est :

 - u₀ = 1
 - uₙ₊₁ = 2 · uₙ

Et sa définition explicite :

 - uₙ = 1 · 2ⁿ

~~~SECTION:notes~~~

Bien détailler que répéter une multiplication,
c'est pareil que faire une puissance.

Montrer aussi que dans l'exemple, pour quelques valeurs
de n, ça fonctionne bien dans les deux cas.

~~~ENDSECTION~~~

<!SLIDE form=geometrique_conversion>

## Exercice

Exprimez les suites géométrique suivantes, définies pour n ≥ 0,
avec une relation par récurrence.

a -> (aₙ) = (1, 1.1, 1.21, 1.331, …) = [   4]

b -> (bₙ) = (-1, 2, -4, 8, …) = [   4]

c -> cₙ = 1/2ⁿ = [   4]

d -> dₙ = aⁿ·bⁿ⁺¹ = [   4]

~~~SECTION:notes~~~

Détailler quelques valeurs pour la c et la d.

a₀=1, aₙ₊₁=aₙ · 1.1
b₀=-1, bₙ₊₁=bₙ · -2
c₀=1, cₙ₊₁=cₙ · 0.5
d₀=b, dₙ₊₁=dₙ · ab

~~~ENDSECTION~~~

<!SLIDE form=geometrique_conversion_2>

## Exercice

Exprimez les suites géométriques suivantes, définies pour n ≥ 0,
avec leur formule explicite.

a -> (aₙ) = (1, 1.1, 1.21, 1.331, …) = [   4]

b -> (bₙ) = (-1, 2, -4, 8, …) = [   4]

c -> c₀ = 1, cₙ₊₁ = cₙ/2 = [   4]

d -> d₀ = a, dₙ₊₁ = 2·d₀·dₙ  = [   4]

~~~SECTION:notes~~~

Détailler quelques valeurs pour la c et la d.

aₙ=1.1ⁿ
bₙ=-1·-2ⁿ
cₙ=1/2ⁿ
dₙ=a·(2a)ⁿ

~~~ENDSECTION~~~
