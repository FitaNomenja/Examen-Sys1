# Examen-Sys1
# WeChall Examen

1. **Inscrivez-vous sur WeChall.**

2. **Entrez le mot de passe WeChall et confirmez-le.**

3. **Utilisez l'adresse IP fournie pour la connexion SSH via Putty.**
   Exemple : `ssh -p 19194 Nomenja@warchall.net`

4. **Connectez-vous à Putty.**
   Exemple :
   - Login: Nomenja
   - Password: Nomenja
   - SSH to: 192.168.138.128
     ```bash
     ssh -p 19194 Nomenja@warchall.net
     ```

5. **Entrez l'adresse IP de WeChall.**
   Exemple : `ssh -p 19194 Nomenja@warchall.net`

6. **Entrez le mot de passe WeChall et résolvez les niveaux.**

7. **Commandes utiles :**
   - `cd`: Changer de répertoire.
   - `pwd`: Afficher le répertoire actuel.
   - `ls`: Afficher le contenu d'un répertoire.
   - `ls –al`: Afficher les fichiers cachés.
   - `cat`: Lire un fichier.
   - `chmod`: Modifier les autorisations de fichier.
     - `chmod +r`: Ajouter les autorisations de lecture.

## Niveau 0 :
- Utilisez `pwd` pour afficher le répertoire actuel.
- `cd /home/level`
- `ls`
- `cd 00_*`
- `ls`
- `cat`
  Mot de passe : "bitwarrior"

## Niveau 1 :
- Utilisez `cd` pour changer de répertoire.
- `cd blue ; hats ; grey ; solution ; patience`
- `cat`
  Mot de passe : "patience"

## Niveau 2 :
- `ls -al`
- `cd .porb`
- `cat`
  Mot de passe : "HiddenIsConfig"

## Niveau 3 :
- Utilisez `ls –al` pour voir les dossiers et fichiers cachés.
- `cd .bash_history`
  Mot de passe : "RepeatingHistory"

## Niveau 4 :
- Revenez dans le dossier de départ.
- `ls`
- `cd level`
- `cd 04_*`
- `ls`
- `chmod +r` : Pour modifier les autorisations du fichier en lecture pour l'utilisateur.
- `cat README2.md`
  Mot de passe : "AndOfCourseIDoKnowChown"

## Niveau 5 :
- `cd /home/level 05_*`
- `ls`
- `cat README.md`
  Mot de passe : "OKPRIVATE"
