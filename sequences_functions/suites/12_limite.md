<!SLIDE form=limite_exemple>

# Limite d'une Suite

Prenez la suite définie pour tout n ≥ 0 par uₙ=0.1ⁿ.
Cette suite ressemble à (1, 0.1, 0.01, 0.001, 0.0001, …)

limite -> Vers quelle valeur semble se rapprocher cette suite ? = [   4]

e1 -> Donnez un n₀ tel que tous les éléments de la suite après uₙ₀ sont inférieurs à 0.001 = [   4]

e2 -> Donnez un n₀ tel que pour tout n ≥ n₀, uₙ est inférieur à 0.000001 = [   4]

e3 -> Donnez un n₀(ε) tel que pour tout n ≥ n₀, uₙ est inférieur à ε = [   4]

~~~SECTION:notes~~~

0

4 ou plus (inférieur strict)

7 ou plus (inférieur strict)

n₀ > log0.1(ε) ou n₀ > ln(ε)/ln(0.1)

Tenter de créer une définition de limite pour
l = 0

Petit btw sur le fait que c'est une suite géométrique

~~~ENDSECTION~~~

<!SLIDE>

## Convergence de Suite

Si, peu importe l'écart ε > 0, au bout d'un moment (n₀),
tous les éléments u de la suite sont au plus écartés de ε d'une valeur l,
alors on dit que :

 - la suite (uₙ) converge
 - la limite de (uₙ) est l

~~~SECTION:notes~~~

écrire la notation avec lim → +inf

donner la version avec quantifieurs,
ou la demander à quelqu'un

~~~ENDSECTION~~~

<!SLIDE form=divergence_exemple>

## Limite d'une Suite Divergente

Prenez la suite définie pour tout n ≥ 0 par uₙ=n².
Cette suite ressemble à (0, 1, 4, 9, 16, 25, 36, 49, …)

limite -> La suite semble-t-elle se rapprocher vers une valeur ? Si oui, laquelle ? = [   4]

e1 -> Donnez un n₀ tel que tous les éléments de la suite après uₙ₀ sont supérieurs à 42 = [   4]

e2 -> Donnez un n₀ tel que pour tout n ≥ n₀, uₙ est supérieur à 1,000,000 = [   4]

e3 -> Donnez un n₀(M) tel que pour tout n ≥ n₀, uₙ est supérieur à M = [   4]

~~~SECTION:notes~~~

non. Bien dire que "infini" c'est pas un réel

7 ou plus

1001 ou plus (supérieur strict)

n₀ > sqrt(M), ou 0 si M est négatif

~~~ENDSECTION~~~

<!SLIDE>

## Divergence de Suite

Si, peu importe la hauteur M, au bout d'un moment (n₀),
tous les éléments u de la suite sont au dessus de M,
alors on dit que :

 - la suite (uₙ) diverge
 - la limite de (uₙ) est +∞

~~~SECTION:notes~~~

écrire la notation avec lim → +inf

donner la version avec quantifieurs,
ou la demander à quelqu'un

~~~ENDSECTION~~~

<!SLIDE>

## Divergence de Suite

Si, peu importe la hauteur M, au bout d'un moment (n₀),
tous les éléments u de la suite sont en dessous de M,
alors on dit que :

 - la suite (uₙ) diverge
 - la limite de (uₙ) est -∞

~~~SECTION:notes~~~

écrire la notation avec lim → +inf

donner la version avec quantifieurs,
ou la demander à quelqu'un

~~~ENDSECTION~~~

<!SLIDE form=autre>

## Divergence de Suite

autre -> Trouvez un exemple de suite qui ne converge pas, et dont la limite n'est ni -∞ ni +∞. = [   4]

On dit alors que la suite diverge, mais ne possède pas de limite.

~~~SECTION:notes~~~

sin(x), -1^n, suite custom genre (0, 1, 0, 1, 0, …)

~~~ENDSECTION~~~
