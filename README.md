# Retour de la banque vers Ratatata

À publier tel quel à la racine de `https://mpguizien-web.github.io` (dépôt public `mpguizien-web.github.io`, GitHub Pages).
- `.well-known/apple-app-site-association` : dit à l'iPhone que `/ratatata/banque…` appartient à Ratatata (lien universel) ;
  l'app de la banque (Revolut…) rouvre alors Ratatata directement, sans Safari.
- `ratatata/banque/index.html` : secours si le lien universel ne joue pas, renvoie vers `ratatata://banque` avec le code.
Aucune donnée personnelle. Puis ajouter `https://mpguizien-web.github.io/ratatata/banque` aux adresses de retour
de l'application dans le Control Panel d'Enable Banking (l'app essaie cette adresse en premier, puis les anciennes).
