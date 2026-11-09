---
name: demarrage
description: Reprise de contexte automatique au début de la discussion. À exécuter dès que l'utilisateur dit « Bonjour » ou « On reprend ».
---

# 🚀 Skill : Démarrage Instantané

## Quand l'activer ?
Dès le premier message de la conversation ou quand l'utilisateur dit :
- *« Bonjour »*
- *« On reprend »*
- *« Où en est-on ? »*

## Ce que doit faire l'IA (Claude ou ChatGPT) :
1. **Lire immédiatement le fichier `Memoire.md`** à la racine du coffre.
2. Si un projet précis est cité, consulter sa fiche dans `02-Projets/`.
3. **Répondre en une seule phrase amicale et directe** :
   > *« Bonjour ! La dernière fois, nous travaillions sur [Projet]. La prochaine étape prévue était [Action]. Par quoi souhaites-tu commencer aujourd'hui ? »*
4. Ne jamais redemander à l'utilisateur ce qui est déjà documenté dans le coffre-fort.

## Navigation
- [[Skills/Index-des-Skills|Retour aux Super-Pouvoirs]] · [[Memoire]]
