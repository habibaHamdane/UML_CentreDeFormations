

# **PROJET UML : conception réseau du centre de formations**

**Sujet :**
[Contexte]https://gitlab.com/simplonlyon/promo12/cpro/project-uml#project-uml

---
**participant.e.s :**
*  Hamdane Habiba
*  Abdelatif El-Mahdi
*  Bensadoun Amel 
*  Lauren Sarah 

---
## Organisation du projet
 
1. Intro !

2. Diagrammes Use Case

3. Use Case Ecrits

4. Diagrammes d'Activité

5. Diagrammes de Classe et d'entités

6. Diagramme de Séquence


---
### Diagrammes de use case 
---
- > [Diagramme USECASE : user](/UseCase/User.jpg)
- > [Diagramme USECASE : candidat.e](/UseCase/ApprenantPotentiel.jpg)
- > [Diagramme USECASE : direct.eur.trice](/UseCase/Directeur.jpg)
- > [Diagramme USECASE : chargé.e de promo](/UseCase/ChargéDePromo.jpg)
- > [Diagramme USECASE : format.eur.rice](/UseCase/Formateur.jpg)
- > [Diagramme USECASE : apprenant.e](/UseCase/Apprenant.jpg)

---
### Use Case Ecrits
---
- > [Use Case Ecrit : se connecter](/UseCaseEcrit/SeConnecter.png)
- > [Use Case Ecrit : candidater](/UseCaseEcrit/Candidater.png)
- > [Use Case Ecrit : ValiderCandidature](/UseCaseEcrit/ValiderCandidature.png)

---
### Diagrammes d'activité
---
- > [Diagramme d'activité : s'inscrire](/Activity/S'inscrire.jpg)
- > [Diagramme d'activité : se connecter](/Activity/Connexion.jpg)
- > [Diagramme d'activité : candidater](/Activity/ApprenantPotentiel.jpg)
- > [Diagramme d'activité : assigner formateur a une formation](/Activity/AssignerFormProm.jpg)

---
### Diagrammes de classe et d'entités
---
- > [Diagramme de classes du centre de formations](/Class/CentreDeFormations.jpg)
- > [Diagramme d'entités : FormateurCreateProject](/Class/FormCreatProj.jpg)
- > [Diagramme d'entités : AssignerProjectToPromo](/Class/ProjProm.jpg)

---
### Diagrammes de séquence
---
- > [Diagramme de séquence : Assigner le projet a une promo](/Sequence/ProjToPromo.jpg)
- > [Diagramme de séquence : Create Project](/Sequence/CreateProject.jpg)
- > [Diagramme de séquence : Assigner Un CP au CF](/Sequnce/CPToCF.jpg)
        
---
# introduction 
## Analyse des roles des participants

---
### Un.e user pourra : 

- S'authentifier selon son rôle

![](/UseCase/User.jpg)

---
### Un.e direct.eur.trice pourra : 

- Se charger du CRUD des centres de formations (Créer, Modifier, lire, supprimer un centre de formation)
- Se charger du CRUD des chargés de promos (Créer, Modifier, lire, supprimer un chargé de promo)
- Assigner les chargés de promos au centre de formation

![](/UseCase/Directeur.jpg)

---
### Un candidat.e pourra : 
- Consulter l'agenda des formations
- Sélectionner une formation 
- Candidater

![](/UseCase/ApprenatPotentiel.jpg)

---
### Un.e chargé.e de promo pourra : 
- Créer une promotion
- Se charge de CRUD format.eur.rice
- Assigner un.e format.eur.rice à une promotion
- Valider une candidature
- Se charge de CRUD apprenant 
- Inviter les apprenants dans une promo
- Gérer les retards / absences
- Gérer l'agenda
    
![](/UseCase/ChargéDePromo.jpg)

---
### Un.e format.eur.rice pourra : 
- Créer un projet
- Assigner un projet à une promo
- Corriger un projet
- Assurer la gestion de livret d'évaluation

![](/UseCase/Formateur.jpg)

---
### Un.e apprenant.e pourra : 
- Consulter un projet
- Proposer un rendu
- Consulter sa progression 
- Rédiger un dossier professionnel
- Rédiger un dossier projet 

![](/UseCase/Apprenant.jpg)





