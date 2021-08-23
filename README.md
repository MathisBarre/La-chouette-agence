# Résultats initials

Testé avec un hebergement Github pages sans modifications du code source originel.

## Scores lighthouse

Accueil mobile :
- Performance: 75
- Accessibilité: 84
- Meilleures pratiques: 86
- SEO: 78

Accueil ordinateur :
- Performance: 82
- Accessibilité: 81
- Meilleures pratiques: 93
- SEO: 90

Contact mobile :
- Performance: 99
- Accessibilité: 76
- Meilleures pratiques: 86
- SEO: 81

Contact ordinateur :
- Performance: 100
- Accessibilité: 76
- Meilleures pratiques: 93
- SEO: 90

# Points d'améliorations

## Performance

- Optimiser les images (poids et format)
- Ajouter des dimensions de bases aux images
- Mettre un cache plus long
- Optimiser les librairies tels que bootstrap

## Accessiblitée 

- Augmenter la lisibilité (couleurs)
- Améliorer l'ordre des titres HTML
- Ajouter un attribut lang à la balise <html>
- Ajouter un nom à la liste
- Remplacer les textes sous forme d'image par un vrai paragraphe HTML

## Meilleures pratique

- Changer de version les librairies avec des failles de sécurités (bootstrap 3.3.5 & jQuery 2.1.0)
- Faire correspondre la taille affiché de la vrai taille des images
- Bootstrap est mal intégré sur la page de contact
- Plusieurs erreur sont reporté dans la console
- Remplacer le lien de navigation "page 2" par un libelé plus parlant (contact) et renommer le fichier par la même occasion

## SEO

- Aucune meta description
- Contient des polices illisibles par leur taille
- Zones de touche (doigt) trop petites
- Balise <title> incomplète c'est juste un "."
