# MethodoMajTX16S

voir Syntaxe

https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

# Procédure de maj de la TX16S avec EdgeTX.

+ Enveler la carte SD de la TX16
+ Copier sur contenu dans un Dossier **SDTX16S-AVANT** sur le bureau
+ Creer le dossier **SDTX16S-APRES** sur le bureau

## Aller le GitHub de EdgeTX

https://github.com/EdgeTX


https://github.com/EdgeTX/edgetx-sdcard (sous release à droite)

+ Download ***c480x272.zip*** (pour TX16S)
+ dezipper sous le dossier **SDTX16S-APRES** sous le répertoire **CARD-SD**

https://github.com/EdgeTX/edgetx-sdcard-sounds (sous release à droite)

+ Download ***edgetx-sdcard-sounds-fr-2.8.0.zip***
+ dezipper sous le dossier **SDTX16S-APRES** sous le répertoire **SOUNDS**

https://github.com/EdgeTX/themes (sous release à droite)

+ Download ***edgetx-themes.zip*** 
+ dezipper sous le dossier **SDTX16S-APRES** sous le répertoire **THEMES**

https://github.com/EdgeTX/edgetx (sous release à droite)

+ Download ***edgetx-cpn-win64-v2.8.4.zip*** 
+ dezipper sous le dossier **SDTX16S-APRES** sous le répertoire **COMPAGNION**
+ Aller Custom/multilingual builds > Multilingual builds are available 
+ Download ***tx16s-lang-v2.8.4.zip***
+ dezipper sous le dossier **SDTX16S-APRES** sous le répertoire **FIRMWARE**
+ aucune le fichier ***tx16s-FR-17692e2.bin***

## Ecraser la carte SD

+ Copier le contenu **CARD-SD** sur la carte SD ![image](https://github.com/PatrickRioche/MethodoMajTX16S/assets/10467749/169ab892-6f07-4bf6-8ddf-076d735c9330)
+ Copier le contenu **SOUNDS**  sur la carte SD
+ Copier le contenu **THEMES**  sur la carte SD
+ Copier le contenu **FIRMWARE**  sur la carte SD

## Recopier les dossiers de l'ancienne carte SD

+ Copier les répertoires sur le carte SD ![image](https://github.com/PatrickRioche/MethodoMajTX16S/assets/10467749/e46d8bb5-17ca-453e-a159-e95deea0e846)

## Mettre la carte SD dans la TX16S

+ **T4+POWER+T1**

## Mise à du MULTI Module

https://downloads.multi-module.org/

+ Download ***mm-stm-serial-taer-v1.3.3.20.bin***
+ Copier le contenu **FIRMWARE**  sur la carte SD

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

+ Phase de vol http://rcaerolab.eklablog.com/opentx-la-logique-et-les-bonnes-pratiques-p1241540#Phases%20de%20vol
+ 
