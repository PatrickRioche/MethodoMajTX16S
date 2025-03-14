# MethodoMajTX16S

voir Syntaxe

https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

# Procédure de maj de la TX16S avec EdgeTX.

+ Enveler la carte SD de la TX16S
+ Creer le dossier **SD-TX16S-NEW** sur le bureau
+ Copier sur contenu de la carte SD de la TX16S dans le dossier **SD-TX16S-NEW** dans un répertoire **SAV-SD-TX16S**

## Aller le GitHub de EdgeTX

https://github.com/EdgeTX


https://github.com/EdgeTX/edgetx-sdcard (sous release à droite)

+ Download ***c480x272.zip*** (pour TX16S)
+ Dezipper sous le dossier **SD-TX16S-NEW** sous le répertoire **CARD-SD**

https://github.com/EdgeTX/edgetx-sdcard-sounds (sous release à droite)

+ Download ***edgetx-sdcard-sounds-fr-2.8.0.zip***
+ Dezipper sous le dossier **SD-TX16S-NEW** sous le répertoire **SOUNDS**

https://github.com/EdgeTX/themes (sous release à droite)

+ Download ***edgetx-themes.zip*** 
+ Dezipper sous le dossier **SD-TX16S-NEW** sous le répertoire **THEMES**

https://github.com/EdgeTX/edgetx (sous release à droite)

+ Download ***edgetx-cpn-win64-v2.8.4.zip*** 
+ Dezipper sous le dossier **SD-TX16S-NEW** sous le répertoire **COMPAGNION**
+ Lancer l'installation du **ficher d'installation de Compagnion sous Windows en mode administrateur**
+ Aller Unofficial builds > Pre-built language firmwares are available here
+ Download ***tx16s-lang-v2.8.4.zip***
+ Dezipper sous le dossier **SD-TX16S-NEW** sous le répertoire **FIRMWARE**
+ Garder uniquement le fichier ***tx16s-FR-17692e2.bin***

## Ecraser la carte SD

**Cette méthode permet d'avoir les nouveautés et de garder tous ses modéles**

+ Copier le contenu **CARD-SD** sur la carte SD ![image](https://github.com/PatrickRioche/MethodoMajTX16S/assets/10467749/169ab892-6f07-4bf6-8ddf-076d735c9330)
+ Copier le contenu **SOUNDS**  sur la carte SD
+ Copier le contenu **THEMES**  sur la carte SD
+ Copier le contenu **FIRMWARE**  sur la carte SD

## Recopier les dossiers de l'ancienne carte SD

+ Copier les répertoires sur le carte SD ![image](https://github.com/PatrickRioche/MethodoMajTX16S/assets/10467749/e46d8bb5-17ca-453e-a159-e95deea0e846)

## Mettre la carte SD dans la TX16S

+ Allumer la TX16S normalement
+ Paramètrage dans Radio Settings > Carte SH
+ Dossier FIRMWARE
+ Cliquer sur le fichier ***tx16s-FR-17692e2.bin***
+ Lancer la mise à jour du  boot load 
+ Eteindre la TX16S
+ Allumer à nouveau la TX16S en appuyant sur le bouton suivant :
+ **T4 + POWER + T1**
+ Dossier FIRMWARE
+ Cliquer sur le fichier ***tx16s-FR-17692e2.bin***
+ Lancer la mise à jour du firmware **par un appui long sur la molette**
+ Attendre que la barre de progression soit verte
+ Cliquer sur Exit pour éteindre la TX16S

## Mise à du MULTI Module

https://downloads.multi-module.org/
![image](https://github.com/user-attachments/assets/1e074f9e-d444-420e-af7b-ce042196bdc7)

![image](https://github.com/user-attachments/assets/7c73ecab-30c7-4cbd-a2f2-0418e2c19283)

+ Download ***mm-stm-serial-taer-air-v1.3.4.31.bin***
+ Copier le contenu **FIRMWARE**  sur la carte SD
+ lancer la mise à jour **par un appui long sur la molette**

## Ne pas oublier 

+ Paramètrage dans Radio Settings > Config Radio
* Ordre des voies préfére : **GAFD**
* Mode : **1 Gauche = Dir+Prf**
+ Paramètrage dans Radio Settings > Fonctions Globales
* GF1 : **ON Volume S1**
+ Paramètrage dans Radio Settings > Ecolage
* **Gaz = CH3 100%**
* **Ail = CH1 100%**
* **Prf = CH2 100%**
* **Dir = CH4 100%**
+ Paramètrage dans Radio Settings > Materiel
* Calibrage **des manches, des sliders S1, S2, LS, RS et des boutons 1-6**

## Lien pour Bugs connus

+ Switch mal identifier : https://frskytaranis.forumactif.org/t13503-tx16s-sous-edgetx-2-7-1-non-des-interrupteurs-non-affiche
+ autres ....

# URL Bonnes pratiques

+ Phase de vol :  http://rcaerolab.eklablog.com/opentx-la-logique-et-les-bonnes-pratiques-p1241540#Phases%20de%20vol
+ Télémétrie Vario : https://www.tranquille-modelisme.fr/opentx-telemetrie-variometre.html
+ Tuto Mise à jour EdgeTX 2.X vers 2.8 ( firmware en français et multilangue ) :  https://www.youtube.com/watch?v=63G2ErnIphw
+ Icons TX16S : https://www.skyraccoon.com/
