# 🚗 Battelle Parking — Prototype interactif Twine

Un prototype narratif et interactif conçu avec **Twine (SugarCube)**, permettant d’explorer les frustrations quotidiennes d’un·e étudiant·e qui doit se garer sur le campus... et de découvrir en quoi **Battelle Parking** peut faire toute la différence.

---

## 🎯 Objectif

Ce projet illustre, sous forme de scénario immersif, les situations typiques rencontrées par les étudiant·e·s en voiture : pluie, bouchons, parkings saturés.  
Grâce à l’application **Battelle Parking**, l’utilisateur peut simuler différents choix de trajet et constater l’impact d’une bonne anticipation.

---
## 🧠 En quoi Battelle Parking est un *Digital Twin* ?

**Battelle Parking** s'inscrit dans la logique d’un **digital twin (jumeau numérique)** du système de stationnement universitaire.

> Un *digital twin* est une **réplique numérique en temps réel** d’un système physique, utilisée pour surveiller, simuler et optimiser son fonctionnement.

🔍 Dans notre cas :
- Chaque **parking physique** est représenté par une **entité numérique** dans l’application.
- Les **données en temps réel** (nombre de places disponibles, saturation, fréquentation horaire) alimentent cette copie numérique.
- L’utilisateur interagit avec cette **réalité augmentée** en consultant l’état des parkings avant de se déplacer.

📈 Cela permet :
- D’**anticiper les décisions** (où et quand se garer)
- De **réduire le trafic et le stress**
- D’**optimiser l’utilisation des parkings**

🎓 Pour les étudiant·e·s, cela devient un **assistant de mobilité intelligent**, qui reflète fidèlement l’état réel du campus en matière de stationnement.

---

## 🧰 Contenu du dépôt

| Dossier/Fichier                      | Description |
|-------------------------------------|-------------|
| `/images/`                          | Gifs et illustrations utilisés dans les passages (pluie, bouchons, horloge, etc.) |
| `/audio/`                           | Effets sonores et ambiances intégrés au prototype (pluie, bus, guidage, notification, etc.) |
| `BattelleParking_final.twee`         | Fichier Twine complet avec narration enrichie, gestion de fond, audio et choix dynamiques |
| `README.md`                         | Ce fichier de documentation 📘 |

---

## 🧑‍💻 Technologies

- [Twine 2.x](https://twinery.org/)
- Format d’histoire : **SugarCube 2.x**
- Langages : HTML / CSS / JavaScript intégrés dans les passages

---

## 🔊 Sons intégrés (extraits depuis [Pixabay](https://pixabay.com/fr/sound-effects/))

- `calming-rain.mp3` : pluie d’ambiance
- `regional-train-bus.mp3` : bruit de bus
- `clock-ticking.mp3` : attente
- `car-parking.mp3`, `fail-parking.mp3` : réussites et échecs au parking
- `system-notification.mp3` : guidage ou alertes

---

## 🎨 Visuels

Les gifs d’ambiance (pluie, bouchons, horloge, voiture…) sont placés en fond selon le passage, pour une immersion visuelle :

- Fond pluie : `pluie.gif`
- Horloge animée : `clock-ticking.gif`
- Bus embouteillé : `bus-busy.gif`
- Bouchon sous la pluie : `rain-bouchon.jpg`

---

## 🗺️ Structure du scénario

L’utilisateur commence par un **choix narratif** (bus / vélo / voiture) et vit une expérience **conditionnelle** :
- Anticiper (consulter Battelle Parking)
- Ignorer (et risquer l’échec…)

💡 Plusieurs fins possibles, humoristiques ou réussies, selon les décisions prises.

---

## ✨ Slogan final

> **Battelle Parking — Moins de stress pour se garer, plus d’énergie pour étudier.**

---

## 📜 Licence

Utilisation à des fins de démonstration pédagogique uniquement.  
Les ressources audio et visuelles proviennent de banques libres de droits (Pixabay, etc.).

---

