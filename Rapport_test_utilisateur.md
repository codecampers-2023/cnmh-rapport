# Rapport test utilisateur                             ## Date: 05/04/2023
## Test utilisateur numero: 1
## Sprint_1: Service Social, Sérvice Medical
## Sujet: Validation des maquettes de projet

### Les intérvenants:

|     Nom    | Prénom       | Profetion                 | function        |
|:----------:|--------------|---------------------------|-----------------|
|  ?         | Fatima Zarae | Directrice du centre CNMH | client          |
|  FTAHI     | ?            | Administrateur            | client          |
|  EL SERRAJ | Fouad        | Chef de l'équipe          | Chef de project |
|  MERRADO   | Abderahmane  | Présentateur              | développeur     |
|  STITOU    | Nada         | mombre 1 de l'équipe      | développeur     |
|  AHOUZI    | Hasnae       | mombre 2 de l'équipe      | développeur     |
|  NAJIM     | Iman         | mombre 3 de l'équipe      | développeur     |

### Les modifications:

* Modification du client :
    1. Modifier le terme __"Patient"__ par __"Bénificiaire(PSH)"__ dans tous le projet
    1. Modifier le terme __"Parents"__ par __"Parents/Tuteurs"__ dans tous le projet
    1. Modifier le ***titre*** le l'interface des rendez-vous du Service medical par : Gestion des Rendez-vous:Prestation
    1. Modifier le ***titre*** le l'interface des rendez-vous du Service social par : Gestion des Rendez-vous:Service Social
    1. Modifier le tableau le l'interface des rendez-vous du Service social en ajoutant la colonne ***"Prestation"***
    1. Renomer les ***Etats*** du rendez-vous par : __Réalisé / En instance d'appel / Planifié__
    1. Renomer l'etape 2 __"Patient"__ par __"Dossier benificiaire"__ sur l'interface ***Gestion des rendez-vous: ***
    1. Ajouter une __barre de recherche__ et __pagination__ sur l'interface ***Gestion des rendez-vous: etape 1 ***
    1. Pas de __"numero dossier"__ dans l'ACCEUIL
    1. Modifier la colonne ***"Etat"*** par ***"Etape de processus"***
    1. Les etapes du processus sont :***Acceuil -> Service social -> Service medical -> Préstation medical__REUDUCATION(5)__***
    1. Modifier le titre ***"Ajouter un nouveau Patient"*** par ***"Entretien Social"*** sur la page __Ajouter un nouveau Patient__
    1. Ajouter le button ***"Ajouter Parent"*** sur etape:1 dans la page __Ajouter un nouveau Patient__
    1. Renomer l'etape:4 "Liste d'attente" par ***"Consultation médecin générale"***
    1. Ajouter le button ***"Ajouter Patient"*** sur etape:2 dans la page __Ajouter un nouveau Patient__
    1. Sur l'etape:3 "Entretien Social" dans la page __Ajouter un nouveau Patient__ déplacer le "Niveau Scolaire" vers l'etape:2 et déplacer "Situation familiale" vers l'etape:1 
    1. Supprimer le tableau de l'etape:4 "Liste d'attente" dans la page __Ajouter un nouveau Patient__
    1. Renomer le titre par __"Gestion list d'attente"__ dans la page ***"Gestion des consultations"***
    1. Ajouter la colonne ***"Numero Dossier"*** et Supprimer les colonnes "N° d'ordre", "Téléphone" et "Date enregistrement" de la page ***"Gestion des consultations"***
    1. Supprimer le button __"AJOUTER SANS RENDEZ-VOUS"__ dans tous le projet
    1. Modifier le terme ***"Consultation"*** par ***"Prestation"*** dans les pages des __"Préstation medical:REUDUCATION(5)"__

### Les remarques:

* Remarques dites par le client :
    1. Pas de données enregistré dans le Pôle medical
    1. "Entretien social" = "Dossier social" avec le parent
    1. "Employés" = "Personnel(RH)"
    1. "Service" = "Prestation" pour les métier de reuducation(5) = "Consultation" pour le médecin générale
    1. Il ya plus la couverture medical "RAMED"
    1. Tous les services medical revient vers le médecin générale sauf le ***médcien neurologue***
    1. Le nombre de préstation est entre 20 et 30 

* Remarques dites par le chef de project :
    * Il vous faut ***un reseau internet interne*** commun entre tous les département du centre pour pouvoir se connecter à l'application par tous le staff addministrative.
    * En cas d'absence du reseau internet interne il vout faut un ***serveur d'ébergement*** pour l'application.


* Remarques dites par l'équipe développeur :
    1. Saisir le nom  et le mdp seulement pour accedé à l'application
    1. faut ajouter ***un filtre*** dans les "list d'attente"

### Les questions/ Les réponses

1. Questions posées par le client:
    * Est-ce qu'on peut _importer_ la data sur des fichier excel directement sur l'application ? /OUI
    * Est-ce qu'on peut _exporter_ la data sur l'apliction vers un fichier excel vers la fin de la journée ? /OUI
    * Est-il possible de noter la date d'enregistrement de chaque activité et quel utilisateur a réalisé cette activité ? /OUI
    * Sur les list d'attente est-ce que je peut avoir la "date d'appel" et "le nombre d'appel" par le personnel du service social ? /OUI


2. Questions posées par l'équipe développeur:
    * Voulez-vous avoir l'application avec multi_langue ? /NON, Francais seul


3. Questions posées par le chef de project:
    * A quelle point vous éte satisfait des maquettes présenté ? /Moyennement Satisfait
    * Est-ce qu'on peut fixer la date du prochain test utilisateur ? /Semaine Prochaine