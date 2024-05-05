+++
title = 'Ubuntu login screen'
date = 2024-05-04T15:48:41+02:00
draft = false
+++
# Changer l'écran d'accueil de Ubuntu 


## Préambule

Nous allons utiliser le script de ce super utilisateur qui a déjà résolu le problème à notre place : 

> https://github.com/PRATAP-KUMAR/ubuntu-gdm-set-background

Rendez-vous sur son github pour lire le fichier `ubuntu-gdm-set-background`

Il s'agit d'un fichier très simple, en plus, les sources sont copyleft avec la licence GPL-3.0, super !

## Étape 1

On télécharge le fichier : 

> curl -L -O https://raw.githubusercontent.com/PRATAP-KUMAR/ubuntu-gdm-set-background/main/ubuntu-gdm-set-background

## Étape 2

On choisit une image de fond d'écran. C'est bon? 
Alors changeons de fond d'écran !

> sudo ./ubuntu-gdm-set-background --image ~/Downloads/mywallpaper.jpg

## Étape 3

Vérifier que le fond d'écran a bien changé (par exemple en verrouillant l'écran avec les touches 'Windows' + 'l')


![joli_fond_d_ecran](../ubuntu-login-screen/joli_fond_d_ecran.webp)
