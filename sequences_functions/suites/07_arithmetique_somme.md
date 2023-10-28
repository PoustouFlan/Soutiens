<!SLIDE form=somme_suite_arithmetique_1>

## Somme d'une Suite Arithmétique

Pouvez-vous calculer la somme suivante ?

1 + 2 + 3 + 4 + … + 98 + 99 + 100

Somme = [   4]

~~~SECTION:notes~~~

Bien montrer l'intuition derrière la formule de somme

Réponse=101 · 50=5050

~~~ENDSECTION~~~

<!SLIDE form=somme_suite_arithmetique_2>

## Somme d'une Suite Arithmétique

En règle générale, lorsque nous avons une suite
arithmétique (uₙ) de premier terme u₁=a et de raison r,
alors :

La somme des n premiers éléments (de u₁ à uₙ) donne
(u₁ + uₙ)·n / 2.

change -> Exprimez cette somme en fonction de a et r = [   4]

shift -> Si le premier terme de (uₙ) était à la place u₀ = a, quelle serait la somme des éléments de (uₙ) de u₀ jusqu'à uₙ ? = [   4]

~~~SECTION:notes~~~

(2a + nr - r)n / 2

(2a + nr)(n + 1) / 2

Petite note sur le fait de retenir n(n+1)/2 et n(n-1)/2
Confirmer les résultats de la slide précédente (1 + … + 100=5050)
avec cela. (avec u1 / un, et a / r aussi)

~~~ENDSECTION~~~

<!SLIDE form=somme_suite_arithmetique_3>

Calculez la somme des 42 premiers termes des suites arithmétiques
suivantes, définies pour tout n ≥ 0 :

a -> (aₙ) = (-20, -19, -18, …) = [   4]

b -> (bₙ) = (41, 39, 37, 35, 33, …) = [   4]

c -> cₙ = a·(n+1) = [   4]

d -> d₀ = a, dₙ₊₁ = dₙ + 2 = [   4]

Exercice supplémentaire sur https://poustouflan.com/supplemental/exercises

~~~SECTION:notes~~~

a: 21

b: 0

c: 43·21 a=903 a

d: (2a + 82)21=42a + 1722

~~~ENDSECTION~~~


<!SLIDE supplemental exercises>

# Suites Arithmétiques

À la SNCF, ce mois-ci, Auguste est payé 4,200€ par mois.

Grâce à la qualité de son code, tous les mois,
son salaire augmente de 100€.

Calculez le montant total qu'Auguste aura gagné en 42 mois.


<!SLIDE supplemental solutions>

# Suites Arithmétiques

Son salaire peut être décrit par la suite

 - u₀ = 4,200
 - uₙ₊₁ = uₙ + 100

C'est une suite arithmétique de premier terme 4,200 et de raison
100.

La formule explicite associée à cette suite est donc

 - uₙ = 4,200 + 100·n

On trouve alors u₄₁ = 4,200 + 4,100 = 8,300, et alors la somme
de son salaire gagné les 42 premiers mois donne :

(u₀ + u₄₁) · 42 / 2 = (4,200 + 8,300) · 21 = 262,500
