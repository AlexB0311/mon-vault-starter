---
name: cloture
description: Clôture la session, résume les accomplissements et met à jour Memoire.md. À exécuter dès que l'utilisateur dit « On s'arrête », « Fin de session » ou « C'est bon pour aujourd'hui ».
---

# 🏁 Skill : Clôture & Sauvegarde de Mémoire

## Quand l'activer ?
Dès que l'utilisateur indique la fin de session :
- *« On s'arrête »*
- *« Fin de session »*
- *« C'est bon pour aujourd'hui »*
- *« À plus tard »*

## Ce que doit faire l'IA (Claude ou ChatGPT) :
1. **Mettre à jour `Memoire.md` à la racine :**
   - Mettre la date du jour.
   - Actualiser l'état des projets en cours dans le tableau.
   - Noter la prochaine action recommandée pour notre prochaine session.
   - Ajouter une ligne résumant cette session dans « Historique des Dernières Sessions ».
2. **Si une fiche de projet a avancé :** Mettre à jour sa section *Où en est-on ?* et cocher les étapes terminées.
3. **Répondre en 3 lignes bien distinctes :**
   - ✅ **Ce qu'on a fait aujourd'hui :** (1 phrase)
   - 📌 **Ce qui reste en cours :** (1 phrase)
   - 👉 **Prochaine étape pour la prochaine fois :** (1 phrase)
   > *« Tout est sauvegardé dans ta mémoire ! Bon repos et à bientôt. »*

## Navigation
- [[Skills/Index-des-Skills|Retour aux Super-Pouvoirs]] · [[Memoire]]
