# Disease propagation

![release](https://img.shields.io/badge/release-v1.0-blueviolet)
![language](https://img.shields.io/badge/language-C%2B%2B-0052cf)
![library](https://img.shields.io/badge/library-SFML-00cf2c)
![size](https://img.shields.io/badge/size-32%20Mo-f12222)
![license](https://img.shields.io/badge/license-CC--0-0bb9ec)

<br/>

Ce dépôt contient le code source d'une simulation de propagation de maladie.

<br/>

<p align="center">
	<img src="https://i.imgur.com/opiz490.png" width="700">
</p>

<br/>

# Utilisation

Le programme comporte un menu intégré pour changer les différents paramètres de la simulation, si vous souhaitez uniquement tester la simulation, vous pouvez consulter les [Releases](https://github.com/angeluriot/Disease_propagation/releases).

<br/>

<p align="center">
	<img src="https://i.imgur.com/bgHVsj3.png" width="700">
</p>

<br/>

# Compilation

## Outils nécéssaires

- [CMake](https://cmake.org/)
- (Windows seulement) Visual Studio
- (Unix seulement) [SFML](https://www.sfml-dev.org/) et GNU Make

Remarque : SFML est aussi nécéssaire pour lancer l'application (ne la distribuez donc pas sans)

## Windows

Ouvrez le dossier du projet, et lancez `cmake .` puis ouvrez la solution générée dans Visual Studio

## Unix

```
$ cmake .
$ make
$ ./Disease_propagation
```

<br/>

# Tests

Voici un test sous forme de gif animé avec les paramètres présentés dans l'image de la partie [Utilisation](#utilisation) :

<br/>

<p align="center">
	<img src="https://i.imgur.com/6u8uwZK.gif" width="700">
</p>

<br/>

# Crédits

* [Angel Uriot](https://github.com/angeluriot) : Créateur du projet.

* [Gabin Lefranc](https://github.com/glcraft) : Ajout d'un CMakeLists.
