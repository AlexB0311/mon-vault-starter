---
name: ranger-boite
description: Trie et range tout ce qui a été déposé en vrac dans _Boite-de-Reception/. À exécuter quand l'utilisateur dit « Range ma boîte », « Trie le sas » ou dépose une note brute.
---

# 📥 Skill : Ranger la Boîte de Réception

## Quand l'activer ?
Quand l'utilisateur dit :
- *« Range ma boîte de réception »*
- *« Trie ce qui traîne »*
- *« Classe cette note brute »*

## Ce que doit faire l'IA (Claude ou ChatGPT) :
1. **Regarder les fichiers** présents dans le dossier `_Boite-de-Reception/` (hors `DEPOSER-ICI.md`).
2. Pour chaque idée ou document trouvé :
   - Déterminer la bonne destination :
     - Projet ou tâche → Créer ou compléter une fiche dans `02-Projets/`.
     - Contact ou rencontre → Créer ou compléter une fiche dans `03-Contacts/`.
     - Article, citation, inspiration → Créer une fiche dans `04-Ressources/`.
   - **Règle Zéro Doublon :** Si une fiche existe déjà sur le sujet, enrichir la note existante au lieu d'en créer une deuxième.
3. **Archiver :** Déplacer le brouillon traité dans `_Archives/`.
4. **Faire un court récapitulatif à l'utilisateur :**
   > *« C'est rangé ! J'ai créé [Fiche A] et complété [Fiche B]. Ta boîte de réception est propre. »*

## Navigation
- [[Skills/Index-des-Skills|Retour aux Super-Pouvoirs]] · [[_Boite-de-Reception/DEPOSER-ICI|Boîte de réception]]
