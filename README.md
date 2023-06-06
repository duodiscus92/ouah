# ouah
Oh! Une Autre Horloge !
Le projet Ouah est un developpement VHDL d'une horloge synchronisée sur le signal DCF77
Il inclut le décodage de la trame numérique DCF77, ainsi que l'affichage des heures, minutes, jour, mois, année sur des afficheurs 7 segments et jour de la semaine sur 7 leds.
Il n'inclut pas la partie radiofréquence : réception de la porteuse 77,5 kHz moduléé et démodulation.
Il existe sur l'e-commerce de nombreux récepteurs/démodulateurs pour moins de 20 € (en 2023). J'ai utilisé celui en vente chez Reichhelt (https://www.reichelt.com/fr/fr/module-r-cepteur-dcf77-dcf77-modul-p57772.html?search=dcf77&&r=1) dont le fonctionnement est moyennement satisfaisant (manque de sensibilité).
Le projet a été développé pour la carte UPDuino3.1 avec le logiciel Radiant de Lattice.
