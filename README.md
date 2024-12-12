# ADDS_Windows
Quête WCS ADDS sous Windows Server 2022

## 1) Installation du rôle ADDS dans Windows Server via le gestionnaire de serveur

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/1-Gestionnaire_de_serveur.png)



## 2) Dans l'assistant ajout de rôle et de fonctionnalités choisir "Service ADDS"

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/2-Assistant_ajout_de_role_et_de_fonctionnalites-ADDS.png)


## 3) Choisir "Ajouter les fonctionnalités, puis choisir "Suivant" ou "Installer" dans les fenêtres suivantes

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/3-Assistant_ajout_de_role_et_de_fonctionnalites-ADDS.png)


## 4) Suivre la progression de l'installation


![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/4-Progression_installation.png)


## 5) Après l'installation du service ADDS, la configuration post déploiement est nécessaire (Pour créer le Controleur de domaine)
Pour ce faire, selectionner le point d'exclamation dans le panneau jaune.
Selectionner "Nouvelle Forêt" puis renseigner le nom de domaine, ici "wilders.lan"

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/5-Configuration_post_deploiement.png)


## 6) Options du Contrôleur de Domaine
Le niveau fonctionel minimum dépend des machines clientes dans le domaine. Ici pour du Windows 10, choisir Windows Server 2016
Puis renseigner un mot de passe du mode de restauration.

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/6-options_du_controleur_de_domaine.png)


## 7) Renseigner un nom Netbios pour des machines anciennes eventuelles sur le réseau

![Install_role_DNS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/7-Nom_Netbios.png)

## 8) définir les Chemins dd'accès des fichiers de base de données ADDS, logs et sysvol

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/8-Chemins_acces.png)


## 9) Récapitulatif avant déploiement du DC

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/8-Recapitulatif.png)


## 10) Installation

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/9-Installation.png)


## 11 Fin de l'installation

![Install_role_ADDS](https://github.com/Hebus79/ADDS_Windows/blob/main/images/10-Fin_installation.png)



## 12 Le contôleur de domaine "wilder.lan" avec ADDS est maintenant créé

