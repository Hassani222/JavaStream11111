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
 
