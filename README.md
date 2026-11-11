# Horizon Épargne

Suivez votre épargne et projetez vos revenus à la retraite, dans une seule page web.

**Ouvrir l'application : <https://rkkv27p2km-eng.github.io/horizon-epargne/>**

## Ce que fait l'outil

- Synthèse du patrimoine financier, par classe d'actifs et par enveloppe (livrets, PEA, assurance-vie, PER, épargne salariale…).
- Projection du capital conservé pour la retraite selon trois scénarios : prudent, central et dynamique.
- Estimation des pensions du régime général et de l'Agirc-Arrco, puis du revenu tiré du capital, en brut et en net d'impôt.
- Suivi d'un objectif de projet (apport immobilier, par exemple) sur l'épargne disponible.
- Assistant de démarrage en quatre étapes, en langage simple.

## Vie privée

Tout se calcule dans votre navigateur. Aucune donnée n'est envoyée à un serveur : il n'y a ni compte, ni traceur, ni bibliothèque externe. Vos chiffres sont enregistrés dans le stockage local du navigateur, sur votre appareil ; téléchargez une sauvegarde depuis l'onglet Réglages pour ne pas les perdre.

## Limites

- Modèle de pension d'un salarié du secteur privé, avec une carrière continue. Il ne s'applique ni aux fonctionnaires ni aux indépendants.
- Règles sociales et fiscales françaises de 2026, modifiables dans Réglages et à mettre à jour chaque année.
- Fiscalité de sortie simplifiée : pas d'abattement annuel sur l'assurance-vie, pas de plafonnement du quotient familial.
- Âge légal et durée d'assurance réglés par défaut sur 64 ans et 172 trimestres : à vérifier pour les personnes nées avant 1969.
- Outil de simulation : il ne constitue ni un conseil en investissement ni un conseil fiscal. Pour vos pensions, seuls votre relevé de carrière et le simulateur officiel M@rel font foi.

## Utilisation hors ligne

Le fichier `index.html` est autonome. Téléchargez-le et ouvrez-le dans un navigateur : il fonctionne sans connexion.

## Mettre à jour les règles

Les valeurs par défaut (plafond de la Sécurité sociale, valeur du point Agirc-Arrco, barème de l'impôt, prélèvements sociaux) se trouvent dans l'objet `regles` de la fonction `EXEMPLE()`, au début du script de `index.html`.
