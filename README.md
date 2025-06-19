# 🏢 Intégration d’un ERP dans une organisation multi-métier (300+ collaborateurs)

Ce dépôt documente la mise en place d’un ERP dans une organisation de plus de 300 personnes, couvrant un périmètre allant du commerce à la facturation, en passant par la gestion des achats, prestations, formation et le suivi de l’activité des collaborateurs.

Le projet a impliqué une refonte profonde des processus, une intégration technique complète au SI existant, et un accompagnement fort des utilisateurs.

## 🎯 Objectifs du projet

- Refondre les processus métiers autour d’un ERP centralisé, en remplacement d’une multitude d’applications métiers en silo, peu communicantes
- Intégrer l’ERP comme nouveau socle du système d'information
- Développer des interfaces internes robustes et sécurisées
- Accompagner les utilisateurs dans l’appropriation de l’outil

## 🧱 Périmètre couvert

- Gestion commerciale (devis, commandes, marketing)
- Suivi de projet et gestion des temps
- Pilotage des services (plannings, interventions, bons de livraison)
- Facturation automatisée
- Intégration au référentiel RH et comptable

👉 [Voir le périmètre fonctionnel détaillé](docs/perimetre-fonctionnel.md)

## 🗺️ Étapes du projet

Le projet a été structuré en plusieurs phases clés, depuis la phase de recherche de solution jusqu'à la mise en production :

- **J0 – Phase d’avant-projet** : audit interne, définition du MVP, démonstration de solutions spécialistes et généralistes sur la base de scénarios d’entreprise, élaboration de l’appel d’offres (CCAP, CCTP), dépouillement et choix de la solution par le CODIR 
- **J1 – Initialisation du projet** : cadrage, gestion des risques, gouvernance
- **J2 – Analyse fonctionnelle** : ateliers métiers, formalisation des besoins
- **J3 – Analyse technique** : interfaçage SI, spécifications des développements
- **J4 – Développements & environnement de test** : mise en place du socle technique
- **J5 – Tests & Formations** : formation des utilisateurs clés, recette fonctionnelle
- **J6 – Préparation de la production** : reprise des données, configuration finale
- **J7 – Mise en production & VSR** : passage en production, accompagnement post-déploiement

👉 [Voir les étapes détaillées du projet](docs/etapes-projet.md)

## ⚙️ Intégration SI

- Développement d'interfaces avec ls solution RH, de gestion des absences, des notes de frais, de gestion des formations et de comptabilité 
- Mécanismes de synchronisation et de supervision des flux via orchestrateur

👉 [Voir les flux inter applicatifs](docs/flux-si.md)


## 🤝 Conduite du changement

La conduite du changement a été un levier essentiel de réussite pour garantir l’adhésion des équipes au nouvel ERP. Elle s’est articulée autour de plusieurs axes complémentaires :

- Sessions de formation ciblées, adaptées aux profils métiers
- Création d’ateliers dédiés aux différents acteurs pour définir leurs contributions dans le nouveau système
- Assistance personnalisée à la reprise des données depuis les anciens outils
- Formation interne des key users pour en faire des relais opérationnels
- Mise à disposition de supports utilisateurs pédagogiques
- Suivi de l’adoption post-déploiement avec points réguliers et ajustements continus


## 📎 Ressources

> Voir le dossier `docs/` pour plus de détails techniques et organisationnels
