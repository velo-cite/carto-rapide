# Carte Rapide aux couleurs de Vélo-Cité

## Utilisation 
- Clone du projet
- dupliquer  `carte-rapide.html` en `x.html`
- Modifier les valeurs associées aux communes à partir de la ligne 55
- Modifier ligne 118 l'interpolation des valeurs (linear, ou ['exponential', x] où x est un nombre entre 0 et 5). Si x est inférieur à 1, il gonfle les petites valeurs. Au dessus, il gonfle les grosses valeurs.
- Modifier ligne 118 la valeur maximum à atteindre (hors interpolation)
