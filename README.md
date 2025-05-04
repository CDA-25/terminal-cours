# Introduction au Terminal

Le terminal (ou invite de commande) est un outil qui permet d’interagir directement avec le système d’exploitation  
via des lignes de commande. C’est un moyen puissant d’exécuter des tâches,  
de naviguer dans les fichiers, et bien plus encore, sans interface graphique.

## 1. Ouvrir le Terminal

•	Sur macOS : Recherchez “Terminal” via Spotlight (Cmd + Espace) et ouvrez-le.
•	Sur Linux : Appuyez sur Ctrl + Alt + T ou cherchez “Terminal” dans le menu.
•	Sur Windows : Utilisez “PowerShell” ou “Invite de commandes” (cmd), ou installez un terminal comme WSL (Windows Subsystem for Linux).

## Les Commandes de Base

1. pwd (Print Working Directory)

Affiche le chemin actuel où vous vous trouvez dans le système de fichiers.
```bash
pwd
```

2. ls (List)

Liste les fichiers et dossiers du répertoire actuel.
```bash
ls        # Liste simple
ls -l     # Liste détaillée avec des informations sur chaque fichier/dossier
ls -a     # Inclut les fichiers cachés (commençant par un ".")
```

3. cd (Change Directory)

Change de répertoire. Vous pouvez naviguer dans le système de fichiers avec cette commande.
```bash
cd nom_du_dossier     # Aller dans un dossier spécifique
cd ..                 # Remonter d'un niveau
cd /chemin/absolu     # Aller vers un chemin absolu
cd ~                  # Aller vers le répertoire personnel
```

4. mkdir (Make Directory)

Crée un nouveau dossier dans l’emplacement actuel.
```bash
mkdir mon_nouveau_dossier
```

5. touch

Crée un nouveau fichier vide dans le répertoire actuel.
```bash
touch mon_fichier.txt
```

6. rm (Remove)

Supprime des fichiers et dossiers. Soyez prudent, cette action est irréversible !
```bash
rm mon_fichier.txt                # Supprime un fichier
rm -r mon_dossier                 # Supprime un dossier et son contenu
```

	⚠️ Attention : L’utilisation de rm -r peut supprimer des dossiers entiers.

7. cp (Copy)

Copie des fichiers ou des dossiers d’un endroit à un autre.
```bash
cp fichier_source.txt dossier_dest      # Copie un fichier
cp -r dossier_source dossier_dest       # Copie un dossier et son contenu
```

8. mv (Move)

Déplace ou renomme des fichiers ou des dossiers.
```bash
mv fichier.txt nouveau_nom.txt          # Renomme un fichier
mv fichier.txt dossier_dest/            # Déplace un fichier dans un autre dossier
```

9. cat

Affiche le contenu d’un fichier directement dans le terminal.
```bsah
cat mon_fichier.txt
```

10. echo

Affiche un texte ou envoie du texte dans un fichier.
```bash
echo "Hello World"          # Affiche "Hello World" dans le terminal
echo "Hello World" > fichier.txt   # Écrit "Hello World" dans un fichier
```

11. man (Manual)

Affiche le manuel d’une commande. Utile pour en apprendre plus sur une commande.
```bash
man ls      # Affiche le manuel pour la commande ls
```

	Astuce : Pour quitter le manuel, appuyez sur q.

## Conclusion

Ces commandes couvrent les bases pour naviguer dans le terminal, gérer des fichiers et des dossiers,  
et effectuer des actions simples. Plus vous les utilisez, plus vous vous habituerez à la structure du terminal et à la logique des commandes.  
Conseil : Utilisez fréquemment ces commandes pour développer vos réflexes et prenez le temps d’explorer avec man  
pour découvrir d’autres options utiles.  
