# ABD-TP07

Authors
-------

- Thomas Bernard
- Anne-Sophie Saint-Omer



Exercice 2 : Recherche d'anagrammes
------------------------------------

Écrire un programme en pseudo-code qui détermine les anagrames des mots lus dans un dictionnaire. Comme fichier dictionnaire on utilisera le fichier des mots de la langue anglaise dico.txt.

1. On veut tous les mots en résultats, même ceux qui n'ont pas d'anagramme.
2. On ne conserve que les mots du dictionnaire qui ont un autre mot comme anagramme.

```
Pour chaque mot1 dans dico.txt
    On crée un tableau de la longueur du mot1
    Chaque cellule contient une lettre du mot1
    
    Pour chaque mot2 dans dico.txt de la même longueur que mot1
        On crée un tableau temporaire qui contient chaque lettre de mot2
        On compare les deux tableaux.
        Si mot1 et mot2 possèdent les mêmes lettres dans un ordre différent
            Afficher mot2 est anagramme de mot1
```
                
