# Rapport test utilisateur
## Date: 05/04/2023
## Test utilisateur numero: 1
## Sprint 1: Service Social, Sérvice Medical
## Sujet: Validation des maquettes du Sprint 1

### Les intervenants:

|     Nom    | Prénom       | Profession                | fonction        |
|:----------:|--------------|---------------------------|-----------------|
|  ?         | Fatima Zahrae| Directrice du centre CNMH | client          |
|  FTAHI     | ?            | Administrateur            | client          |
|  EL SERRAJ | Fouad        | Chef de l'équipe          | Chef de project |
|  MERRADO   | Abderahmane  | Présentateur              | développeur     |
|  STITOU    | Nada         | mombre 1 de l'équipe      | développeur     |
|  AHOUZI    | Hasnae       | mombre 2 de l'équipe      | développeur     |
|  NAJIM     | Iman         | mombre 3 de l'équipe      | développeur     |


### Les modifications:

* Modification du client :
    1. Modifier le terme __"Patient"__ par __"Bénéficiaire(PSH)"__ dans tous le projet
    1. Modifier le terme __"Parents"__ par __"Parents/Tuteurs"__ dans tous le projet
    1. Modifier le ***titre*** le l'interface des rendez-vous du Service médical par : Gestion des Rendez-vous:Prestation
    1. Modifier le ***titre*** le l'interface des rendez-vous du Service social par : Gestion des Rendez-vous:Service Social
    1. Modifier le tableau le l'interface des rendez-vous du Service social en ajoutant la colonne ***"Prestation"***
    1. Renommer les ***Etats*** du rendez-vous par : __Réalisé / En instance d'appel / Planifié
    1. Renommer l'étape 2 __"Patient"__ par __"Dossier beneficiaire"__ sur l'interface ***Gestion des rendez-vous: ***
    1. Ajouter une barre de recherche et pagination sur l'interface ***Gestion des rendez-vous: etape 1 ***
    1. Pas de __"numero dossier"__ dans l'ACCEUIL
    1. Modifier la colonne ***"Etat"*** par ***"Etape de processus"***
    1. Les étapes du processus sont :***Acceuil -> Service social -> Service medical -> Préstation medical__REUDUCATION(5)__***
    1. Modifier le titre ***"Ajouter un nouveau Patient"*** par ***"Entretien Social"*** sur la page __Ajouter un nouveau Patient__
    1. Ajouter le button ***"Ajouter Parent"*** sur etape:1 dans la page __Ajouter un nouveau Patient__
    1. Renommer l'étape:4 "Liste d'attente" par ***"Consultation médecin générale"***
    1. Ajouter le button ***"Ajouter Patient"*** sur etape:2 dans la page __Ajouter un nouveau Patient__
    1. Sur l'etape:3 "Entretien Social" dans la page __Ajouter un nouveau Patient__ déplacer le "Niveau Scolaire" vers l'étape:2 et déplacer "Situation familiale" vers l'étape:1
    1. Supprimer le tableau de l'étape:4 "Liste d'attente" dans la page __Ajouter un nouveau Patient__
    1. Renommer le titre par __"Gestion list d'attente"__ dans la page ***"Gestion des consultations"***
    1. Ajouter la colonne ***"Numero Dossier"*** et Supprimer les colonnes "N° d'ordre", "Téléphone" et "Date enregistrement" de la page ***"Gestion des consultations"***
    1. Supprimer le button __"AJOUTER SANS RENDEZ-VOUS"__ dans tous le projet
    1. Modifier le terme ***"Consultation"*** par ***"Prestation"*** dans les pages des __"Prestation médicale:RÉÉDUCATION(5)"__


### Les remarques:

* Remarques dites par le client :
    * Pas de données enregistré dans le Pôle médical
    * "Entretien social" = "Dossier social" avec le parent
    * "Employés" = "Personnel(RH)"
    * "Service" = "Prestation" pour les métier de rééducation(5) = "Consultation" pour le médecin générale
    * Il ya plus la couverture médicale "RAMED"
    * Tous les services medical revient vers le médecin générale sauf le ***médecin neurologue***
    * Le nombre de prestation est entre 20 et 30

* Remarques dites par le chef de project :
    * Il vous faut ***un réseau internet interne*** commun entre tous les département du centre pour pouvoir se connecter à l'application par tous le staff administratif.
    * En cas d'absence du réseau internet interne il vous faut un ***serveur d'hébergement*** pour l'application.

* Remarques dites par l'équipe développeur :
    * Saisir le nom  et le mdp seulement pour accéder à l'application
    * faut ajouter ***un filtre*** dans les "list d'attente"


### Les questions /Les réponses

1. Questions posées par le client:
    * Est-ce qu'on peut _importer_ la data sur des fichier excel directement sur l'application ? /OUI
    * Est-ce qu'on peut _exporter_ la data sur l'application vers un fichier excel vers la fin de la journée ? /OUI
    * Est-il possible de noter la date d'enregistrement de chaque activité et quel utilisateur a réalisé cette activité ? /OUI
    * Sur les list d'attente est-ce que je peut avoir la "date d'appel" et "le nombre d'appel" par le personnel du service social ? /OUI

2. Questions posées par l'équipe développeur:
    * Voulez-vous avoir l'application avec une multi langue ? /NON, Francais seul

3. Questions posées par le chef de project:
    * A quel point vous été satisfait des maquettes présenté ? /Moyennement Satisfait
    * Est-ce qu'on peut fixer la date du prochain test utilisateur ? /Semaine Prochaine
    