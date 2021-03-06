---
title: Ekylibre 0.3.0 sorti
name: ekylibre-0-3-0
---
La version 0.3.0 est sortie. Comparée aux anciennes versions, c’est la première fois qu’elle est disponible sous forme de paquet pour les systèmes Debian (à partir de Squeeze) et Ubuntu (à partir de Lucid Lynx).

Voici les principaux changements :

  - Ajout du code de la société dans les URL. Ex. : http://mon.domaine.tld/MA-SOCIETE
  - Internationalisation de l’application en Français, Anglais et Arabe (à 81%)
  - Ajout du tri automatique dans les extractions dans l’ordre des colonnes.
  - Ajout du module Finances, qui regroupent toutes les opérations financières classiques : Encaissements, Décaissements, Remises en banque et Virements internes
  - Ajout de la gestion de Trésorerie pour gérer tous les dépôts d’argent : Compte bancaires ou caisse.
  - Amélioration de la gestion d’îlots
  - Suppression du lien Tableau de bord en haut du panneau latéral gauche
  - Changements en interne :
      - Tables renommées (Certaines extractions peuvent en subir directement les conséquences en n’étant plus compatibles)
      - Passage du framework à Ruby on Rails 2.3.10
      - Utilisation de Bundler pour gérer les gems
      - Suppression de plusieurs plugins obsolètes
      - Création automatisée de paquet Debian
      - Refactorisation du système de création des paquets d’installation

