# Réponses 

## Mission 5

1. l’identifiant court du premier commit ; 

R:c881d57  / Creation de index.html

2. le commit correspondant à l’ajout de la page Contact ; 

R: aefd166 / Creation de la page contact.html

3. le nombre actuel de commits ; 

R:7

4. la commande utilisée pour afficher l’historique sous forme graphique.

R: git log --oneline --graph --all


5. Commande utilisée pour examiner précisément un commit de la fonctionnalité Contact:

R : git show aefd166



## Mission 7

Commande utilisée pour annuler les modifications : git restore index.html
Vérification : git status:
On branch main
nothing to commit, working tree clean

## Mission 8

Commande : git reset --mixed HEAD~1

Le commit "Test affichage" est annulé, main revient au commit d'avant (HEAD~1).

La modification est toujours dans style.css parce que --mixed enlève le commit et le staging, mais ne touche pas les fichiers.

git reset --hard HEAD~1 aurait aussi supprimé la modification du fichier (et elle serait perdue).