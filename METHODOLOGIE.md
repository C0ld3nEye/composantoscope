# Méthodologie de Composantoscope (v0 — 31/10/2026)

## Panier de référence
- 4 catégories suivies : DDR5 32 Go, DDR5 16 Go, DDR4 32 Go, DDR4 16 Go (GPU et SSD à venir).
- Pour chaque catégorie : médiane des meilleures offres relevées chez les e-commerçants français.

## Sources
- v0 : relevés publics de comparateurs français (attribution incluse dans chaque relevé JSON).
- v1 (à venir) : flux produits d'affiliation (catalogues marchands destinés aux affiliés) pour relevés multi-enseignes quotidiens + suivi d'articles de référence du marché.

## Base de l'indice
- Indice RAM DDR5 32 Go : base 100 = septembre 2025 (kit DDR5-6000 32 Go à 126 €, relevé documenté).
- La médiane d'un kit DDR5 32 Go vaut 3,75 fois son prix de septembre 2025.

## Règle du signal « acheter / attendre » (publique, mécanique)
1. Si les prévisions contractuelles trimestrielles (TrendForce & co.) sont à la hausse ET que la tendance retail 30 jours est plate ou haussière → **besoin réel : acheter maintenant ; pas de besoin : attendre**.
2. Le signal bascule vers « attendre » pour tous si la tendance retail 30 jours devient négative ET que la prévision contractuelle suivante est stable ou baissière.
3. Toute bascule est expliquée dans le journal des versions ci-dessous, avec les chiffres qui l'ont provoquée.

## Journal des versions
- 31/10/2026 : v0 — premier relevé (source ramradar.fr), indice DDR5 32 Go = 375 (base 100 = sept. 2025). Signal : besoin réel → acheter ; sinon → attendre (contrats DRAM prévus +10 à 15 % au T4 2026 selon TrendForce ; SK hynix annonce une hausse au moins jusqu'en 2027).
- 17/11/2026 : v0 (sans changement de version) — 18e relevé, indice 402 (stable vs la veille). Évaluation de la règle : tendance retail 30 jours plate/haussière en niveau élevé (~400), prévisions contractuelles toujours haussières (TrendForce +10 à 15 % T4 2026 ; SK hynix jusqu'en 2027) → condition 2 de bascule non remplie, le signal « acheter si besoin réel / attendre sinon » est maintenu sans modification de la carte signal.
