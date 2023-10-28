<!SLIDE form=somme_suite_geometrique_1>

## Somme d'une Suite Arithmétique

Pouvez-vous calculer la somme suivante ?

2 + 20 + 200 + … + 2,000,000

Somme = [   4]

Et celle-ci ?
Indice : pensez en binaire !

1 + 2 + 4 + 8 + … + 512 + 1,024

Somme = [   4]


~~~SECTION:notes~~~

2,222,222
2,047

~~~ENDSECTION~~~

<!SLIDE form=somme_suite_geometrique_2>

## Somme d'une Suite Géométrique

En règle générale, lorsque nous avons une suite
géomtétrique (uₙ) de premier terme u₀=a et de raison q,
alors :

La somme des n premiers éléments (de u₀ à uₙ₋₁) donne
a·(1-qⁿ)/(1-q).

shift -> Quelle est la somme des éléments de (uₙ) de u₀ jusqu'à uₙ ? Simplifier l'expression au maximum. = [   4]

~~~SECTION:notes~~~

Preuve en live:
S=1 + q + q² + … + qⁿ
qS=q + q² +  … + qⁿ + qⁿ⁺¹
qS=S-1 + qⁿ⁺¹
S=(qⁿ⁺¹-1)/(q-1)

a·(1-qⁿ⁺¹)/(1-q).

Confirmer les résultats de la slide précédente (1 + … + 100=5050)
avec cela. (avec u1 / un, et a / r aussi)

~~~ENDSECTION~~~

<!SLIDE form=somme_suite_geometrique_3>

Calculez la somme des 42 premiers termes des suites géométriques
suivantes, définies pour tout n ≥ 0 :

a -> (aₙ) = (-1, 1, -1, 1, -1, …) = [   4]

b -> (bₙ) = (1, 1.1, 1.21, 1.331, …) = [   4]

c -> cₙ = (a + b)ⁿ = [   4]

d -> d₀ = a, dₙ₊₁ = a·b·dₙ = [   4]

Exercice supplémentaire sur https://poustouflan.com/supplemental/exercises

~~~SECTION:notes~~~

a: 0

b: 10·(1.1⁴²-1)

c: (1-(a+b)⁴²)/(1-a-b)

d: a(1-(ab)⁴²)/(1-ab)

~~~ENDSECTION~~~


<!SLIDE supplemental exercises>

# Suites Géométriques

Oxian mange une fois par mois au Sumaya. Ce mois-ci, le prix
du Sumaya est à 13.50€

À cause de l'inflation, le prix du repas augmente de 2%
chaque mois.

Calculez le montant total qu'Oxian aura dépensé en 42 mois.


<!SLIDE supplemental solutions>

# Suites Géométriques

Le prix du Sumaya peut être décrit par la suite

 - u₀ = 13.50
 - uₙ₊₁ = 1.02·uₙ

C'est une suite géométrique de premier terme 13.50 et de raison
1.02.

La formule explicite associée à cette suite est donc

 - uₙ = 13.50·1.02ⁿ

Oxian dépensera au total 50 · 13.5 · (1.02⁴² - 1) = 675 · (1.02⁴² - 1),
soit environ 875€.
