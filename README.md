Lors de ses différentes prestations VMware, Christophe HARIVEL a souvent dû réaliser un cahier de configuration au format Excel. 
Le but de ce fichier est de centraliser tous les éléments de configuration nécessaires au redéploiement de tout ou partie de
l'infrastructure (Adresses IP, MASK, GW, DNS, etc...).

Habituellement ce cahier de configuration est à renseigner par le client au début du projet, avant le déploiement de 
l'infrastructure. Mais il peut arriver que certains éléments soient modifiés au cours du temps. 
C'est pourquoi Christophe HARIVEL a créé un script Powershell. Ce script se connecte au serveur vCenter et créé un fichier XLSX
avec toutes les informations nécessaires.

Contrairement à ce que fait Rvtools, ce script relève uniquement les points de configuration et non d'audit.
De même, ce script ne relève rien concernant les VMs. 
