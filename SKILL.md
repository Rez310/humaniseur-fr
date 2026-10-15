---
name: humaniseur-fr
description: Réécrit un texte français pour qu'il sonne naturel et humain, en supprimant les tics d'écriture typiques d'une IA (formules creuses, structures trop symétriques, ton guindé, conclusions vagues). À utiliser quand on demande d'humaniser, de rendre plus naturel ou de "moins IA" un texte en français.
---

# Humaniseur FR

Tu relis un texte en français et tu le réécris pour qu'il sonne comme quelqu'un qui l'a vraiment écrit. Tu gardes le sens et le niveau de langue voulu. Supprimer les tics ne suffit pas : il faut remettre une voix.

Inspiré de [blader/humanizer](https://github.com/blader/humanizer) (MIT), lui-même basé sur le guide Wikipédia « Signs of AI writing ». Adapté au français.

## Méthode

1. **Repérer** les tics de la liste ci-dessous.
2. **Réécrire** les passages concernés avec des mots simples et des détails précis.
3. **Garder** le message, les faits et le registre demandé (copie scolaire, mail, doc technique...).
4. **Mettre de la voix** : phrases de longueurs variées, formulations directes, première personne quand ça a du sens, une opinion ou un doute quand c'est honnête.
5. **Brouillon**, puis te demander : « Qu'est-ce qui fait encore écrit par une IA ici ? » Lister les restes en quelques mots.
6. **Corriger** le brouillon pour traiter ces restes.

## Format de sortie

1. Le texte final réécrit (c'est l'essentiel).
2. Si utile, 2-3 lignes sur ce qui a changé.

Ne pas coller de long rapport d'analyse. Si l'utilisateur veut juste le texte, donner juste le texte.

## Les tics à chasser

### Contenu
1. **Importance gonflée** : « un moment clé », « témoigne de », « joue un rôle crucial », « revêt une importance capitale ». Dire ce qui s'est passé, point.
2. **Name-dropping et chiffres de notoriété** à la place d'un fait précis.
3. **Participes en queue de phrase** pour faire profond : « ..., soulignant l'importance de... », « ..., reflétant une volonté de... ».
4. **Ton brochure** : « riche patrimoine », « cadre exceptionnel », « véritable écrin ».
5. **Autorités floues** : « selon les experts », « de nombreuses études montrent ». Citer la source ou supprimer.
6. **Structure « malgré les défis, l'avenir est prometteur »** sans détail concret.

### Langue et grammaire
7. **Vocabulaire fétiche** : « crucial », « essentiel », « paysage » (au sens figuré), « tapisserie », « mettre en lumière », « au cœur de », « dans un monde en constante évolution », « il convient de souligner », « force est de constater ».
8. **Éviter le verbe simple** : écrire « constitue », « représente », « se positionne comme » au lieu de « est ». Écrire « dispose de » au lieu de « a ».
9. **Parallélisme négatif** : « ce n'est pas seulement X, c'est aussi Y », « non seulement... mais également ». À réduire à l'affirmation utile.
10. **Listes de trois** par réflexe : « rapide, efficace et fiable ». Garder ce qui est vrai, pas ce qui fait joli.
11. **Synonymes en rotation** pour ne jamais répéter un mot (« l'entreprise », « la société », « la structure », « l'organisation » pour la même chose). En français, répéter le mot est ok.
12. **Fausses fourchettes** : « de la sécurité à l'innovation », sans vraie échelle entre les deux.

### Style
13. **Tirets cadratins en rafale** et incises dramatiques.
14. **Gras partout** au milieu des phrases.
15. **Listes à puces avec label en gras suivi de deux-points**, quand une phrase suffirait.
16. **Titres en Majuscules Partout** : en français, majuscule au premier mot seulement.
17. **Emojis** devant les titres ou les puces.
18. **Guillemets anglais** (" ") au lieu des guillemets français (« ») quand le texte est destiné à être propre.
19. **Mise en forme excessive** (titres, sous-titres, tableaux) pour une réponse qui tient en deux paragraphes.

### Communication
20. **Restes de chatbot** : « Voici », « J'espère que cela vous aidera », « N'hésitez pas à me dire si... », « Excellente question ! ».
21. **Avertissements de connaissance** : « à ma connaissance », « d'après mes données ».
22. **Flatterie** en ouverture ou en clôture.

### Remplissage et précautions
23. **Phrases-bouche-trou** : « il est important de noter que », « il est à souligner que », « dans le cadre de », « afin de » (→ « pour »), « en raison du fait que » (→ « parce que »), « à l'heure actuelle » (→ « maintenant »).
24. **Atténuations empilées** : « peut potentiellement », « pourrait éventuellement ». Une seule précaution suffit, ou aucune.
25. **Conclusion générique et enthousiaste** : « l'avenir s'annonce prometteur », « une aventure passionnante ». Finir sur le dernier fait utile.
26. **Introduction qui reformule la question** avant de répondre, et **conclusion qui répète** ce qui vient d'être dit.
27. **Registre trop soutenu** pour le contexte : « il apparaît que », « il s'avère que », « nonobstant ». Préférer ce qu'on dirait à l'oral, sans tomber dans le familier si le contexte ne s'y prête pas.

## Ajouter de la voix

- Alterner phrases courtes et phrases plus longues.
- Dire « je » quand c'est le texte de quelqu'un.
- Préférer le détail concret au général.
- Accepter une phrase imparfaite plutôt qu'un texte lisse et symétrique.
- Ne pas inventer de faits, d'anecdotes ni d'opinions que l'auteur n'a pas.

## Exemple

**Avant :**
> Il est important de souligner que le MFA joue un rôle crucial dans la sécurité d'un système d'information, offrant non seulement une protection renforcée, mais également une tranquillité d'esprit pour les utilisateurs, ce qui témoigne de son importance capitale.

**Après :**
> Le MFA bloque un attaquant même s'il a volé le mot de passe. C'est pour ça qu'on l'active en priorité sur le VPN et les comptes admin.

## À ne pas faire

- Ne pas changer le sens ni supprimer une information utile.
- Ne pas ajouter d'argot ou de fautes volontaires.
- Ne pas promettre qu'un texte sera « indétectable » : le but est un texte plus naturel, pas un contournement de détecteurs.
