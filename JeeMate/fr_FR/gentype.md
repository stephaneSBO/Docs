# L'application est sur les stores.

L'application est disponible sur les stores en BETA (IOS ou Android). <br/>
Il faudra donc avoir le plugin BETA et suivre le [Fil community](https://community.jeedom.com/t/jeemate-version-0-9-0-android-ios-et-le-debut-de-la-personnalisation/60221?u=titi_titi)
Ou sur le discord de DomoTech [Fil community](https://discord.gg/zvGTDfE)

Cordialement
Thibaut Et Pascal
   
   
   


Plugin officiel de l'application JeeMate sur Android.
Et dans le Futur sur Android TV et IOS

![JeeMate Icon](../images/jeemate_icon.png)

Ce plugin permet d'appairer JeeMate avec votre serveur Jeedom, très facilement en seulement quelques clics. afin de créer un équipement virtuel qui vous permettra, via l'application, d'envoyer et recevoir des notifications,  et déclencher des événements basés sur la géolocalisation de votre appareil.

Sommaire
==============================

 - [Présentation de l'application](#paragraphe1)
 - [Fonctionnalités](#paragraphe2)
 - [Compatibilité avec Jeedom](#paragraphe3)
 - [Compatibilité avec les plugins Jeedom](#paragraphe4)
 - [Tableau des compatibilités](#paragraphe5)
	 - [Chauffage](#paragraphe5-1)
	 - [Généric](#paragraphe5-2)
	 - [Lumière](#paragraphe5-3)
	 - [Mode](#paragraphe5-4)
	 - [Portail/Garage](#paragraphe5-5)
	 - [Prise](#paragraphe5-6)
	 - [Serrure](#paragraphe5-7)
	 - [Sirène](#paragraphe5-8)
	 - [Thermostat](#paragraphe5-9)
	 - [Volet](#paragraphe5-10)
	 - [Caméra](#paragraphe5-11)
 - [Configuration du plugin JeeMate](#paragraphe6)
 - [Premier lancement de l'app JeeMate](#paragraphe7)
 - [Fonctionnalités](#paragraphe8)
	 - [Onglets Favoris Maison ](#paragraphe8-1)
	 - [Onglet Pièces ](#paragraphe8-2)
	 - [Designs Jeedom et pages web favorites ](#paragraphe8-3)
	 - [Onglet Caméras](#paragraphe8-4)
	 - [Menu JeeMate ](#paragraphe8-5)
 - [Configuration](#paragraphe9)
	 - [Notifications](#paragraphe9-1)
	 - [Géoloc](#paragraphe9-2)
		 - [Etats : Mobile & Stationnaire](#paragraphe9-2-1)
		 - [Domicile et Zones (aka Geofencing)](#paragraphe9-2-2)
		 - [Gestion de la présence des membres, géoloc et tracés](#paragraphe9-2-3)
	 - [Connecteur Jeedom](#paragraphe9-3)
	 - [Caméra](#paragraphe9-4)
	 - [Reconnaissance vocale](#paragraphe9-5)
	 - [Service SMS](#paragraphe9-6)
	 - [Service SIP](#paragraphe9-7)
	 - [Sécurité](#paragraphe9-8)
	 - [Thème](#paragraphe9-9)
	 - [Sauver/Importer App](#paragraphe9-10)
	 - [Pages Widgets](#paragraphe9-11)
		 - [Thermostat](#paragraphe9-11-1)
		 - [Lumière](#paragraphe9-11-2)
 - [Les commandes Infos/Actions disponibles dans un équipement JeeMate](#paragraphe10)
	 - [Notifications](#paragraphe10-1)
	 - [Capteurs disponibles sur votre appareil JeeMate](#paragraphe10-2)
	 - [Send SMS](#paragraphe10-3)
	 - [TTS Speak](#paragraphe10-4)
	 - [Send Action](#paragraphe10-5)
 - [Questions fréquentes](#paragraphe11)



Présentation de l'application <a name="paragraphe1"></a>
==============================

JeeMate est une application mobile compatible avec Jeedom.<br/>Contrôlez facilement votre maison intelligente grâce à son interface intuitive et customisable.<br/>JeeMate dispose de nombreuses fonctionnalités, et est compatible avec de nombreux plugins Jeedom.<br/>JeeMate utilise les types génériques de Jeedom.

Sentez-vous toujours proche de chez vous!
Depuis n'importe où, vous pourrez :
- Interagir avec votre maison intelligente
- Monitorer et contrôler vos équipements
- Recevoir et répondre aux notifications PUSH, textes, images et/ou vocales.
- Gérer la présence et automatiser des actions en fonction de votre localisation
- Visualiser vos caméras, ou streams externes en Live
- Visualiser l'historique de vos équipements si préalablement activés dans Jeedom
- Envoyer des commandes vocales à votre serveur Jeedom, sans passer par les serveurs cloud, avec écoute en continue ou non, et hotword custom
- Utiliser l'application en mode tablette de contrôle à la maison, et utiliser des fonctions d'intelligence artificielles de la caméra
- Envoyer et recevoir des sms
- etc.

Grâce à son interface customisable, vous pourrez aussi :
- Définir des équipements et scènes favoris
- Filtrer l'affichage dans vos Favoris et Pièces, par type
- Réorganiser l'ordre d'affichage
- Customiser vos widgets
- Customiser l'affichage global ou par Pièces
- Customiser certaines parties de l'interface
- Changer complètement l'interface, grâce aux différents thèmes ainsi que leurs variantes Jour/Nuit aka "Light/dark"
- Sécuriser l'accès à chaque équipements! Grâce à un digicode ou la reconnaissance biométrique (faciale ou empreinte digitale)
- Afficher vos designs Jeedom et autres pages favorites, comme des pages persos grafana ou autres
- Ou encore créer des scénarios grâce à son éditeur.
- etc.

L'application mobile et son plugin ont été développés avec comme objectifs principaux :
- "mobile-first" afin de réduire la dépendance à un autre périphérique tel qu'un ordinateur que ce soit pour le rendu dans l'application mobile et d'autres tâches quotidiennes
- contrôler votre maison intelligente le plus simplement possible, avec le moins d'étapes tout en ayant de nombreuses possibilités de customisation
- réduire le nombre de plugins utilisés et les ressources de votre serveur Jeedom
- réduire le nombre d'applications mobiles utilisées et les ressources de votre équipement

JeeMate gère aussi les droits utilisateurs et mots de passe Jeedom sur les commandes, préalablement définis dans votre Jeedom.

**Note : L'utilisation continue du GPS en tâche de fond peut réduire la durée de vie de la batterie. JeeMate contient des paramètres afin d'optimiser ceci (cf doc ci-dessous)**


Compatibilité avec Jeedom <a name="paragraphe3"></a>
==============================

JeeMate gère les types génériques définis dans JEEDOM et plus!
Pour qu'un équipement apparaisse dans JeeMate, l'équipement doit être visible et avec des types génériques configurés sur ses commandes.

[Plus d'informations sur les types génériques.](https://www.jeedom.com/blog/3327-application-mobile-les-types-generiques/)

Dans certains cas, JeeMate va aussi au-delà des types génériques en rendant compatibles certains plugins.
JeeMate gère certains plugins Jeedom Officiels, ainsi que d'autres développés par la communauté.

Tableau des compatibilités <a name="paragraphe5"></a>
==============================

TODO : Ajouter les autres types, avec plus d'informations pour la configuration.
#### Chauffage <a name="paragraphe5-1"></a>

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Chauffage fil pilote Etat       | Info      | Oui          |
| Chauffage fil pilote Bouton     | Action    | Non          |
| Chauffage fil pilote Bouton OFF | Action    | Oui          |
| Chauffage fil pilote Bouton ON  | Action    | Oui          |

#### Généric <a name="paragraphe5-2"></a>

| Type générique                        | Sous-type | Compatible ? |
| ------------------------------------- | --------- | ------------ |
| Tous                                  | Info      | Oui          |

#### Lumière <a name="paragraphe5-3"></a>

| Type générique     | Sous-type | Compatible ? |
| ------------------ | --------- | ------------ |
| Lumière couleur    | Info      | Oui          |
| Lumière Etat       | Info      | Oui          |
| Lumière Bouton Off | Action    | Oui          |
| Lumière Bouton On  | Action    | Oui          |
| Lumière Couleur    | Action    | Oui          |
| Lumière Mode       | Action    | Oui          |
| Lumière Slider     | Action    | Oui          |
| Lumière Toggle     | Action    | Oui          |

#### Mode <a name="paragraphe5-4"></a>

| Type générique | Sous-type | Compatible ? |
| -------------- | --------- | ------------ |
| Mode Info      | Info      | Oui          |
| Mode Action    | Action    | Oui          |

#### Portail/Garage <a name="paragraphe5-5"></a>

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Garage état ouvrant             | Info      | Oui          |
| Portail état ouvrant            | Info      | Oui          |
| Portail ou garage bouton toggle | Action    | Oui          |

#### Prise <a name="paragraphe5-6"></a>

| Type générique   | Sous-type | Compatible ? |
| ---------------- | --------- | ------------ |
| Prise Etat       | Info      | Oui          |
| Prise Bouton Off | Action    | Oui          |
| Prise Bouton On  | Action    | Oui          |
| Prise Slider     | Action    | Oui          |

#### Serrure <a name="paragraphe5-7"></a>

| Type générique        | Sous-type | Compatible ? |
| --------------------- | --------- | ------------ |
| Serrure Etat          | Info      | Oui          |
| Serrure Bouton Fermer | Action    | Oui          |
| Serrure Bouton Ouvrir | Action    | Oui          |

#### Sirène <a name="paragraphe5-8"></a>

| Type générique    | Sous-type | Compatible ? |
| ----------------- | --------- | ------------ |
| Sirène Etat       | Info      | Oui          |
| Sirène Bouton Off | Action    | Oui          |
| Sirène Bouton On  | Action    | Oui          |

#### Thermostat <a name="paragraphe5-9"></a>

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Thermostat Température ambiante | Info      | Oui          |
| Thermostat Humidité ambiante    | Info      | Oui          |
| Thermostat Mode                 | Info      | Oui          |
| Thermostat consigne             | Action    | Oui          |
| Thermostat Mode                 | Action    | Oui          |

#### Volet <a name="paragraphe5-10"></a>

| Type générique         | Sous-type | Compatible ? |
| ---------------------- | --------- | ------------ |
| Volet BSO Etat         | Info      | Oui          |
| Volet Etat             | Info      | Oui          |
| Volet BSO Bouton Down  | Action    | Oui          |
| Volet BSO Bouton Up    | Action    | Oui          |
| Volet Bouton Descendre | Action    | Oui          |
| Volet Bouton Monter    | Action    | Oui          |
| Volet Bouton Slider    | Action    | Oui          |
| Volet Bouton Stop      | Action    | Oui          |

#### Caméra <a name="paragraphe5-11"></a>

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Etat                            | Info      | Oui          |
| Mouvement caméra vers le bas    | Action    | Oui          |
| Mouvement caméra vers la droite | Action    | Oui          |
| Mouvement caméra vers la gauche | Action    | Oui          |
| Mouvement caméra vers le haut   | Action    | Oui          |
| Preset caméra                   | Action    | Non          |
| Stop caméra                     | Action    | Non          |
| Zoom caméra vers l'arrière      | Action    | Oui          |
| Zoom caméra vers l'avant        | Action    | Oui          |


Configuration du plugin JeeMate <a name="paragraphe6"></a>
==============================

Après téléchargement du plugin, vous devez commencer par l'activer.


Test

#include "file_gentype.md.md"
