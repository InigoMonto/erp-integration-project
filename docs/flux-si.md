# 🔄 Flux d'intégration avec le SI existant

L'intégration de l'ERP dans le système d'information repose sur un ensemble d'interfaces structurées permettant de garantir la cohérence des données, la continuité des processus métiers, et l’interopérabilité entre les applications existantes.

## 🖼️ Illustration des flux

![Illustration des flux SI](images/schema-des-flux.jpg)

- **Gestion des absences** ⟶ ERP  
  Synchronisation des absences saisies dans le logiciel de gestion des absences pour prise en compte dans les temps projets et aider à la saisie d'activité.

- **Gestion des collaborateurs** ⟶ ERP  
  Échange unidirectionnel pour mettre à jour les données RH de l'ERP, le référentiel étant le logiciel RH

- **Gestion des formations** ⟷ ERP  
  Échange bidirectionnel : dans un premier temps, les formations planifiées sur l’ERP sont exportées vers le logiciel de gestion des formations pour permettre la création des conventions de formation nécessaires à la certification Qualiopi. Une fois la gestion administrative finalisée (émargement, feuilles de présence, etc.), un flux retour permet de faire évoluer l’état de la formation afin d’enclencher la facturation.

- **ERP ⟶ Infocentre**  
  Alimentation d’un entrepôt de données interne, permettant de croiser les informations issues de l’ERP avec celles d’autres outils du système d’information, en vue de produire des tableaux de bord consolidés et contextualisés.

- **ERP ⟶ Comptabilité**  
  Génération automatique des écritures comptables issues des ventes, achats, et traitements analytiques.



Ces flux ont été modélisés selon des standards de type ETL/API/FTP selon les systèmes sources, avec une attention portée à la supervision, à la traçabilité et à la résilience.

---

🔙 [Retour au README principal](../README.md)
