# CluAreas

[![Release](https://img.shields.io/github/v/release/The-Gate-Project/CluAreas?include_prereleases&color=41788a)](https://github.com/The-Gate-Project/CluAreas/releases)
[![Published](https://img.shields.io/github/release-date-pre/The-Gate-Project/CluAreas?display_date=published_at&label=published&color=014a69)](https://github.com/The-Gate-Project/CluAreas/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/The-Gate-Project/CluAreas/total?color=41788a)](https://github.com/The-Gate-Project/CluAreas/releases)

[![Language](https://img.shields.io/badge/language-french%20%7C%20schinese-014a69)](https://github.com/The-Gate-Project/CluAreas/releases)
[![Games](https://img.shields.io/badge/games-BGEE%20%a0%20BG2EE%20%a0%20EET%20%a0%20IWDEE-41788a)](https://github.com/The-Gate-Project/CluAreas/releases)

<!--

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FThe-Gate-Project%2FCluAreas&countColor=41788a&style=flat)

[![Platform](https://img.shields.io/badge/platform-Windows%20%a0%20macOS%20%a0%20Linux%20%a0%20Project%20Infinity-014a69)](https://github.com/The-Gate-Project/CluAreas/releases)
-->

**Auteur** : ****


## Description :
---------------


Traduction des CheatsAreas (Zones du jeu accessibles grâce à la CLUA console)

Pour BGEE, BGSoD, BG2EE et EET. Également compatible avec IWDEE.


- **Si vous prévoyez d'installer EET, Installez ce mod après EET**


- **Installer ce mod après Check the bodies, Trials of the Luremaster et Test Your Mettle**


- **Il est préférable d'installer CluAreas après les mods qui ajoutent de nouvelles zones à la CluaConsole, ceux-ci peuvent se baser sur les nom anglais pour s'insérer dans le jeu.**


- **Il est préférable d'installer CluAreas après les mods d'interface (UI)** 


- **Pour utiliser la CLUAConsole le Debug Mode doit être activé à l'aide de l'un des mods ci-dessous.**


[Reveal Hidden Gameplay Options](https://github.com/Argent77/A7-HiddenGameplayOptions/releases)

[EEUITweaks ](https://github.com/r-e-d/EEUITweaks/releases)


- **Ou bien manuellement !**
  
Pour les Enhanced Editions, il faut se rendre dans **Mes Documents**, le répertoire ou se situe les "save" du jeu. (nommé "Baldur's Gate - Enhanced Edition", "Baldur's Gate II - Enhanced Edition" ou "Baldur's Gate - Enhanced Edition Trilogy" pour EET)

Dans le fichier **Baldur.lua** ajoutez la ligne suivante en dessous de n'importe quelle ligne similaire :

    SetPrivateProfileString('Program Options','Debug Mode','1')


## Composants :
---------------

### Areas Cheats


#### Choix 1 : Traduit en français les noms des cartes du jeu accessible dans la CLUAConsole

<details>
  <summary>Aperçu choix 1</summary>

![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR01.png)
![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR02.png)
![BG2EE](https://11jo.github.io/L-P-T/Pictures/CluaFR/BG2EECLUAFR01.png)
 
</details>



#### Choix 2 : Ajoute l'accès aux extensions pendant la campagne principale. 
	- Donne acces aux Fosses noires et au tutoriel dans BGEE et BGEE
	- Donne acces aux zones de Siege Of Dragonspear dans BGEESoD et aux zones de ToB dans BG2EE
	- Pour Icewind Dale ce sera Heart of Winter et Trials of the Lurmaster
	- Ajoute une séparation entre les campagnes, voir aperçu ci-dessous

<details>
  <summary>Aperçu choix 2</summary>

![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR10.png)
![BGSoD](https://11jo.github.io/L-P-T/Pictures/CluaFR/BGEECLUAFR11.png)
![BG2EE](https://11jo.github.io/L-P-T/Pictures/CluaFR/BG2EECLUAFR10.png)
 
</details>



### Areas Cheats pour MODS


Traduit en français les noms des cartes ajoutées par des mods dans la CLUAConsole

<details>
  <summary>Aperçu pour les mods</summary>

![Mod](https://11jo.github.io/L-P-T/Pictures/CluaFR/MODSCLUAFR01.png)
![Mod](https://11jo.github.io/L-P-T/Pictures/CluaFR/MODSCLUAFR02.png)
 
</details>

Ce composant détecte automatiquement si certains mods sont installés...


<details>
  <summary>Liste des mods concernés</summary>

Mods supportés :

- Check the bodies

- Trials of the Luremaster
 
- Test Your Mettle
 
- IWD1_EET

Mods **bientôt** supportés :

- IWD2_EET
 
</details>


## Installation :
----------------


Extraire l'archive dans le répertoire du jeu et lancer Setup-CluAreas.exe, puis suivre les indications.


## Compatibilité :
----------------


CluAreas devrait être installé après les mods qui ajoutent des nouvelles cartes et peuvent se baser sur les nom anglais pour s'insérer dans la CLUAConsole.



Pour le composant Areas Cheats pour MODS, celui-ci doit s'installer impérativement après les mods qui ajoutent des nouvelles cartes afin de les intégrer lui même à la CLUAConsole. (Voir la liste des mods concernés)


## Remerciement :
----------------


Un grand merci à Selphira  !

Thanks to : 

- MephistoSatanDevil


## Version History :
----------------


v1.0 : 

- Initial release

v1.1

- BWS-FR-Fixpack detection update for new version

V1.2

- Cleanup and Typos in tp2
- Uniformisation
- Delete Unused folder

V2.0

- Simplified Chinese Translation thanks to MephistoSatanDevil.
- Mod renamed from CLUAFr to CluAreas.
- InfinityUI compatibility
- EEFixpack compatibility (And probably other mods modifying Areas description in the CLUAConsole.)
