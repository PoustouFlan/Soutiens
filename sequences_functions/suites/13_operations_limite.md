<!SLIDE form=usual_limits>

## Pour aller plus vite

La preuve ε — n₀ c'est bien, mais c'est long.

À la place, on préfère apprendre par cœur les
limites des suites usuelles, puis apprendre
comment les combiner.

Pour chacune des suites suivantes, définies pour tout
n > 0, déterminer leur limite.

a -> aₙ=n = ___

b -> bₙ=1/n = ___

c -> cₙ=eⁿ = ___

d -> dₙ=ln(n) = ___

e -> eₙ=√n = ___

f -> fₙ=42 = ___

g -> gₙ=n³ = ___

~~~SECTION:notes~~~
écrire la notation avec lim → +inf

donner quelques valeurs, voire montrer un graphe

+inf

0

+inf

+inf

+inf

42

+inf
~~~ENDSECTION~~~

<!SLIDE form=limite_geometrique>

## Limite d'une Suite Géométrique

Soit (uₙ) une suite géométrique de raison q.
Trouvez la limite de uₙ en fonction de q.

Limite = [   7]

~~~SECTION:notes~~~
Montrez quelques suites sur GeoGebra

N = 42

q = 0.5

i = Sequence(n, n, 0, N)

u = Sequence(q^n, n, 0, N)

(i, u)

Dire que l'exponentielle c'est juste un cas particulier de géométrique

~~~ENDSECTION~~~

<!SLIDE>

## Combiner des Limites

| Limite de (uₙ) | Limite de (vₙ) | Limite de (uₙ + vₙ) | Limite de (uₙ · vₙ) | Limite de (uₙ / vₙ) |
|:--------------:|:--------------:|:-------------------:|:-------------------:|:-------------------:|
| +∞             | +∞             |                     |                     |                     |
| +∞             | -∞             |                     |                     |                     |
| +∞             | 0              |                     |                     |                     |
| +∞             | b<0            |                     |                     |                     |
| +∞             | pas de limite  |                     |                     |                     |
| -∞             | -∞             |                     |                     |                     |
| -∞             | 0              |                     |                     |                     |
| a<0            | b>0            |                     |                     |                     |
| a>0            | pas de limite  |                     |                     |                     |
| pas de limite  | b<0            |                     |                     |                     |
| pas de limite  | pas de limite  |                     |                     |                     |

~~~SECTION:notes~~~
Donner des exemples pour un peu chaque cas

Aussi, pour les cas indéterminés, montrez plusieurs cas contradictoires
~~~ENDSECTION~~~

<!SLIDE form=combiner_limites>

Calculez la limite des suites suivantes, définies pour tout n > 0 :

a -> aₙ=n² + n - 1 = [   4]

b -> bₙ=-n² + 3 = [   4]

c -> cₙ=3/√n = [   4]

d -> dₙ=-n·2ⁿ = [   4]

e -> eₙ=(-0.5)ⁿ/n² + 3 = [   4]

~~~SECTION:notes~~~

+inf

-inf

0

-inf

3

~~~ENDSECTION~~~
