<!SLIDE supplemental exercises>

# Suites Arithmético-Géométriques

Joseph Marchand possède 42€ sur son compte en banque.
Chaque année, Joseph Marchand dépense 10% de son argent dans des crêpes,
puis reçois 10€ en cadeau de Noël.

Modélisez l'argent que possède Joseph Marchand au fil des ans avec une
suite (uₙ), et donnez sa définition par récurrence.

Considérez la suite "auxiliaire" vₙ = uₙ - 100.
Montrez que vₙ est une suite géométrique, et calculez sa raison.

Trouvez une forme explicite pour vₙ, et ainsi déduisez une forme
explicite pour uₙ.

Combien d'argent aura Joseph Marchand dans 42 ans ?

<!SLIDE supplemental solutions>

# Suites Arithmético-Géométriques

Soit uₙ l'argent que possède Joseph Marchand lors de l'année n.
Durant l'année, Joseph Marchand dépense 10% de son argent, il lui
restera alors 0.9 · uₙ.

Ensuite, à la fin de l'année, Joseph Marchand reçois 10€.
Au début de l'année prochaine, Joseph Marchand aura alors 0.9 · uₙ + 10€.

On a donc :

 - u₀ = 42
 - uₙ₊₁ = 0.9 · uₙ + 10.

Considérons alors la suite vₙ = uₙ - 100.
On a donc :

 - vₙ₊₁ = uₙ₊₁ - 100 = 0.9 · uₙ + 10 - 100 = 0.9 · uₙ - 90
 - uₙ = vₙ + 100 en renversant l'équation de vₙ
 - vₙ₊₁ = 0.9 · (vₙ + 100) - 90 = 0.9 · vₙ

(vₙ) est donc une suite géométrique de raison 0.9.

On peut donc en déduire une formule explicite pour vₙ :

 - v₀ = u₀ - 100 = 42 - 100 = -58
 - vₙ = -58 · 0.9ⁿ

Et alors, vu que uₙ = vₙ + 100 :

 - uₙ = -58 · 0.9ⁿ + 100

Dans 42 ans, Joseph marchand possèdera -59 · 0.9⁴² + 100 ≈ 99.29€
