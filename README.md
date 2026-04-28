# Volets_Connectes-IOT  
Volets Connectés – Application Flutter & Firmware ESP32
Volets Connectés est une solution IoT complète qui permet de contrôler à distance les volets roulants d’une maison.
Le système s’articule autour de :

Élément	Rôle
ESP32 (firmware)	Gestion du Wi‑Fi/Bluetooth, communication MQTT, pilotage des relais.
Application Flutter	Interface utilisateur moderne (Material 3, glassmorphism), provisioning Bluetooth du ESP32, envoi des commandes via MQTT.
Principales fonctionnalités
Provisioning Bluetooth : découverte du ESP32 et configuration (SSID Wi‑Fi, mot de passe, nom de la pièce).
Contrôle MQTT : ouvrir, fermer, stopper et régler l’ouverture en pourcentage.
UI riche : tableau de bord avec cartes, glissière de réglage, notifications Snackbar.
Gestion multi‑appareil : chaque volet possède un deviceId unique.
Multiplateforme : Android, iOS, Windows, macOS et Linux.
