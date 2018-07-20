<p align="center">
  <img width="440" height="184" src="github.png">
</p>

# TP Git / Github
Présentation de quelques commandes utilisables sur Git et avec Github ainsi qu'un rappel des commandes Unix. 

## Commandes Git
*Pour être utilisables sur Git, chaque instruction doit être précédée par "**git**".*

Commande | Description | Option(s) utile(s) | Exemple d'utilisation 
-------- | -------- | -------- | --------
**init** | Initialise le repository. | | git init
**commit** | Permet d'appliquer les changements ajoutés à l'index. | -m : ajoute un message pour décrire les changements appliqués (obligatoire). | git commit -m "Description du commit"
**log** | Affiche l'historique de tous les commits avec la date, l'heure, l'auteur et le numéro du commit. | --oneline : affiche une version synthétisée de l'historique. --graph --decorate : affiche un graphe de l'historique des commits prenant en compte les fusions de branches. | git log --oneline
**checkout** | Permet de changer de branche active ou de restaurer des fichiers anciens. | -b : crée une nouvelle branche. | git checkout -b nouvelleBranche
**push** | Envoie les commits faits en local vers un repository distant. | -u : pour une branche envoyée vers un repository distant, crée un upstream de référence. | git push -u origin master

## Commandes Unix

Commande | Description | Option(s) utile(s) | Exemple d'utilisation 
-------- | -------- | -------- | --------
**ls** | Affiche la liste des fichiers et dossiers du fichier courant. | -a : affiche tous les éléments ainsi que ceux masqués. | ls
**cd** | Permet de changer de répertoire. | | cd MonDossier
**mkdir** | Crée un nouveau dossier. | | mkdir MonNouveauDossier
