SAFAA HASSANI 
4IIR groupe 2
EMSI moulay youssef 

![f754bd04-918d-40dc-958e-f25908204f23](https://github.com/user-attachments/assets/cd89d028-dee6-4934-95ff-c205f2c5eac3)


Projet 

Titre du Projet : Système de Détection et Prévention des Crises Émotionnelles en Milieu Scolaire
Description : Solution utilisant la computer vision et l'analyse comportementale pour détecter les signes de détresse émotionnelle chez les élèves, générer des alertes aux conseillers et proposer des interventions personnalisées.
Technologies Suggérées : Python (OpenCV, TensorFlow), Spring Boot, React, PostgreSQL
Thèmes Principaux : Santé émotionnelle, Reconnaissance Hybride

Descriptif

---

Le système de détection et de prévention des crises émotionnelles en milieu scolaire repose sur une modélisation orientée objets utilisant des classes hiérarchisées pour représenter les différents acteurs et données du projet. Une classe mère **User** regroupe les attributs communs tels que l’identifiant, le nom, le prénom et l’email, tandis que des classes filles spécialisées comme **Etudiant**, **Conseiller** et **Administrateur** héritent de ces propriétés et ajoutent leurs caractéristiques propres, par exemple la classe ou l’âge pour l’étudiant, et la spécialité pour le conseiller. De même, une classe abstraite **Observation** permet de représenter toute donnée issue de l’analyse comportementale ou émotionnelle, et ses sous-classes **EmotionRecord** et **BehaviorRecord** détaillent respectivement les émotions détectées et les comportements observés. Enfin, les classes **Alert** et **Intervention** gèrent la réponse du système en enregistrant les alertes générées et les actions entreprises par le conseiller, créant ainsi une structure cohérente, extensible et adaptée au fonctionnement du système.


 ---
 1️⃣ Gestion des utilisateurs

Le système gère plusieurs types d’utilisateurs :

-Administrateurs

-Conseillers scolaires / Psychologues

-Enseignants

-Élèves

Chaque utilisateur possède :

Des informations personnelles

Un compte avec rôle associé

Un état d’accès : actif, restreint ou désactivé

L’état et le rôle contrôlent les droits :
→ un enseignant peut signaler un comportement
→ un conseiller peut analyser les alertes
→ un élève a accès uniquement à son espace bien-être
---
2️⃣ Profils émotionnels des élèves

Chaque élève possède un profil émotionnel contenant :

*Informations scolaires (classe, âge…)

*Historique des observations comportementales

*Scores psychologiques (stress, anxiété…)

*Alertes précédentes et interventions réalisées

Ce profil permet de suivre l’évolution du bien-être de l’élève.
---
3️⃣ Collecte d’observations

Le système recueille des données provenant de :

Computer vision : expressions faciales, isolement social, gestes inhabituels

Rapports enseignants (incidents, baisse de participation…)

Auto-évaluations via questionnaires

Chaque observation est analysée et convertie en indicateurs émotionnels.
---
4️⃣ Alerte émotionnelle

Lorsque des signes de détresse sont détectés, une alerte est générée. Elle regroupe :

L’élève concerné

La gravité du risque (faible, moyen, élevé)

Le comportement suspect identifié

La date et le contexte scolaire

Une alerte suit un cycle défini :


---
5️⃣ Analyse comportementale

Chaque alerte est composée de données comportementales :

Expressions relevées

Risques détectés

Statistiques émotionnelles

Le système utilise l’intelligence artificielle pour :

Classifier la nature du risque

Calculer un score de danger

Déclencher des mesures préventives
---
6️⃣ Suivi et Intervention

Une alerte validée déclenche un plan de prise en charge, contenant :

Type d’intervention recommandée (séance de soutien, entretien…)

Responsable en charge (conseiller)

Dates des suivis programmés

Résultats des actions menées

Un suivi réussi contribue à la prévention de futures crises.

---

7️⃣ Gestion de la confidentialité et accès sécurisé

Le système garantit :

La sécurité des données psychologiques

Les droits d’accès selon les rôles

La conformité éthique et scolaire

La confidentialité est essentielle pour protéger la vie privée des élèves.
